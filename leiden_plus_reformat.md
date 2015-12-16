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

_To get this PN preview:_ Text: Ὀχυρυγχίτου…App: or Ὀξυρυγχίτου νομοῦ

_Use this Leiden+:_ `<:Ὀχυρυγχίτου|alt|Ὀξυρυγχίτου νομοῦ:>`

_To create this XML:_ `<app type="alternative"><lem>Ὀχυρυγχίτου</lem><rdg>Ὀξυρυγχίτου νομοῦ</rdg></app>`

_Example PN Link:_ [BGU.6.1265](http://papyri.info/hgv/4548)

Alternate readings posited by the editor. Preferred reading (`<lem>`) will appear in the text, the alternative (`<rdg>`) in the apparatus.

### Alternate reading, multiple <a id="alternate-reading-multiple"></a>

_To get this PN preview:_ Text: [ - ca.? - ] ̣αμεν ̣ν̣…App: or [ἀπογρα]ψ̣αμένη̣ν̣, or [θρε]ψ̣αμένη̣ν̣

_Use this Leiden+:_ `<:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:>`

_To create this XML:_ `<app type="alternative"><lem><gap reason="lost" extent="unknown" unit="character"/><gap reason="illegible" quantity="1" unit="character"/>αμεν<gap reason="illegible" quantity="1" unit="character"/><unclear>ν</unclear></lem><rdg><supplied reason="lost">ἀπο`

_Example PN Link:_

Multiple alternate readings posited by the editor. Preferred reading (`<lem>`) will appear in the text, the alternatives (`<rdg>`) in the apparatus. 

Where the papyrus reads, e.g. [ - - - ] ̣αμεν ̣ν̣ and the editor posits perhaps [ἀπογρα]ψ̣αμένη̣ν̣ or [θρε]ψ̣αμένη̣ν̣, encode: 

<:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:>

### Alternate reading (uncertain) <a id="alternate-reading-uncertain"></a>

_To get this PN preview:_ Text: Ὀχυρυγχίτου(?)…App: or Ὀξυρυγχίτου νομοῦ(?)

_Use this Leiden+:_ `<:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):>`

_To create this XML:_ `<app type="alternative"><lem>Ὀχυρυγχίτου<certainty match=".." locus="value"/></lem><rdg>Ὀξυρυγχίτου νομοῦ<certainty match=".." locus="value"/></rdg></app>`

_Example PN Link:_ [bgu;6;1265](http://papyri.info/ddbdp/bgu;6;1265)

By definition, all alternate readings are uncertain, but to indicate especial uncertainty as to one or both possibilities, enter as follows: 

<:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):>

## Apparatus, Berichtigungliste corrections <a id="apparatus-berichtigungliste-corrections"></a>

### BL correction <a id="bl-correction"></a>

_To get this PN preview:_ Text: αἱ τοῦ…App: BL 9.17: Θίτου Original ed.

_Use this Leiden+:_ `<:αἱ τοῦ=BL 9.17|ed|Θίτου:>`

_To create this XML:_ `<app type="editorial"><lem resp="BL 9.17">αἱ τοῦ</lem><rdg>Θίτου</rdg></app>`

_Example PN Link:_ [BGU.1.141](http://papyri.info/hgv/8916)

To indicate corrections that have been flagged in the Berichtigungsliste, e.g. <:αἱ τοῦ=BL 9.17|ed|Θίτου:>, where αἱ τοῦ is the correction recorded by BL and Θίτου is the deprecated reading.

### BL correction (uncertain) <a id="bl-correction-uncertain"></a>

_To get this PN preview:_ Text: αἱ τοῦ(?)…App: BL 9.17: Θίτου Original ed.

_Use this Leiden+:_ `<:αἱ τοῦ(?)=BL 9.17|ed|Θίτου:>`

_To create this XML:_ `<app type="editorial"><lem resp="BL 9.17">αἱ τοῦ<certainty match=".." locus="value"/></lem><rdg>Θίτου</rdg></app>`

_Example PN Link:_ [bgu;1;141](http://papyri.info/hgv/8916)

To indicate uncertain corrections that have been flagged in the Berichtigungsliste

## Apparatus, complicated corrections

### Complicated corrections

_To get this PN preview:_ 275. corr. ex σ ̣ ̣[ -ca.?- ] (or γ ̣ ̣ ̣[ -ca.?- ]), BL 15.2 : ξτρ[ατηλάτης] (l. στρ[ατηλάτης) (or ̣γρ[ -ca.?- ]) J. Cowey, ZPE 150 (2020) 321-323 : στυ̣ρ[ατ -ca.?- ] (l. στρ[ατιώτης (or στρ[ατηγία])) R. Ast, CdE 100 (2018) 13-15 (BL 14.5) : etc.

_Use this Leiden+:_ `<:<:στρ[ατηγὸς]|subst|<:σ.2[.?]|alt|γ.3[.?]:>:>=BL 15.2||ed||<:<:στρ[ατηλάτης]|reg|ξτρ[ατηλάτης]:>|alt|.1γρ[.?]:>=J. Cowey, ZPE 150 (2020) 321-323|<:<:στρ[ατιώτης]|alt|στρ[ατηγία]:>|reg|στυ̣ρ[ατ][.?]:>=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)|<:Συρ[ίων](?)|`

_To create this XML:_ `<app type="editorial"><lem resp="BL 15.2"><subst><add place="inline">στρ<supplied reason="lost">ατηγὸς</supplied></add><del rend="corrected"><app type="alternative"><lem>σ<gap reason="illegible" quantity="2" unit="character"/><gap reason="lost" extent="un`

_Example PN Link:_

Leiden+ is capable of handling even extremely complicated series of corrections. Take the following completely fictional example: 

275. <:<:στρ[ατηγὸς]|subst|<:σ.2[.?]|alt|γ.3[.?]:>:>=BL 19.2||ed|| 
<:<:στρ[ατηλάτης]|reg|ξ̣τ̣ρ[ατηλάτης]:>|alt|.1γρ[.?]:>=J. Cowey, ZPE 150 (2020) 321-323| 
<:<:στρ[ατιώτης]|alt|στρ[ατηγία]:>|reg|στυ̣ρ[ατ][.?]:>=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)| 
<:Συρ[ίων](?)|reg|<:<:Σο̣υ̣ρ[ίων]||alt||Συ̣υ̣ρ[ίων]|Σω̣υ̣ρ[ίων]:>|subst|Σ.2ρ[ίων]:>:>=Original Edition:> 

This means: 
(1) at line 275 the DDbDP prints στρ[ατηγὸς], which the scribe himself corrected from either "σ . . [ca.?]" or "γ . . . [ca.?]", and which is recorded in BL vol.19 p.2 

(2) previously, Cowey had argued (in ZPE 150) for correcting the text to either στρ[ατηλάτης], which is a modern regularization of ξ̣τ̣ρ[ατηλάτης], or to ". γρ[ca.?]" 

(3) before Cowey, Ast had suggested (in CdÉ 100) that the papyrus reads στυ̣ρ[ατ- ca.?], which should be regularized either to στρ[ατιώτης] or to στρ[ατηγία]; this was subsequently picked up by BL 14.5 

(4) The original editors of the papyrus thought that the scribe had originally written "Σ . . ρ[ίων]", and then corrected it to either Σο̣υ̣ρ[ίων] or Συ̣υ̣ρ[ίων] or Σω̣υ̣ρ[ίων], any one of which should perhaps be regularized to Συρ[ίων] 

Under this model, simple corrections may be concatenated: 

275a. <:στρ[ατηγὸς]=BL 15.2||ed|| 
στρ[ατηλάτης]=J. Cowey, ZPE 150 (2020) 321-323| 
στρ[ατιώτης]=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)| 
Συρ[ίων]=Original Edition:> 

or, any class of correction may be 'nested' inside any other (as above).
