# Text Leiden+ Documentation

- [Apparatus, alternate reading](#apparatus-alternate-reading)
    - [Alternate reading](#alternate-reading)
    - [Alternate reading, multiple](#alternate-reading-multiple)
    - [Alternate reading (uncertain)](#alternate-reading-uncertain)
- [Apparatus, Berichtigungliste corrections](#apparatus-berichtigungliste-corrections)
    - [BL correction](#bl-correction)
    - [BL correction (uncertain)](#bl-correction-uncertain)

## Apparatus, alternate reading <a id="apparatus-alternate-reading"></a>

### Alternate reading <a id="alternate-reading"></a>

_To get this PN preview:_ `Text: Ὀχυρυγχίτου…App: or Ὀξυρυγχίτου νομοῦ`

_Use this Leiden+:_ `<:Ὀχυρυγχίτου|alt|Ὀξυρυγχίτου νομοῦ:>`

_To create this XML:_ `<app type="alternative"><lem>Ὀχυρυγχίτου</lem><rdg>Ὀξυρυγχίτου νομοῦ</rdg></app>`

_Example PN Link:_ [BGU.6.1265](http://papyri.info/hgv/4548)

Alternate readings posited by the editor. Preferred reading (`<lem>`) will appear in the text, the alternative (`<rdg>`) in the apparatus.

### Alternate reading, multiple <a id="alternate-reading-multiple"></a>

_To get this PN preview:_ `Text: [ - ca.? - ] ̣αμεν ̣ν̣…App: or [ἀπογρα]ψ̣αμένη̣ν̣, or [θρε]ψ̣αμένη̣ν̣`

_Use this Leiden+:_ `<:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:>`

_To create this XML:_ `<app type="alternative"><lem><gap reason="lost" extent="unknown" unit="character"/><gap reason="illegible" quantity="1" unit="character"/>αμεν<gap reason="illegible" quantity="1" unit="character"/><unclear>ν</unclear></lem><rdg><supplied reason="lost">ἀπο`

_Example PN Link:_

Multiple alternate readings posited by the editor. Preferred reading (`<lem>`) will appear in the text, the alternatives (`<rdg>`) in the apparatus. 

Where the papyrus reads, e.g. [ - - - ] ̣αμεν ̣ν̣ and the editor posits perhaps [ἀπογρα]ψ̣αμένη̣ν̣ or [θρε]ψ̣αμένη̣ν̣, encode: 

<:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:>

### Alternate reading (uncertain) <a id="alternate-reading-uncertain"></a>

_To get this PN preview:_ `Text: Ὀχυρυγχίτου(?)…App: or Ὀξυρυγχίτου νομοῦ(?)`

_Use this Leiden+:_ `<:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):>`

_To create this XML:_ `<app type="alternative"><lem>Ὀχυρυγχίτου<certainty match=".." locus="value"/></lem><rdg>Ὀξυρυγχίτου νομοῦ<certainty match=".." locus="value"/></rdg></app>`

_Example PN Link:_ [bgu;6;1265](http://papyri.info/ddbdp/bgu;6;1265)

By definition, all alternate readings are uncertain, but to indicate especial uncertainty as to one or both possibilities, enter as follows: 

<:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):>

## Apparatus, Berichtigungliste corrections <a id="apparatus-berichtigungliste-corrections"></a>

### BL correction <a id="bl-correction"></a>

_To get this PN preview:_ `Text: αἱ τοῦ…App: BL 9.17: Θίτου Original ed.`

_Use this Leiden+:_ `<:αἱ τοῦ=BL 9.17|ed|Θίτου:>`

_To create this XML:_ `<app type="editorial"><lem resp="BL 9.17">αἱ τοῦ</lem><rdg>Θίτου</rdg></app>`

_Example PN Link:_ [BGU.1.141](http://papyri.info/hgv/8916)

To indicate corrections that have been flagged in the Berichtigungsliste, e.g. <:αἱ τοῦ=BL 9.17|ed|Θίτου:>, where αἱ τοῦ is the correction recorded by BL and Θίτου is the deprecated reading.

### BL correction (uncertain) <a id="bl-correction-uncertain"></a>

_To get this PN preview:_ `Text: αἱ τοῦ(?)…App: BL 9.17: Θίτου Original ed.`

_Use this Leiden+:_ `<:αἱ τοῦ(?)=BL 9.17|ed|Θίτου:>`

_To create this XML:_ `<app type="editorial"><lem resp="BL 9.17">αἱ τοῦ<certainty match=".." locus="value"/></lem><rdg>Θίτου</rdg></app>`

_Example PN Link:_ [bgu;1;141](http://papyri.info/hgv/8916)

To indicate uncertain corrections that have been flagged in the Berichtigungsliste

## Apparatus, complicated corrections

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

## Apparatus, editorial correction

### Editorial correction

_To get this PN preview:_ `Text: κγ…App: bgu 1 p.357: κϛ Original ed.`

_Use this Leiden+:_ `<:<#κγ=23#>=BGU 1 p.357|ed|<#κϛ=26#>:>`

_To create this XML:_ `<app type="editorial"><lem resp="BGU 1 p.357"><num value="23">κγ</num></lem><rdg><num value="26">κϛ</num></rdg></app>`

_Example PN Link:_ [BGU.1.154](http://papyri.info/hgv/8922)

Used for two situations: to indicate a correction proposed in a publication (not reported by Berichtigungsliste); either 

1. correction proposed in series Corrigenda list: `<:<#κγ=23#>|ed:BGU 1 p.357|<#κϛ=26#>:>`, where κγ is the new reading and κϛ is the deprecated reading. 
2. or proposed in a publication: `<:(διαγρ(άφου))=N. Gonis, ZPE 143 (2003) 150|ed|(διαγρ(αφῆς)):>`, where διαγρ(άφου) is the new reading and διαγρ(αφῆς) is the deprecated reading.

### Editorial correction (uncertain)

_To get this PN preview:_ `Text: κγ(?)…App: bgu 1 p.357: κϛ Original ed.`

_Use this Leiden+:_ `<:<#κγ=23#>(?)=bgu 1 p.357|ed|<#κϛ=26#>:>`

_To create this XML:_ `<app type="editorial"><lem resp="bgu 1 p.357"><num value="23">κγ</num><certainty match=".." locus="value"/></lem><rdg><num value="26">κϛ</num></rdg></app>`

_Example PN Link:_ [bgu;1;154](http://papyri.info/ddbdp/bgu;1;154)

Where an editorial correction is only tentative, uncertain, enter as follows: 

`<:<#κγ=23#>(?)=BGU 1 p.357|ed|<#κϛ=26#>:>`

## Apparatus, orthographic regularization

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
