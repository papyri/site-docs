# Text Leiden+ Documentation

- For a briefer introduction one can also use: [Guide to SoSOL](https://docs.google.com/document/d/184yKsyRCRtrxW3rK5pfyokr-U9uc0cALrm3k0IQu-gE/edit)
- For a beta version of a list of g types see: [Sigla, Special Characters, Scribal Punctuation, and Glyphs](https://github.com/papyri/site-docs/blob/master/gtypes.md)
- [Formatting - Word and Document](#formatting---word-and-document) <a id="top"></a>
    - [Document Division](#document-division)
    - [Line Numbers](#line-number)
	- [Non-standard Line Formats](#non-standard)
    - [Vacat](#vacat)
    - [Insertions and Marginalia](#marginalia)
    - [Special Text Formatting](#special-formatting)
- [Preservation](#preservation)
    - [Letters Lost](#letters-lost)
    - [Lines Lost](#lines-lost)
    - [Illegible](#illegible)
    - [Vestiges](#vestiges)
- [Leiden Conventions](#leiden-conventions)
    - [Leiden Angle Brackets `< >`](#leiden-angle-brackets--)
    - [Leiden Braces `{ }`](#leiden-braces--)
    - [Leiden Double Square Brackets `〚 〛`](#leiden-double-square-brackets--)
    - [Leiden Parentheses `( )`](#leiden-parentheses--)
    - [Leiden Square Brackets `[ ]`](#leiden-square-brackets--)
    - [Leiden Underline `___`](#leiden-underline-___)
- [Other Editorial Conventions](#other-editorial-conventions)
    - [Handshift](#handshift)
    - [Editorial Note](#editorial-note)
    - [Quotation](#quotation)
- [Apparatus](#apparatus)
    - [Orthographic Regularization](#orthographic-regularization)
    - [Alternate Reading](#alternate-reading)
    - [Scribal Correction](#scribal-correction)
    - [Spelling Correction](#spelling-correction)
- [Corrections to Published Texts](#corrections-to-published-texts)
    - [Berichtigungliste Corrections](#berichtigungliste-corrections)
    - [Journal Article Corrections](#journal-article-corrections)
    - [Editorial Correction](#editorial-correction)
    - [PN/PE Correction](#pnpe-correction)
    - [Complicated Corrections](#complicated-corrections)
- [Numbers and Special Characters](#numbers-and-special-characters)
    - [Numbers](#numbers)
    - [Diacriticals](#diacriticals)
    - [Special Characters](#special-characters)
- [Language](#language)
    - [Non-default Language](#non-default-language)
    - [Omitted](#omitted)
    - [Orthographic Regularization, for Language](#orthographic-regularization-for-language)

## Formatting - Word and Document <a id="formatting---word-and-document"></a>

### Document Division <a id="document-division"></a> ([return to top](#top))

#### Document Div, `ab` (anonymous block)

_To get this PN preview:_ PN does not indicate explicitly

_Use this Leiden+:_ `<= =>`

_To create this XML:_ `<ab> </ab>`

_Example PN Link:_

Every block of text must be enclosed in a `<= ... =>` pair.

***

#### Document Div, recto/verso

_To get this PN preview:_ `recto/verso`

_Use this Leiden+:_ `<D=.r<= 1. line of text 2. line of text =>=D> <D=.v<= 3. line of text 4. line of text =>=D>`

_To create this XML:_ `<div n="r" type="textpart"><ab> <lb n="1"/>line of text <lb n="2"/>line of text </ab></div> <div n="v" type="textpart"><ab> <lb n="3"/>line of text <lb n="4"/>line of text </ab></div>`

_Example PN Link:_

Recto and verso are indicated with closed pairs of tags as follows:

		<S=.grc
		<D=.r<=
		1. line of text
		2. line of text
		=>=D>
		<D=.v<=
		3. line of text
		4. line of text
		=>=D>

Note that the pair of tags inside the recto/verso tags and directly adjacent to the text is the `<= =>` pair (see Document Division, ab)

Please note that the sequence "<S=.grc" must always be present at the very top of the page. If it is deleted what follows can only be saved in Broken Leiden+. "grc" indicates the use of Ancient Greek as the language. This can, of course, be changed to the appropriate language, e.g. "la" for Latin. "<S=.language marker" must always be present.

***

#### Document Div, fragment

_To get this PN preview:_ `fragment 1/fragment 2`

_Use this Leiden+:_ `<D=.1.fragment<= 1. line of text 2. line of text =>=D> <D=.2.fragment<= 3. line of text 4. line of text =>=D>`

_To create this XML:_ `<div n="1" subtype="fragment" type="textpart"><ab> <lb n="1"/>line of text <lb n="2"/>line of text </ab></div> <div n="2" subtype="fragment" type="textpart"><ab> <lb n="3"/>line of text <lb n="4"/>line of text </ab></div>`

_Example PN Link:_

Fragments are indicated with closed pairs of tags as follows:

		<D=.1.fragment<=
		1. line of text
		2. line of text
		=>=D>
		<D=.2.fragment<=
		3. line of text
		4. line of text
		=>=D>

Note that the pair of tags inside the fragment tags and directly adjacent to the text is the `<= =>` pair (see Document Division, ab)

***

#### Document Div, part

_To get this PN preview:_ `part A/part B`

_Use this Leiden+:_ `<D=.A.part<= 1. line of text 2. line of text =>=D> <D=.B.part<= 3. line of text 4. line of text =>=D>`

_To create this XML:_ `<div n="A" subtype="part" type="textpart"><ab> <lb n="1"/>line of text <lb n="2"/>line of text </ab></div> <div n="B" subtype="part" type="textpart"><ab> <lb n="3"/>line of text <lb n="4"/>line of text </ab></div>`

_Example PN Link:_

Parts of a document are indicated with closed pairs of tags as follows:

		<D=.A.part<=
		1. line of text
		2. line of text
		=>=D>
		<D=.B.part<=
		3. line of text
		4. line of text
		=>=D>

Note that the pair of tags inside the part tags and directly adjacent to the text is the `<= =>` pair (see Document Division, ab)

***

#### Document Div, column

_To get this PN preview:_ `column i / column ii`

_Use this Leiden+:_ `<D=.i.column<= 1. line of text 2. line of text =>=D> <D=.ii.column<= 3. line of text 4. line of text =>=D>`

_To create this XML:_ `<div n="i" subtype="column" type="textpart"><ab> <lb n="1"/>line of text <lb n="2"/>line of text </ab></div> <div n="ii" subtype="column" type="textpart"><ab> <lb n="3"/>line of text <lb n="4"/>line of text </ab></div>`

_Example PN Link:_

Columns are indicated with closed pairs of tags as follows:

		<D=.i.column<=
		1. line of text
		2. line of text
		=>=D>
		<D=.ii.column<=
		3. line of text
		4. line of text
		=>=D>

Note that the pair of tags inside the column tags and directly adjacent to the text is the `<= =>` pair (see Document Division, ab)

***

#### Document Div, folio

_To get this PN preview:_ `folio a / folio b`

_Use this Leiden+:_ `<D=.a.folio<= 1. line of text 2. line of text =>=D> <D=.b.folio<= 3. line of text 4. line of text =>=D>`

_To create this XML:_ `<div n="a" subtype="folio" type="textpart"><ab> <lb n="1"/>line of text <lb n="2"/>line of text </ab></div> <div n="b" subtype="folio" type="textpart"><ab> <lb n="3"/>line of text <lb n="4"/>line of text </ab></div>`

_Example PN Link:_

Folios are indicated with closed pairs of tags as follows:

		<D=.a.folio<=
		1. line of text
		2. line of text
		=>=D>
		<D=.b.folio<=
		3. line of text
		4. line of text
		=>=D>

Note that the pair of tags inside the folio tags and directly adjacent to the text is the `<= =>` pair (see Document Division, ab)

***

#### Document Div, convex / concave

_To get this PN preview:_ `side convex/side concave`

_Use this Leiden+:_ `<D=.convex.side<= 1. line of text 2. line of text =>=D> <D=.concave.side<= 3. line of text 4. line of text =>=D>`

_To create this XML:_ `<div n="convex" subtype="side" type="textpart"><ab> <lb n="1"/>line of text <lb n="2"/>line of text </ab></div> <div n="concave" subtype="side" type="textpart"><ab> <lb n="3"/>line of text <lb n="4"/>line of text </ab></div>`

_Example PN Link:_ [o.krok;2;328](https://papyri.info/hgv/704613)

Each side of the ostracon is indicated with closed pairs of tags as follows:

		<D=.convex.side<=
		1. line of text
		2. line of text
		=>=D>
		<D=.concave.side<=
		3. line of text
		4. line of text
		=>=D>

Note that the pair of tags inside the division tags and directly adjacent to the text is the `<= =>` pair (see Document Division, ab)

***

#### Document Div, nested

_To get this PN preview:_ Divisions indicated variously

_Use this Leiden+:_ `<D=.a.folio<= 1. line of text 2. line of text =>=D> <D=.b.folio<= 3. line of text 4. line of text =>=D>`

_To create this XML:_ `<div n="a" subtype="folio" type="textpart"><ab> <lb n="1"/>line of text <lb n="2"/>line of text </ab></div> <div n="b" subtype="folio" type="textpart"><ab> <lb n="3"/>line of text <lb n="4"/>line of text </ab></div>`

_Example PN Link:_

Document divisions can be nested so long as tag pairs no not overlap:

		<D=.r
		<D=.i.column<=
		1. line of text
		2. line of text
		=>=D>
		<D=.ii.column
		<D=.a.fragment<=
		1. line of text
		2. line of text
		=>=D>
		<D=.b.fragment<=
		1. line of text
		2. line of text
		=>=D>
		=D>
		=D>
		<D=.v<=
		1. line of text
		=>=D>

Note that no matter how nested the divisions are, the pair of tags directly adjacent to the text is always the `<= =>` pair (see Document Division, ab)

***

### Line Number <a id="line-number"></a> ([return to top](#top))

#### Line break

_To get this PN preview:_ `1.`

_Use this Leiden+:_ `1.`

_To create this XML:_ `<lb n="1"/>`

_Example PN Link:_ [P.Oxy.1.117](http://papyri.info/hgv/28409)

To indicate line number. Every line must have a line number.

***

#### Words that wrap across lines

_To get this PN preview:_ `5`

_Use this Leiden+:_ `5.-`

_To create this XML:_ `<lb n="5" break="no"/>`

_Example PN Link:_ [p.col.;10;259](http://papyri.info/hgv/10559)

Words that wrap from the end of one line to the beginning of the next. Note that in Leiden+ the hyphen must be written at the start of the following line:

		12. ἃς καὶ <:ἀποδώσει|orth|αποδωσι:> ἐν μηνὶ Πα
		13.- ῦ̣[νι τοῦ] ἐνεσ[τ]ῶτος ἔτους

In the PN the hyphen will be displayed in the expected location:

		ἃς καὶ ἀποδώσει ἐν μηνὶ Πα-
		ῦ̣[νι τοῦ] ἐνεσ[τ]ῶτος ἔτους

***

#### Line 5 to 6

_To get this PN preview:_ `5/6`

_Use this Leiden+:_ `5/6.`

_To create this XML:_ `<lb n="5/6"/>`

_Example PN Link:_ [P.Oxy.1.117](http://papyri.info/hgv/28409)

For use in rare cases in which lines are presented so as not to indicate break; not recommended.

***

### Non-standard Line Position <a id="non-standard"></a> ([return to top](#top))

#### Line rendered perpendicular to the main body of text

_To get this PN preview:_ `ø --> 2. (perpendicular)`

_Use this Leiden+:_ `(2, perpendicular)`

_To create this XML:_ `<lb n="2" rend="perpendicular"/>`

_Example PN Link:_ [P.Berl.Bibl.12](http://papyri.info/hgv/31065)

Numbered line written perpendicular to main text.

***

#### Line rendered inverse to the main body of text

_To get this PN preview:_ `ø --> 8. (inverse)`

_Use this Leiden+:_ `(8, inverse)`

_To create this XML:_ `<lb n="8" rend="inverse"/>`

_Example PN Link:_ [P.Oxy.16.1951](http://papyri.info/hgv/35611)

Numbered line written inverse to main text.

***

#### Line with word-wrap written inverse to main text

_To get this PN preview:_ `ø --> 3. (inverse) with hyphen at end of preceding line`

_Use this Leiden+:_ `(3.-, inverse)`

_To create this XML:_ `<lb n="3" rend="inverse" break="no"/>`

_Example PN Link:_ [SB.24.16170](http://papyri.info/ddbdp/sb;24;16170)

For lines written inverse / perpendicular to main text and containing a word-wrap, simply add hyphen to the regular convention.

***

#### Line indented (i.e., in eisthesis) relative to the main body of text 

_To get this PN preview:_ `ø --> 2. 	κτλ.`

_Use this Leiden+:_ `(2, indent) κτλ.`

_To create this XML:_ `<lb n="2" rend="indent"/>`

_Example PN Link:_ [BASP 54 (2017) 120](http://papyri.info/hgv/704970)

Numbered line indented (i.e., in eisthesis) relative to the main text. Where the beginning of a line is deliberately left blank, it is preferable to encode an indent instead of using vac.?

***

#### Line outdented (i.e., in ekthesis) relative to the main body of text

_To get this PN preview:_ `ø --> 2. κτλ.`

_Use this Leiden+:_ `(2, outdent) κτλ.`

_To create this XML:_ `<lb n="2" rend="outdent"/>`

_Example PN Link:_ [BGU I 52](http://papyri.info/hgv/9097)

Numbered line outdented (i.e., in ekthesis) relative to the main text.

***

#### Line with word-wrap indented or outdented (i.e., in eisthesis or ekthesis) relative to the main body of text

_To get this PN preview:_ `ø --> 2. 	κτλ. (with hyphen at end of previous line`

_Use this Leiden+:_ `(2.-, indent) κτλ.` or `(2.-, outdent) κτλ.`

_To create this XML:_ `<lb n="2" rend="indent" break="no"/>` or `<lb n="2" rend="outdent" break="no"/>`

_Example PN Link:_ [BASP 58 (2021) 130 No. 41](http://papyri.info/hgv/971690)

Words that wrap from the end of one line to the beginning of the next, when the next line is in eisthesis or ekthesis. 

***

#### Line written in left margin

_To get this PN preview:_ `3,ms`

_Use this Leiden+:_ `3,ms.`

_To create this XML:_ `<lb n="3,ms"/>`

_Example PN Link:_ [P.Hib.1.74](http://papyri.info/hgv/8223)

Numbered line written in left margin.

***

#### Line written in right margin

_To get this PN preview:_ `3,md`

_Use this Leiden+:_ `3,md.`

_To create this XML:_ `<lb n="3,md"/>`

_Example PN Link:_ [O.Berenike 2.231](http://papyri.info/hgv/89257)

Numbered line written in right margin.

***

#### Line written in upper margin

_To get this PN preview:_ `1,msup`

_Use this Leiden+:_ `1,msup.`

_To create this XML:_ `<lb n="1,msup"/>`

_Example PN Link:_ [P.Alex. inv. 239](http://papyri.info/hgv/36891)

Numbered line written in upper margin.

***

#### Line written in lower margin

_To get this PN preview:_ `1,minf`

_Use this Leiden+:_ `1,minf.`

_To create this XML:_ `<lb n="1,minf"/>`

_Example PN Link:_ [O.Camb. 3](http://papyri.info/hgv/44242)

Numbered line written in lower margin.

***

#### Line rendered perpendicular to the main body of text in margin

_To get this PN preview:_ `8,ms --> 8,ms (perpendicular)` (for left margin) or `8,md --> 8,md (perpendicular)` (for right margin)

_Use this Leiden+:_ `(8,ms, perpendicular)` or `(8,md, perpendicular)`

_To create this XML:_ `<lb n="8,ms" rend="perpendicular"/>` or `<lb n="8,md" rend="perpendicular"/>`

_Example PN Link:_ [P.Harr.1.161](http://papyri.info/hgv/37268)

Numbered line written in a margin and perpendicular to main text. The designations `ms` and `md` specify which margin contains the text (sinistra/left, and dextra/right, respectively).

***

#### Line rendered inverse to the main body of text in lower margin

_To get this PN preview:_ `16,minf --> 16,minf (inverse)` NOTE: getting cut off at left

_Use this Leiden+:_ `(16,minf, inverse)`

_To create this XML:_ `<lb n="16,minf" rend="inverse"/>`

_Example PN Link:_ [P.Cair.Zen.5.59838](http://papyri.info/hgv/1462)

Numbered line written in lower margin and inverse to main text.

***

### Vacat <a id="vacat"></a> ([return to top](#top))

#### Character space extent unknown

_To get this PN preview:_ `vac.`

_Use this Leiden+:_ `vac.?`

_To create this XML:_ `<space extent="unknown" unit="character"/>`

_Example PN Link:_ [P.Berl.Leihg.2.39](http://papyri.info/hgv/10223)

Vacat of unknown number of characters. It is tempting to use `vac.?` to replicate the modern print publication convention of separating, e.g. items from numbers in accounts and the like. Rampant use of `vac.?` for this purpose is discouraged. Use `vac.?` only where there is empty space on the physical text; if such is not verifiable against image or original do not use `vac.?`.

***

#### Character space quantity

_To get this PN preview:_ `--> vac.3`

_Use this Leiden+:_ `vac.3`

_To create this XML:_ `<space quantity="3" unit="character"/>`

_Example PN Link:_

Vacat of known number of characters.

***

#### Character space range

_To get this PN preview:_ `--> vac.2-5`

_Use this Leiden+:_ `vac.2-5`

_To create this XML:_ `<space atLeast="2" atMost="5" unit="character"/>`

_Example PN Link:_

Vacat of known range of characters.

***

#### Character space quantity precision low

_To get this PN preview:_ `--> vac. ca.3`

_Use this Leiden+:_ `vac.ca.3`

_To create this XML:_ `<space quantity="3" unit="character" precision="low"/>`

_Example PN Link:_

Vacat of estimated range of characters.

***

#### Line space extent unknown

_To get this PN preview:_ `--> vac. ? lines`

_Use this Leiden+:_ `vac.?lin`

_To create this XML:_ `<space extent="unknown" unit="line"/>`

_Example PN Link:_

Vacat of unknown number of lines.

***

#### Line space quantity

_To get this PN preview:_ `--> vac. 3 lines`

_Use this Leiden+:_ `vac.3lin`

_To create this XML:_ `<space quantity="3" unit="line"/>`

_Example PN Link:_

Vacat of known number of lines.

***

#### Line space range

_To get this PN preview:_ `--> vac. 2-5 lines`

_Use this Leiden+:_ `vac.2-5lin`

_To create this XML:_ `<space atLeast="2" atMost="5" unit="line"/>`

_Example PN Link:_

Vacat of known range of lines.

***

#### Line space quantity precision low

_To get this PN preview:_ `--> vac ca.3 lines`

_Use this Leiden+:_ `vac.ca.3lin`

_To create this XML:_ `<space quantity="3" unit="line" precision="low"/>`

_Example PN Link:_

Vacat of estimated number of lines.

***

### Insertions and Marginalia <a id="marginalia"></a> ([return to top](#top))

#### Text inserted / added above line

_To get this PN preview:_ `\ὅλων/`

_Use this Leiden+:_ `\ὅλων/`

_To create this XML:_ `<add place="above">ὅλων</add>`

_Example PN Link:_ [P.Matr.2](http://papyri.info/hgv/18216)

To indicate text inserted or added above a line, as 'afterthought' or self-correction (for conventional drop-ins: `\καὶ/`)

***

#### Text inserted / added below line

_To get this PN preview:_ `/δ\`

_Use this Leiden+:_ `//<#δ=4#>\\`

_To create this XML:_ `<add place="below"><num value="4">δ</num></add>`

_Example PN Link:_

To indicate text inserted or added below a line, as 'afterthought' or self-correction (see print conventional: `/καὶ\`)

***

#### Text inserted / added to the left margin

_To get this PN preview:_ `(added at left: καὶ)`

_Use this Leiden+:_ `||left:καὶ||`

_To create this XML:_ `<add place="left">καὶ</add>`

_Example PN Link:_ [p.jena;2;10](http://papyri.info/hgv/128690)

To indicate text inserted / added to the left of a line

***

#### Text inserted / added to the right margin

_To get this PN preview:_ `(added at right: καὶ)`

_Use this Leiden+:_ `||right:καὶ||`

_To create this XML:_ `<add place="right">καὶ</add>`

_Example PN Link:_

To indicate text inserted / added to the right of a line

***

#### Text added between lines

_To get this PN preview:_ `ὧν (in smaller font)`

_Use this Leiden+:_ `||interlin: ὧ( ῾)ν||`

_To create this XML:_ `<add place="interlinear"><hi rend="asper">ὧ</hi>ν</add>`

_Example PN Link:_ [P.Panop.14](http://papyri.info/hgv/32564)

To indicate text added between two lines

***

#### Text sling in margin

_To get this PN preview:_ `ν`

_Use this Leiden+:_ `<|ν|>`

_To create this XML:_ `<add rend="sling" place="margin">ν</add>`

_Example PN Link:_ [BGU.1.303](http://papyri.info/hgv/41055)

Need to create detailed instructions and explanation

***

#### Text underline in margin

_To get this PN preview:_ `οὕτως ἔχει`

_Use this Leiden+:_ `<_οὕτως ἔχει_>`

_To create this XML:_ `<add rend="underline" place="margin">οὕτως ἔχει</add>`

_Example PN Link:_ [P.Prag.2.137](http://papyri.info/hgv/12794)

Need to create detailed instructions and explanation

***

#### Text above line with cert low

_To get this PN preview:_ `Θέ̣ων̣(?) = SoSOL, Θέ̣ων̣(?)/ = PN`

_Use this Leiden+:_ `Θέ̣ων̣?/`

_To create this XML:_ `<add cert="low" place="above">Θ<unclear>έ</unclear>ω<unclear>ν</unclear></add>`

_Example PN Link:_ [PSI.4.281](http://papyri.info/ddbdp/psi;4;281)

Need to create detailed instructions and explanation

***

### Special Text Formatting <a id="special-formatting"></a> ([return to top](#top))

#### Text in box

_To get this PN preview:_ `Text: milestone01…App: ctr.11. Text in box`

_Use this Leiden+:_ `###`

_To create this XML:_ `<milestone rend="box" unit="undefined"/>`

_Example PN Link:_ [BGU.7.1537](http://papyri.info/hgv/4787)

To indicate text written inside a 'box'.

***

#### Tall text

_To get this PN preview:_ `ø --> render taller`

_Use this Leiden+:_ `~||x||~tall`

_To create this XML:_ `<hi rend="tall">x</hi>`

_Example PN Link:_ [P.Oslo.2.26](http://papyri.info/hgv/21513)

Oversized / tall text.

***

#### Superscripted text

_To get this PN preview:_ `superscript`

_Use this Leiden+:_ `|^Ἡρωνείνῳ^|`

_To create this XML:_ `<hi rend="superscript">Ἡρωνείνῳ</hi>`

_Example PN Link:_ [P.Laur.1.3](http://papyri.info/hgv/31500)

Text written in superscript, as distinct from text added above the line, as 'afterthought' or 'self-correction' (for which use `\καὶ/`). In general we do not encode superscript characters that indicate abbreviation.

***

#### Subscripted text

_To get this PN preview:_ `subscript`

_Use this Leiden+:_ `\|τα|/`

_To create this XML:_ `<hi rend="subscript">τα</hi>`

_Example PN Link:_

To indicate subscripted text, as distinct from text added from below the line (for which use `//καὶ\\`).

***

#### Supraline

_To get this PN preview:_ `νο ̣--> with supraline`

_Use this Leiden+:_ `¯νο.1¯`

_To create this XML:_ `<hi rend="supraline">νο<gap reason="illegible" quantity="1" unit="character"/></hi>`

_Example PN Link:_ [P.Lips.1.102](http://papyri.info/hgv/33704)

To indicate supralines, most often used in case of numbers (not, as rule, for expansions)

***

#### Supraline and underline

_To get this PN preview:_ `ø --> underline and supraline`

_Use this Leiden+:_ `¯_εὐτύχει=_¯`

_To create this XML:_ `<hi rend="supraline-underline">εὐτύχει</hi>`

_Example PN Link:_ [BGU.4.1201](http://papyri.info/hgv/18651)

To indicate text that is both underlined and supralined.

***

## Preservation <a id="preservation"></a>

### Letters Lost <a id="letters-lost"></a> ([return to top](#top))

See [Leiden Square Brackets `[ ]`](#leiden-square-brackets--).

***

### Lines Lost <a id="lines-lost"></a> ([return to top](#top))

#### Known number of lines missing

_To get this PN preview:_ `[7 lines missing]`

_Use this Leiden+:_ `lost.7lin`

_To create this XML:_ `<gap reason="lost" quantity="7" unit="line"/>`

_Example PN Link:_ [P.Oxy.3.617](http://papyri.info/hgv/20672)

To indicate a known number of lost lines.

***

#### Approximate number of lines lost

_To get this PN preview:_ `[ca 7 lines missing]`

_Use this Leiden+:_ `lost.ca.7lin`

_To create this XML:_ `<gap reason="lost" quantity="7" unit="line" precision="low"/>`

_Example PN Link:_ [O.Kell.13](http://papyri.info/hgv/74537)

To indicate approximate number of lines lost.

***

#### Approximate range of lines lost

_To get this PN preview:_ `[3-4 lines missing]`

_Use this Leiden+:_ `lost.3-4lin`

_To create this XML:_ `<gap reason="lost" atLeast="3" atMost="4" unit="line"/>`

_Example PN Link:_ [P.Lille.1.29](http://papyri.info/hgv/3231)

To indicate approximate range of lines lost.

***

#### Unknown number of lines lost

_To get this PN preview:_ `-- -- -- -- -- -- -- -- -- --`

_Use this Leiden+:_ `lost.?lin`

_To create this XML:_ `<gap reason="lost" extent="unknown" unit="line"/>`

_Example PN Link:_

To indicate unknown number of lines lost. This is used to indicate "break" in the papyrus. Enter as follows:

		1. lost.?lin
		1. first line of text
		2. second line of text
		3. third line of text
		3. lost.?lin

***

#### Unknown number of lines lost (uncertain)

_To get this PN preview:_ `-- -- -- -- -- -- -- -- -- -- (?)`

_Use this Leiden+:_ `lost.?lin(?)`

_To create this XML:_ `<gap reason="lost" extent="unknown" unit="line"><certainty match=".." locus="name"/></gap>`

_Example PN Link:_ [O.Did.401](http://papyri.info/hgv/144962)

To indicate that we are uncertain as to whether an unknown number of lines are lost.

***

### Illegible <a id="illegible"></a> ([return to top](#top))

#### Gap illegible character

_To get this PN preview:_ ` ̣ ̣ ̣`

_Use this Leiden+:_ `.3`

_To create this XML:_ `<gap reason="illegible" quantity="3" unit="character"/>`

_Example PN Link:_ [O.Berenike.1.6](http://papyri.info/ddbdp/o.berenike;1;6)

To indicate a known number of illegible characters.

***

#### Gap illegible character (unknown)

_To get this PN preview:_ `- ca. ? -`

_Use this Leiden+:_ `.?`

_To create this XML:_ `<gap reason="illegible" extent="unknown" unit="character"/>`

_Example PN Link:_ [P.Berl.Leihg.1.13](http://papyri.info/hgv/10193)

To indicate an unknown number of illegible characters.

***

#### Approximate number of illegible characters

_To get this PN preview:_ `- ca.23 -`

_Use this Leiden+:_ `ca.23`

_To create this XML:_ `<gap reason="illegible" quantity="23" unit="character" precision="low"/>`

_Example PN Link:_ [P.Wisc.1.1](http://papyri.info/hgv/26917)

To indicate an estimated number of illegible characters.

***

#### Known number of illegible characters

_To get this PN preview:_ `- ca.43 -`

_Use this Leiden+:_ `.43`

_To create this XML:_ `<gap reason="illegible" quantity="43" unit="character"/>`

_Example PN Link:_ [SB.20.14241](http://papyri.info/hgv/23699)

To indicate a known number of illegible characters. Note: all strings of illegible characters greater than 8 are rendered as approximations. So, `".43"` will be encoded as a piece of editorial certainty (`<gap reason="illegible" quantity="43" unit="character"/>`), but will nevertheless be displayed as an approximation: `"- ca.43 -"`

***

#### Range of illegible characters

_To get this PN preview:_ `-9-10-`

_Use this Leiden+:_ `.9-10`

_To create this XML:_ `<gap reason="illegible" atLeast="9" atMost="10" unit="character"/>`

_Example PN Link:_ [P.Eleph.Wagner.1.288](http://papyri.info/hgv/74479)

To indicate a known range of illegible characters.

***

#### Known number of illegible lines

_To get this PN preview:_ `Traces 5 lines`

_Use this Leiden+:_ `.5lin`

_To create this XML:_ `<gap reason="illegible" quantity="5" unit="line"/>`

_Example PN Link:_ [P.Hib.2.253](http://papyri.info/hgv/8291)

To indicate a known number of illegible lines (e.g. vestiges)

***

#### Approximate number of illegible lines

_To get this PN preview:_ `Traces ca.20 lines`

_Use this Leiden+:_ `ca.20lin`

_To create this XML:_ `<gap reason="illegible" quantity="20" unit="line" precision="low"/>`

_Example PN Link:_ [SB.24.15920](http://papyri.info/hgv/25460)

To indicate an estimated number of illegible lines (e.g. vestiges).

***

#### Range of illegible lines

_To get this PN preview:_ `Traces 2-3 lines`

_Use this Leiden+:_ `.2-3lin`

_To create this XML:_ `<gap reason="illegible" atLeast="2" atMost="3" unit="line"/>`

_Example PN Link:_ [SB.20.14571](http://papyri.info/hgv/38499)

To indicate a range of illegible lines.

***

### Vestiges <a id="vestiges"></a> ([return to top](#top))

#### Vestiges n lines

_To get this PN preview:_ `Traces 15 lines`

_Use this Leiden+:_ `vestig.15lin`

_To create this XML:_ `<gap reason="illegible" quantity="15" unit="line"><desc>vestiges</desc></gap>`

_Example PN Link:_ [P.Stras.6.559](http://papyri.info/hgv/16792)

Vestiges of known number of lines.

***

#### Vestiges range of lines

_To get this PN preview:_ `Traces 2-3 lines`

_Use this Leiden+:_ `vestig.2-3lin`

_To create this XML:_ `<gap reason="illegible" atLeast="2" atMost="3" unit="line"><desc>vestiges</desc></gap>`

_Example PN Link:_ [BGU.3.916](http://papyri.info/hgv/9414)

Vestiges of known range of lines.

***

#### Vestiges ca.n lines

_To get this PN preview:_ `Traces ca.3 lines`

_Use this Leiden+:_ `ex. vestig.ca.3lin`

_To create this XML:_ `ex. <gap reason="illegible" quantity="3" unit="line" precision="low"><desc>vestiges</desc></gap>`

_Example PN Link:_

Vestiges of estimated number of lines.

***

#### Vestiges ? lines

_To get this PN preview:_ `-ca.?- --> Traces ? lines`

_Use this Leiden+:_ `vestig.?lin`

_To create this XML:_ `<gap reason="illegible" extent="unknown" unit="line"/>`

_Example PN Link:_ [P.Stras.6.559](http://papyri.info/hgv/16792)

Vestiges of unknown number of lines.

***

#### Vestiges ? characters

_To get this PN preview:_ `-ca.?- --> Traces`

_Use this Leiden+:_ `vestig`

_To create this XML:_ `<gap reason="illegible" extent="unknown" unit="character"><desc>vestiges</desc></gap>`

_Example PN Link:_ [O.Berenike.1.76](http://papyri.info/hgv/70853)

Vestiges of unknown number of characters. NOTE: You must enter a space after vestig; so, not `"vestig"` but `"vestig "`.

***

#### Vestiges ca.n characters

_To get this PN preview:_ `ca.traces - --> Traces 8 char. / Traces ca.14 char.`

_Use this Leiden+:_ `vestig.14char`

_To create this XML:_ `<gap reason="illegible" quantity="14" unit="character"><desc>vestiges</desc></gap>`

_Example PN Link:_ [P.Lips.1.21](http://papyri.info/hgv/22338)

Vestiges of known number of characters. Note: all vestige strings greater than 8 characters are rendered as approximations. So, `"vestig.14char"` will be encoded as a piece of editorial certainty, but will nevertheless be displayed as an approximation: `"Traces ca.14 char."`

***

#### Vestiges ca.n characters

_To get this PN preview:_ ` ̣ ̣ ̣ --> Traces ca.3 char.`

_Use this Leiden+:_ `example only - vestig.ca.3char`

_To create this XML:_ `example only - <gap reason="illegible" quantity="3" unit="character" precision="low"><desc>vestiges</desc></gap>`

_Example PN Link:_

Vestiges of estimated number of characters.

***

#### Vestiges range of characters

_To get this PN preview:_ `-ca.15-30- --> Traces ca.15-30 characters`

_Use this Leiden+:_ `vestig.15-30char`

_To create this XML:_ `<gap reason="illegible" atLeast="15" atMost="30" unit="character"><desc>vestiges</desc></gap>`

_Example PN Link:_ [P.Oxy.50.3557](http://papyri.info/hgv/15381)

Vestiges of range of characters.

***

## Leiden Conventions <a id="leiden-conventions"></a>

### Leiden Angle Brackets `< >` <a id="leiden-angle-brackets--"></a> ([return to top](#top))

#### Supplied omitted

_To get this PN preview:_ `<ἀπεγραψάμην>`

_Use this Leiden+:_ `<ἀπεγραψάμην>`

_To create this XML:_ `<supplied reason="omitted">ἀπεγραψάμην</supplied>`

_Example PN Link:_ [BGU.1.117](http://papyri.info/hgv/8891)

Text omitted by scribe, inserted by modern editor. To indicate such added text, enclose it in angle brackets: e.g. `<ἀπεγραψάμην>`, `ἀπ<ε>γραψάμην`, etc.

***

#### Supplied omitted (uncertain)

_To get this PN preview:_ `<οὐκ(?)>`

_Use this Leiden+:_ `<οὐκ(?)>`

_To create this XML:_ `<supplied reason="omitted" cert="low">οὐκ</supplied>`

_Example PN Link:_ [P.Oxy.50.3581](http://papyri.info/hgv/32313)

To indicate text omitted by scribe and uncertainly inserted by modern editor.

***

#### Supplied omitted (inline)

_To get this PN preview:_ `ἀπ<ε>γραψάμην`

_Use this Leiden+:_ `ἀπ<ε>γραψάμην`

_To create this XML:_ `ἀπ<supplied reason="omitted">ε</supplied>γραψάμην`

_Example PN Link:_ [bgu;1;154](http://papyri.info/ddbdp/bgu;1;154)

Note: for cases like `ἀπ<ε>γραψάμην` the DDbDP has historically entered an orthographic correction of the entire word, i.e. `<:ἀπεγραψάμην|orth|απγραψαμην:>`. Recommended practice now is to enter just the angle brackets wherever possible: `ἀπ<ε>γραψάμην`.

For more on this, see the documentation entry under Orthographic Correction.

***

### Leiden Braces `{ }` <a id="leiden-braces--"></a> ([return to top](#top))

#### Surplus text

_To get this PN preview:_ `{ὀνόματος}`

_Use this Leiden+:_ `{ὀνόματος}`

_To create this XML:_ `<surplus>ὀνόματος</surplus>`

_Example PN Link:_ [P.Oxy.50.3583](http://papyri.info/hgv/15402)

Surplus text written by scribe, deleted by modern editor. To indicate such text enclose it in braces: e.g. `{ὀνόματος}`, `ὀνό{μ}ματος`.

***

#### Surplus text (inline)

_To get this PN preview:_ `ὁμο{μο}λογῶ.`

_Use this Leiden+:_ `ὁμο{μο}λογῶ.`

_To create this XML:_ `ὁμο<surplus>μο</surplus>λογῶ.`

_Example PN Link:_

Surplus text written by scribe, deleted by modern editor.

For cases like `ὁμολογῶι` enter an orthographic regularization of the entire word, i.e. `<:ὁμολογῶ|reg|ὁμολογῶι:>`. But where the letter(s) is genuinely superfluous, use braces: `ὁμο{μο}λογῶ`.

***

### Leiden Double Square Brackets `〚 〛` <a id="leiden-double-square-brackets--"></a> ([return to top](#top))

#### Deletion

_To get this PN preview:_ `〚τοῖς κορασίοις〛`

_Use this Leiden+:_ `〚τοῖς κορασίοις〛`

_To create this XML:_ `<del rend="erasure">τοῖς κορασίοις</del>`

_Example PN Link:_ [BGU.1.34](http://papyri.info/hgv/20193)

Text deleted in antiquity. Note: this convention has been used to cover many modes of deletion (cancellation by slashes, expunction, strike-through, bracket-like marks on the papyrus, etc). Appearance of `〚...〛` does not imply one mode or another.

***

#### Deletion with slashes

_To get this PN preview:_ `Text: τραπέζης Φρέμει...App: 5. Text canceled with slashes`

_Use this Leiden+:_ `〚/ τραπέζης Φρέμει. 〛`

_To create this XML:_ `<del rend="slashes"> τραπέζης Φρέμει. </del>`

_Example PN Link:_ [cpr;1;15](http://papyri.info/ddbdp/cpr;1;15)

Text deleted with slashes in antiquity: `〚/ τραπέζης Φρέμει.〛`

***

#### Deletion with cross-strokes

_To get this PN preview:_ `Text: (hand 4) -ca.?-….App: v.1. Text canceled with cross-strokes`

_Use this Leiden+:_ `〚X $m4 lost.?lin 〛`

_To create this XML:_ `<del rend="cross-strokes"> <handShift new="m4"/> <gap reason="lost" extent="unknown" unit="line"/> </del>`

_Example PN Link:_ [p.lips;1;98](http://papyri.info/ddbdp/p.lips;1;98)

Text deleted with cross-strokes in antiquity: `〚X $m4 lost.?lin〛`

***

### Leiden Parentheses `( )` <a id="leiden-parentheses--"></a> ([return to top](#top))

#### Expansion of part of word `στρατηγ(ός)`

_To get this PN preview:_ `στρατηγ(ός)`

_Use this Leiden+:_ `(στρατηγ(ός))`

_To create this XML:_ `<expan>στρατηγ<ex>ός</ex></expan>`

_Example PN Link:_ [P.Col.10.285](http://papyri.info/hgv/41444) line 33.

Ancient abbreviations. Note: Leiden+ handles `στρατηγ( )` and `στρατηγ(ός)` differently. Where the abbreviation is expanded -- as in the case of `στρατηγ(ός)` -- enter as follows: `(στρατηγ(ός))`. For the other case, see below under Abbreviation.

***

#### Uncertain expansion of part of a word `Καρ(ανίδι(?))`

_To get this PN preview:_ `Καρ(ανίδι(?))`

_Use this Leiden+:_ `(Καρ(ανίδι?))`

_To create this XML:_ `<expan>Καρ<ex cert="low">ανίδι</ex></expan>`

_Example PN Link:_ bgu;1;154

Ancient abbreviations. For uncertain expansions, add `"?"` inside the expanded part of the word `(στρατηγ(ός)) --> (στρατηγ(ός?))`.

***

#### Partial expansion of part of a word `Καρ(ανίδ )`

_To get this PN preview:_ `Καρ(ανίδ ) --> Καρ(ανίδ-)???`

_Use this Leiden+:_ `(Καρ(ανίδ ))`

_To create this XML:_ `<expan>Καρ<ex>ανίδ </ex></expan>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/hgv/8922)

Ancient abbreviations. Where a word is only partially expanded (for example because the termination is unknown), enter as follows:

    Καρ(ανίδ )

Note: leave two spaces between the last character and the closing parens.

***

#### Expansion of whole word `(ἔτους)`

_To get this PN preview:_ `((ἔτους))`

_Use this Leiden+:_ `((ἔτους))`

_To create this XML:_ `<expan><ex>ἔτους</ex></expan>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/hgv/8922)

For symbols that are fully expanded enter as follows: `((ἔτους))`.

***

#### Expansion of whole word `(ἔ̣τ̣ο̣υ̣ς̣) / (ἔτους?)`

_To get this PN preview:_ `(ἔτους(?))`

_Use this Leiden+:_ `((ἔτους?))`

_To create this XML:_ `<expan><ex cert="low">ἔτους</ex></expan>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/hgv/8922)

For symbols that are fully expanded, but uncertainly read enter as follows: `((ἔτους?))`. This is often represented in print by `(ἔ̣τ̣ο̣υ̣ς̣) / (ἔτους?)`.

***

#### Partial expansion of whole word `(δραχμ )`

_To get this PN preview:_ `(ἔτ ) --> (ἔτ-)???`

_Use this Leiden+:_ `((ἔτ ))`

_To create this XML:_ `<expan><ex>ἔτ </ex></expan>`

_Example PN Link:_ [BGU.1.154](http://papyri.info/hgv/8922)

For symbols that are partially expanded enter as follows (for example because the termination is unknown):

    ((ἔτ ))

Note: leave two spaces between the last character and the closing parens.

***

#### Abbreviation, `στρατηγ( )`

_To get this PN preview:_ `ομυο( )`

_Use this Leiden+:_ `(|ομυο|)`

_To create this XML:_ `<abbr>ομυο</abbr>`

_Example PN Link:_ [BGU.1.110](http://papyri.info/hgv/8884)

Ancient abbreviations. Note: Leiden+ treats resolved and unresolved abbreviations differently: so, enter

    (στρατηγ(ός)) for στρατηγ(ός)

but enter

    (|στρατηγ|) for στρατηγ( )

***

#### Abbreviation with markup `σ[τρ]α̣τ̣ηγ( )`

_To get this PN preview:_ `[  ̣  ̣  ̣  ̣  ̣  ̣  ̣  ̣]χυρι̣ο( )`

_Use this Leiden+:_ `(|[.8]χυρι̣ο|)`

_To create this XML:_ `<abbr><gap reason="lost" quantity="8" unit="character"/>χυρ<unclear>ι</unclear>ο</abbr>`

_Example PN Link:_ [BGU.1.110](http://papyri.info/hgv/8884)

For unresolved abbreviations: `(|σ[τρ]α̣τ̣ηγ|) = σ[τρ]α̣τ̣ηγ( )`

***

#### Abbreviation, `λ( )(?)`

_To get this PN preview:_ `λ( )(?)`

_Use this Leiden+:_ `(|λ(?)|)`

_To create this XML:_ `<abbr>λ<certainty locus="name" match=".."/></abbr>`

_Example PN Link:_ [P.Lips.1.40](http://papyri.info/hgv/33700)

Ancient abbreviations. Where the expansion is unknown and it is not even certain whether the character(s) on the papyrus is meant to be an expansion or not, enter:

    (|λ(?)|)

This could indicate `λ` (i.e. 30) or, e.g. `λ(όγος)`; but we cannot say for certain.

***

### Leiden Square Brackets `[ ]` <a id="leiden-square-brackets--"></a> ([return to top](#top))

#### Lost character gap quantity

_To get this PN preview:_ `[ ̣ ̣ ̣ ̣ ̣ ̣ ̣ ̣ ] / [ -ca.43- ]`

_Use this Leiden+:_ `[.8] or [.43]`

_To create this XML:_ `<gap reason="lost" quantity="8" unit="character"/> or <gap reason="lost" quantity="43" unit="character"/>`

_Example PN Link:_ [BGU.1.110](http://papyri.info/hgv/8884)

Known number of characters lost in lacuna. Note: all strings of lost characters greater than 8 are rendered as approximations. So, `"[.43]"` will be encoded as a piece of editorial certainty, but will nevertheless be displayed as an approximation: `"[ - ca.43 - ]"`

***

#### Lost character gap quantity precision low

_To get this PN preview:_ `[ -ca.5- ]`

_Use this Leiden+:_ `[ca.5]`

_To create this XML:_ `<gap reason="lost" quantity="5" unit="character" precision="low"/>`

_Example PN Link:_ [O.Douch.2.88](http://papyri.info/hgv/34423)

To indicate an approximate number of lost characters inside lacuna, enter `[ca.5]`, where `'5'` is the number of lost characters.

***

#### Lost character gap range

_To get this PN preview:_ `[ -ca.11-15- ]`

_Use this Leiden+:_ `[.11-15]`

_To create this XML:_ `<gap reason="lost" atLeast="11" atMost="15" unit="character"/>`

_Example PN Link:_ [P.Oxy.46.3285](http://papyri.info/hgv/63672)

Known range of characters lost in lacuna.

***

#### Lost character gap unknown quantity

_To get this PN preview:_ `[ - ca. ? - ]`

_Use this Leiden+:_ `[.?]`

_To create this XML:_ `<gap reason="lost" extent="unknown" unit="character"/>`

_Example PN Link:_ [O.Berenike.1.6](http://papyri.info/ddbdp/o.berenike;1;6)

Unknown number of characters lost in lacuna.

***

#### Supplied lost words

_To get this PN preview:_ `[ὁμο]λογῶ`

_Use this Leiden+:_ `[ὁμο]λογῶ`

_To create this XML:_ `<supplied reason="lost">ὁμο</supplied>λογῶ`

_Example PN Link:_ [P.Matr.2](http://papyri.info/hgv/18216)

Letters lost in lacuna, restored by modern editor.

***

#### Supplied lost cert low

_To get this PN preview:_ `ἡμετέρ[α μήτηρ (?) - ca. ? - ]`

_Use this Leiden+:_ `ἡμετέρ[α μήτηρ (?)] [.?]`

_To create this XML:_ `ἡμετέρ<supplied reason="lost" cert="low">α μήτηρ </supplied> <gap reason="lost" extent="unknown" unit="character"/>`

_Example PN Link:_ [P.Matr.5](http://papyri.info/hgv/18218)

Letters lost in lacuna, restored by modern editor; restoration uncertain

Example: `ἡμετέρ[α μήτηρ (?) -ca.?- ]`

Note that the restoration of μήτηρ is uncertain, but the lacuna after it is not. Thus, encode as follows:

    ἡμετέρ[α μήτηρ (?)] [.?]

In order to indicate that the one restoration is uncertain and the other certain. For even greater precision, we might enter:

    ἡμετέρ[α] [μήτηρ (?)] [.?]

***

### Leiden Underline `___` <a id="leiden-underline-___"></a> ([return to top](#top))

#### Supplied parallel

_To get this PN preview:_ `Πόσεις`

_Use this Leiden+:_ `|_Πόσεις_|`

_To create this XML:_ `<supplied evidence="parallel" reason="undefined">Πόσεις</supplied>`

_Example PN Link:_ [P.Berl.Leihg.2.39](http://papyri.info/ddbdp/p.berl.leihg;2;39)

Text supplied from parallel text, other copy, or transcription of previously visible text that is now lost or illegible.

***

#### Supplied parallel, low certainty

_To get this PN preview:_ `ἀρ(τάβας(?)) δωδέκ(ατον) εἰκ(οστοτέταρτον(?)) (ἀρτάβας) ιβ´ κδ´ † Ἀγαθάμμωνapp02 †/ ((tachygraphic-marks))`

_Use this Leiden+:_ `|_(ἀρ(τάβας?)) (δωδέκ(ατον)) (εἰκ(οστοτέταρτον?)) ((ἀρτάβας)) <#ιβ=frac1/12#> <#κδ=frac1/24#> *stauros* <:Ἀγαθάμμων|BL:8.441|(δ(ι)) (|μ|) κάμμονι:> *stauros*/ *tachygraphic-marks*(?)_|

_To create this XML:_ `<supplied evidence="parallel" reason="undefined" cert="low"><expan>ἀρ<ex cert="low">τάβας</ex></expan> <expan>δωδέκ<ex>ατον</ex></expan> <expan>εἰκ<ex cert="low">οστοτέταρτον</ex></expan> <expan><ex>ἀρτάβας</ex></expan> <num value="1/12" rend="fraction">ι`

_Example PN Link:_ [Stud.Pal.3.503](http://papyri.info/hgv/37758)

Need to create detailed instructions and explanation

***

#### Supplied parallel, lost

_To get this PN preview:_ `???`

_Use this Leiden+:_ `_[abc]_`

_To create this XML:_ example only - `<supplied evidence="parallel" reason="lost">abc</supplied>`

_Example PN Link:_

Need to create detailed instructions and explanation

***

## Other Editorial Conventions <a id="other-editorial-conventions"></a>

### Handshift <a id="handshift"></a> ([return to top](#top))

_To get this PN preview:_ `(hand 4)`

_Use this Leiden+:_ `$m4`

_To create this XML:_ `<handShift new="m4"/>`

_Example PN Link:_ [P.Berl.Leihg.2.35](http://papyri.info/hgv/10223)

Handshift. Note: where there are multiple hands, you do not need to indicate the first.

***

#### Handshift (uncertain)

_To get this PN preview:_ `(hand 3?)`

_Use this Leiden+:_ `$m3(?)`

_To create this XML:_ `<handShift new="m3" cert="low"/>`

_Example PN Link: [P.Polit.Iud.19](http://papyri.info/hgv/44635)

Uncertain handshift.

***

### Editorial Note <a id="editorial-note"></a> ([return to top](#top))

_To get this PN preview:_ `(BGU 1,108,r reprinted in WChr 227 )`

_Use this Leiden+:_ `/*BGU 1,108,r reprinted in WChr 227*/`

_To create this XML:_ `<note xml:lang="en">BGU 1,108,r reprinted in WChr 227 </note>`

_Example PN Link:_ [BGU.1.108](http://papyri.info/ddbdp/bgu;1;108)

To indicate modern editorial comment, for example that the recto of a given text has been republished elsewhere, or that a missing string should be a month name. Use sparingly.

***

### Quotation <a id="quotation"></a> ([return to top](#top))

_To get this PN preview:_ `'ὁ γὰ̣ρ̣ ἐ̣λ̣εῶ̣ν̣ [πτωχόν]'`

_Use this Leiden+:_ `" ὁ γὰ̣ρ̣ ἐ̣λ̣εῶ̣ν̣ [πτωχόν] "`

_To create this XML:_ `<q> ὁ γ<unclear>ὰρ</unclear> <unclear>ἐλ</unclear>ε<unclear>ῶν</unclear> <supplied reason="lost">πτωχόν</supplied> </q>`

_Example PN Link:_ [P.Gen.2.1.14](http://papyri.info/hgv/34027)

Modern mark indicating quotation.

***

## Apparatus <a id="apparatus"></a>

### Orthographic Regularization <a id="orthographic-regularization"></a> ([return to top](#top))

_To get this PN preview:_ `Text: φρόνδει[σ]ο̣ν App: l. φρόντι[σ]ον`

_Use this Leiden+:_ `<:φρόντι[σ]ον|reg|φρόνδει[σ]ο̣ν:>`

_To create this XML:_ `<choice><reg>φρόντι<supplied reason="lost">σ</supplied>ον</reg><orig>φρόνδει<supplied reason="lost">σ</supplied><unclear>ο</unclear>ν</orig></choice>`

_Example PN Link:_

To be used for two classes of 'correction':

1. Regularization/'correction' of non-standard orthographic form, e.g. αἰνακούεις for ἐνακούεις; in such cases the form is 'correct' but is not spelled in the canonical fashion.
2. Correction of syntax not morphology, e.g. τῷ for τοῦ; in such cases the form is a valid one, but is not strictly correct in the context.

In past, DDbDP suppressed all diacriticals from the mistaken reading. NOTE that DDbDP now presents the reading of the papyrus in the text and the regularized reading in the apparatus (per modern convention). To support that change, we now enter orthographic 'corrections' differently.

1. For `φρόνδει[σ]ο̣ν --> φρόντισον` encode, `<:φρόντι[σ]ον|reg|φρόνδει[σ]ο̣ν:>` (Note: all Leiden except underdots on left side of 'reg')
2. PN displays: `text: φρόνδει[σ]ο̣ν / app: Read φρόντι[σ]ον`

***

#### Apparatus, orthographic regularization, multiple

_To get this PN preview:_ `Text: ἀ̣νύεται….App: l. ἀνοίεται (?), i.e. ἀνοίγεται (?)`

_Use this Leiden+:_ `<:ἀνοίγεται (?)|ἀνοίεται (?)||reg||ἀ̣νύεται:>`

_To create this XML:_ `<choice><reg cert="low">ἀνοίγεται </reg><reg cert="low">ἀνοίεται </reg><orig><unclear>ἀ</unclear>νύεται</orig></choice>`

_Example PN Link:_

Leiden+ supports not only simple regularizations but 'chains' of regularization. For example, let us say that I scribe wrote "ἀ̣νύεται", which is held to be a likely phonetic representation of ἀνοίεται, which itself perhaps ought to be regularized to ἀνοίγεται.

    <:ἀνοίγεται (?)|ἀνοίεται (?)||reg||ἀ̣νύεται:>

***

#### Apparatus, orthographic regularization, for language

_To get this PN preview:_ `Text: ⲁⲣⲁⲕ….App: i.e. Greek ἄρακος`

_Use this Leiden+:_ `<:ἄρακος=grc|reg|ⲁⲣⲁⲕ:>`

_To create this XML:_ `<choice><reg xml:lang="grc">ἄρακος</reg><orig>ⲁⲣⲁⲕ</orig></choice>`

_Example PN Link:_

Leiden+ treats multi-lingual equivalencies as a kind of rough 'regularization'. So, if a mainly Greek text has some Coptic written in it, and you would like to indicate the Greek word that a Coptic word represents, mark up as follows:

    <:ἄρακος=grc|reg|ⲁⲣⲁⲕ:>

The text will print `ⲁⲣⲁⲕ` and the app will read `"i.e. Greek ἄρακος"`

***

### Alternate Reading <a id="alternate-reading"></a> ([return to top](#top))

_To get this PN preview:_ `Text: Ὀχυρυγχίτου…App: or Ὀξυρυγχίτου νομοῦ`

_Use this Leiden+:_ `<:Ὀχυρυγχίτου|alt|Ὀξυρυγχίτου νομοῦ:>`

_To create this XML:_ `<app type="alternative"><lem>Ὀχυρυγχίτου</lem><rdg>Ὀξυρυγχίτου νομοῦ</rdg></app>`

_Example PN Link:_ [BGU.6.1265](http://papyri.info/hgv/4548)

Alternate readings posited by the editor. Preferred reading (`<lem>`) will appear in the text, the alternative (`<rdg>`) in the apparatus.

***

#### Alternate reading, multiple <a id="alternate-reading-multiple"></a>

_To get this PN preview:_ `Text: [ - ca.? - ] ̣αμεν ̣ν̣…App: or [ἀπογρα]ψ̣αμένη̣ν̣, or [θρε]ψ̣αμένη̣ν̣`

_Use this Leiden+:_ `<:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:>`

_To create this XML:_ `<app type="alternative"><lem><gap reason="lost" extent="unknown" unit="character"/><gap reason="illegible" quantity="1" unit="character"/>αμεν<gap reason="illegible" quantity="1" unit="character"/><unclear>ν</unclear></lem><rdg><supplied reason="lost">ἀπο`

_Example PN Link:_

Multiple alternate readings posited by the editor. Preferred reading (`<lem>`) will appear in the text, the alternatives (`<rdg>`) in the apparatus.

Where the papyrus reads, e.g. `[ - - - ] ̣αμεν ̣ν̣` and the editor posits perhaps `[ἀπογρα]ψ̣αμένη̣ν̣` or `[θρε]ψ̣αμένη̣ν̣`, encode:

    <:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:>

***

#### Alternate reading (uncertain) <a id="alternate-reading-uncertain"></a>

_To get this PN preview:_ `Text: Ὀχυρυγχίτου(?)…App: or Ὀξυρυγχίτου νομοῦ(?)`

_Use this Leiden+:_ `<:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):>`

_To create this XML:_ `<app type="alternative"><lem>Ὀχυρυγχίτου<certainty match=".." locus="value"/></lem><rdg>Ὀξυρυγχίτου νομοῦ<certainty match=".." locus="value"/></rdg></app>`

_Example PN Link:_ [bgu;6;1265](http://papyri.info/ddbdp/bgu;6;1265)

By definition, all alternate readings are uncertain, but to indicate especial uncertainty as to one or both possibilities, enter as follows:

    <:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):>

***

### Scribal Correction <a id="scribal-correction"></a> ([return to top](#top))

_To get this PN preview:_ `Text: τοῦ…App: corr. from της`

_Use this Leiden+:_ `<:τοῦ|subst|της:>`

_To create this XML:_ `<subst><add place="inline">τοῦ</add><del rend="corrected">της</del></subst>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/ddbdp/bgu;1;154)

To indicate scribal corrections and alterations. Note that as a general rule, the original reading does not carry diacriticals; also that this apparatus tag is used for entire words and not for the corrected characters alone.

Indicating that the scribe wrote της and corrected to τοῦ: `<:τοῦ|subst|της:>`

    No: τ<:οῦ|subst|ης:>
    Yes: <:τοῦ|subst|της:>

***

#### Scribal correction (uncertain)

_To get this PN preview:_ `Text: τοῦ…App: corr. from της --> Text: τοῦ(?)…App: corr. from της(?)`

_Use this Leiden+:_ `<:τοῦ(?)|subst|της(?):>`

_To create this XML:_ `<subst><add place="inline">τοῦ<certainty match=".." locus="value"/></add><del rend="corrected">της<certainty match=".." locus="value"/></del></subst>`

_Example PN Link:_ [BGU.1.154](http://papyri.info/ddbdp/bgu;1;154)

To indicate scribal corrections and alterations where one or both readings is uncertain. Follow the conventions for an ordinary scribal correction, but add (?) to the affected reading.

    <:τοῦ|subst|της:> --> <:τοῦ(?)|subst|της(?):>

***

### Spelling Correction <a id="spelling-correction"></a> ([return to top](#top))

_To get this PN preview:_ `Text: τιμὴν….App: τμμὴν pap.`

_Use this Leiden+:_ `<:τιμὴν|corr|τμμὴν:>`

_To create this XML:_ `<choice><corr>τιμὴν</corr><sic>τμμὴν</sic></choice>`

_Example PN Link:_

For correction of outright scribal error, e.g. `στ[ρ]α̣ττεός` for `στρατηγός`.

1. where possible enter `στρατ{τ}ηγός` rather than `<:στρατηγός|corr|στραττηγός:>`
(NOTE: this does not apply to e.g. `ὁμολογῶι`, which is to be encoded as an orthographic regularization: `<:ὁμολογῶ|reg|ὁμολογῶι:>`)
2. where possible enter `στρα<τ>ηγός` rather than `<:στρατηγός|corr|στραηγός:>`
3. in the case of `στ[ρ]α̣ττεός` for `στρατηγός`
    1. enter `<:(στ[ρ]ατ{τ}η<γ>(ός))|corr|(στ[ρ]α̣ττε(ός)):>` (Note: all Leiden except for underdots on left side of `'corr'`)
    2. PN displays: `text: στ[ρ]α̣ττε(ός) / app: l. στρατηγός (corr)`

***

## Corrections to Published Texts <a id="corrections-to-published-texts"></a>

### Berichtigungliste Corrections <a id="berichtigungliste-corrections"></a> ([return to top](#top))

_To get this PN preview:_ `Text: αἱ τοῦ…App: BL 9.17: Θίτου Original ed.`

_Use this Leiden+:_ `<:αἱ τοῦ=BL 9.17|ed|Θίτου:>`

_To create this XML:_ `<app type="editorial"><lem resp="BL 9.17">αἱ τοῦ</lem><rdg>Θίτου</rdg></app>`

_Example PN Link:_ [BGU.1.141](http://papyri.info/hgv/8916)

To indicate corrections that have been flagged in the Berichtigungsliste, e.g. <:αἱ τοῦ=BL 9.17|ed|Θίτου:>, where αἱ τοῦ is the correction recorded by BL and Θίτου is the deprecated reading.

***

#### Berichtigungsliste correction (uncertain) <a id="bl-correction-uncertain"></a>

_To get this PN preview:_ `Text: αἱ τοῦ(?)…App: BL 9.17: Θίτου Original ed.`

_Use this Leiden+:_ `<:αἱ τοῦ(?)=BL 9.17|ed|Θίτου:>`

_To create this XML:_ `<app type="editorial"><lem resp="BL 9.17">αἱ τοῦ<certainty match=".." locus="value"/></lem><rdg>Θίτου</rdg></app>`

_Example PN Link:_ [bgu;1;141](http://papyri.info/hgv/8916)

To indicate uncertain corrections that have been flagged in the Berichtigungsliste

***

### Journal Article Corrections <a id="journal-article-corrections"></a> ([return to top](#top))

_To get this PN preview:_ `Text: N. Gonis, ZPE 166 (2008) 268 : Αὐρηλίου prev. ed.`

_Use this Leiden+:_ `<:Ἀντωνίνου=N. Gonis, ZPE 166 (2008) 268|ed|Αὐρηλίου:>`

_To create this XML:_ `<app type="editorial"><lem resp="N. Gonis, ZPE 166 (2008) 268">Ἀντωνίνου</lem><rdg>Αὐρηλίου</rdg></app>`

_Example PN Link:_ [BGU.1.237](http://papyri.info/hgv/8998)

To indicate corrections that have been flagged in a journal article, e.g. <:Ἀντωνίνου=N. Gonis, ZPE 166 (2008) 268|ed|Αὐρηλίου:>, where Ἀντωνίνου is the correction recorded by the article and Αὐρηλίου is the deprecated reading.

***	    
	    
### Editorial Correction <a id="editorial-correction"></a> ([return to top](#top))

_To get this PN preview:_ `Text: κγ…App: bgu 1 p.357: κϛ Original ed.`

_Use this Leiden+:_ `<:<#κγ=23#>=BGU 1 p.357|ed|<#κϛ=26#>:>`

_To create this XML:_ `<app type="editorial"><lem resp="BGU 1 p.357"><num value="23">κγ</num></lem><rdg><num value="26">κϛ</num></rdg></app>`

_Example PN Link:_ [BGU.1.154](http://papyri.info/hgv/8922)

Used for two situations: to indicate a correction proposed in a publication (not reported by Berichtigungsliste); either

1. correction proposed in series Corrigenda list: `<:<#κγ=23#>=bgu 1 p.357|ed|<#κϛ=26#>:>`, where κγ is the new reading and κϛ is the deprecated reading.
2. or proposed in a publication: `<:(διαγρ(άφου))=N. Gonis, ZPE 143 (2003) 150|ed|(διαγρ(αφῆς)):>`, where διαγρ(άφου) is the new reading and διαγρ(αφῆς) is the deprecated reading.

***

#### Editorial correction (uncertain)

_To get this PN preview:_ `Text: κγ(?)…App: bgu 1 p.357: κϛ Original ed.`

_Use this Leiden+:_ `<:<#κγ=23#>(?)=bgu 1 p.357|ed|<#κϛ=26#>:>`

_To create this XML:_ `<app type="editorial"><lem resp="bgu 1 p.357"><num value="23">κγ</num><certainty match=".." locus="value"/></lem><rdg><num value="26">κϛ</num></rdg></app>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/ddbdp/bgu;1;154)

Where an editorial correction is only tentative, uncertain, enter as follows:

    <:<#κγ=23#>(?)=BGU 1 p.357|ed|<#κϛ=26#>:>

***

### PN/PE Correction <a id="pnpe-correction"></a> ([return to top](#top))

_To get this PN preview:_ `Text: τοῦ…App: W.G. Claytor (CPR VI plate 35): Om. Original ed.`

_Use this Leiden+:_ `<:τοῦ=PN W.G. Claytor (CPR VI plate 35)|ed|:>`

_To create this XML:_ `<app type="editorial"><lem resp="PN W.G. Claytor (CPR VI plate 35)">τοῦ</lem><rdg/></app>`

_Example PN Link:_ [cpr;6;82](http://papyri.info/ddbdp/cpr;6;82)

Indicates a correction proposed directly to DDbDP via PE.

So, the following emendation observes the omission from an edition of a word clearly visible (from the published plate) on the papyrus:

    <:τοῦ=PN W.G. Claytor (CPR VI plate 35)|ed|:>

The corrected text is το­ῦ and the deprecated text is 'null', since this corrects an omission. Had the emendation sought to correct an existing (rather than omitted) reading, it might have looked like this:

    <:τοῦ=PN W.G. Claytor (CPR VI plate 35)|ed|μου:>

***

### Complicated Corrections <a id="complicated-corrections"></a> ([return to top](#top))

_To get this PN preview:_ `275. corr. ex σ ̣ ̣[ -ca.?- ] (or γ ̣ ̣ ̣[ -ca.?- ]), BL 15.2 : ξτρ[ατηλάτης] (l. στρ[ατηλάτης) (or ̣γρ[ -ca.?- ]) J. Cowey, ZPE 150 (2020) 321-323 : στυ̣ρ[ατ -ca.?- ] (l. στρ[ατιώτης (or στρ[ατηγία])) R. Ast, CdE 100 (2018) 13-15 (BL 14.5) : etc.`

_Use this Leiden+:_ `<:<:στρ[ατηγὸς]|subst|<:σ.2[.?]|alt|γ.3[.?]:>:>=BL 15.2||ed||<:<:στρ[ατηλάτης]|reg|ξτρ[ατηλάτης]:>|alt|.1γρ[.?]:>=J. Cowey, ZPE 150 (2020) 321-323|<:<:στρ[ατιώτης]|alt|στρ[ατηγία]:>|reg|στυ̣ρ[ατ][.?]:>=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)|<:Συρ[ίων](?)|`

_To create this XML:_ `<app type="editorial"><lem resp="BL 15.2"><subst><add place="inline">στρ<supplied reason="lost">ατηγὸς</supplied></add><del rend="corrected"><app type="alternative"><lem>σ<gap reason="illegible" quantity="2" unit="character"/><gap reason="lost" extent="un`

_Example PN Link:_

Leiden+ is capable of handling even extremely complicated series of corrections. Take the following completely fictional example:

    275. <:<:στρ[ατηγὸς]|subst|<:σ.2[.?]|alt|γ.3[.?]:>:>=BL 19.2||ed||
    <:<:στρ[ατηλάτης]|reg|ξ̣τ̣ρ[ατηλάτης]:>|alt|.1γρ[.?]:>=J. Cowey, ZPE 150 (2020) 321-323|
    <:<:στρ[ατιώτης]|alt|στρ[ατηγία]:>|reg|στυ̣ρ[ατ][.?]:>=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)|
    <:Συρ[ίων](?)|reg|<:<:Σο̣υ̣ρ[ίων]||alt||Συ̣υ̣ρ[ίων]|Σω̣υ̣ρ[ίων]:>|subst|Σ.2ρ[ίων]:>:>=Original Edition:>

This means:

1. at line 275 the DDbDP prints `στρ[ατηγὸς]`, which the scribe himself corrected from either `"σ . . [ca.?]"` or `"γ . . . [ca.?]"`, and which is recorded in BL vol.19 p.2
2. previously, Cowey had argued (in ZPE 150) for correcting the text to either στρ[ατηλάτης], which is a modern regularization of `ξ̣τ̣ρ[ατηλάτης]`, or to `". γρ[ca.?]" `
3. before Cowey, Ast had suggested (in CdÉ 100) that the papyrus reads στυ̣ρ[ατ- ca.?], which should be regularized either to στρ[ατιώτης] or to στρ[ατηγία]; this was subsequently picked up by BL 14.5
4. The original editors of the papyrus thought that the scribe had originally written "Σ . . ρ[ίων]", and then corrected it to either `Σο̣υ̣ρ[ίων] or Συ̣υ̣ρ[ίων] or Σω̣υ̣ρ[ίων]`, any one of which should perhaps be regularized to `Συρ[ίων] `

Under this model, simple corrections may be concatenated:

    275a. <:στρ[ατηγὸς]=BL 15.2||ed||
    στρ[ατηλάτης]=J. Cowey, ZPE 150 (2020) 321-323|
    στρ[ατιώτης]=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)|
    Συρ[ίων]=Original Edition:>

or, any class of correction may be 'nested' inside any other (as above).

***

## Numbers and Special Characters <a id="numbers-and-special-characters"></a>

### Numbers <a id="numbers"></a> ([return to top](#top))

#### Number whole

_To get this PN preview:_ `ιϛ`

_Use this Leiden+:_ `<#ιϛ=16#>`

_To create this XML:_ `<num value="16">ιϛ</num>`

_Example PN Link:_ [P.Berl.Leihg.1.8](http://papyri.info/hgv/10217)

Numbers should be accompanied by their values.

***

#### Number fraction

_To get this PN preview:_ `ιϛ`

_Use this Leiden+:_ `<#ιϛ=1/16#>`

_To create this XML:_ `<num value="1/16">ιϛ</num>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/ddbdp/bgu;1;154)

Fractions should be accompanied by their values, just as whole numbers.

Please note that papyri.info uses a _Greek delta_ (NOT a Latin "d") for 1/4: `<num value="1/4">δ</num>`. Other notable Unicode characters are 𐅵 for 1/2 `<num value="1/2">𐅵</num>` and 𐅷 for 2/3 `<num value="2/3">𐅷</num>`.

***

#### Number with `'`

_To get this PN preview:_ `λβ´`

_Use this Leiden+:_ `<#λβ '=1/32#>`

_To create this XML:_ `<num value="1/32" rend="tick">λβ</num>`

_Example PN Link:_ [P.Matr.1](http://papyri.info/hgv/18215)

To indicate the presence of a tick on the papyrus. This works for both fractions and whole numbers. In the PN a mouseover pop-up will alert you as to whether a number is whole or fraction. Note: the tick must be the standard ascii (`'`), not a Smart Quote, and not a Greek Unicode apostrophe (just as the system requires `<...>` and does not permit Greek Unicode `⟨...⟩`)

For example:

		<γ '=3>
		<γ '=1/3>

***

#### Uncertainly read number

_To get this PN preview:_ `σ̣ν̣ϛ̣´`

_Use this Leiden+:_ `<#σ̣ν̣ϛ̣ '=1/256#>`

_To create this XML:_ `<num value="1/256" rend="tick"><unclear>σνϛ</unclear></num>`

_Example PN Link:_ [O.Bodl.2](http://papyri.info/hgv/72534)

Underdot numbers as you would any other uncertainly read character.

***

#### Illegible numbers

_To get this PN preview:_ `  ̣  ̣`

_Use this Leiden+:_ `<#.2=#>`

_To create this XML:_ `<num><gap reason="illegible" quantity="2" unit="character"/></num>`

_Example PN Link:_ [P.Oxy.64.4435](http://papyri.info/hgv/32161)

To indicate presence of an illegible number

***

#### Missing numbers

_To get this PN preview:_ `[  ̣  ̣ ]`

_Use this Leiden+:_ `<#[.2]=#>`

_To create this XML:_ `<num><gap reason="lost" quantity="2" unit="character"/></num>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/ddbdp/bgu;1;154)

To indicate a lost number, simply enter a lacuna where you would normally enter the Greek number and leave the value blank.

***

#### Number, no symbol

_To get this PN preview:_ `nothing`

_Use this Leiden+:_ `<#=4#>`

_To create this XML:_ `<num value="4"/>`

_Example PN Link:_ [P.Matr.2](http://papyri.info/hgv/18216)

Numbers that are spelled out in Latin and Greek are followed by 'empty' number tags.

***

#### Number, fraction, no symbol

_To get this PN preview:_ `nothing`

_Use this Leiden+:_ `<#=1/8#>`

_To create this XML:_ `<num value="1/8"/>`

_Example PN Link:_ [P.Matr.2](http://papyri.info/hgv/18216)

Numbers that are spelled out in Latin and Greek are followed by 'empty' number tags.

***

#### Number with symbol & value with markup

_To get this PN preview:_ `ι[ε(?)] = SoSOL, α[ε][̣]̣ = PN`

_Use this Leiden+:_ `<#ι[ε(?)]=15#>`

_To create this XML:_ `<num value="15">ι<supplied reason="lost" cert="low">ε</supplied></num>`

_Example PN Link:_ [P.Berl.Leihg.1.8](http://papyri.info/hgv/10217)

Need to create detailed instructions and explanation

***

### Diacriticals <a id="diacriticals"></a> ([return to top](#top))

#### Diaeresis

_To get this PN preview:_ `Text: υ ἱ(¨)οῦ…App:16. υϊου pap.`

_Use this Leiden+:_ `υ ἱ(¨)οῦ`

_To create this XML:_ `υ<hi rend="diaeresis">ἱ</hi>οῦ`

_Example PN Link:_ [P.Berl.Leihg.2.35](http://papyri.info/hgv/10223)

Diaeresis written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed. Example: `υ ἱ(¨)οῦ`

***

#### Asper

_To get this PN preview:_ `Text: ὧ ... App: ὡ pap.`

_Use this Leiden+:_ `ὧ( ῾)`

_To create this XML:_ `<hi rend="asper">ὧ</hi>`

_Example PN Link:_ [P.Oxy.14.1765](http://papyri.info/hgv/31807)

Asper written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

***

#### Acute

_To get this PN preview:_ `Text: ὃ ... App.: ό pap.`

_Use this Leiden+:_ `ὃ(´)`

_To create this XML:_ `<hi rend="acute">ὃ</hi>`

_Example PN Link:_ [P.Oxy.16.1854](http://papyri.info/hgv/37860)

Acute written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

***

#### Circumflex

_To get this PN preview:_ `Text: ὑ ... App: ῦ pap.`

_Use this Leiden+:_ `ὑ(^)`

_To create this XML:_ `<hi rend="circumflex">ὑ</hi>`

_Example PN Link:_ [P.Oxy.1.125](http://papyri.info/hgv/20769)

Circumflex written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

***

#### Lenis

_To get this PN preview:_ `Text: ἄ ... App.: ἀ pap.`

_Use this Leiden+:_ `Ἀ( ᾿)`

_To create this XML:_ `<hi rend="lenis">Ἀ</hi>`

_Example PN Link:_ [BGU.3.715](http://papyri.info/hgv/9313)

Lenis written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

***

#### Double diacritical

_To get this PN preview:_ `Text: ἵ ... App.: ἱ pap. ί pap. --> Text: ἵ ... App.: ἵ pap.`

_Use this Leiden+:_ `ἵ( ῾´)`

_To create this XML:_ `<hi rend="asper"><hi rend="acute">ἵ</hi></hi>`

_Example PN Link:_ [P.Ryl.4.624](http://papyri.info/hgv/32762)

Multiple ancient diacriticals. For double diacriticals simply combine the ordinary symbols inside a single pair pf parens.

***

#### Diacritical over illegible character

_To get this PN preview:_ `Text: ̣ ... App.: ¨ pap.`

_Use this Leiden+:_ `.1(¨)`

_To create this XML:_ `<hi rend="diaeresis"><gap reason="illegible" quantity="1" unit="character"/></hi>`

_Example PN Link:_ [CPR.5.6](http://papyri.info/hgv/16028)

Ancient diacritical written atop illegible character. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

***

#### Diacritical over lost character

_To get this PN preview:_ `Text: [ ̣] ... App.: ´ pap.`

_Use this Leiden+:_ `[.1](´)`

_To create this XML:_ `<hi rend="acute"><gap reason="lost" quantity="1" unit="character"/></hi>`

_Example PN Link:_ [P.Wisc.2.70](http://papyri.info/hgv/26685)

Ancient diacritical written atop character that is now lost in lacuna. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

***

### Special Characters <a id="special-characters"></a> ([return to top](#top))

#### Paragraphos

_To get this PN preview:_ `——`

_Use this Leiden+:_ `----`

_To create this XML:_ `<milestone rend="paragraphos" unit="undefined"/>`

_Example PN Link:_ [BGU.1.28](http://papyri.info/hgv/9025)

To indicate paragraphos between, say, lines 4 and 5, enter as follows:


		3. text

		4. text

		----

		5. text


Note: paragraphoi should be entered 'between lines', as above, and not on their own lines.

***

#### Horizontal rule on papyrus

_To get this PN preview:_ `————————`

_Use this Leiden+:_ `--------`

_To create this XML:_ `<milestone rend="horizontal-rule" unit="undefined"/>`

_Example PN Link:_ [BGU.7.1526](http://papyri.info/hgv/4776)

To indicate horizontal rule on papyrus. To indicate paragraphos between, say, lines 4 and 5, enter as follows:


		3. text

		4. text

		--------

		5. text


Note: horizontal rules should be entered 'between lines', as above, and not on their own lines.

***

#### Wavy Line

_To get this PN preview:_ `~~~~~~~~`

_Use this Leiden+:_ `~~~~~~~~`

_To create this XML:_ `<milestone rend="wavy-line" unit="undefined"></>`

_Example PN Link:_ [BGU.19.2777](http://papyri.info/hgv/91687)

To indicate a wavy line between, say, lines 4 and 5, enter as follows:


		3. text

		4. text

		~~~~~~~~

		5. text


Note: wavy lines should be entered 'between lines', as above, and not on their own lines.

***

#### Diple obelismene or forked paragraphos

_To get this PN preview:_ `>---`

_Use this Leiden+:_ `>---`

_To create this XML:_ `<milestone rend="diple-obelismene" unit="undefined"></>`

_Example PN Link:_ [TM 59697](http://papyri.info/dclp/59697)

To indicate a forked paragraphos or diple obelismene between, say, lines 4 and 5, enter as follows:


		3. text

		4. text

		>---

		5. text


Note: a diple obelismene should be entered 'between lines', as above, and not on its own line.

***

#### Coronis

_To get this PN preview:_ `⸎`

_Use this Leiden+:_ `-$$-`

_To create this XML:_ `<milestone rend="coronis" unit="undefined"></>`

_Example PN Link:_ [BKT.9.88](http://papyri.info/dclp/60216)

To indicate a coronis between, say, lines 4 and 5, enter as follows:


		3. text

		4. text

		-$$-

		5. text


Note: a coronis should be entered 'between lines', as above, and not on its own line.

***

#### Non-alphabetical characters or symbols (example: slanting-stroke)

_To get this PN preview:_ `/`

_Use this Leiden+:_ `*slanting-stroke*`

_To create this XML:_ `<g type="slanting-stroke"/>`

_Example PN Link:_ [P.Berl.Leihg.2.38](http://papyri.info/hgv/10227)

To indicate slanting stroke(s) written on papyrus.

***

#### Uncertain non-alphabetical characters or symbols (example: check)

_To get this PN preview:_ `/̣`

_Use this Leiden+:_ `*check?*`

_To create this XML:_ `<unclear><g type="check"/></unclear>`

_Example PN Link:_ [BGU.1.186](http://papyri.info/hgv/8946)

Unclear ancient 'check' mark on papyrus.

***

#### Non-alphabetical character with symbol (example: Chi-rho)

_To get this PN preview:_ `☧`

_Use this Leiden+:_ `*chirho*`

_To create this XML:_ `<g type="chirho"/g>`

_Example PN Link:_

To indicate chi-rho symbol; you may indicate preferred Unicode symbol: `*chirho,☧*`

***

#### Uncertain non-alphabetical character with symbol (example: Chi-rho)

_To get this PN preview:_ `☧̣`

_Use this Leiden+:_ `*chirho?*`

_To create this XML:_ `<unclear><g type="chirho"/></unclear>`

_Example PN Link:_ [p.jena;2;19](http://papyri.info/hgv/128700)

To indicate an uncertain chi-rho symbol; you may indicate preferred Unicode symbol: `*chirho?,☧*`

***

#### Filler stroke

_To get this PN preview:_ `―`

_Use this Leiden+:_ `*filler(extension)*`

_To create this XML:_ `<g rend="extension" type="filler"/>`

_Example PN Link:_ [P.Berl.Leihg.1.17](http://papyri.info/hgv/10201)

Filler strokes, usually at end of line.

***

#### Filler stroke (uncertain)

_To get this PN preview:_ `ø --> ―(?)`

_Use this Leiden+:_ `*filler(extension)?*`

_To create this XML:_ `<unclear><g rend="extension" type="filler"/></unclear>`

_Example PN Link:_ [BGU.2.509](http://papyri.info/hgv/28171)

Unclear filler stroke on papyrus.

***

#### S-type etous

_To get this PN preview:_ `((s-etous))`

_Use this Leiden+:_ `*s-etous*`

_To create this XML:_ `<g type="s-etous"/>`

_Example PN Link:_ [P.Lips.1.109](http://papyri.info/hgv/22431)

S-type etous symbol.

***

#### 'Parens' on papyrus

_To get this PN preview:_ `((parens-punctuation-opening)) ((parens-punctuation-closing)) --> distinct unicode parens`

_Use this Leiden+:_ `*parens-punctuation-opening* *parens-punctuation-closing*`

_To create this XML:_ `<g type="parens-punctuation-opening"/> <g type="parens-punctuation-closing"/>`

_Example PN Link:_ [bgu.7.1621](http://papyri.info/ddbdp/bgu;7;1621)

Text marked in antiquity with opening parens, closing parens, or both. If the ancient parens indicate(s) deletion mark the affected string with `((parens-punctuation-opening))` and/or `((parens-punctuation-closing))` and fully enclose in `〚...〛`. If the semantic meaning of the parens is not clearly deletion, then use `((parens-punctuation-opening))` and/or `((parens-punctuation-closing))` alone.

***

#### Figure on papyri

_To get this PN preview:_ `seal`

_Use this Leiden+:_ `#seal`

_To create this XML:_ `<figure><figDesc>seal</figDesc></figure>`

_Example PN Link:_ [P.Cair.Zen.1.59003](http://papyri.info/ddbdp/p.cair.zen;1;59003)

Need to create detailed instructions and explanation

***

## Language <a id="language"></a>

### Non-default Language <a id="non-default-language"></a> ([return to top](#top))

_To get this PN preview:_ `γενήσεται`

_Use this Leiden+:_ `~|γενήσεται|~grc`

_To create this XML:_ `<foreign xml:lang="grc">γενήσεται</foreign>`

_Example PN Link:_ [SB.20.14688](http://papyri.info/hgv/23792)

Indicate text strings written in a language/script other than the document's default as follows:

		Greek = ~|γενήσεται|~grc
		Latin = ~|comes|~la
		Coptic = ~|ⲁⲛⲟⲕ|~cop 
		Demotic = ~|ı͗bd|~egy-Egyd 
		Ancient Greek in Latin script = ~|di emu|~grc-Latn
		Latin in Greek script = ~|σουσκριβερεντ|~la-Grek

NOTE: You must enter a space after the language designator; so, not `"~la"`, but `"~la "`.

NOTE: The standard language designators are: `ar` (Arabic); `cop` (Coptic); `egy-Egyd` (Demotic); `grc` (Greek); `la` (Latin); `grc-Latn` (Ancient Greek in Latin script); `la-Grek` (Latin in Greek script).

***

#### Non-default Language: Latin

_To get this PN preview:_ `comes`

_Use this Leiden+:_ `~|comes|~la`

_To create this XML:_ `<foreign xml:lang="la">comes</foreign>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/ddbdp/bgu;1;154)

If the default language of a text is Greek, mark strings of Latin as follows: `~|comes|~la`

***

### Omitted <a id="omitted"></a> ([return to top](#top))

#### Omitted language

_To get this PN preview:_ `Demotic 1 line`

_Use this Leiden+:_ `(Lang: Demotic 1 lines)`

_To create this XML:_ `<gap reason="ellipsis" quantity="1" unit="line"><desc>Demotic</desc></gap>`

_Example PN Link:_ [P.Hib.1.142](http://papyri.info/hgv/4593)

Lines of Demotic omitted from DDbDP or edition.

***

#### Omitted language

_To get this PN preview:_ `Coptic ? lines`

_Use this Leiden+:_ `(Lang: Coptic ? lines)`

_To create this XML:_ `<gap reason="ellipsis" extent="unknown" unit="line"><desc>Coptic</desc></gap>`

_Example PN Link:_ [Stud.Pal.10.172](http://papyri.info/hgv/15004)

Lines of Coptic omitted from DDbDP or edition.

***

#### Omitted language

_To get this PN preview:_ `Demotic ? lines`

_Use this Leiden+:_ `(Lang: Demotic ? lines)`

_To create this XML:_ `<gap reason="ellipsis" extent="unknown" unit="line"><desc>Demotic</desc></gap>`

_Example PN Link:_ [T.Mom.Louvre.30](http://papyri.info/hgv/54520)

Unknown number of lines of Demotic omitted from DDbDP or edition.

***

#### Omitted language

_To get this PN preview:_ `Demotic 2 characters`

_Use this Leiden+:_ `(Lang: Demotic 2 char)`

_To create this XML:_ `<gap reason="ellipsis" quantity="2" unit="character"><desc>Demotic</desc></gap>`

_Example PN Link:_ [O.Wilck.457](http://papyri.info/hgv/50773)

Demotic characters omitted from DDbDP or edition.

***

#### Omitted language

_To get this PN preview:_ `Demotic ? characters`

_Use this Leiden+:_ `(Lang: Demotic ? char)`

_To create this XML:_ `<gap reason="ellipsis" extent="unknown" unit="character"><desc>Demotic</desc></gap>`

_Example PN Link:_ [O.Leid.15](http://papyri.info/hgv/43479)

Unknown number of Demotic characters omitted from DDbDP or edition.

***

#### Untranscribed

_To get this PN preview:_ `19 lines untranscribed`

_Use this Leiden+:_ `(Lines: 19 non transcribed)`

_To create this XML:_ `<gap reason="ellipsis" quantity="19" unit="line"><desc>non transcribed</desc></gap>`

_Example PN Link:_ [P.Tebt.2.574](http://papyri.info/hgv/28475)

Known number of lines left untranscribed by editor.

***

#### Untranscribed

_To get this PN preview:_ `? lines untranscribed`

_Use this Leiden+:_ `(Lines: ? non transcribed)`

_To create this XML:_ `<gap reason="ellipsis" extent="unknown" unit="line"><desc>non transcribed</desc></gap>`

_Example PN Link:_ [Stud.Pal.10.178](http://papyri.info/hgv/38980)

Unknown number of lines left untranscribed by editor.

***

#### Untranscribed

_To get this PN preview:_ `1-3 lines untranscribed`

_Use this Leiden+:_ `(Lines: 1-3 non transcribed)`

_To create this XML:_ `<gap reason="ellipsis" atLeast="1" atMost="3" unit="line"><desc>non transcribed</desc></gap>`

_Example PN Link:_ [P.Oxy.58.3958](http://papyri.info/hgv/17940)

Range of lines left untranscribed by editor.

***

#### Untranscribed

_To get this PN preview:_ `ca.7 lines untranscribed`

_Use this Leiden+:_ `(Lines: ca.7 non transcribed)`

_To create this XML:_ `<gap reason="ellipsis" quantity="7" unit="line" precision="low"><desc>non transcribed</desc></gap>`

_Example PN Link:_ [P.Oxy.2.396](http://papyri.info/hgv/25686)

Estimated number of lines left untranscribed by editor.

***

#### Untranscribed

_To get this PN preview:_ `? characters untranscribed`

_Use this Leiden+:_ `(Chars: ? non transcribed)`

_To create this XML:_ `<gap reason="ellipsis" extent="unknown" unit="character"><desc>non transcribed</desc></gap>`

_Example PN Link:_ [SB.20.14952](http://papyri.info/hgv/29504)

Unknown number of characters left untranscribed by editor.

***

#### Untranscribed

_To get this PN preview:_ `1 character untranscribed`

_Use this Leiden+:_ `(Chars: 1 non transcribed)`

_To create this XML:_ `<gap reason="ellipsis" quantity="1" unit="character"><desc>non transcribed</desc></gap>`

_Example PN Link:

Known number of characters left untranscribed by editor.

***

#### Untranscribed

_To get this PN preview:_ `1-2 characters untranscribed`

_Use this Leiden+:_ `(Chars: 1-2 non transcribed)`

_To create this XML:_ `<gap reason="ellipsis" atLeast="1" atMost="2" unit="character"><desc>non transcribed</desc></gap>`

_Example PN Link:_ [P.Eleph.Wagner.1.365](http://papyri.info/hgv/34332)

Range of characters left untranscribed by editor.

***

#### Untranscribed

_To get this PN preview:_ `ca.18 characters untranscribed`

_Use this Leiden+:_ `(Chars: ca.18 non transcribed)`

_To create this XML:_ `<gap reason="ellipsis" quantity="18" unit="character" precision="low"><desc>non transcribed</desc></gap>`

_Example PN Link:_

Estimated number of characters left untranscribed by editor.

***

### Orthographic Regularization, for Language <a id="orthographic-regularization-for-language"></a> ([return to top](#top))

_To get this PN preview:_ `Text: ⲁⲣⲁⲕ….App: i.e. Greek ἄρακος`

_Use this Leiden+:_ `<:ἄρακος=grc|reg|ⲁⲣⲁⲕ:>`

_To create this XML:_ `<choice><reg xml:lang="grc">ἄρακος</reg><orig>ⲁⲣⲁⲕ</orig></choice>`

_Example PN Link:_

Leiden+ treats multi-lingual equivalencies as a kind of rough 'regularization'. So, if a mainly Greek text has some Coptic written in it, and you would like to indicate the Greek word that a Coptic word represents, mark up as follows:

    <:ἄρακος=grc|reg|ⲁⲣⲁⲕ:>

The text will print `ⲁⲣⲁⲕ` and the app will read `"i.e. Greek ἄρακος"`
