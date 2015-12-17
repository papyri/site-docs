# Text Leiden+ Documentation

- Formatting - Word and Document
    - Document Division
    - Line Number
    - Vacat
    - Marginalia vel sim.
    - Special Formatting
- Preservation
    - Letters Lost
    - Lines Lost
    - Illegible
    - Vestiges
- Leiden Conventions
    - Leiden Angle Brackets `< >`
    - Leiden Braces `{ }`
    - Leiden Double Square Brackets `〚 〛`
    - Leiden Parentheses `( )`
    - Leiden Square Brackets `[ ]`
    - Leiden Underline `___`
        - Supplied
- Other Editorial Conventions
    - Handshift
    - Editorial Note
    - Quotation
- Apparatus
    - Orthographic Regularization
    - Diacriticals
    - Alternate Reading
    - Scribal Correction
    - Spelling Correction
- Corrections to Published Texts
    - Berichtigungliste Corrections
    - Editorial Correction
    - PN/PE Correction
    - Complicated Corrections
- Numbers and Special Characters
    - Number
    - Numbers
    - Diacriticals
    - Special Characters
- Language
    - Language
    - Omitted
    - Orthographic Regularization, for Language

## Formatting - Word and Document
### Document Division

#### Document Div, `ab` (anonymous block)

_To get this PN preview:_ PN does not indicate explicitly

_Use this Leiden+:_ `<= =>`

_To create this XML:_ `<ab> </ab>`

_Example PN Link:_

Every block of text must be enclosed in a `<= ... =>` pair.

#### Document Div, recto/verso

_To get this PN preview:_ `recto/verso`

_Use this Leiden+:_ `<D=.r<= 1. line of text 2. line of text =>=D> <D=.v<= 3. line of text 4. line of text =>=D>`

_To create this XML:_ `<div n="r" type="textpart"><ab> <lb n="1"/>line of text <lb n="2"/>line of text </ab></div> <div n="v" type="textpart"><ab> <lb n="3"/>line of text <lb n="4"/>line of text </ab></div>`

_Example PN Link:_

Recto and verso are indicated with closed pairs of tags as follows: 

		<D=.r<= 
		1. line of text 
		2. line of text 
		=>=D> 
		<D=.v<= 
		3. line of text 
		4. line of text 
		=>=D> 

Note that the pair of tags inside the recto/verso tags and directly adjacent to the text is the `<= =>` pair (see Document Division, ab)

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

### Line Number
### Vacat
### Marginalia vel sim.
### Special Formatting
## Preservation
### Letters Lost
### Lines Lost
### Illegible
### Vestiges
## Leiden Conventions
### Leiden Angle Brackets `< >`
### Leiden Braces `{ }`
### Leiden Double Square Brackets `〚 〛`
### Leiden Parentheses `( )`
### Leiden Square Brackets `[ ]`
### Leiden Underline `___`
#### Supplied
## Other Editorial Conventions
### Handshift
### Editorial Note

_To get this PN preview:_ `(BGU 1,108,r reprinted in WChr 227 )`

_Use this Leiden+:_ `/*BGU 1,108,r reprinted in WChr 227 */`

_To create this XML:_ `<note xml:lang="en">BGU 1,108,r reprinted in WChr 227 </note>`

