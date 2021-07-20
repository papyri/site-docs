# Sigla, Special Characters, Punctuation, and Glyphs

- Scribes and users occasionally adorn a text with paratextual material or other lexical aids. This help file offers a guide to encoding them:
- [Sigla](#sigla) <a id="top"></a>
    - [Crosses](#crosses)
    - [Strokes, Dots, and Checks](#strokes-and-checks)
    - [Scribal Punctuation](#scribal-punctuation)
- [Critical Symbols](#critical-symbols) <a id="top"></a>
    - [Aristarchan symbols](#aristarchan)
    - [Other symbols and marginalia](#other-symbols)
- [Parentheses and Braces](#scribal-parentheses) <a id="top"></a>
    - [Scribal Parentheses](#parentheses)
    - [Scribal Braces](#braces)
- [Misc. Symbols](#misc) <a id="top"></a>
    - [Magic and Monogram](#magic)
    - [Decoration](#decoration)
- [Unclear, Unintelligible, or Undefined](#unclear) <a id="top"></a>
    - [Unclear symbols](#unclear-symbols)

## Sigla <a id="sigla"></a>

### Crosses <a id="crosses"></a> ([return to top](#top))

#### Simple cross

_To get this PN preview:_ †

_Use this Leiden+:_ `*stauros*`

_To create this XML:_ `<g type="stauros"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***

#### Rho-cross

_To get this PN preview:_ ⳨

_Use this Leiden+:_ `*rho-cross*`

_To create this XML:_ `<g type="rho-cross"/>`

_Example PN Link:_ [PSI.17.1701](https://papyri.info/hgv/786119)

For staurograms of the tau-rho variety, as distinct from the `*chirho*` or `*stauros*`.

***

#### Chi-rho cross

_To get this PN preview:_ ☧

_Use this Leiden+:_ `*chirho*`

_To create this XML:_ `<g type="chirho"/>`

_Example PN Link:_ [P.Yale.1.71](https://papyri.info/hgv/16844)

For staurograms of the chi-rho variety, as distinct from the `*rho-cross*` or `*stauros*`.

***

### Strokes, Dots, and Checks <a id="strokes-and-checks"></a> ([return to top](#top))

#### Dash

_To get this PN preview:_ —

_Use this Leiden+:_ `*dash*`

_To create this XML:_ `<g type="dash"/>`

_Example PN Link:_ [CPR.30.22](https://papyri.info/hgv/79319)

For a horizontal or filler stroke that appears mid-line, often (but not necessarily) in the context of a register. For filler strokes at the end of a line, use `*filler(extension)*`.

***

#### Filler stroke

_To get this PN preview:_ —

_Use this Leiden+:_ `*filler(extension)*`

_To create this XML:_ `<g rend="extension" type="filler"/>`

_Example PN Link:_ [P.Amst.1.12](https://papyri.info/DCLP/61329)

For a filler stroke or other space filler at the end of a line. For a horizontal stroke mid-line, use `*dash*`.

***

#### Slanting stroke

_To get this PN preview:_ /

_Use this Leiden+:_ `*slanting-stroke*`

_To create this XML:_ `<g type="slanting-stroke"/>`

_Example PN Link:_ [P.Worp.48](https://papyri.info/hgv/115577)

For a diagonal slash used in-line. For slashes which appear in the left-hand margin, use `*check*`.

***

#### Reverse slanting stroke

_To get this PN preview:_ \ (PN does not yet support this character)

_Use this Leiden+:_ `*reverse-slanting-stroke*`

_To create this XML:_ `<g type="reverse-slanting-stroke"/>`

_Example PN Link:_ [SB.14.11692](https://papyri.info/hgv/30884)

For a backslash or inverted diagonal stroke. Not yet supported by EpiDoc stylesheet (consolidate with `*backslash*` first?)

***

#### Double vertical bar

_To get this PN preview:_ ‖

_Use this Leiden+:_ `*double-vertical-bar*`

_To create this XML:_ `<g type="double-vertical-bar"/>`

_Example PN Link:_ [P.Lund.2.5](https://papyri.info/hgv/41035)

For twinned vertical bars.

***


#### Long vertical bar

_To get this PN preview:_ |

_Use this Leiden+:_ `*long-vertical-bar*`

_To create this XML:_ `<g type="long-vertical-bar"/>`

_Example PN Link:_ [SB.3.7013](https://papyri.info/hgv/31057)

For a single vertical line occupying the height of a letter or more.

***


#### Swungdash

_To get this PN preview:_ ~

_Use this Leiden+:_ `*swungdash*`

_To create this XML:_ `<g type="swungdash"/>`

_Example PN Link:_ [TM 60668](https://papyri.info/dclp/60668)

For a short horizontal line that is wavy instead of straight.

***

#### Guide-dot

_To get this PN preview:_ PN does not yet support this character

_Use this Leiden+:_ `*guide-dot*`

_To create this XML:_ `<g type="guide-dot"/>`

_Example PN Link:_ [P.Leid.Inst.79](https://papyri.info/hgv/38784/source)

For inline dot(s) that fill space or which coordinate entries in a register. Enter the character separately for each dot. NB: For a dot in the left margin, use `*dot*`; for a horizontal line used to coordinate entries in a register, use `*dash*`. Not yet supported by EpiDoc stylesheet.

***

#### Dot

_To get this PN preview:_ •

_Use this Leiden+:_ `*dot*`

_To create this XML:_ `<g type="dot"/>`

_Example PN Link:_ [O.Heid.341](https://papyri.info/hgv/80547)

For dots that appear in the left margin, as in a checklist. These are occasionally difficult to distinguish from `*check*`. Mid-line or in-line dots should use `*guide-dot*`, unless they are punctuation (in which case, use `*middot*`). 

***

#### Check

_To get this PN preview:_ ／

_Use this Leiden+:_ `*check*`

_To create this XML:_ `<g type="check"/>`

_Example PN Link:_ [P.Pintaudi.21](https://papyri.info/hgv/38709)

For slashes that appear in the left margin, as in a checklist. These are occasionally difficult to distinguish from `*dot*`, and are not interchangeable with `*slanting-stroke*`, which typically appears in-line.

***

#### Tachygraphic marks

_To get this PN preview:_ tachygr. marks

_Use this Leiden+:_ `*tachygraphic-marks*`

_To create this XML:_ `<g type="tachygraphic-marks"/>`

_Example PN Link:_ [P.Cair.Masp.1.67045](https://papyri.info/hgv/18997)

For undecipherable tachygraphy. Cf. `*unintelligible*`, for a single symbol or glyph.

***

### Scribal Punctuation <a id="scribal-punctuation"></a> ([return to top](#top))

#### Apostrophe or Diastole

_To get this PN preview:_ ’

_Use this Leiden+:_ `*apostrophe*`

_To create this XML:_ `<g type="apostrophe"/>`

_Example PN Link:_ [P.Brook.87](https://papyri.info/hgv/30806)

For a scribal apostrophe, whether as a marker of elision, word-division, or as a separator of double consonants. These will appear in the apparatus criticus.

***

#### High point or ana-stigme

_To get this PN preview:_ ˙

_Use this Leiden+:_ `*high-punctus*`

_To create this XML:_ `<g type="high-punctus"/>`

_Example PN Link:_ [P.Oxy.58.3920](https://papyri.info/hgv/17904)

For scribal punctuation in the form of a high dot.

***

#### Mid point, interpunct, or mese-stigme

_To get this PN preview:_ ·

_Use this Leiden+:_ `*middot*`

_To create this XML:_ `<g type="middot"/>`

_Example PN Link:_ [C.Ep.Lat.10](https://papyri.info/hgv/15965)

For scribal punctuation in the form of a raised dot, including the Latin interpunct.

***

#### Low point, kato-stigme, or hypo-stigme

_To get this PN preview:_ .

_Use this Leiden+:_ `*low-punctus*`

_To create this XML:_ `<g type="low-punctus"/>`

_Example PN Link:_ [Stud.Pal.20.212](https://papyri.info/hgv/36613)

For scribal punctuation in the form of a low dot.

***

#### Dipunct or dicolon

_To get this PN preview:_ ∶

_Use this Leiden+:_ `*dipunct*`

_To create this XML:_ `<g type="dipunct"/>`

_Example PN Link:_ [Stud.Pal.8.1245](https://papyri.info/hgv/38103)

For scribal punctuation in the form of a dicolon or dipunct.

***

#### Tripunct

_To get this PN preview:_ ⋮

_Use this Leiden+:_ `*tripunct*`

_To create this XML:_ `<g type="tripunct"/>`

_Example PN Link:_ [CPR.31.18](https://papyri.info/hgv/140877)

For scribal punctuation in the form of a tripunct.

***

#### Tetrapunct

_To get this PN preview:_ ⁞

_Use this Leiden+:_ `*tetrapunct*`

_To create this XML:_ `<g type="tetrapunct"/>`

_Example PN Link:_ [TM 65258](https://papyri.info/dclp/65258)

For scribal punctuation in the form of a tetrapunct.

***

#### Hypodiastole

_To get this PN preview:_ ⸒

_Use this Leiden+:_ `*hypodiastole*`

_To create this XML:_ `<g type="hypodiastole"/>`

_Example PN Link:_ [PSI.16.1604](https://papyri.info/dclp/220506)

For scribal punctuation in the form of a hypodiastole, which resembles a comma.

***

## Critical Symbols <a id="critical-symbols"></a>

### Aristarchan Symbols <a id="aristarchan"></a> ([return to top](#top))

#### Asteriskos

_To get this PN preview:_ ※

_Use this Leiden+:_ `*asteriskos*`

_To create this XML:_ `<g type="asteriskos"/>`

_Example PN Link:_ [P.Grenf.1.5](https://papyri.info/dclp/61986)

For the asteriskos, whether used according to Aristarchus' system (i.e., marking genuine lines found elsewhere) or not.

***
#### Antisigma

_To get this PN preview:_ ͻ

_Use this Leiden+:_ `*antisigma*`

_To create this XML:_ `<g type="antisigma"/>`

_Example PN Link:_ [TM 63850](https://papyri.info/dclp/63850)

For the antisigma, whether used according to Aristarchus' system (i.e., marking lines with comparable content) or not. In papyri antisigma frequently marks revisions (esp. textual variants) and comments.

***
#### Antisigma periestigmene (or 'dotted' antisigma)

_To get this PN preview:_ ͽ

_Use this Leiden+:_ `*antisigma-periestigmene*`

_To create this XML:_ `<g type="antisigma-periestigmene"/>`

_Example PN Link:_ 

For the dotted antisigma, whether used according to Aristarchus' system (i.e., marking lines with comparable content, or for transposition) or not.

***
#### Diple

_To get this PN preview:_ ›

_Use this Leiden+:_ `*diple*`

_To create this XML:_ `<g type="diple"/>`

_Example PN Link:_ [BKT.10.1](https://papyri.info/dclp/175242)

For the wedge-shaped diple, typically used in the left-hand margin to mark any number of interesting features about a passage.

***

#### Diple periestigmene (or 'dotted' diple)

_To get this PN preview:_ ⸖

_Use this Leiden+:_ `*diple-periestigmene*`

_To create this XML:_ `<g type="diple-periestigmene"/>`

_Example PN Link:_ 

For the dotted diple, whether used according to Aristarchus' system (i.e., marking disagreement with Zenodotus) or not.

***

#### Obelos

_To get this PN preview:_ ―

_Use this Leiden+:_ `*obelos*`

_To create this XML:_ `<g type="obelos"/>`

_Example PN Link:_ 

For the marginal obelos, whether used according to Aristarchus' system (i.e., marking a spurious line) or not.

***

### Other Symbols <a id="other-symbols"></a> ([return to top](#top))

#### Downwards ancora

_To get this PN preview:_ ⸔

_Use this Leiden+:_ `*downwards-ancora*`

_To create this XML:_ `<g type="downwards-ancora"/>`

_Example PN Link:_ [P.Oxy.65.4452vo](https://papyri.info/dclp/60568)

The downwards ancora typically indicates an omission, and points to the margin where the omitted text has been supplied.

***

#### Upwards ancora

_To get this PN preview:_ ⸕

_Use this Leiden+:_ `*upwards-ancora*`

_To create this XML:_ `<g type="upwards-ancora"/>`

_Example PN Link:_ [P.Amh.1.1](https://papyri.info/dclp/64754)

The upwards ancora typically indicates an omission, and points to the margin where the omitted text has been supplied.

***

#### Dotted Obelos

_To get this PN preview:_ ⸓

_Use this Leiden+:_ `*dotted-obelos*`

_To create this XML:_ `<g type="dotted-obelos"/>`

_Example PN Link:_ [P.Ryl.3.467](https://papyri.info/dclp/65055)

For the dotted obelos, whether the obelos itself is horizontal or diagonal.

***

#### Chi periestigmenon (or dotted chi)

_To get this PN preview:_ Χ·

_Use this Leiden+:_ `*chi-periestigmenon*`

_To create this XML:_ `<g type="chi-periestigmenon"/>`

_Example PN Link:_ 

For the dotted chi.

***

## Parentheses and Braces <a id="scribal-parentheses"></a>

### Scribal Parentheses <a id="parentheses"></a>([return to top](#top))

#### Scribal parenthesis (opening), for text on a single line

_To get this PN preview:_ (

_Use this Leiden+:_ `*parens-punctuation-opening*`

_To create this XML:_ `<g type="parens-punctuation-opening"/>`

_Example PN Link:_ [BGU.7.1621](https://papyri.info/hgv/27592)

For text marked in antiquity with the opening of a parenthesis, bracketing something on a single line of text. For parentheses that envelop multiple lines, use `parens-upper-opening`, `parens-middle-opening`, and `parens-lower-opening` on the individual lines, as well as `parens-upper-closing`, `parens-middle-closing`, and `parens-lower-closing` (where present). If the ancient parens indicate(s) deletion mark the affected string with `*parens-punctuation-opening*` and fully enclose in 〚...〛. If the semantic meaning of the parens is not clearly deletion, then use `*parens-punctuation-opening*` alone.

***


#### Scribal parenthesis (closing), for text on a single line

_To get this PN preview:_ )

_Use this Leiden+:_ `*parens-punctuation-closing*`

_To create this XML:_ `<g type="parens-punctuation-closing"/>`

_Example PN Link:_ [BGU.7.1621](https://papyri.info/hgv/27592)

For text marked in antiquity with the closing of a parenthesis, bracketing something on a single line of text. For parentheses that envelop multiple lines, use `parens-upper-opening`, `parens-middle-opening`, and `parens-lower-opening` on the individual lines, as well as `parens-upper-closing`, `parens-middle-closing`, and `parens-lower-closing` (where present). If the ancient parens indicate(s) deletion, mark the affected string with `*parens-punctuation-closing*` and fully enclose in 〚...〛. If the semantic meaning of the parens is not clearly deletion, then use `*parens-punctuation-closing*` alone.

***

#### Multi-line scribal parenthesis (opening)

_To get this PN preview:_ ⎛, ⎜, and ⎝

_Use this Leiden+:_ `*parens-upper-opening*`, `*parens-middle-opening*`, `*parens-lower-opening*`

_To create this XML:_ `<g type="parens-upper-opening"/>`, `<g type="parens-middle-opening"/>`, and `<g type="parens-lower-opening"/>` 

_Example PN Link:_ [CPR.7.8](https://papyri.info/hgv/26662)

For text marked in antiquity with the opening of a parenthesis, bracketing multiple lines of text. Use `*parens-upper-opening*` for the topmost line, `*parens-lower-opening*` for the last line, and `*parens-middle-opening*` for any lines in between. For parenthesis on a single line, use `*parens-punctuation-opening*` and `*parens-punctuation-closing*`.

***

#### Multi-line scribal parenthesis (closing)

_To get this PN preview:_ ⎞, ⎟, and ⎠

_Use this Leiden+:_ `*parens-upper-closing*`, `*parens-middle-closing*`, `*parens-lower-closing*`

_To create this XML:_ `<g type="parens-upper-closing"/>`, `<g type="parens-middle-closing"/>`, and `<g type="parens-lower-closing"/>` 

_Example PN Link:_ [CPR.7.8](https://papyri.info/hgv/26662)

For text marked in antiquity with the opening of a parenthesis, bracketing multiple lines of text. Use `*parens-upper-closing*` for the topmost line, `*parens-lower-closing*` for the last line, and `*parens-middle-closing*` for any lines in between. For parenthesis on a single line, use `*parens-punctuation-opening*` and `*parens-punctuation-closing*`.

***

### Scribal Braces <a id="braces"></a>([return to top](#top))

#### Scribal braces

_To get this PN preview:_ 

_Use this Leiden+:_ 

_To create this XML:_ 

_Example PN Link:_ 

Need to consult with James regarding this set, for which EpiDoc stylesheets already support `*upper-brace-opening*`, `*upper-brace-closing*`, `*center-brace-opening*`, `*center-brace-closing*`, `*lower-brace-opening*`, `*lower-brace-closing*`, `*parens-deletion-opening*`, and `*parens-deletion-closing*`. 

***

## Misc. Symbols <a id="misc"></a>

### Magic and Monogram <a id="magic"></a>([return to top](#top))

#### Magical symbol

_To get this PN preview:_ ((magical-symbol))

_Use this Leiden+:_ `*magical-symbol*`

_To create this XML:_ `<g type="magical-symbol"/>`

_Example PN Link:_ [TM 64757](https://papyri.info/dclp/64757)

For magical symbols that are unsupported by Unicode and cannot be displayed.

***
#### Monogram

_To get this PN preview:_ monogr.

_Use this Leiden+:_ `*monogram*`

_To create this XML:_ `<g type="monogram"/>`

_Example PN Link:_ [CPR.9.17](https://papyri.info/hgv/45311)

Needs description added.

***

#### Paraphe

_To get this PN preview:_ ((paraphe))

_Use this Leiden+:_ `*paraphe*`

_To create this XML:_ `<g type="paraphe"/>`

_Example PN Link:_ [TravMém.16.361_1](https://papyri.info/hgv/702253)

Needs description added.

***

### Decoration <a id="decoration"></a>([return to top](#top))

#### Decorative X

_To get this PN preview:_ ☓

_Use this Leiden+:_ `*x*`

_To create this XML:_ `<g type="x"/>`

_Example PN Link:_ [P.Sarap.92](https://papyri.info/hgv/17117)

For a decorative X, as often appears on a document docket to separate entities.

***

#### Series of Decorative Xs

_To get this PN preview:_ ☓☓☓☓☓

_Use this Leiden+:_ `*xs*`

_To create this XML:_ `<g type="xs"/>`

_Example PN Link:_ [P.Brook.6](https://papyri.info/hgv/27388)

For a series of Xs, added as adornment or space filler. NB: PN will display five Xs, regardless of the number on the papyrus

***

## Unclear, Unintelligible, or Undefined <a id="unclear"></a>

### Unclear Symbols <a id="unclear-symbols"></a>([return to top](#top))

#### Unintelligible

_To get this PN preview:_ ((unintelligible))

_Use this Leiden+:_ `*unintelligible*`

_To create this XML:_ `<g type="unintelligible"/>`

_Example PN Link:_ [P.Cair.Isid.20](https://papyri.info/hgv/10353)

For an unintelligible or unidentifiable symbol. Cf. `*tachygraphic-marks*`, for a longer series of indecipherable writing.

***

#### Undefined

_To get this PN preview:_ ((undefined))

_Use this Leiden+:_ `*undefined*`

_To create this XML:_ `<g type="undefined"/>`

_Example PN Link:_ [TM 62479](https://papyri.info/dclp/62479)

Needs description added. TM 62479 is the transcription with this type.

***

#### Unclear or uncertain symbol

_To get this PN preview:_ ☧̣ or ((asteriskos?))

_Use this Leiden+:_ `*chirho?*` or `*asteriskos?*`

_To create this XML:_ `<unclear><g type="chirho"/></unclear>` or `<unclear><g type="asteriskos"/></unclear>`

_Example PN Link:_ [SB.18.13762](https://papyri.info/hgv/36300)

When a symbol is read but with doubt, add ? (i.e., a question mark) to the penultimate position in the Leiden+ description. The Unicode character will appear either with an underdot, or with a question mark.

***

