# Sigla, Special Characters, Punctuation, and Glyphs

- Scribes and users occasionally adorn a text with paratextual material or other lexical aids. This help file offers a guide to encoding them:
- [Sigla](#Sigla) <a id="top"></a>
    - [Crosses](#crosses)
    - [Strokes, Dots, and Checks](#strokes-and-checks)
    - [Scribal Punctuation](#scribal-punctuation)
- [Critical Symbols](#critical-symbols) <a id="top"></a>
    - [Aristarchan symbols](#aristarchan)
    - [Other symbols and marginalia](#other-symbols)
- [Parentheses and Braces](#scribal-parentheses) <a id="top"></a>
    - [Scribal Parentheses](#parentheses)
    - [Scribal Braces](#braces)
- [Unclear Symbols](#unclear) <a id="top"></a>
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

This gtype is used for staurograms of the tau-rho variety, as distinct from the `*chirho*` or `*stauros*`.

***

#### Chi-rho cross

_To get this PN preview:_ ☧

_Use this Leiden+:_ `*chirho*`

_To create this XML:_ `<g type="chirho"/>`

_Example PN Link:_ [P.Yale.1.71](https://papyri.info/hgv/16844)

This gtype is used for staurograms of the chi-rho variety, as distinct from the `*rho-cross*` or `*stauros*`.

***

### Strokes, Dots, and Checks <a id="strokes-and-checks"></a> ([return to top](#top))

#### Dash

_To get this PN preview:_ —

_Use this Leiden+:_ `*dash*`

_To create this XML:_ `<g type="dash"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For a horizontal or filler stroke that appears mid-line, often in the context of a register. For filler strokes at the end of a line, use `*filler(extension)*`.

***

#### Filler stroke

_To get this PN preview:_ —

_Use this Leiden+:_ `*filler(extension)*`

_To create this XML:_ `<g rend="extension" type="filler"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For a filler stroke or other space filler at the end of a line. For a horizontal stroke mid-line, use `*dash*`.

***

#### Slanting stroke

_To get this PN preview:_ /

_Use this Leiden+:_ `*slanting-stroke*`

_To create this XML:_ `<g type="slanting-stroke"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For a diagonal slash used in-line. For slashes which appear in the left-hand margin, use `*check*`.

***

#### Reverse slanting stroke

_To get this PN preview:_ \

_Use this Leiden+:_ `*reverse-slanting-stroke*`

_To create this XML:_ `<g type="reverse-slanting-stroke"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For a backslash or inverted diagonal stroke.

***

#### Double vertical bar

_To get this PN preview:_ ‖

_Use this Leiden+:_ `*double-vertical-bar*`

_To create this XML:_ `<g type="double-vertical-bar"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***


#### Long vertical bar

_To get this PN preview:_ |

_Use this Leiden+:_ `*long-vertical-bar*`

_To create this XML:_ `<g type="long-vertical-bar"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***


#### Swungdash

_To get this PN preview:_ ~

_Use this Leiden+:_ `*swungdash*`

_To create this XML:_ `<g type="swungdash"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***

#### Guide-dot

_To get this PN preview:_ PN does not yet support this character

_Use this Leiden+:_ `*guide-dot*`

_To create this XML:_ `<g type="guide-dot"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For inline dot(s) that fill space or which coordinate entries in a register. Enter the character separately for each dot. NB: For a dot in the left margin, use `*dot*`; for a horizontal line used to coordinate entries in a register, use `*dash*`.

***

#### Dot

_To get this PN preview:_ •

_Use this Leiden+:_ `*dot*`

_To create this XML:_ `<g type="dot"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For dots that appear in the left margin, as in a checklist. Mid-line or in-line dots should use `*guide-dot*`, unless they are punctuation (in which case, use `*middot*`). These are occasionally difficult to distinguish from `*check*`.

***

#### Check

_To get this PN preview:_ ／

_Use this Leiden+:_ `*check*`

_To create this XML:_ `<g type="check"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For slashes that appear in the left margin, as in a checklist. These are occasionally difficult to distinguish from `*dot*`, and are not interchangeable with `*slanting-stroke*`, which appears in-line.

***


#### Tachygraphic marks

_To get this PN preview:_ tachygr. marks

_Use this Leiden+:_ `*tachygraphic-marks*`

_To create this XML:_ `<g type="tachygraphic-marks"/>`

_Example PN Link:_ [Stud.Pal.3.503](http://papyri.info/hgv/37758)

For undecipherable tachygraphy.

***

### Scribal Punctuation <a id="scribal-punctuation"></a> ([return to top](#top))

#### Apostrophe or Diastole

_To get this PN preview:_ ’

_Use this Leiden+:_ `*apostrophe*`

_To create this XML:_ `<g type="apostrophe"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For a scribal apostrophe, whether as a marker of elision, word-division, or as a separator of double consonants. 

***

#### High point or ana-stigme

_To get this PN preview:_ ˙

_Use this Leiden+:_ `*high-punctus*`

_To create this XML:_ `<g type="high-punctus"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For scribal punctuation in the form of a high dot.

***

#### Mid point, interpunct, or mese-stigme

_To get this PN preview:_ ·

_Use this Leiden+:_ `*middot*`

_To create this XML:_ `<g type="middot"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For scribal punctuation in the form of a raised dot.

***

#### Low point or kato-stigme

_To get this PN preview:_ .

_Use this Leiden+:_ `*low-punctus*`

_To create this XML:_ `<g type="low-punctus"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For scribal punctuation in the form of a low dot.

***

#### Dipunct or dicolon

_To get this PN preview:_ ∶

_Use this Leiden+:_ `*dipunct*`

_To create this XML:_ `<g type="dipunct"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For scribal punctuation in the form of a dicolon or dipunct.

***

#### Tripunct

_To get this PN preview:_ ⋮

_Use this Leiden+:_ `*tripunct*`

_To create this XML:_ `<g type="tripunct"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For scribal punctuation in the form of a tripunct.

***

#### Tetrapunct

_To get this PN preview:_ ⁞

_Use this Leiden+:_ `*tetrapunct*`

_To create this XML:_ `<g type="tetrapunct"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

This gtype is used for scribal punctuation in the form of a tetrapunct.

***

#### Hypodiastole

_To get this PN preview:_ ⸒

_Use this Leiden+:_ `*hypodiastole*`

_To create this XML:_ `<g type="hypodiastole"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***

## Critical Symbols <a id="critical-symbols"></a>

### Aristarchan Symbols <a id="aristarchan"></a> ([return to top](#top))

#### Asteriskos

_To get this PN preview:_ ※

_Use this Leiden+:_ `*asteriskos*`

_To create this XML:_ `<g type="asteriskos"/>`

_Example PN Link:_ [P.Grenf.1.5](https://papyri.info/dclp/61986)

For the asteriskos.

***
#### Antisigma

_To get this PN preview:_ ͻ

_Use this Leiden+:_ `*antisigma*`

_To create this XML:_ `<g type="antisigma"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***
#### Antisigma periestigmene

_To get this PN preview:_ ͽ

_Use this Leiden+:_ `*antisigma-periestigmene*`

_To create this XML:_ `<g type="antisigma-periestigmene"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***
#### Diple

_To get this PN preview:_ ›

_Use this Leiden+:_ `*diple*`

_To create this XML:_ `<g type="diple"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***

#### Diple periestigmene (or 'dotted' diple)

_To get this PN preview:_ ⸖

_Use this Leiden+:_ `*diple-periestigmene*`

_To create this XML:_ `<g type="diple-periestigmene"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***

#### Obelos

_To get this PN preview:_ ―

_Use this Leiden+:_ `*obelos*`

_To create this XML:_ `<g type="obelos"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***

### Other Symbols <a id="other-symbols"></a> ([return to top](#top))

#### Downwards ancora

_To get this PN preview:_ ⸔

_Use this Leiden+:_ `*downwards-ancora*`

_To create this XML:_ `<g type="downwards-ancora"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***

#### Upwards ancora

_To get this PN preview:_ ⸕

_Use this Leiden+:_ `*upwards-ancora*`

_To create this XML:_ `<g type="upwards-ancora"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***

#### Dotted Obelos

_To get this PN preview:_ ⸓

_Use this Leiden+:_ `*dotted-obelos*`

_To create this XML:_ `<g type="dotted-obelos"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***

#### Chi periestigmenon (or dotted chi)

_To get this PN preview:_ Χ·

_Use this Leiden+:_ `*chi-periestigmenon*`

_To create this XML:_ `<g type="chi-periestigmenon"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For simple crosses or staurograms.

***

## Parentheses and Braces <a id="scribal-parentheses"></a>

### Scribal Parentheses <a id="parentheses"></a>([return to top](#top))

#### Scribal parenthesis (opening), for text on a single line

_To get this PN preview:_ (

_Use this Leiden+:_ `*parens-punctuation-opening*`

_To create this XML:_ `<g type="parens-punctuation-opening"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For the opening of a scribal parenthesis bracketing something on a single line of text. For sets of brackets enveloping multiple lines, use `parens-upper-opening`, `parens-middle-opening`, and `parens-lower-opening` as well as `parens-upper-closing`, `parens-middle-closing`, and `parens-lower-closing`. 

***


#### Scribal parenthesis (closing), for text on a single line

_To get this PN preview:_ )

_Use this Leiden+:_ `*parens-punctuation-closing*`

_To create this XML:_ `<g type="parens-punctuation-closing"/>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For the closing of a scribal parenthesis bracketing something on a single line of text. For sets of brackets enveloping multiple lines, use `parens-upper-opening`, `parens-middle-opening`, and `parens-lower-opening` as well as `parens-upper-closing`, `parens-middle-closing`, and `parens-lower-closing`. 

***

#### Multi-line scribal parenthesis (opening)

_To get this PN preview:_ ⎛, ⎜, and ⎝

_Use this Leiden+:_ `*parens-upper-opening*`, `*parens-middle-opening*`, `*parens-lower-opening*`

_To create this XML:_ `<g type="parens-upper-opening"/>`, `<g type="parens-middle-opening"/>`, and `<g type="parens-lower-opening"/>` 

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For the opening of a scribal parenthesis bracketing multiple lines of text. Use `*parens-upper-opening*` for the topmost line, `*parens-lower-opening*` for the last line, and `*parens-middle-opening*` for any lines in between. 

***

#### Multi-line scribal parenthesis (closing)

_To get this PN preview:_ ⎞, ⎟, and ⎠

_Use this Leiden+:_ `*parens-upper-closing*`, `*parens-middle-closing*`, `*parens-lower-closing*`

_To create this XML:_ `<g type="parens-upper-closing"/>`, `<g type="parens-middle-closing"/>`, and `<g type="parens-lower-closing"/>` 

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For the opening of a scribal parenthesis bracketing multiple lines of text. Use `*parens-upper-closing*` for the topmost line, `*parens-lower-closing*` for the last line, and `*parens-middle-closing*` for any lines in between. 

***

#### Multi-line scribal parenthesis (closing)

_To get this PN preview:_ (

_Use this Leiden+:_ `*parens-punctuation-opening*`

_To create this XML:_ `parens-punctuation-opening`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

For the opening of a scribal parenthesis bracketing something on a single line of text. For sets of brackets enveloping multiple lines, use `parens-upper-opening`, `parens-middle-opening`, and `parens-lower-opening` as well as `parens-upper-closing`, `parens-middle-closing`, and `parens-lower-closing`. 

***

### Scribal Braces <a id="braces"></a>([return to top](#top))

#### Unclear or uncertain symbol

_To get this PN preview:_ ☧̣ or ((asteriskos?))

_Use this Leiden+:_ `*chirho?*` or `*asteriskos?*`

_To create this XML:_ `<unclear><g type="chirho"/></unclear>` or `<unclear><g type="asteriskos"/></unclear>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

When a symbol is unclear or uncertain, add ? (i.e., a question mark) to the penultimate position in the Leiden+ description. 

***

## Unclear Symbols <a id="unclear"></a>

### Unclear Symbols <a id="unclear-symbols"></a>([return to top](#top))

#### Unclear or uncertain symbol

_To get this PN preview:_ ☧̣ or ((asteriskos?))

_Use this Leiden+:_ `*chirho?*` or `*asteriskos?*`

_To create this XML:_ `<unclear><g type="chirho"/></unclear>` or `<unclear><g type="asteriskos"/></unclear>`

_Example PN Link:_ [O.Ashm.Shelt.37](https://papyri.info/hgv/70589)

When a symbol is unclear or uncertain, add ? (i.e., a question mark) to the penultimate position in the Leiden+ description. 

***