_Example PN Link:_ [BGU.1.108](http://papyri.info/ddbdp/bgu;1;108)

To indicate modern editorial comment, for example that the recto of a given text has been republished elsewhere, or that a missing string should be a month name. Use sparingly.

### Quotation
## Apparatus
### Orthographic Regularization

_To get this PN preview:_ `Text: φρόντι[σ]ον….App: φρόνδει[σ]ο̣ν pap.`

_Use this Leiden+:_ `<:φρόντι[σ]ον|reg|φρόνδει[σ]ο̣ν:>`

_To create this XML:_ `<choice><reg>φρόντι<supplied reason="lost">σ</supplied>ον</reg><orig>φρόνδει<supplied reason="lost">σ</supplied><unclear>ο</unclear>ν</orig></choice>`

_Example PN Link:_

To be used for two classes of 'correction': 

1. Regularization/'correction' of non-standard orthographic form, e.g. αἰνακούεις for ἐνακούεις; in such cases the form is 'correct' but is not spelled in the canonical fashion. 
2. Correction of syntax not morphology, e.g. τῷ for τοῦ; in such cases the form is a valid one, but is not strictly correct in the context. 

In past, DDbDP suppressed all diacriticals from the mistaken reading. NOTE that DDbDP now presents the reading of the papyrus in the text and the regularized reading in the apparatus (per modern convention). To support that change, we now enter orthographic 'corrections' differently. 

1. For φρόνδει[σ]ο̣ν --> φρόντισον encode, `<:φρόντι[σ]ον|reg|φρόνδει[σ]ο̣ν:>` (Note: all Leiden except underdots on left side of 'reg') 
2. PN displays: `text: φρόνδει[σ]ο̣ν / app: Read φρόντι[σ]ον`

#### Apparatus, orthographic regularization, multiple

_To get this PN preview:_ `Text: ἀ̣νύεται….App: l. ἀνοίεται (?), i.e. ἀνοίγεται (?)`

_Use this Leiden+:_ `<:ἀνοίγεται (?)|ἀνοίεται (?)||reg||ἀ̣νύεται:>`

_To create this XML:_ `<choice><reg cert="low">ἀνοίγεται </reg><reg cert="low">ἀνοίεται </reg><orig><unclear>ἀ</unclear>νύεται</orig></choice>`

_Example PN Link:_

Leiden+ supports not only simple regularizations but 'chains' of regularization. For example, let us say that I scribe wrote "ἀ̣νύεται", which is held to be a likely phonetic representation of ἀνοίεται, which itself perhaps ought to be regularized to ἀνοίγεται. 

    <:ἀνοίγεται (?)|ἀνοίεται (?)||reg||ἀ̣νύεται:>

#### Apparatus, orthographic regularization, for language

_To get this PN preview:_ `Text: ⲁⲣⲁⲕ….App: i.e. Greek ἄρακος`

_Use this Leiden+:_ `<:ἄρακος=grc|reg|ⲁⲣⲁⲕ:>`

_To create this XML:_ `<choice><reg xml:lang="grc">ἄρακος</reg><orig>ⲁⲣⲁⲕ</orig></choice>`

_Example PN Link:_

Leiden+ treats multi-lingual equivalencies as a kind of rough 'regularization'. So, if a mainly Greek text has some Coptic written in it, and you would like to indicate the Greek word that a Coptic word represents, mark up as follows: 

    <:ἄρακος=grc|reg|ⲁⲣⲁⲕ:> 

The text will print `ⲁⲣⲁⲕ` and the app will read `"i.e. Greek ἄρακος"`

### Diacriticals

#### Diaeresis

_To get this PN preview:_ `Text: υ ἱ(¨)οῦ…App:16. υϊου pap.`

_Use this Leiden+:_ `υ ἱ(¨)οῦ`

_To create this XML:_ `υ<hi rend="diaeresis">ἱ</hi>οῦ`

_Example PN Link:_ [P.Berl.Leihg.2.35](http://papyri.info/hgv/10223)

Diaeresis written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed. Example: `υ ἱ(¨)οῦ`

#### Asper

_To get this PN preview:_ `Text: ὧ ... App: ὡ pap.`

_Use this Leiden+:_ `ὧ( ῾)`

_To create this XML:_ `<hi rend="asper">ὧ</hi>`

_Example PN Link:_ [P.Oxy.14.1765](http://papyri.info/hgv/31807)

Asper written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

#### Acute

_To get this PN preview:_ `Text: ὃ ... App.: ό pap.`

_Use this Leiden+:_ `ὃ(´)`

_To create this XML:_ `<hi rend="acute">ὃ</hi>`

_Example PN Link:_ [P.Oxy.16.1854](http://papyri.info/hgv/37860)

Acute written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

#### Circumflex

_To get this PN preview:_ `Text: ὑ ... App: ῦ pap.`

_Use this Leiden+:_ `ὑ(^)`

_To create this XML:_ `<hi rend="circumflex">ὑ</hi>`

_Example PN Link:_ [P.Oxy.1.125](http://papyri.info/hgv/20769)

Circumflex written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

#### Lenis

_To get this PN preview:_ `Text: ἄ ... App.: ἀ pap.`

_Use this Leiden+:_ `Ἀ( ᾿)`

_To create this XML:_ `<hi rend="lenis">Ἀ</hi>`

_Example PN Link:_ [BGU.3.715](http://papyri.info/hgv/9313)

Lenis written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

#### Double diacritical

_To get this PN preview:_ `Text: ἵ ... App.: ἱ pap. ί pap. --> Text: ἵ ... App.: ἵ pap.`

_Use this Leiden+:_ `ἵ( ῾´)`

_To create this XML:_ `<hi rend="asper"><hi rend="acute">ἵ</hi></hi>`

_Example PN Link:_ [P.Ryl.4.624](http://papyri.info/hgv/32762)

Multiple ancient diacriticals. For double diacriticals simply combine the ordinary symbols inside a single pair pf parens.

#### Diacritical over illegible character

_To get this PN preview:_ `Text: ̣ ... App.: ¨ pap.`

_Use this Leiden+:_ `.1(¨)`

_To create this XML:_ `<hi rend="diaeresis"><gap reason="illegible" quantity="1" unit="character"/></hi>`

_Example PN Link:_ [CPR.5.6](http://papyri.info/hgv/16028)

Ancient diacritical written atop illegible character. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

#### Diacritical over lost character

_To get this PN preview:_ `Text: [ ̣] ... App.: ´ pap.`

_Use this Leiden+:_ `[.1](´)`

_To create this XML:_ `<hi rend="acute"><gap reason="lost" quantity="1" unit="character"/></hi>`

_Example PN Link:_ [P.Wisc.2.70](http://papyri.info/hgv/26685)

Ancient diacritical written atop character that is now lost in lacuna. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.

### Alternate Reading <a id="alternate-reading"></a>

_To get this PN preview:_ `Text: Ὀχυρυγχίτου…App: or Ὀξυρυγχίτου νομοῦ`

_Use this Leiden+:_ `<:Ὀχυρυγχίτου|alt|Ὀξυρυγχίτου νομοῦ:>`

_To create this XML:_ `<app type="alternative"><lem>Ὀχυρυγχίτου</lem><rdg>Ὀξυρυγχίτου νομοῦ</rdg></app>`

_Example PN Link:_ [BGU.6.1265](http://papyri.info/hgv/4548)

Alternate readings posited by the editor. Preferred reading (`<lem>`) will appear in the text, the alternative (`<rdg>`) in the apparatus.

#### Alternate reading, multiple <a id="alternate-reading-multiple"></a>

_To get this PN preview:_ `Text: [ - ca.? - ] ̣αμεν ̣ν̣…App: or [ἀπογρα]ψ̣αμένη̣ν̣, or [θρε]ψ̣αμένη̣ν̣`

_Use this Leiden+:_ `<:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:>`

_To create this XML:_ `<app type="alternative"><lem><gap reason="lost" extent="unknown" unit="character"/><gap reason="illegible" quantity="1" unit="character"/>αμεν<gap reason="illegible" quantity="1" unit="character"/><unclear>ν</unclear></lem><rdg><supplied reason="lost">ἀπο`

_Example PN Link:_

Multiple alternate readings posited by the editor. Preferred reading (`<lem>`) will appear in the text, the alternatives (`<rdg>`) in the apparatus. 

Where the papyrus reads, e.g. `[ - - - ] ̣αμεν ̣ν̣` and the editor posits perhaps `[ἀπογρα]ψ̣αμένη̣ν̣` or `[θρε]ψ̣αμένη̣ν̣`, encode: 

    <:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:>

#### Alternate reading (uncertain) <a id="alternate-reading-uncertain"></a>

_To get this PN preview:_ `Text: Ὀχυρυγχίτου(?)…App: or Ὀξυρυγχίτου νομοῦ(?)`

_Use this Leiden+:_ `<:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):>`

_To create this XML:_ `<app type="alternative"><lem>Ὀχυρυγχίτου<certainty match=".." locus="value"/></lem><rdg>Ὀξυρυγχίτου νομοῦ<certainty match=".." locus="value"/></rdg></app>`

_Example PN Link:_ [bgu;6;1265](http://papyri.info/ddbdp/bgu;6;1265)

By definition, all alternate readings are uncertain, but to indicate especial uncertainty as to one or both possibilities, enter as follows: 

    <:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):>

### Scribal Correction

_To get this PN preview:_ `Text: τοῦ…App: corr. from της`

_Use this Leiden+:_ `<:τοῦ|subst|της:>`

_To create this XML:_ `<subst><add place="inline">τοῦ</add><del rend="corrected">της</del></subst>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/ddbdp/bgu;1;154)

To indicate scribal corrections and alterations. Note that as a general rule, the original reading does not carry diacriticals; also that this apparatus tag is used for entire words and not for the corrected characters alone. 

Indicating that the scribe wrote της and corrected to τοῦ: `<:τοῦ|subst|της:>`

    No: τ<:οῦ|subst|ης:> 
    Yes: <:τοῦ|subst|της:>

#### Scribal correction (uncertain)

_To get this PN preview:_ `Text: τοῦ…App: corr. from της --> Text: τοῦ(?)…App: corr. from της(?)`

_Use this Leiden+:_ `<:τοῦ(?)|subst|της(?):>`

_To create this XML:_ `<subst><add place="inline">τοῦ<certainty match=".." locus="value"/></add><del rend="corrected">της<certainty match=".." locus="value"/></del></subst>`

_Example PN Link:_ [BGU.1.154](http://papyri.info/ddbdp/bgu;1;154)

To indicate scribal corrections and alterations where one or both readings is uncertain. Follow the conventions for an ordinary scribal correction, but add (?) to the affected reading. 

    <:τοῦ|subst|της:> --> <:τοῦ(?)|subst|της(?):>

### Spelling Correction

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

## Corrections to Published Texts
### Berichtigungliste Corrections

_To get this PN preview:_ `Text: αἱ τοῦ…App: BL 9.17: Θίτου Original ed.`

_Use this Leiden+:_ `<:αἱ τοῦ=BL 9.17|ed|Θίτου:>`

_To create this XML:_ `<app type="editorial"><lem resp="BL 9.17">αἱ τοῦ</lem><rdg>Θίτου</rdg></app>`

_Example PN Link:_ [BGU.1.141](http://papyri.info/hgv/8916)

To indicate corrections that have been flagged in the Berichtigungsliste, e.g. <:αἱ τοῦ=BL 9.17|ed|Θίτου:>, where αἱ τοῦ is the correction recorded by BL and Θίτου is the deprecated reading.

#### Berichtigungsliste correction (uncertain) <a id="bl-correction-uncertain"></a>

_To get this PN preview:_ `Text: αἱ τοῦ(?)…App: BL 9.17: Θίτου Original ed.`

_Use this Leiden+:_ `<:αἱ τοῦ(?)=BL 9.17|ed|Θίτου:>`

_To create this XML:_ `<app type="editorial"><lem resp="BL 9.17">αἱ τοῦ<certainty match=".." locus="value"/></lem><rdg>Θίτου</rdg></app>`

_Example PN Link:_ [bgu;1;141](http://papyri.info/hgv/8916)

To indicate uncertain corrections that have been flagged in the Berichtigungsliste


### Editorial Correction

_To get this PN preview:_ `Text: κγ…App: bgu 1 p.357: κϛ Original ed.`

_Use this Leiden+:_ `<:<#κγ=23#>=BGU 1 p.357|ed|<#κϛ=26#>:>`

_To create this XML:_ `<app type="editorial"><lem resp="BGU 1 p.357"><num value="23">κγ</num></lem><rdg><num value="26">κϛ</num></rdg></app>`

_Example PN Link:_ [BGU.1.154](http://papyri.info/hgv/8922)

Used for two situations: to indicate a correction proposed in a publication (not reported by Berichtigungsliste); either 

1. correction proposed in series Corrigenda list: `<:<#κγ=23#>|ed:BGU 1 p.357|<#κϛ=26#>:>`, where κγ is the new reading and κϛ is the deprecated reading. 
2. or proposed in a publication: `<:(διαγρ(άφου))=N. Gonis, ZPE 143 (2003) 150|ed|(διαγρ(αφῆς)):>`, where διαγρ(άφου) is the new reading and διαγρ(αφῆς) is the deprecated reading.

#### Editorial correction (uncertain)

_To get this PN preview:_ `Text: κγ(?)…App: bgu 1 p.357: κϛ Original ed.`

_Use this Leiden+:_ `<:<#κγ=23#>(?)=bgu 1 p.357|ed|<#κϛ=26#>:>`

_To create this XML:_ `<app type="editorial"><lem resp="bgu 1 p.357"><num value="23">κγ</num><certainty match=".." locus="value"/></lem><rdg><num value="26">κϛ</num></rdg></app>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/ddbdp/bgu;1;154)

Where an editorial correction is only tentative, uncertain, enter as follows: 

`<:<#κγ=23#>(?)=BGU 1 p.357|ed|<#κϛ=26#>:>`

### PN/PE Correction

_To get this PN preview:_ `Text: τοῦ…App: G. Claytor (CPR VI plate 35): Om. Original ed.`

_Use this Leiden+:_ `<:τοῦ=PN G. Claytor (CPR VI plate 35)|ed|:>`

_To create this XML:_ `<app type="editorial"><lem resp="PN G. Claytor (CPR VI plate 35)">τοῦ</lem><rdg/></app>`

_Example PN Link:_ [cpr;6;82](http://papyri.info/ddbdp/cpr;6;82)

Indicates a correction proposed directly to DDbDP via PE. 

So, the following emendation observes the omission from an edition of a word clearly visible (from the published plate) on the papyrus: 

    <:τοῦ=PN G. Claytor (CPR VI plate 35)|ed|:> 

The corrected text is το­ῦ and the deprecated text is 'null', since this corrects an omission. Had the emendation sought to correct an existing (rather than omitted) reading, it might have looked like this: 

    <:τοῦ=PN G. Claytor (CPR VI plate 35)|ed|μου:> 

### Complicated Corrections

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

## Numbers and Special Characters
### Number
### Numbers
### Diacriticals
### Special Characters
## Language
### Language
### Omitted
### Orthographic Regularization, for Language

_To get this PN preview:_ `Text: ⲁⲣⲁⲕ….App: i.e. Greek ἄρακος`

_Use this Leiden+:_ `<:ἄρακος=grc|reg|ⲁⲣⲁⲕ:>`

_To create this XML:_ `<choice><reg xml:lang="grc">ἄρακος</reg><orig>ⲁⲣⲁⲕ</orig></choice>`

_Example PN Link:_

Leiden+ treats multi-lingual equivalencies as a kind of rough 'regularization'. So, if a mainly Greek text has some Coptic written in it, and you would like to indicate the Greek word that a Coptic word represents, mark up as follows: 

    <:ἄρακος=grc|reg|ⲁⲣⲁⲕ:> 

The text will print `ⲁⲣⲁⲕ` and the app will read `"i.e. Greek ἄρακος"`

