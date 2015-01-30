<h1>
Text Leiden+ Documentation
</h1>
<!--?xml version='1.0' encoding='utf-8' ?-->



<style type="text/css">
.intro {
  margin: 0.25em;
  padding: 0.5em;
  padding-left: 0.5em;
  border: 1px solid black;
  font-size: large;
  background-color: #8edefa; }

.category {
  margin: 0.25em;
  padding: 0.5em;
  padding-left: 0.5em;
  border: 1px solid black;
  text-align: left;
  background-color: #eaeaea; }

.category_display {
  font-size: large;
  background-color: #eaeaea; }

.toggle_button a {
  text-decoration: underline;
  cursor: pointer;
  color: blue; }

.examples {
  margin: 0.25em;
  padding: 0.5em;
  padding-left: 0.5em;
  border: 1px solid black;
  background-color: white; }
  .examples .description {
    padding-left: 1em;
    padding-right: 1em;
    background-color: #005daa;
    color: white;
    font-weight: bold;
    float: left; }
  .examples .preview {
    padding-left: 1em;
    float: left; }
  .examples .note {
    padding-left: 1em;
    padding-bottom: 1em;
    float: left; }
  .examples .sep {
    color: #970000;
    font-weight: bold;
    font-style: oblique;
    padding-left: 1em;
    float: left; }
  .examples .leiden, .examples .filename {
    padding-left: 3.75em;
    float: left; }
  .examples .xml {
    padding-left: 2.75em;
    float: left; }
  .examples hr {
    clear: both;
    display: block;
    visibility: hidden; }

#key {
  margin: 0.25em;
  padding: 0.5em;
  padding-left: 0.5em;
  border: 1px solid black;
  border: 1px dashed black;
  background-color: silver; }
</style>
<script type="text/javascript">
  //<![CDATA[
    function toggle_div(obj) {
      var el = document.getElementById(obj);
      if ( el.style.display != "none" ) {
        el.style.display = 'none';
      }
      else {
        el.style.display = '';
      }
    }
  //]]>
</script>


<div id="key">
<div class="intro">
Each Text Leiden+ Documentation Category with Examples
</div>
</div>
<div class="category" id="all" style="display:;">
<div class="category_display">
See All Documentation
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;all-examples&#39;);">
See All Examples
</a>
</div>
</div>
<div class="examples" id="all-examples" style="display:none;">
<div class="description">
Alternate reading
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: Ὀχυρυγχίτου…App: or Ὀξυρυγχίτου νομοῦ
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:Ὀχυρυγχίτου|alt|Ὀξυρυγχίτου νομοῦ:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="alternative"&gt;&lt;lem&gt;Ὀχυρυγχίτου&lt;/lem&gt;&lt;rdg&gt;Ὀξυρυγχίτου νομοῦ&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/4548" onclick="window.open(this.href);return false;">
BGU.6.1265
</a>
</div>
<hr>
<div class="note">
Alternate readings posited by the editor. Preferred reading (&lt;lem&gt;) will appear in the text, the alternative (&lt;rdg&gt;) in the apparatus.
</div>
<hr>
<div class="description">
Alternate reading, multiple
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: [ - ca.? - ] ̣αμεν ̣ν̣…App: or [ἀπογρα]ψ̣αμένη̣ν̣, or [θρε]ψ̣αμένη̣ν̣
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="alternative"&gt;&lt;lem&gt;&lt;gap reason="lost" extent="unknown" unit="character"/&gt;&lt;gap reason="illegible" quantity="1" unit="character"/&gt;αμεν&lt;gap reason="illegible" quantity="1" unit="character"/&gt;&lt;unclear&gt;ν&lt;/unclear&gt;&lt;/lem&gt;&lt;rdg&gt;&lt;supplied reason="lost"&gt;ἀπο
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Multiple alternate readings posited by the editor. Preferred reading (&lt;lem&gt;) will appear in the text, the alternatives (&lt;rdg&gt;) in the apparatus.
<br>
<br>Where the papyrus reads, e.g. [ - - - ] ̣αμεν ̣ν̣ and the editor posits perhaps [ἀπογρα]ψ̣αμένη̣ν̣ or [θρε]ψ̣αμένη̣ν̣, encode:
<br>
<br>&lt;:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:&gt;
</div>
<hr>
<div class="description">
Alternate reading (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: Ὀχυρυγχίτου(?)…App: or Ὀξυρυγχίτου νομοῦ(?)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="alternative"&gt;&lt;lem&gt;Ὀχυρυγχίτου&lt;certainty match=".." locus="value"/&gt;&lt;/lem&gt;&lt;rdg&gt;Ὀξυρυγχίτου νομοῦ&lt;certainty match=".." locus="value"/&gt;&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;6;1265" onclick="window.open(this.href);return false;">
bgu;6;1265
</a>
</div>
<hr>
<div class="note">
By definition, all alternate readings are uncertain, but to indicate especial uncertainty as to one or both possibilities, enter as follows: 
<br>
<br>&lt;:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):&gt;
</div>
<hr>
<div class="description">
BL correction
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: αἱ τοῦ…App: BL 9.17: Θίτου Original ed.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:αἱ τοῦ=BL 9.17|ed|Θίτου:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="BL 9.17"&gt;αἱ τοῦ&lt;/lem&gt;&lt;rdg&gt;Θίτου&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8916" onclick="window.open(this.href);return false;">
BGU.1.141
</a>
</div>
<hr>
<div class="note">
To indicate corrections that have been flagged in the Berichtigungsliste, e.g. &lt;:αἱ τοῦ=BL 9.17|ed|Θίτου:&gt;, where αἱ τοῦ is the correction recorded by BL and Θίτου is the deprecated reading.
</div>
<hr>
<div class="description">
BL correction (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: αἱ τοῦ(?)…App: BL 9.17: Θίτου Original ed.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:αἱ τοῦ(?)=BL 9.17|ed|Θίτου:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="BL 9.17"&gt;αἱ τοῦ&lt;certainty match=".." locus="value"/&gt;&lt;/lem&gt;&lt;rdg&gt;Θίτου&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;141" onclick="window.open(this.href);return false;">
bgu;1;141
</a>
</div>
<hr>
<div class="note">
To indicate uncertain corrections that have been flagged in the Berichtigungsliste
</div>
<hr>
<div class="description">
Complicated corrections
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
275. corr. ex σ  ̣  ̣[ -ca.?- ] (or γ  ̣  ̣  ̣[ -ca.?- ]), BL 15.2 : ξτρ[ατηλάτης] (l. στρ[ατηλάτης) (or   ̣γρ[ -ca.?- ]) J. Cowey, ZPE 150 (2020) 321-323 : στυ̣ρ[ατ -ca.?- ] (l. στρ[ατιώτης (or στρ[ατηγία])) R. Ast, CdE 100 (2018) 13-15 (BL 14.5) : etc.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:&lt;:στρ[ατηγὸς]|subst|&lt;:σ.2[.?]|alt|γ.3[.?]:&gt;:&gt;=BL 15.2||ed||&lt;:&lt;:στρ[ατηλάτης]|reg|ξτρ[ατηλάτης]:&gt;|alt|.1γρ[.?]:&gt;=J. Cowey, ZPE 150 (2020) 321-323|&lt;:&lt;:στρ[ατιώτης]|alt|στρ[ατηγία]:&gt;|reg|στυ̣ρ[ατ][.?]:&gt;=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)|&lt;:Συρ[ίων](?)|
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="BL 15.2"&gt;&lt;subst&gt;&lt;add place="inline"&gt;στρ&lt;supplied reason="lost"&gt;ατηγὸς&lt;/supplied&gt;&lt;/add&gt;&lt;del rend="corrected"&gt;&lt;app type="alternative"&gt;&lt;lem&gt;σ&lt;gap reason="illegible" quantity="2" unit="character"/&gt;&lt;gap reason="lost" extent="un
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Leiden+ is capable of handling even extremely complicated series of corrections. Take the following completely fictional example:
<br>
<br>
<br>275. &lt;:&lt;:στρ[ατηγὸς]|subst|&lt;:σ.2[.?]|alt|γ.3[.?]:&gt;:&gt;=BL 19.2||ed||
<br>&lt;:&lt;:στρ[ατηλάτης]|reg|ξ̣τ̣ρ[ατηλάτης]:&gt;|alt|.1γρ[.?]:&gt;=J. Cowey, ZPE 150 (2020) 321-323|
<br>&lt;:&lt;:στρ[ατιώτης]|alt|στρ[ατηγία]:&gt;|reg|στυ̣ρ[ατ][.?]:&gt;=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)|
<br>&lt;:Συρ[ίων](?)|reg|&lt;:&lt;:Σο̣υ̣ρ[ίων]||alt||Συ̣υ̣ρ[ίων]|Σω̣υ̣ρ[ίων]:&gt;|subst|Σ.2ρ[ίων]:&gt;:&gt;=Original Edition:&gt;
<br>
<br>This means:
<br>(1) at line 275 the DDbDP prints στρ[ατηγὸς], which the scribe himself corrected from either "σ . . [ca.?]" or "γ . . . [ca.?]", and which is recorded in BL vol.19 p.2
<br>
<br>(2) previously, Cowey had argued (in ZPE 150) for correcting the text to either στρ[ατηλάτης], which is a modern regularization of ξ̣τ̣ρ[ατηλάτης], or to ". γρ[ca.?]"
<br>
<br>(3) before Cowey, Ast had suggested (in CdÉ 100) that the papyrus reads στυ̣ρ[ατ- ca.?], which should be regularized either to στρ[ατιώτης] or to στρ[ατηγία]; this was subsequently picked up by BL 14.5
<br>
<br>(4) The original editors of the papyrus thought that the scribe had originally written "Σ . . ρ[ίων]", and then corrected it to either Σο̣υ̣ρ[ίων] or Συ̣υ̣ρ[ίων] or Σω̣υ̣ρ[ίων], any one of which should perhaps be regularized to Συρ[ίων]
<br>
<br>Under this model, simple corrections may be concatenated:
<br>
<br>275a. &lt;:στρ[ατηγὸς]=BL 15.2||ed||
<br>στρ[ατηλάτης]=J. Cowey, ZPE 150 (2020) 321-323|
<br>στρ[ατιώτης]=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)|
<br>Συρ[ίων]=Original Edition:&gt;
<br>
<br>or, any class of correction may be 'nested' inside any other (as above).
</div>
<hr>
<div class="description">
Editorial correction
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: κγ…App: bgu 1 p.357: κϛ Original ed.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:&lt;#κγ=23#&gt;=BGU 1 p.357|ed|&lt;#κϛ=26#&gt;:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="BGU 1 p.357"&gt;&lt;num value="23"&gt;κγ&lt;/num&gt;&lt;/lem&gt;&lt;rdg&gt;&lt;num value="26"&gt;κϛ&lt;/num&gt;&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8922" onclick="window.open(this.href);return false;">
BGU.1.154
</a>
</div>
<hr>
<div class="note">
Used for two situations: to indicate a correction proposed in a publication (not reported by Berichtigungsliste); either 
<br>
<br>(1) correction proposed in series Corrigenda list: &lt;:&lt;#κγ=23#&gt;|ed:BGU 1 p.357|&lt;#κϛ=26#&gt;:&gt;, where κγ is the new reading and κϛ is the deprecated reading.
<br>
<br>(2) or proposed in a publication: &lt;:(διαγρ(άφου))=N. Gonis, ZPE 143 (2003) 150|ed|(διαγρ(αφῆς)):&gt;, where διαγρ(άφου) is the new reading and διαγρ(αφῆς) is the deprecated reading.
</div>
<hr>
<div class="description">
Editorial correction (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: κγ(?)…App: bgu 1 p.357: κϛ Original ed.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:&lt;#κγ=23#&gt;(?)=bgu 1 p.357|ed|&lt;#κϛ=26#&gt;:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="bgu 1 p.357"&gt;&lt;num value="23"&gt;κγ&lt;/num&gt;&lt;certainty match=".." locus="value"/&gt;&lt;/lem&gt;&lt;rdg&gt;&lt;num value="26"&gt;κϛ&lt;/num&gt;&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
Where an editorial correction is only tentative, uncertain, enter as follows:
<br>
<br>&lt;:&lt;#κγ=23#&gt;(?)=BGU 1 p.357|ed|&lt;#κϛ=26#&gt;:&gt;
</div>
<hr>
<div class="description">
Orthographic regularization
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: φρόντι[σ]ον….App: φρόνδει[σ]ο̣ν pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:φρόντι[σ]ον|reg|φρόνδει[σ]ο̣ν:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;choice&gt;&lt;reg&gt;φρόντι&lt;supplied reason="lost"&gt;σ&lt;/supplied&gt;ον&lt;/reg&gt;&lt;orig&gt;φρόνδει&lt;supplied reason="lost"&gt;σ&lt;/supplied&gt;&lt;unclear&gt;ο&lt;/unclear&gt;ν&lt;/orig&gt;&lt;/choice&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
To be used for two classes of 'correction':
<br>
<br>(1) Regularization/'correction' of non-standard orthographic form, e.g. αἰνακούεις for ἐνακούεις; in such cases the form is 'correct' but is not spelled in the canonical fashion.
<br>
<br>(2) Correction of syntax not morphology, e.g. τῷ for τοῦ; in such cases the form is a valid one, but is not strictly correct in the context.
<br>
<br>In past, DDbDP suppressed all diacriticals from the mistaken reading. NOTE that DDbDP now presents the reading of the papyrus in the text and the regularized reading in the apparatus (per modern convention). To support that change, we now enter orthographic 'corrections' differently.
<br>
<br>(1) For φρόνδει[σ]ο̣ν --&gt; φρόντισον encode, &lt;:φρόντι[σ]ον|reg|φρόνδει[σ]ο̣ν:&gt; (Note: all Leiden except underdots on left side of 'reg')
<br>(2) PN displays: text: φρόνδει[σ]ο̣ν / app: Read φρόντι[σ]ον
</div>
<hr>
<div class="description">
Orthographic regularization, for language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ⲁⲣⲁⲕ….App: i.e. Greek ἄρακος
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:ἄρακος=grc|reg|ⲁⲣⲁⲕ:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;choice&gt;&lt;reg xml:lang="grc"&gt;ἄρακος&lt;/reg&gt;&lt;orig&gt;ⲁⲣⲁⲕ&lt;/orig&gt;&lt;/choice&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Leiden+ treats multi-lingual equivalencies as a kind of rough 'regularization'. So, if a mainly Greek text has some Coptic written in it, and you would like to indicate the Greek word that a Coptic word represents, mark up as follows:
<br>
<br>&lt;:ἄρακος=grc|reg|ⲁⲣⲁⲕ:&gt;
<br>
<br>The text will print ⲁⲣⲁⲕ and the app will read "i.e. Greek ἄρακος"
</div>
<hr>
<div class="description">
Orthographic regularization, multiple
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ἀ̣νύεται….App: l. ἀνοίεται (?), i.e. ἀνοίγεται (?)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:ἀνοίγεται (?)|ἀνοίεται (?)||reg||ἀ̣νύεται:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;choice&gt;&lt;reg cert="low"&gt;ἀνοίγεται &lt;/reg&gt;&lt;reg cert="low"&gt;ἀνοίεται &lt;/reg&gt;&lt;orig&gt;&lt;unclear&gt;ἀ&lt;/unclear&gt;νύεται&lt;/orig&gt;&lt;/choice&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Leiden+ supports not only simple regularizations but 'chains' of regularization. For example, let us say that I scribe wrote "ἀ̣νύεται", which is held to be a likely phonetic representation of ἀνοίεται, which itself perhaps ought to be regularized to ἀνοίγεται.
<br>
<br>&lt;:ἀνοίγεται (?)|ἀνοίεται (?)||reg||ἀ̣νύεται:&gt;
<br>
<br>
</div>
<hr>
<div class="description">
PN/PE correction
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: τοῦ…App: G. Claytor (CPR VI plate 35): Om. Original ed.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:τοῦ=PN G. Claytor (CPR VI plate 35)|ed|:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="PN G. Claytor (CPR VI plate 35)"&gt;τοῦ&lt;/lem&gt;&lt;rdg/&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/cpr;6;82" onclick="window.open(this.href);return false;">
cpr;6;82
</a>
</div>
<hr>
<div class="note">
Indicates a correction proposed directly to DDbDP via PE. 
<br>
<br>So, the following emendation observes the omission from an edition of a word clearly visible (from the published plate) on the papyrus:
<br>
<br>&lt;:τοῦ=PN G. Claytor (CPR VI plate 35)|ed|:&gt;
<br>
<br>The corrected text is το­ῦ and the deprecated text is 'null', since this corrects an omission. Had the emendation sought to correct an existing (rather than omitted) reading, it might have looked like this:
<br>
<br>&lt;:τοῦ=PN G. Claytor (CPR VI plate 35)|ed|μου:&gt;
<br>
</div>
<hr>
<div class="description">
Scribe correcting self
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: τοῦ…App: corr. from της
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:τοῦ|subst|της:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;subst&gt;&lt;add place="inline"&gt;τοῦ&lt;/add&gt;&lt;del rend="corrected"&gt;της&lt;/del&gt;&lt;/subst&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
To indicate scribal corrections and alterations. Note that as a general rule, the original reading does not carry diacriticals; also that this apparatus tag is used for entire words and not for the corrected characters alone.
<br>
<br>Indicating that the scribe wrote της and corrected to τοῦ: &lt;:τοῦ|subst|της:&gt;
<br>
<br>No: τ&lt;:οῦ|subst|ης:&gt;
<br>Yes: &lt;:τοῦ|subst|της:&gt;
</div>
<hr>
<div class="description">
Scribe correcting self (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: τοῦ…App: corr. from της --&gt; Text: τοῦ(?)…App: corr. from της(?)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:τοῦ(?)|subst|της(?):&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;subst&gt;&lt;add place="inline"&gt;τοῦ&lt;certainty match=".." locus="value"/&gt;&lt;/add&gt;&lt;del rend="corrected"&gt;της&lt;certainty match=".." locus="value"/&gt;&lt;/del&gt;&lt;/subst&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8922" onclick="window.open(this.href);return false;">
BGU.1.154
</a>
</div>
<hr>
<div class="note">
To indicate scribal corrections and alterations where one or both readings is uncertain. Follow the conventions for an ordinary scribal correction, but add (?) to the affected reading.
<br>
<br>&lt;:τοῦ|subst|της:&gt; --&gt; &lt;:τοῦ(?)|subst|της(?):&gt;
</div>
<hr>
<div class="description">
Spelling correction
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: τιμὴν….App: τμμὴν pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:τιμὴν|corr|τμμὴν:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;choice&gt;&lt;corr&gt;τιμὴν&lt;/corr&gt;&lt;sic&gt;τμμὴν&lt;/sic&gt;&lt;/choice&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
For correction of outright scribal error, e.g. στ[ρ]α̣ττεός for στρατηγός.
<br>
<br>(1) where possible enter στρατ{τ}ηγός rather than &lt;:στρατηγός|corr|στραττηγός:&gt;
<br>(NOTE: this does not apply to e.g. ὁμολογῶι, which is to be encoded as an orthographic regularization: &lt;:ὁμολογῶ|reg|ὁμολογῶι:&gt;)
<br>(2) where possible enter στρα&lt;τ&gt;ηγός rather than &lt;:στρατηγός|corr|στραηγός:&gt;
<br>(3) in the case of στ[ρ]α̣ττεός for στρατηγός
<br>(3a) enter &lt;:(στ[ρ]ατ{τ}η&lt;γ&gt;(ός))|corr|(στ[ρ]α̣ττε(ός)):&gt; (Note: all Leiden except for underdots on left side of 'corr'
<br>(3b) PN displays: text: στ[ρ]α̣ττε(ός) / app: l. στρατηγός (corr)
</div>
<hr>
<div class="description">
Diaeresis
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: υ ἱ(¨)οῦ…App:16. υϊου pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
υ ἱ(¨)οῦ
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
υ&lt;hi rend="diaeresis"&gt;ἱ&lt;/hi&gt;οῦ
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10223" onclick="window.open(this.href);return false;">
P.Berl.Leihg.2.35
</a>
</div>
<hr>
<div class="note">
Diaeresis written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed. Example: υ ἱ(¨)οῦ
</div>
<hr>
<div class="description">
Asper
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ὧ ... App: ὡ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 ὧ( ῾)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="asper"&gt;ὧ&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/31807" onclick="window.open(this.href);return false;">
P.Oxy.14.1765
</a>
</div>
<hr>
<div class="note">
Asper written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Acute
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ὃ ... App.: ό pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 ὃ(´)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="acute"&gt;ὃ&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/37860" onclick="window.open(this.href);return false;">
P.Oxy.16.1854
</a>
</div>
<hr>
<div class="note">
Acute written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Circumflex
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ὑ ... App: ῦ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 ὑ(^)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="circumflex"&gt;ὑ&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/20769" onclick="window.open(this.href);return false;">
P.Oxy.1.125
</a>
</div>
<hr>
<div class="note">
Circumflex written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Lenis
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ἄ ... App.: ἀ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 Ἀ( ᾿)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="lenis"&gt;Ἀ&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/9313" onclick="window.open(this.href);return false;">
BGU.3.715
</a>
</div>
<hr>
<div class="note">
Lenis written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Double diacritical
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ἵ ... App.: ἱ pap. ί pap. --&gt; Text: ἵ ... App.: ἵ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 ἵ( ῾´)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="asper"&gt;&lt;hi rend="acute"&gt;ἵ&lt;/hi&gt;&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/32762" onclick="window.open(this.href);return false;">
P.Ryl.4.624
</a>
</div>
<hr>
<div class="note">
Multiple ancient diacriticals. For double diacriticals simply combine the ordinary symbols inside a single pair pf parens.
</div>
<hr>
<div class="description">
Diacritical over illegible character
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text:   ̣ ... App.:     ¨ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 .1(¨)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="diaeresis"&gt;&lt;gap reason="illegible" quantity="1" unit="character"/&gt;&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/16028" onclick="window.open(this.href);return false;">
CPR.5.6
</a>
</div>
<hr>
<div class="note">
Ancient diacritical written atop illegible character. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Diacritical over lost character
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: [  ̣] ... App.:      ´ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 [.1](´)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="acute"&gt;&lt;gap reason="lost" quantity="1" unit="character"/&gt;&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/26685" onclick="window.open(this.href);return false;">
P.Wisc.2.70
</a>
</div>
<hr>
<div class="note">
Ancient diacritical written atop character that is now lost in lacuna. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Document Div, ab
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
PN does not indicate explicitly
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;= =&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;ab&gt; &lt;/ab&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Every block of text must be enclosed in a &lt;= ... =&gt; pair.
</div>
<hr>
<div class="description">
Document Div, recto/verso
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
recto/verso
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.r&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.v&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="r" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="v" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Recto and verso are indicated with closed pairs of tags as follows:
<br>
<br>&lt;D=.r&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.v&lt;=
<br>3. line of text
<br>4. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that the pair of tags inside the recto/verso tags and directly adjacent to the text is the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Document Div, fragment
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
fragment 1/fragment 2
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.1.fragment&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.2.fragment&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="1" subtype="fragment" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="2" subtype="fragment" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Fragments are indicated with closed pairs of tags as follows:
<br>
<br>&lt;D=.1.fragment&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.2.fragment&lt;=
<br>3. line of text
<br>4. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that the pair of tags inside the fragment tags and directly adjacent to the text is the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Document Div, part
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
part A/part B
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.A.part&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.B.part&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="A" subtype="part" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="B" subtype="part" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Parts of a document are indicated with closed pairs of tags as follows:
<br>
<br>&lt;D=.A.part&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.B.part&lt;=
<br>3. line of text
<br>4. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that the pair of tags inside the part tags and directly adjacent to the text is the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Document Div, column
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
column i / column ii
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.i.column&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.ii.column&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="i" subtype="column" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="ii" subtype="column" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Columns are indicated with closed pairs of tags as follows:
<br>
<br>&lt;D=.i.column&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.ii.column&lt;=
<br>3. line of text
<br>4. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that the pair of tags inside the column tags and directly adjacent to the text is the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Document Div, folio
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
folio a / folio b
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.a.folio&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.b.folio&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="a" subtype="folio" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="b" subtype="folio" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Folios are indicated with closed pairs of tags as follows:
<br>
<br>&lt;D=.a.folio&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.b.folio&lt;=
<br>3. line of text
<br>4. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that the pair of tags inside the folio tags and directly adjacent to the text is the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Document Div, nested
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Divisions indicated variously
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.a.folio&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.b.folio&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="a" subtype="folio" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="b" subtype="folio" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Document divisions can be nested so long as tag pairs no not overlap:
<br>
<br>&lt;D=.r
<br>&lt;D=.i.column&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.ii.column
<br>&lt;D=.a.fragment&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.b.fragment&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>=D&gt;
<br>=D&gt;
<br>&lt;D=.v&lt;=
<br>1. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that no matter how nested the divisions are, the pair of tags directly adjacent to the text is always the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Note
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(BGU 1,108,r reprinted in WChr 227 )
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
/*BGU 1,108,r reprinted in WChr 227 */
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;note xml:lang="en"&gt;BGU 1,108,r reprinted in WChr 227 &lt;/note&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;108" onclick="window.open(this.href);return false;">
BGU.1.108
</a>
</div>
<hr>
<div class="note">
To indicate modern editorial comment, for example that the recto of a given text has been republished elsewhere, or that a missing string should be a month name. Use sparingly.
</div>
<hr>
<div class="description">
Handshift
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(hand 4)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
$m4 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;handShift new="m4"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10223" onclick="window.open(this.href);return false;">
P.Berl.Leihg.2.35
</a>
</div>
<hr>
<div class="note">
Handshift. Note: where there are multiple hands, you do not need to indicate the first.
</div>
<hr>
<div class="description">
Handshift (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(hand 3?)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
$m3(?) 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;handShift new="m3" cert="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/44635" onclick="window.open(this.href);return false;">
P.Polit.Iud.19
</a>
</div>
<hr>
<div class="note">
Uncertain handshift.
</div>
<hr>
<div class="description">
gap illegible character
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
 ̣  ̣  ̣
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.3
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="3" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/o.berenike;1;6" onclick="window.open(this.href);return false;">
O.Berenike.1.6
</a>
</div>
<hr>
<div class="note">
To indicate a known number of illegible characters.
</div>
<hr>
<div class="description">
Approximate number of illegible characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
- ca.23 - 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ca.23
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="23" unit="character" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/26917" onclick="window.open(this.href);return false;">
P.Wisc.1.1
</a>
</div>
<hr>
<div class="note">
To indicate an estimated number of illegible characters.
</div>
<hr>
<div class="description">
Known number of illegible characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
- ca.43 -
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.43
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="43" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/23699" onclick="window.open(this.href);return false;">
SB.20.14241
</a>
</div>
<hr>
<div class="note">
To indicate a known number of illegible characters. Note: all strings of illegible characters greater than 8 are rendered as approximations. So, ".43" will be encoded as a piece of editorial certainty (&lt;gap reason="illegible" quantity="43" unit="character"/&gt;), but will nevertheless be displayed as an approximation: "- ca.43 -"
</div>
<hr>
<div class="description">
Range of illegible characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
- ca. 9-10 -
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.9-10
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" atLeast="9" atMost="10" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/74479" onclick="window.open(this.href);return false;">
P.Eleph.Wagner.1.288
</a>
</div>
<hr>
<div class="note">
To indicate a known range of illegible characters.
</div>
<hr>
<div class="description">
Known number of illegible lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces 5 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.5lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="5" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8291" onclick="window.open(this.href);return false;">
P.Hib.2.253
</a>
</div>
<hr>
<div class="note">
To indicate a known number of illegible lines (e.g. vestiges)
</div>
<hr>
<div class="description">
Approximate number of illegible lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces ca.20 lines 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ca.20lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="20" unit="line" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/25460" onclick="window.open(this.href);return false;">
SB.24.15920
</a>
</div>
<hr>
<div class="note">
To indicate an estimated number of illegible lines (e.g. vestiges).
</div>
<hr>
<div class="description">
Range of illegible lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces 2-3 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.2-3lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" atLeast="2" atMost="3" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/38499" onclick="window.open(this.href);return false;">
SB.20.14571
</a>
</div>
<hr>
<div class="note">
To indicate a range of illegible lines.
</div>
<hr>
<div class="description">
gap illegible character unknown
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
- ca. ? -
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.?
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" extent="unknown" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10193" onclick="window.open(this.href);return false;">
P.Berl.Leihg.1.13
</a>
</div>
<hr>
<div class="note">
To indicate an unknown number of illegible characters.
</div>
<hr>
<div class="description">
Text inserted / added above line
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
\ὅλων/
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
\ὅλων/
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add place="above"&gt;ὅλων&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18216" onclick="window.open(this.href);return false;">
P.Matr.2
</a>
</div>
<hr>
<div class="note">
To indicate text inserted or added above a line, as 'afterthought' or self-correction (for conventional drop-ins: \καὶ/ )
</div>
<hr>
<div class="description">
Text inserted / added below line
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
/δ\
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
//&lt;#δ=4#&gt;\\
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add place="below"&gt;&lt;num value="4"&gt;δ&lt;/num&gt;&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
To indicate text inserted or added below a line, as 'afterthought' or self-correction (see print conventional: /καὶ\ )
</div>
<hr>
<div class="description">
Text inserted / added to the left margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(added at left: αβγ)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
||left:καὶ||
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add place="left"&gt;καὶ&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/128690" onclick="window.open(this.href);return false;">
p.jena;2;10
</a>
</div>
<hr>
<div class="note">
To indicate text inserted / added to the left of a line
</div>
<hr>
<div class="description">
Text inserted / added to the right margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(added at right: αβγ)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
||right:καὶ||
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add place="right"&gt;καὶ&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
To indicate text inserted / added to the right of a line
</div>
<hr>
<div class="description">
Text added between lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ὧν (in smaller font)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&gt;) ὧ( ῾)ν(&lt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add place="interlinear"&gt;&lt;hi rend="asper"&gt;ὧ&lt;/hi&gt;ν&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/32564" onclick="window.open(this.href);return false;">
P.Panop.14
</a>
</div>
<hr>
<div class="note">
To indicate text added between two lines
</div>
<hr>
<div class="description">
Non default language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
γενήσεται
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
~|γενήσεται|~grc 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;foreign xml:lang="grc"&gt;γενήσεται&lt;/foreign&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/23792" onclick="window.open(this.href);return false;">
SB.20.14688
</a>
</div>
<hr>
<div class="note">
Indicate text strings written in a language/script other than the document's default as follows:
<br>
<br>Greek = ~|γενήσεται|~grc 
<br>Latin = ~|comes|~la 
<br>Ancient Greek in Latin script = ~|di emu|~grc-Latn 
<br>Latin in Greek script = ~|σουσκριβερεντ|~la-Grek
<br>
<br>NOTE: You must enter a space after the language designator; so, not "~la", but "~la ".
</div>
<hr>
<div class="description">
Non default language: Latin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
comes
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
~|comes|~la 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;foreign xml:lang="la"&gt;comes&lt;/foreign&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
If the default language of a text is Greek, mark strings of Latin as follows: ~|comes|~la
</div>
<hr>
<div class="description">
Supplied omitted
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
&lt;ἀπεγραψάμην&gt;
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;ἀπεγραψάμην&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;supplied reason="omitted"&gt;ἀπεγραψάμην&lt;/supplied&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8891" onclick="window.open(this.href);return false;">
BGU.1.117
</a>
</div>
<hr>
<div class="note">
Text omitted by scribe, inserted by modern editor. To indicate such added text, enclose it in angle brackets: e.g. &lt;ἀπεγραψάμην&gt;, ἀπ&lt;ε&gt;γραψάμην, etc.
</div>
<hr>
<div class="description">
Supplied omitted (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
&lt;οὐκ(?)&gt;
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;οὐκ(?)&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;supplied reason="omitted" cert="low"&gt;οὐκ&lt;/supplied&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/32313" onclick="window.open(this.href);return false;">
P.Oxy.50.3581
</a>
</div>
<hr>
<div class="note">
To indicate text omitted by scribe and uncertainly inserted by modern editor.
</div>
<hr>
<div class="description">
Supplied omitted
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ἀπ&lt;ε&gt;γραψάμην
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ἀπ&lt;ε&gt;γραψάμην
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
ἀπ&lt;supplied reason="omitted"&gt;ε&lt;/supplied&gt;γραψάμην
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
Note: for cases like ἀπ&lt;ε&gt;γραψάμην the DDbDP has historically entered an orthographic correction of the entire word, i.e. &lt;:ἀπεγραψάμην|orth|απγραψαμην:&gt;. Recommended practice now is to enter just the angle brackets wherever possible: ἀπ&lt;ε&gt;γραψάμην.
<br>
<br>For more on this, see the documentation entry under Orthographic Correction.
</div>
<hr>
<div class="description">
Surplus text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
{ὀνόματος}
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
{ὀνόματος}
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;surplus&gt;ὀνόματος&lt;/surplus&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/15402" onclick="window.open(this.href);return false;">
P.Oxy.50.3583
</a>
</div>
<hr>
<div class="note">
Surplus text written by scribe, deleted by modern editor. To indicate such text enclose it in braces: e.g. {ὀνόματος}, ὀνό{μ}ματος.
</div>
<hr>
<div class="description">
Surplus text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ὁμο{μο}λογῶ.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ὁμο{μο}λογῶ.
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
ὁμο&lt;surplus&gt;μο&lt;/surplus&gt;λογῶ.
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Surplus text written by scribe, deleted by modern editor.
<br>
<br>For cases like ὁμολογῶι enter an orthographic regularization of the entire word, i.e. &lt;:ὁμολογῶ|reg|ὁμολογῶι:&gt;. But where the letter(s) is genuinely superfluous, use braces: ὁμο{μο}λογῶ.
</div>
<hr>
<div class="description">
Deletion
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
〚τοῖς κορασίοις〛
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
〚τοῖς κορασίοις〛
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;del rend="erasure"&gt;τοῖς κορασίοις&lt;/del&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/20193" onclick="window.open(this.href);return false;">
BGU.1.34
</a>
</div>
<hr>
<div class="note">
Text deleted in antiquity. Note: this convention has been used to cover many modes of deletion (cancellation by slashes, expunction, strike-through, bracket-like marks on the papyrus, etc). Appearance of 〚...〛 does not imply one mode or another.
</div>
<hr>
<div class="description">
Deletion with slashes
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: τραπέζης Φρέμει...App: 5. Text canceled with slashes
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
〚/ τραπέζης Φρέμει. 〛
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;del rend="slashes"&gt; τραπέζης Φρέμει. &lt;/del&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/cpr;1;15" onclick="window.open(this.href);return false;">
cpr;1;15
</a>
</div>
<hr>
<div class="note">
Text deleted with slashes in antiquity: 〚/ τραπέζης Φρέμει.〛
</div>
<hr>
<div class="description">
Deletion with cross-strokes
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: (hand 4) -ca.?-….App: v.1. Text canceled with cross-strokes
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
〚X $m4  lost.?lin 〛
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;del rend="cross-strokes"&gt; &lt;handShift new="m4"/&gt; &lt;gap reason="lost" extent="unknown" unit="line"/&gt; &lt;/del&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/p.lips;1;98" onclick="window.open(this.href);return false;">
p.lips;1;98
</a>
</div>
<hr>
<div class="note">
Text deleted with cross-strokes in antiquity: 〚X $m4 lost.?lin〛
</div>
<hr>
<div class="description">
abbreviation, στρατηγ( )
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ομυο(&nbsp;)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(|ομυο|)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;abbr&gt;ομυο&lt;/abbr&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8884" onclick="window.open(this.href);return false;">
BGU.1.110
</a>
</div>
<hr>
<div class="note">
Ancient abbreviations. Note: Leiden+ treats resolved and unresolved abbreviations differently: so,<br><br>enter (στρατηγ(ός)) for στρατηγ(ός)<br><br>but<br><br>enter (|στρατηγ|) for στρατηγ( ) 
</div>
<hr>
<div class="description">
abbreviation with markup σ[τρ]α̣τ̣ηγ(  )
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣]χυρι̣ο(&nbsp;)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(|[.8]χυρι̣ο|)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;abbr&gt;&lt;gap reason="lost" quantity="8" unit="character"/&gt;χυρ&lt;unclear&gt;ι&lt;/unclear&gt;ο&lt;/abbr&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8884" onclick="window.open(this.href);return false;">
BGU.1.110
</a>
</div>
<hr>
<div class="note">
For unresolved abbreviations· (|σ[τρ]α̣τ̣ηγ|) = σ[τρ]α̣τ̣ηγ(  )
</div>
<hr>
<div class="description">
abbreviation, λ(  )(?) 
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
λ(  )(?) 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(|λ(?)|)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;abbr&gt;λ&lt;certainty locus="name" match=".."/&gt;&lt;/abbr&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/33700" onclick="window.open(this.href);return false;">
P.Lips.1.40
</a>
</div>
<hr>
<div class="note">
Ancient abbreviations. Where the expansion is unknown and it is not even certain whether the character(s) on the papyrus is meant to be an expansion or not, enter:
<br>
<br>(|λ(?)|)
<br>
<br>This could indicate λ (i.e. 30) or, e.g. λ(όγος); but we cannot say for ceertain.
</div>
<hr>
<div class="description">
expan on part of word στρατηγ(ός)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Καρ(ανίδι)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Καρ(ανίδι))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;Καρ&lt;ex&gt;ανίδι&lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8922" onclick="window.open(this.href);return false;">
BGU.1.154
</a>
</div>
<hr>
<div class="note">
Ancient abbreviations. Note: Leiden+ handles στρατηγ( ) and στρατηγ(ός) differently. Where the abbreviation is expanded -- as in the case of στρατηγ(ός) -- enter as follows: (στρατηγ(ός)). For the other case, see elsewhere under Leiden Parentheses (  ).
</div>
<hr>
<div class="description">
uncertain expansion of part of a word Καρ(ανίδι(?))
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Καρ(ανίδι(?))
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Καρ(ανίδι?))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;Καρ&lt;ex cert="low"&gt;ανίδι&lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
Ancient abbreviations. For uncertain expansions, add "?" inside the expanded part of the word (στρατηγ(ός)) --&gt; (στρατηγ(ός?)).
</div>
<hr>
<div class="description">
partial expansion of part of a word Καρ(ανίδ  )
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Καρ(ανίδ  ) --&gt; Καρ(ανίδ-)???
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Καρ(ανίδ  ))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;Καρ&lt;ex&gt;ανίδ  &lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
Ancient abbreviations. Where a word is only partially expanded (for example because the termination is unknown), enter as follows:
<br>
<br>Καρ(ανίδ  )
<br>
<br>Note: leave two spaces between the last character and the closing parens.
</div>
<hr>
<div class="description">
expansion of whole word (ἔτους)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
((ἔτους))
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
((ἔτους))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;&lt;ex&gt;ἔτους&lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
For symbols that are fully expanded enter as follows: ((ἔτους)).
</div>
<hr>
<div class="description">
expansion of whole word (ἔ̣τ̣ο̣υ̣ς̣) / (ἔτους?)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(ἔτους(?))
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
((ἔτους?))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;&lt;ex cert="low"&gt;ἔτους&lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
For symbols that are fully expanded, but uncertainly read enter as follows: ((ἔτους?)). This is often represented in print by (ἔ̣τ̣ο̣υ̣ς̣) / (ἔτους?).
</div>
<hr>
<div class="description">
partial expansion of whole word (δραχμ  )
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(ἔτ  ) --&gt; (ἔτ-)???
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
((ἔτ  ))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;&lt;ex&gt;ἔτ  &lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8922" onclick="window.open(this.href);return false;">
BGU.1.154
</a>
</div>
<hr>
<div class="note">
For symbols that are partially expanded enter as follows (for example because the termination is unknown):
<br>
<br>((ἔτ  ))
<br>
<br>Note: leave two spaces between the last character and the closing parens. 
</div>
<hr>
<div class="description">
lost character gap quantity precision low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[ -ca.5- ]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[ca.5]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" quantity="5" unit="character" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/34423" onclick="window.open(this.href);return false;">
O.Douch.2.88
</a>
</div>
<hr>
<div class="note">
To indicate an approximate number of lost characters inside lacuna, enter [ca.5], where '5' is the number of lost characters.
</div>
<hr>
<div class="description">
lost character gap quantity
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[  ̣  ̣  ̣  ̣  ̣  ̣  ̣  ̣ ] / [ -ca.43- ] 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[.8] or [.43]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" quantity="8" unit="character"/&gt; or &lt;gap reason="lost" quantity="43" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8884" onclick="window.open(this.href);return false;">
BGU.1.110
</a>
</div>
<hr>
<div class="note">
Known number of characters lost in lacuna. Note: all strings of lost characters greater than 8 are rendered as approximations. So, "[.43]" will be encoded as a piece of editorial certainty, but will nevertheless be displayed as an approximation: "[ - ca.43 - ]"
</div>
<hr>
<div class="description">
lost character gap range
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[ -ca.11-15- ]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[.11-15]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" atLeast="11" atMost="15" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/63672" onclick="window.open(this.href);return false;">
P.Oxy.46.3285
</a>
</div>
<hr>
<div class="note">
Known range of characters lost in lacuna.
</div>
<hr>
<div class="description">
lost character gap unknown quantity
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[ - ca. ? - ]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[.?]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" extent="unknown" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/o.berenike;1;6" onclick="window.open(this.href);return false;">
O.Berenike.1.6
</a>
</div>
<hr>
<div class="note">
Unknown number of characters lost in lacuna.
</div>
<hr>
<div class="description">
supplied lost words
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[ὁμο]λογῶ
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[ὁμο]λογῶ
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;supplied reason="lost"&gt;ὁμο&lt;/supplied&gt;λογῶ
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18216" onclick="window.open(this.href);return false;">
P.Matr.2
</a>
</div>
<hr>
<div class="note">
Letters lost in lacuna, restored by modern editor.
</div>
<hr>
<div class="description">
supplied lost cert low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ἡμετέρ[α μήτηρ (?) - ca. ? - ]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ἡμετέρ[α μήτηρ (?)] [.?]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
ἡμετέρ&lt;supplied reason="lost" cert="low"&gt;α μήτηρ &lt;/supplied&gt; &lt;gap reason="lost" extent="unknown" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18218" onclick="window.open(this.href);return false;">
P.Matr.5
</a>
</div>
<hr>
<div class="note">
Letters lost in lacuna, restored by modern editor; restoration uncertain
<br>
<br>Example: ἡμετέρ[α μήτηρ (?) -ca.?- ]
<br>
<br>Note that the restoration of μήτηρ is uncertain, but the lacuna after it is not. Thus, encode as follows: 
<br>
<br>ἡμετέρ[α μήτηρ (?)] [.?]
<br>
<br>in order to indicate that the one restoration is uncertain and the other certain. For even greater precision, we might enter:
<br>
<br>ἡμετέρ[α] [μήτηρ (?)] [.?]
<br>
<br>
</div>
<hr>
<div class="description">
supplied parallel
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Πόσεις
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
|_Πόσεις_|
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;supplied evidence="parallel" reason="undefined"&gt;Πόσεις&lt;/supplied&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/p.berl.leihg;2;39" onclick="window.open(this.href);return false;">
P.Berl.Leihg.2.39
</a>
</div>
<hr>
<div class="note">
Text supplied from parallel text, other copy, or transcription of previously visible text that is now lost or illegible.
</div>
<hr>
<div class="description">
Line rendered perpendicular to the main body of text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; 2. (perpendicular)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(2, perpendicular)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="2" rend="perpendicular"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/31065" onclick="window.open(this.href);return false;">
P.Berl.Bibl.12
</a>
</div>
<hr>
<div class="note">
Numbered line written perpendicular to main text.
</div>
<hr>
<div class="description">
line rendered inverse to the main body of text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; 8. (inverse)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(8, inverse)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="8" rend="inverse"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/35611" onclick="window.open(this.href);return false;">
P.Oxy.16.1951
</a>
</div>
<hr>
<div class="note">
Numbered line written inverse to main text.
</div>
<hr>
<div class="description">
line rendered perpendicular to the main body of text in left margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
8,ms --&gt; 8,ms (perpendicular)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(8,ms, perpendicular)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="8,ms" rend="perpendicular"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/37268" onclick="window.open(this.href);return false;">
P.Harr.1.161
</a>
</div>
<hr>
<div class="note">
Numbered line written in left margin and perpendicular to main text.
</div>
<hr>
<div class="description">
line rendered inverse to the main body of text in lower margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
16,minf --&gt; 16,minf (inverse) NOTE: getting cut off at left
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(16,minf, inverse)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="16,minf" rend="inverse"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/1462" onclick="window.open(this.href);return false;">
P.Cair.Zen.5.59838
</a>
</div>
<hr>
<div class="note">
Numbered line written in lower margin and inverse to main text.
</div>
<hr>
<div class="description">
Line written in left margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
3,ms
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
3,ms. 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="3,ms"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8223" onclick="window.open(this.href);return false;">
P.Hib.1.74
</a>
</div>
<hr>
<div class="note">
Numbered line written in left margin.
</div>
<hr>
<div class="description">
line 5 to 6
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
5/6
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
5/6. 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="5/6"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/28409" onclick="window.open(this.href);return false;">
P.Oxy.1.117
</a>
</div>
<hr>
<div class="note">
For use in rare cases in which lines are presented so as not to indicate break; not recommended.
</div>
<hr>
<div class="description">
line break
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
1. 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
1. 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="1"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/28409" onclick="window.open(this.href);return false;">
P.Oxy.1.117
</a>
</div>
<hr>
<div class="note">
To indicate line number. Every line must have a line number.
</div>
<hr>
<div class="description">
Words that wrap across lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
5
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
5.- 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="5" type="inWord"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10559" onclick="window.open(this.href);return false;">
p.col.;10;259
</a>
</div>
<hr>
<div class="note">
Words that wrap from the end of one line to the beginning of the next. Note that in Leiden+ the hyphen must be written at the start of the following line:
<br>
<br> 12. ἃς καὶ &lt;:ἀποδώσει|orth|αποδωσι:&gt; ἐν μηνὶ Πα
<br> 13.- ῦ̣[νι τοῦ] ἐνεσ[τ]ῶτος ἔτους
<br>
<br>In the PN the hyphen will be displayed in the expected location:
<br>
<br>  ἃς καὶ ἀποδώσει ἐν μηνὶ Πα-
<br>  ῦ̣[νι τοῦ] ἐνεσ[τ]ῶτος ἔτους
<br>
</div>
<hr>
<div class="description">
Line with word-wrap written inverse to main text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; 3. (inverse) with hyphen at end of preceding line
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(3.-, inverse)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="3" rend="inverse" type="inWord"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/sb;24;16170" onclick="window.open(this.href);return false;">
SB.24.16170
</a>
</div>
<hr>
<div class="note">
For lines written inverse / perpendicular to main text and containing a word-wrap, simply add hyphen to the regular convention.
</div>
<hr>
<div class="description">
Known number of lines missing
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[7 lines missing]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
lost.7lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" quantity="7" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/20672" onclick="window.open(this.href);return false;">
P.Oxy.3.617
</a>
</div>
<hr>
<div class="note">
To indicate a known number of lost lines.
</div>
<hr>
<div class="description">
Approximate number of lines lost
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[ca 7 lines missing]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
lost.ca.7lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" quantity="7" unit="line" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/74537" onclick="window.open(this.href);return false;">
O.Kell.13
</a>
</div>
<hr>
<div class="note">
To indicate approximate number of lines lost.
</div>
<hr>
<div class="description">
Approximate range of lines lost
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[3-4 lines missing]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
lost.3-4lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" atLeast="3" atMost="4" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/3231" onclick="window.open(this.href);return false;">
P.Lille.1.29
</a>
</div>
<hr>
<div class="note">
To indicate approximate range of lines lost.
</div>
<hr>
<div class="description">
Unknown number of lines lost
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
-- -- -- -- -- -- -- -- -- --
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
lost.?lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" extent="unknown" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
To indicate unknown number of lines lost. This is used to indicate "break" in the papyrus. Enter as follows:
<br>
<br>1. lost.?lin
<br>1. first line of text
<br>2. second line of text
<br>3. third line of text
<br>3. lost.?lin
</div>
<hr>
<div class="description">
num with symbol &amp; value with markup
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ι[ε(?)] = SoSOL,  α[ε][̣]̣ = PN
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#ι[ε(?)]=15#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="15"&gt;ι&lt;supplied reason="lost" cert="low"&gt;ε&lt;/supplied&gt;&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10217" onclick="window.open(this.href);return false;">
P.Berl.Leihg.1.8
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
<div class="description">
Number whole
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ιϛ
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#ιϛ=16#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="16"&gt;ιϛ&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10217" onclick="window.open(this.href);return false;">
P.Berl.Leihg.1.8
</a>
</div>
<hr>
<div class="note">
Numbers should be accompanied by their values.
</div>
<hr>
<div class="description">
Number fraction
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ιϛ
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#ιϛ=1/16#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="1/16"&gt;ιϛ&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
Fractions should be accompanied by their values, just as whole numbers.
</div>
<hr>
<div class="description">
Number with '
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
λβ´
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#λβ '=1/32#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="1/32" rend="tick"&gt;λβ&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18215" onclick="window.open(this.href);return false;">
P.Matr.1
</a>
</div>
<hr>
<div class="note">
To indicate the presence of a tick on the papyrus. This works for both fractions and whole numbers. In the PN a mouseover pop-up will alert you as to whether a number is whole or fraction. Note: the tick must be the standard ascii ('), not a Smart Quote, and not a Greek Unicode apostrophe (just as the system requires &lt;...&gt; and does not permit Greek Unicode ⟨...⟩)
<br>
<br>For example:
<br>&lt;γ '=3&gt;
<br>&lt;γ '=1/3&gt;
</div>
<hr>
<div class="description">
Uncertainly read number
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
σ̣ν̣ϛ̣´
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#σ̣ν̣ϛ̣ '=1/256#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="1/256" rend="tick"&gt;&lt;unclear&gt;σνϛ&lt;/unclear&gt;&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/72534" onclick="window.open(this.href);return false;">
O.Bodl.2
</a>
</div>
<hr>
<div class="note">
Underdot numbers as you would any other uncertainly read character.
</div>
<hr>
<div class="description">
Illegible numbers
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
&nbsp;&nbsp;̣&nbsp;&nbsp;̣
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#.2=#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num&gt;&lt;gap reason="illegible" quantity="2" unit="character"/&gt;&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/32161" onclick="window.open(this.href);return false;">
P.Oxy.64.4435
</a>
</div>
<hr>
<div class="note">
To indicate presence of an illegible number
</div>
<hr>
<div class="description">
Missing numbers
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[&nbsp;&nbsp;̣&nbsp;&nbsp;̣ ]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#[.2]=#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num&gt;&lt;gap reason="lost" quantity="2" unit="character"/&gt;&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
To indicate a lost number, simply enter a lacuna where you would normally enter the Greek number and leave the value blank.
</div>
<hr>
<div class="description">
num no symbol
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
nothing 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#=4#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="4"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18216" onclick="window.open(this.href);return false;">
P.Matr.2
</a>
</div>
<hr>
<div class="note">
Numbers that are spelled out in Latin and Greek are followed by 'empty' number tags.
</div>
<hr>
<div class="description">
num fraction no symbol
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
nothing 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#=1/8#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="1/8"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18216" onclick="window.open(this.href);return false;">
P.Matr.2
</a>
</div>
<hr>
<div class="note">
Numbers that are spelled out in Latin and Greek are followed by 'empty' number tags.
</div>
<hr>
<div class="description">
Omitted language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Demotic 1 line
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lang: Demotic 1 lines)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="1" unit="line"&gt;&lt;desc&gt;Demotic&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/4593" onclick="window.open(this.href);return false;">
P.Hib.1.142
</a>
</div>
<hr>
<div class="note">
Lines of Demotic omitted from DDbDP or edition. 
</div>
<hr>
<div class="description">
Omitted language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Coptic ? lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lang: Coptic ? lines)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" extent="unknown" unit="line"&gt;&lt;desc&gt;Coptic&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/15004" onclick="window.open(this.href);return false;">
Stud.Pal.10.172
</a>
</div>
<hr>
<div class="note">
Lines of Coptic omitted from DDbDP or edition.
</div>
<hr>
<div class="description">
Omitted language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Demotic ? lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lang: Demotic ? lines)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" extent="unknown" unit="line"&gt;&lt;desc&gt;Demotic&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/54520" onclick="window.open(this.href);return false;">
T.Mom.Louvre.30
</a>
</div>
<hr>
<div class="note">
Unknown number of lines of Demotic omitted from DDbDP or edition.
</div>
<hr>
<div class="description">
Omitted language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Demotic 2 characters
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lang: Demotic 2 char)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="2" unit="character"&gt;&lt;desc&gt;Demotic&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/50773" onclick="window.open(this.href);return false;">
O.Wilck.457
</a>
</div>
<hr>
<div class="note">
Demotic characters omitted from DDbDP or edition.
</div>
<hr>
<div class="description">
Omitted language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Demotic ? characters
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lang: Demotic ? char)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" extent="unknown" unit="character"&gt;&lt;desc&gt;Demotic&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/43479" onclick="window.open(this.href);return false;">
O.Leid.15
</a>
</div>
<hr>
<div class="note">
Unknown number of Demotic characters omitted from DDbDP or edition.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
19 lines untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lines: 19 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="19" unit="line"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/28475" onclick="window.open(this.href);return false;">
P.Tebt.2.574
</a>
</div>
<hr>
<div class="note">
Known number of lines left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
? lines untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lines: ? non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" extent="unknown" unit="line"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/38980" onclick="window.open(this.href);return false;">
Stud.Pal.10.178
</a>
</div>
<hr>
<div class="note">
Unknown number of lines left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
1-3 lines untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lines: 1-3 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" atLeast="1" atMost="3" unit="line"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/17940" onclick="window.open(this.href);return false;">
P.Oxy.58.3958
</a>
</div>
<hr>
<div class="note">
Range of lines left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ca.7 lines untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lines: ca.7 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="7" unit="line" precision="low"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/25686" onclick="window.open(this.href);return false;">
P.Oxy.2.396
</a>
</div>
<hr>
<div class="note">
Estimated number of lines left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
? characters untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Chars: ? non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" extent="unknown" unit="character"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/29504" onclick="window.open(this.href);return false;">
SB.20.14952
</a>
</div>
<hr>
<div class="note">
Unknown number of characters left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
1 character untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Chars: 1 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="1" unit="character"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Known number of characters left untranscribed by editor. 
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
1-2 characters untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Chars: 1-2 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" atLeast="1" atMost="2" unit="character"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/34332" onclick="window.open(this.href);return false;">
P.Eleph.Wagner.1.365
</a>
</div>
<hr>
<div class="note">
Range of characters left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ca.18 characters untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Chars: ca.18 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="18" unit="character" precision="low"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Estimated number of characters left untranscribed by editor.
</div>
<hr>
<div class="description">
Quotation
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
'ὁ γὰ̣ρ̣ ἐ̣λ̣εῶ̣ν̣ [πτωχόν]'
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
" ὁ γὰ̣ρ̣ ἐ̣λ̣εῶ̣ν̣ [πτωχόν] "
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;q&gt; ὁ γ&lt;unclear&gt;ὰρ&lt;/unclear&gt; &lt;unclear&gt;ἐλ&lt;/unclear&gt;ε&lt;unclear&gt;ῶν&lt;/unclear&gt; &lt;supplied reason="lost"&gt;πτωχόν&lt;/supplied&gt; &lt;/q&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/34027" onclick="window.open(this.href);return false;">
P.Gen.2.1.14
</a>
</div>
<hr>
<div class="note">
Modern mark indicating quotation.
</div>
<hr>
<div class="description">
figure on papyri
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
seal
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
#seal
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;figure&gt;&lt;figDesc&gt;seal&lt;/figDesc&gt;&lt;/figure&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/p.cair.zen;1;59003" onclick="window.open(this.href);return false;">
P.Cair.Zen.1.59003
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
<div class="description">
Paragraphos
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
——
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
----
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;milestone rend="paragraphos" unit="undefined"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/9025" onclick="window.open(this.href);return false;">
BGU.1.28
</a>
</div>
<hr>
<div class="note">
To indicate paragraphos between, say, lines 4 and 5, enter as follows:
<br>
<br>3. text
<br>4. text
<br>----
<br>5. text
<br>
<br>Note: paragraphoi should be entered 'between lines', as above, and not on their own lines.
</div>
<hr>
<div class="description">
Horizontal rule on papyrus
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
————————
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
--------
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;milestone rend="horizontal-rule" unit="undefined"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/4776" onclick="window.open(this.href);return false;">
BGU.7.1526
</a>
</div>
<hr>
<div class="note">
To indicate horizontal rule on papyrus. To indicate paragraphos between, say, lines 4 and 5, enter as follows:
<br>
<br>3. text
<br>4. text
<br>--------
<br>5. text 
<br>
<br>Note: horizontal rules should be entered 'between lines', as above, and not on their own lines.
</div>
<hr>
<div class="description">
Non-alphabetical characters or symbols (example: slanting-stroke)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
/
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*slanting-stroke*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;g type="slanting-stroke"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10227" onclick="window.open(this.href);return false;">
P.Berl.Leihg.2.38
</a>
</div>
<hr>
<div class="note">
To indicate slanting stroke(s) written on papyrus.
</div>
<hr>
<div class="description">
Uncertain non-alphabetical characters or symbols (example: check)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
 /̣
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*check?*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;unclear&gt;&lt;g type="check"/&gt;&lt;/unclear&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8946" onclick="window.open(this.href);return false;">
BGU.1.186
</a>
</div>
<hr>
<div class="note">
Unclear ancient 'check' mark on papyrus.
</div>
<hr>
<div class="description">
Non-alphabetical character with symbol (example: Chi-rho)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
☧
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*chirho,☧*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;g type="chirho"&gt;☧&lt;/g&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
To indicate chi-rho symbol; you may indicate preferred Unicode symbol: *chirho,☧*
</div>
<hr>
<div class="description">
Uncertain non-alphabetical character with symbol (example: Chi-rho)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
☧̣
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*chirho?,☧*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;unclear&gt;&lt;g type="chirho"&gt;☧&lt;/g&gt;&lt;/unclear&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/128700" onclick="window.open(this.href);return false;">
p.jena;2;19
</a>
</div>
<hr>
<div class="note">
To indicate an uncertain chi-rho symbol; you may indicate preferred Unicode symbol: *chirho?,☧*
</div>
<hr>
<div class="description">
Filler stroke
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
―
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*filler(extension)*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;g rend="extension" type="filler"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10201" onclick="window.open(this.href);return false;">
P.Berl.Leihg.1.17
</a>
</div>
<hr>
<div class="note">
Filler strokes, usually at end of line.
</div>
<hr>
<div class="description">
Filler stroke (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; ―(?)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*filler(extension)?*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;unclear&gt;&lt;g rend="extension" type="filler"/&gt;&lt;/unclear&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/28171" onclick="window.open(this.href);return false;">
BGU.2.509
</a>
</div>
<hr>
<div class="note">
Unclear filler stroke on papyrus.
</div>
<hr>
<div class="description">
S-type etous
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
((s-etous))
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*s-etous*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;g type="s-etous"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/22431" onclick="window.open(this.href);return false;">
P.Lips.1.109
</a>
</div>
<hr>
<div class="note">
S-type etous symbol.
</div>
<hr>
<div class="description">
'Parens' on papyrus
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
((parens-punctuation-opening))  ((parens-punctuation-closing)) --&gt; distinct unicode parens
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*parens-punctuation-opening*  *parens-punctuation-closing*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;g type="parens-punctuation-opening"/&gt;  &lt;g type="parens-punctuation-closing"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Text marked in antiquity with opening parens, closing parens, or both. If the ancient parens indicate(s) deletion mark the affected string with ((parens-punctuation-opening)) and/or ((parens-punctuation-closing)) and fully enclose in 〚...〛. If the semantic meaning of the parens is not clearly deletion, then use ((parens-punctuation-opening)) and/or ((parens-punctuation-closing)) alone.
</div>
<hr>
<div class="description">
Text in box
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: milestone01…App: ctr.11. Text in box
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
###
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;milestone rend="box" unit="undefined"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/4787" onclick="window.open(this.href);return false;">
BGU.7.1537
</a>
</div>
<hr>
<div class="note">
To indicate text written inside a 'box'.
</div>
<hr>
<div class="description">
Tall text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; render taller
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
~||x||~tall
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="tall"&gt;x&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/21513" onclick="window.open(this.href);return false;">
P.Oslo.2.26
</a>
</div>
<hr>
<div class="note">
Oversized / tall text.
</div>
<hr>
<div class="description">
Superscripted text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
superscript
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
|^Ἡρωνείνῳ^|
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="superscript"&gt;Ἡρωνείνῳ&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/31500" onclick="window.open(this.href);return false;">
P.Laur.1.3
</a>
</div>
<hr>
<div class="note">
Text written in superscript, as distinct from text added above the line, as 'afterthought' or 'self-correction' (for which use \καὶ/). In general we do not encode superscript characters that indicate abbreviation.
</div>
<hr>
<div class="description">
Subscripted text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
subscript
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
\|τα|/
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="subscript"&gt;τα&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
To indicate subscripted text, as distinct from text added from below the line (for which use //καὶ\\).
</div>
<hr>
<div class="description">
Supraline
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
νο  ̣--&gt; with supraline
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
¯νο.1¯
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="supraline"&gt;νο&lt;gap reason="illegible" quantity="1" unit="character"/&gt;&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/33704" onclick="window.open(this.href);return false;">
P.Lips.1.102
</a>
</div>
<hr>
<div class="note">
To indicate supralines, most often used in case of numbers (not, as rule, for expansions)
</div>
<hr>
<div class="description">
Supraline and underline
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; underline and supraline
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
=εὐτύχει=
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="supraline-underline"&gt;εὐτύχει&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18651" onclick="window.open(this.href);return false;">
BGU.4.1201
</a>
</div>
<hr>
<div class="note">
To indicate text that is both underlined and supralined.
</div>
<hr>
<div class="description">
supplied parallel cert low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ἀρ(τάβας(?)) δωδέκ(ατον) εἰκ(οστοτέταρτον(?)) (ἀρτάβας) ιβ´ κδ´ † Ἀγαθάμμωνapp02 †/ ((tachygraphic-marks))
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
|_(ἀρ(τάβας?)) (δωδέκ(ατον)) (εἰκ(οστοτέταρτον?)) ((ἀρτάβας)) &lt;#ιβ=frac1/12#&gt; &lt;#κδ=frac1/24#&gt; *stauros* &lt;:Ἀγαθάμμων|BL:8.441|(δ(ι)) (|μ|) κάμμονι:&gt; *stauros*/ *tachygraphic-marks*(?)_|
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;supplied evidence="parallel" reason="undefined" cert="low"&gt;&lt;expan&gt;ἀρ&lt;ex cert="low"&gt;τάβας&lt;/ex&gt;&lt;/expan&gt; &lt;expan&gt;δωδέκ&lt;ex&gt;ατον&lt;/ex&gt;&lt;/expan&gt; &lt;expan&gt;εἰκ&lt;ex cert="low"&gt;οστοτέταρτον&lt;/ex&gt;&lt;/expan&gt; &lt;expan&gt;&lt;ex&gt;ἀρτάβας&lt;/ex&gt;&lt;/expan&gt; &lt;num value="1/12" rend="fraction"&gt;ι
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/37758" onclick="window.open(this.href);return false;">
Stud.Pal.3.503
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
<div class="description">
supplied parallel lost
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
???
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
_[abc]_
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
example only - &lt;supplied evidence="parallel" reason="lost"&gt;abc&lt;/supplied&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist 
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
<div class="description">
text sling in margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ν
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;|ν|&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add rend="sling" place="margin"&gt;ν&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/41055" onclick="window.open(this.href);return false;">
BGU.1.303
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
<div class="description">
text underline in margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
οὕτως ἔχει
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;_οὕτως ἔχει_&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add rend="underline" place="margin"&gt;οὕτως ἔχει&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/12794" onclick="window.open(this.href);return false;">
P.Prag.2.137
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
<div class="description">
text above line with cert low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Θέ̣ων̣(?) = SoSOL,  Θέ̣ων̣(?)/ = PN
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
Θέ̣ων̣?/
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add cert="low" place="above"&gt;Θ&lt;unclear&gt;έ&lt;/unclear&gt;ω&lt;unclear&gt;ν&lt;/unclear&gt;&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/psi;4;281" onclick="window.open(this.href);return false;">
PSI.4.281
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
<div class="description">
character space extent unknown
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
vac.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.?
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space extent="unknown" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10223" onclick="window.open(this.href);return false;">
P.Berl.Leihg.2.39
</a>
</div>
<hr>
<div class="note">
Vacat of unknown number of characters. It is tempting to use vac.? to replicate the modern print publication convention of separating, e.g. items from numbers in accounts and the like. Rampant use of vac.? for this purpose is discouraged. Use vac.? only where there is empty space on the physical text; if such is not verifiable against image or original do not use vac.?.
</div>
<hr>
<div class="description">
character space quantity
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac.3
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.3
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space quantity="3" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of known number of characters.
</div>
<hr>
<div class="description">
character space range
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac.2-5
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.2-5
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space atLeast="2" atMost="5" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of known range of characters.
</div>
<hr>
<div class="description">
character space quantity precision low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac. ca.3
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.ca.3
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space quantity="3" unit="character" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of estimated range of characters.
</div>
<hr>
<div class="description">
line space extent unknown
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac. ? lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.?lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space extent="unknown" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of unknown number of lines.
</div>
<hr>
<div class="description">
line space quantity
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac. 3 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.3lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space quantity="3" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of known number of lines.
</div>
<hr>
<div class="description">
line space range
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac. 2-5 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.2-5lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space atLeast="2" atMost="5" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of known range of lines.
</div>
<hr>
<div class="description">
line space quantity precision low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac ca.3 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.ca.3lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space quantity="3" unit="line" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of estimated number of lines.
</div>
<hr>
<div class="description">
Vestiges n lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces 15 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig.15lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="15" unit="line"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/16792" onclick="window.open(this.href);return false;">
P.Stras.6.559
</a>
</div>
<hr>
<div class="note">
Vestiges of known number of lines.
</div>
<hr>
<div class="description">
Vestiges range of lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces 2-3 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig.2-3lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" atLeast="2" atMost="3" unit="line"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/9414" onclick="window.open(this.href);return false;">
BGU.3.916
</a>
</div>
<hr>
<div class="note">
Vestiges of known range of lines.
</div>
<hr>
<div class="description">
Vestiges ca.n lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces ca.3 lines 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ex. vestig.ca.3lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
ex. &lt;gap reason="illegible" quantity="3" unit="line" precision="low"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vestiges of estimated number of lines.
</div>
<hr>
<div class="description">
Vestiges ? lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
-ca.?- --&gt; Traces ? lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig.?lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" extent="unknown" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/16792" onclick="window.open(this.href);return false;">
P.Stras.6.559
</a>
</div>
<hr>
<div class="note">
Vestiges of unknown number of lines.
</div>
<hr>
<div class="description">
Vestiges ? characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
-ca.?- --&gt; Traces
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" extent="unknown" unit="character"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/70853" onclick="window.open(this.href);return false;">
O.Berenike.1.76
</a>
</div>
<hr>
<div class="note">
Vestiges of unknown number of characters. NOTE: You must enter a space after vestig; so, not "vestig" but "vestig ".
</div>
<hr>
<div class="description">
Vestiges ca.n characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ca.traces - --&gt; Traces 8 char. / Traces ca.14 char.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig.14char
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="14" unit="character"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/22338" onclick="window.open(this.href);return false;">
P.Lips.1.21
</a>
</div>
<hr>
<div class="note">
Vestiges of known number of characters. Note: all vestige strings greater than 8 characters are rendered as approximations. So, "vestig.14char" will be encoded as a piece of editorial certainty, but will nevertheless be displayed as an approximation: "Traces ca.14 char."
</div>
<hr>
<div class="description">
Vestiges ca.n characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
  ̣  ̣  ̣  --&gt; Traces ca.3 char.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
example only - vestig.ca.3char
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
example only - &lt;gap reason="illegible"  quantity="3" unit="character" precision="low"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vestiges of estimated number of characters.
</div>
<hr>
<div class="description">
Vestiges range of characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
-ca.15-30- --&gt; Traces ca.15-30 characters
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig.15-30char
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" atLeast="15" atMost="30" unit="character"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/15381" onclick="window.open(this.href);return false;">
P.Oxy.50.3557
</a>
</div>
<hr>
<div class="note">
Vestiges of range of characters.
</div>
<hr>
</div>
<div class="category" id="Apparatus, alternate reading" style="display:;">
<div class="category_display">
Apparatus, alternate reading
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Apparatus, alternate reading-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Apparatus, alternate reading-examples" style="display:none;">
<div class="description">
Alternate reading
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: Ὀχυρυγχίτου…App: or Ὀξυρυγχίτου νομοῦ
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:Ὀχυρυγχίτου|alt|Ὀξυρυγχίτου νομοῦ:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="alternative"&gt;&lt;lem&gt;Ὀχυρυγχίτου&lt;/lem&gt;&lt;rdg&gt;Ὀξυρυγχίτου νομοῦ&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/4548" onclick="window.open(this.href);return false;">
BGU.6.1265
</a>
</div>
<hr>
<div class="note">
Alternate readings posited by the editor. Preferred reading (&lt;lem&gt;) will appear in the text, the alternative (&lt;rdg&gt;) in the apparatus.
</div>
<hr>
<div class="description">
Alternate reading, multiple
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: [ - ca.? - ] ̣αμεν ̣ν̣…App: or [ἀπογρα]ψ̣αμένη̣ν̣, or [θρε]ψ̣αμένη̣ν̣
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="alternative"&gt;&lt;lem&gt;&lt;gap reason="lost" extent="unknown" unit="character"/&gt;&lt;gap reason="illegible" quantity="1" unit="character"/&gt;αμεν&lt;gap reason="illegible" quantity="1" unit="character"/&gt;&lt;unclear&gt;ν&lt;/unclear&gt;&lt;/lem&gt;&lt;rdg&gt;&lt;supplied reason="lost"&gt;ἀπο
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Multiple alternate readings posited by the editor. Preferred reading (&lt;lem&gt;) will appear in the text, the alternatives (&lt;rdg&gt;) in the apparatus.
<br>
<br>Where the papyrus reads, e.g. [ - - - ] ̣αμεν ̣ν̣ and the editor posits perhaps [ἀπογρα]ψ̣αμένη̣ν̣ or [θρε]ψ̣αμένη̣ν̣, encode:
<br>
<br>&lt;:[.?].1αμεν.1ν̣||alt||[ἀπογρα]ψ̣αμένη̣ν̣|[θρε]ψ̣αμένη̣ν̣:&gt;
</div>
<hr>
<div class="description">
Alternate reading (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: Ὀχυρυγχίτου(?)…App: or Ὀξυρυγχίτου νομοῦ(?)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="alternative"&gt;&lt;lem&gt;Ὀχυρυγχίτου&lt;certainty match=".." locus="value"/&gt;&lt;/lem&gt;&lt;rdg&gt;Ὀξυρυγχίτου νομοῦ&lt;certainty match=".." locus="value"/&gt;&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;6;1265" onclick="window.open(this.href);return false;">
bgu;6;1265
</a>
</div>
<hr>
<div class="note">
By definition, all alternate readings are uncertain, but to indicate especial uncertainty as to one or both possibilities, enter as follows: 
<br>
<br>&lt;:Ὀχυρυγχίτου(?)|alt|Ὀξυρυγχίτου νομοῦ(?):&gt;
</div>
<hr>
</div>
</div>
<div class="category" id="Apparatus, Berichtigungliste corrections" style="display:;">
<div class="category_display">
Apparatus, Berichtigungliste corrections
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Apparatus, Berichtigungliste corrections-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Apparatus, Berichtigungliste corrections-examples" style="display:none;">
<div class="description">
BL correction
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: αἱ τοῦ…App: BL 9.17: Θίτου Original ed.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:αἱ τοῦ=BL 9.17|ed|Θίτου:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="BL 9.17"&gt;αἱ τοῦ&lt;/lem&gt;&lt;rdg&gt;Θίτου&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8916" onclick="window.open(this.href);return false;">
BGU.1.141
</a>
</div>
<hr>
<div class="note">
To indicate corrections that have been flagged in the Berichtigungsliste, e.g. &lt;:αἱ τοῦ=BL 9.17|ed|Θίτου:&gt;, where αἱ τοῦ is the correction recorded by BL and Θίτου is the deprecated reading.
</div>
<hr>
<div class="description">
BL correction (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: αἱ τοῦ(?)…App: BL 9.17: Θίτου Original ed.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:αἱ τοῦ(?)=BL 9.17|ed|Θίτου:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="BL 9.17"&gt;αἱ τοῦ&lt;certainty match=".." locus="value"/&gt;&lt;/lem&gt;&lt;rdg&gt;Θίτου&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;141" onclick="window.open(this.href);return false;">
bgu;1;141
</a>
</div>
<hr>
<div class="note">
To indicate uncertain corrections that have been flagged in the Berichtigungsliste
</div>
<hr>
</div>
</div>
<div class="category" id="Apparatus, complicated corrections" style="display:;">
<div class="category_display">
Apparatus, complicated corrections
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Apparatus, complicated corrections-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Apparatus, complicated corrections-examples" style="display:none;">
<div class="description">
Complicated corrections
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
275. corr. ex σ  ̣  ̣[ -ca.?- ] (or γ  ̣  ̣  ̣[ -ca.?- ]), BL 15.2 : ξτρ[ατηλάτης] (l. στρ[ατηλάτης) (or   ̣γρ[ -ca.?- ]) J. Cowey, ZPE 150 (2020) 321-323 : στυ̣ρ[ατ -ca.?- ] (l. στρ[ατιώτης (or στρ[ατηγία])) R. Ast, CdE 100 (2018) 13-15 (BL 14.5) : etc.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:&lt;:στρ[ατηγὸς]|subst|&lt;:σ.2[.?]|alt|γ.3[.?]:&gt;:&gt;=BL 15.2||ed||&lt;:&lt;:στρ[ατηλάτης]|reg|ξτρ[ατηλάτης]:&gt;|alt|.1γρ[.?]:&gt;=J. Cowey, ZPE 150 (2020) 321-323|&lt;:&lt;:στρ[ατιώτης]|alt|στρ[ατηγία]:&gt;|reg|στυ̣ρ[ατ][.?]:&gt;=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)|&lt;:Συρ[ίων](?)|
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="BL 15.2"&gt;&lt;subst&gt;&lt;add place="inline"&gt;στρ&lt;supplied reason="lost"&gt;ατηγὸς&lt;/supplied&gt;&lt;/add&gt;&lt;del rend="corrected"&gt;&lt;app type="alternative"&gt;&lt;lem&gt;σ&lt;gap reason="illegible" quantity="2" unit="character"/&gt;&lt;gap reason="lost" extent="un
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Leiden+ is capable of handling even extremely complicated series of corrections. Take the following completely fictional example:
<br>
<br>
<br>275. &lt;:&lt;:στρ[ατηγὸς]|subst|&lt;:σ.2[.?]|alt|γ.3[.?]:&gt;:&gt;=BL 19.2||ed||
<br>&lt;:&lt;:στρ[ατηλάτης]|reg|ξ̣τ̣ρ[ατηλάτης]:&gt;|alt|.1γρ[.?]:&gt;=J. Cowey, ZPE 150 (2020) 321-323|
<br>&lt;:&lt;:στρ[ατιώτης]|alt|στρ[ατηγία]:&gt;|reg|στυ̣ρ[ατ][.?]:&gt;=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)|
<br>&lt;:Συρ[ίων](?)|reg|&lt;:&lt;:Σο̣υ̣ρ[ίων]||alt||Συ̣υ̣ρ[ίων]|Σω̣υ̣ρ[ίων]:&gt;|subst|Σ.2ρ[ίων]:&gt;:&gt;=Original Edition:&gt;
<br>
<br>This means:
<br>(1) at line 275 the DDbDP prints στρ[ατηγὸς], which the scribe himself corrected from either "σ . . [ca.?]" or "γ . . . [ca.?]", and which is recorded in BL vol.19 p.2
<br>
<br>(2) previously, Cowey had argued (in ZPE 150) for correcting the text to either στρ[ατηλάτης], which is a modern regularization of ξ̣τ̣ρ[ατηλάτης], or to ". γρ[ca.?]"
<br>
<br>(3) before Cowey, Ast had suggested (in CdÉ 100) that the papyrus reads στυ̣ρ[ατ- ca.?], which should be regularized either to στρ[ατιώτης] or to στρ[ατηγία]; this was subsequently picked up by BL 14.5
<br>
<br>(4) The original editors of the papyrus thought that the scribe had originally written "Σ . . ρ[ίων]", and then corrected it to either Σο̣υ̣ρ[ίων] or Συ̣υ̣ρ[ίων] or Σω̣υ̣ρ[ίων], any one of which should perhaps be regularized to Συρ[ίων]
<br>
<br>Under this model, simple corrections may be concatenated:
<br>
<br>275a. &lt;:στρ[ατηγὸς]=BL 15.2||ed||
<br>στρ[ατηλάτης]=J. Cowey, ZPE 150 (2020) 321-323|
<br>στρ[ατιώτης]=R. Ast, CdE 100 (2018) 13-15 (BL 14.5)|
<br>Συρ[ίων]=Original Edition:&gt;
<br>
<br>or, any class of correction may be 'nested' inside any other (as above).
</div>
<hr>
</div>
</div>
<div class="category" id="Apparatus, editorial correction" style="display:;">
<div class="category_display">
Apparatus, editorial correction
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Apparatus, editorial correction-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Apparatus, editorial correction-examples" style="display:none;">
<div class="description">
Editorial correction
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: κγ…App: bgu 1 p.357: κϛ Original ed.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:&lt;#κγ=23#&gt;=BGU 1 p.357|ed|&lt;#κϛ=26#&gt;:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="BGU 1 p.357"&gt;&lt;num value="23"&gt;κγ&lt;/num&gt;&lt;/lem&gt;&lt;rdg&gt;&lt;num value="26"&gt;κϛ&lt;/num&gt;&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8922" onclick="window.open(this.href);return false;">
BGU.1.154
</a>
</div>
<hr>
<div class="note">
Used for two situations: to indicate a correction proposed in a publication (not reported by Berichtigungsliste); either 
<br>
<br>(1) correction proposed in series Corrigenda list: &lt;:&lt;#κγ=23#&gt;|ed:BGU 1 p.357|&lt;#κϛ=26#&gt;:&gt;, where κγ is the new reading and κϛ is the deprecated reading.
<br>
<br>(2) or proposed in a publication: &lt;:(διαγρ(άφου))=N. Gonis, ZPE 143 (2003) 150|ed|(διαγρ(αφῆς)):&gt;, where διαγρ(άφου) is the new reading and διαγρ(αφῆς) is the deprecated reading.
</div>
<hr>
<div class="description">
Editorial correction (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: κγ(?)…App: bgu 1 p.357: κϛ Original ed.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:&lt;#κγ=23#&gt;(?)=bgu 1 p.357|ed|&lt;#κϛ=26#&gt;:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="bgu 1 p.357"&gt;&lt;num value="23"&gt;κγ&lt;/num&gt;&lt;certainty match=".." locus="value"/&gt;&lt;/lem&gt;&lt;rdg&gt;&lt;num value="26"&gt;κϛ&lt;/num&gt;&lt;/rdg&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
Where an editorial correction is only tentative, uncertain, enter as follows:
<br>
<br>&lt;:&lt;#κγ=23#&gt;(?)=BGU 1 p.357|ed|&lt;#κϛ=26#&gt;:&gt;
</div>
<hr>
</div>
</div>
<div class="category" id="Apparatus, orthographic regularization" style="display:;">
<div class="category_display">
Apparatus, orthographic regularization
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Apparatus, orthographic regularization-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Apparatus, orthographic regularization-examples" style="display:none;">
<div class="description">
Orthographic regularization
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: φρόντι[σ]ον….App: φρόνδει[σ]ο̣ν pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:φρόντι[σ]ον|reg|φρόνδει[σ]ο̣ν:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;choice&gt;&lt;reg&gt;φρόντι&lt;supplied reason="lost"&gt;σ&lt;/supplied&gt;ον&lt;/reg&gt;&lt;orig&gt;φρόνδει&lt;supplied reason="lost"&gt;σ&lt;/supplied&gt;&lt;unclear&gt;ο&lt;/unclear&gt;ν&lt;/orig&gt;&lt;/choice&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
To be used for two classes of 'correction':
<br>
<br>(1) Regularization/'correction' of non-standard orthographic form, e.g. αἰνακούεις for ἐνακούεις; in such cases the form is 'correct' but is not spelled in the canonical fashion.
<br>
<br>(2) Correction of syntax not morphology, e.g. τῷ for τοῦ; in such cases the form is a valid one, but is not strictly correct in the context.
<br>
<br>In past, DDbDP suppressed all diacriticals from the mistaken reading. NOTE that DDbDP now presents the reading of the papyrus in the text and the regularized reading in the apparatus (per modern convention). To support that change, we now enter orthographic 'corrections' differently.
<br>
<br>(1) For φρόνδει[σ]ο̣ν --&gt; φρόντισον encode, &lt;:φρόντι[σ]ον|reg|φρόνδει[σ]ο̣ν:&gt; (Note: all Leiden except underdots on left side of 'reg')
<br>(2) PN displays: text: φρόνδει[σ]ο̣ν / app: Read φρόντι[σ]ον
</div>
<hr>
</div>
</div>
<div class="category" id="Apparatus, orthographic regularization, for language" style="display:;">
<div class="category_display">
Apparatus, orthographic regularization, for language
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Apparatus, orthographic regularization, for language-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Apparatus, orthographic regularization, for language-examples" style="display:none;">
<div class="description">
Orthographic regularization, for language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ⲁⲣⲁⲕ….App: i.e. Greek ἄρακος
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:ἄρακος=grc|reg|ⲁⲣⲁⲕ:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;choice&gt;&lt;reg xml:lang="grc"&gt;ἄρακος&lt;/reg&gt;&lt;orig&gt;ⲁⲣⲁⲕ&lt;/orig&gt;&lt;/choice&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Leiden+ treats multi-lingual equivalencies as a kind of rough 'regularization'. So, if a mainly Greek text has some Coptic written in it, and you would like to indicate the Greek word that a Coptic word represents, mark up as follows:
<br>
<br>&lt;:ἄρακος=grc|reg|ⲁⲣⲁⲕ:&gt;
<br>
<br>The text will print ⲁⲣⲁⲕ and the app will read "i.e. Greek ἄρακος"
</div>
<hr>
</div>
</div>
<div class="category" id="Apparatus, orthographic regularization, multiple" style="display:;">
<div class="category_display">
Apparatus, orthographic regularization, multiple
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Apparatus, orthographic regularization, multiple-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Apparatus, orthographic regularization, multiple-examples" style="display:none;">
<div class="description">
Orthographic regularization, multiple
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ἀ̣νύεται….App: l. ἀνοίεται (?), i.e. ἀνοίγεται (?)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:ἀνοίγεται (?)|ἀνοίεται (?)||reg||ἀ̣νύεται:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;choice&gt;&lt;reg cert="low"&gt;ἀνοίγεται &lt;/reg&gt;&lt;reg cert="low"&gt;ἀνοίεται &lt;/reg&gt;&lt;orig&gt;&lt;unclear&gt;ἀ&lt;/unclear&gt;νύεται&lt;/orig&gt;&lt;/choice&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Leiden+ supports not only simple regularizations but 'chains' of regularization. For example, let us say that I scribe wrote "ἀ̣νύεται", which is held to be a likely phonetic representation of ἀνοίεται, which itself perhaps ought to be regularized to ἀνοίγεται.
<br>
<br>&lt;:ἀνοίγεται (?)|ἀνοίεται (?)||reg||ἀ̣νύεται:&gt;
<br>
<br>
</div>
<hr>
</div>
</div>
<div class="category" id="Apparatus, PN/PE Correction" style="display:;">
<div class="category_display">
Apparatus, PN/PE Correction
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Apparatus, PN/PE Correction-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Apparatus, PN/PE Correction-examples" style="display:none;">
<div class="description">
PN/PE correction
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: τοῦ…App: G. Claytor (CPR VI plate 35): Om. Original ed.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:τοῦ=PN G. Claytor (CPR VI plate 35)|ed|:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;app type="editorial"&gt;&lt;lem resp="PN G. Claytor (CPR VI plate 35)"&gt;τοῦ&lt;/lem&gt;&lt;rdg/&gt;&lt;/app&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/cpr;6;82" onclick="window.open(this.href);return false;">
cpr;6;82
</a>
</div>
<hr>
<div class="note">
Indicates a correction proposed directly to DDbDP via PE. 
<br>
<br>So, the following emendation observes the omission from an edition of a word clearly visible (from the published plate) on the papyrus:
<br>
<br>&lt;:τοῦ=PN G. Claytor (CPR VI plate 35)|ed|:&gt;
<br>
<br>The corrected text is το­ῦ and the deprecated text is 'null', since this corrects an omission. Had the emendation sought to correct an existing (rather than omitted) reading, it might have looked like this:
<br>
<br>&lt;:τοῦ=PN G. Claytor (CPR VI plate 35)|ed|μου:&gt;
<br>
</div>
<hr>
</div>
</div>
<div class="category" id="Apparatus, Scribal Correction" style="display:;">
<div class="category_display">
Apparatus, Scribal Correction
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Apparatus, Scribal Correction-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Apparatus, Scribal Correction-examples" style="display:none;">
<div class="description">
Scribe correcting self
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: τοῦ…App: corr. from της
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:τοῦ|subst|της:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;subst&gt;&lt;add place="inline"&gt;τοῦ&lt;/add&gt;&lt;del rend="corrected"&gt;της&lt;/del&gt;&lt;/subst&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
To indicate scribal corrections and alterations. Note that as a general rule, the original reading does not carry diacriticals; also that this apparatus tag is used for entire words and not for the corrected characters alone.
<br>
<br>Indicating that the scribe wrote της and corrected to τοῦ: &lt;:τοῦ|subst|της:&gt;
<br>
<br>No: τ&lt;:οῦ|subst|ης:&gt;
<br>Yes: &lt;:τοῦ|subst|της:&gt;
</div>
<hr>
<div class="description">
Scribe correcting self (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: τοῦ…App: corr. from της --&gt; Text: τοῦ(?)…App: corr. from της(?)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:τοῦ(?)|subst|της(?):&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;subst&gt;&lt;add place="inline"&gt;τοῦ&lt;certainty match=".." locus="value"/&gt;&lt;/add&gt;&lt;del rend="corrected"&gt;της&lt;certainty match=".." locus="value"/&gt;&lt;/del&gt;&lt;/subst&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8922" onclick="window.open(this.href);return false;">
BGU.1.154
</a>
</div>
<hr>
<div class="note">
To indicate scribal corrections and alterations where one or both readings is uncertain. Follow the conventions for an ordinary scribal correction, but add (?) to the affected reading.
<br>
<br>&lt;:τοῦ|subst|της:&gt; --&gt; &lt;:τοῦ(?)|subst|της(?):&gt;
</div>
<hr>
</div>
</div>
<div class="category" id="Apparatus, spelling correction" style="display:;">
<div class="category_display">
Apparatus, spelling correction
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Apparatus, spelling correction-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Apparatus, spelling correction-examples" style="display:none;">
<div class="description">
Spelling correction
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: τιμὴν….App: τμμὴν pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;:τιμὴν|corr|τμμὴν:&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;choice&gt;&lt;corr&gt;τιμὴν&lt;/corr&gt;&lt;sic&gt;τμμὴν&lt;/sic&gt;&lt;/choice&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
For correction of outright scribal error, e.g. στ[ρ]α̣ττεός for στρατηγός.
<br>
<br>(1) where possible enter στρατ{τ}ηγός rather than &lt;:στρατηγός|corr|στραττηγός:&gt;
<br>(NOTE: this does not apply to e.g. ὁμολογῶι, which is to be encoded as an orthographic regularization: &lt;:ὁμολογῶ|reg|ὁμολογῶι:&gt;)
<br>(2) where possible enter στρα&lt;τ&gt;ηγός rather than &lt;:στρατηγός|corr|στραηγός:&gt;
<br>(3) in the case of στ[ρ]α̣ττεός for στρατηγός
<br>(3a) enter &lt;:(στ[ρ]ατ{τ}η&lt;γ&gt;(ός))|corr|(στ[ρ]α̣ττε(ός)):&gt; (Note: all Leiden except for underdots on left side of 'corr'
<br>(3b) PN displays: text: στ[ρ]α̣ττε(ός) / app: l. στρατηγός (corr)
</div>
<hr>
</div>
</div>
<div class="category" id="Diacriticals" style="display:;">
<div class="category_display">
Diacriticals
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Diacriticals-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Diacriticals-examples" style="display:none;">
<div class="description">
Diaeresis
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: υ ἱ(¨)οῦ…App:16. υϊου pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
υ ἱ(¨)οῦ
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
υ&lt;hi rend="diaeresis"&gt;ἱ&lt;/hi&gt;οῦ
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10223" onclick="window.open(this.href);return false;">
P.Berl.Leihg.2.35
</a>
</div>
<hr>
<div class="note">
Diaeresis written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed. Example: υ ἱ(¨)οῦ
</div>
<hr>
<div class="description">
Asper
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ὧ ... App: ὡ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 ὧ( ῾)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="asper"&gt;ὧ&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/31807" onclick="window.open(this.href);return false;">
P.Oxy.14.1765
</a>
</div>
<hr>
<div class="note">
Asper written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Acute
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ὃ ... App.: ό pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 ὃ(´)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="acute"&gt;ὃ&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/37860" onclick="window.open(this.href);return false;">
P.Oxy.16.1854
</a>
</div>
<hr>
<div class="note">
Acute written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Circumflex
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ὑ ... App: ῦ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 ὑ(^)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="circumflex"&gt;ὑ&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/20769" onclick="window.open(this.href);return false;">
P.Oxy.1.125
</a>
</div>
<hr>
<div class="note">
Circumflex written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Lenis
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ἄ ... App.: ἀ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 Ἀ( ᾿)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="lenis"&gt;Ἀ&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/9313" onclick="window.open(this.href);return false;">
BGU.3.715
</a>
</div>
<hr>
<div class="note">
Lenis written by scribe. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Double diacritical
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: ἵ ... App.: ἱ pap. ί pap. --&gt; Text: ἵ ... App.: ἵ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 ἵ( ῾´)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="asper"&gt;&lt;hi rend="acute"&gt;ἵ&lt;/hi&gt;&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/32762" onclick="window.open(this.href);return false;">
P.Ryl.4.624
</a>
</div>
<hr>
<div class="note">
Multiple ancient diacriticals. For double diacriticals simply combine the ordinary symbols inside a single pair pf parens.
</div>
<hr>
<div class="description">
Diacritical over illegible character
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text:   ̣ ... App.:     ¨ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 .1(¨)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="diaeresis"&gt;&lt;gap reason="illegible" quantity="1" unit="character"/&gt;&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/16028" onclick="window.open(this.href);return false;">
CPR.5.6
</a>
</div>
<hr>
<div class="note">
Ancient diacritical written atop illegible character. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
<div class="description">
Diacritical over lost character
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: [  ̣] ... App.:      ´ pap.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
 [.1](´)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="acute"&gt;&lt;gap reason="lost" quantity="1" unit="character"/&gt;&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/26685" onclick="window.open(this.href);return false;">
P.Wisc.2.70
</a>
</div>
<hr>
<div class="note">
Ancient diacritical written atop character that is now lost in lacuna. Note: the letter containing the ancient diacritical must be preceded at left by an extra space, even if the letter is midword; this space will not be displayed.
</div>
<hr>
</div>
</div>
<div class="category" id="Document Division" style="display:;">
<div class="category_display">
Document Division
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Document Division-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Document Division-examples" style="display:none;">
<div class="description">
Document Div, ab
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
PN does not indicate explicitly
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;= =&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;ab&gt; &lt;/ab&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Every block of text must be enclosed in a &lt;= ... =&gt; pair.
</div>
<hr>
<div class="description">
Document Div, recto/verso
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
recto/verso
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.r&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.v&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="r" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="v" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Recto and verso are indicated with closed pairs of tags as follows:
<br>
<br>&lt;D=.r&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.v&lt;=
<br>3. line of text
<br>4. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that the pair of tags inside the recto/verso tags and directly adjacent to the text is the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Document Div, fragment
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
fragment 1/fragment 2
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.1.fragment&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.2.fragment&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="1" subtype="fragment" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="2" subtype="fragment" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Fragments are indicated with closed pairs of tags as follows:
<br>
<br>&lt;D=.1.fragment&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.2.fragment&lt;=
<br>3. line of text
<br>4. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that the pair of tags inside the fragment tags and directly adjacent to the text is the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Document Div, part
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
part A/part B
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.A.part&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.B.part&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="A" subtype="part" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="B" subtype="part" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Parts of a document are indicated with closed pairs of tags as follows:
<br>
<br>&lt;D=.A.part&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.B.part&lt;=
<br>3. line of text
<br>4. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that the pair of tags inside the part tags and directly adjacent to the text is the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Document Div, column
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
column i / column ii
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.i.column&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.ii.column&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="i" subtype="column" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="ii" subtype="column" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Columns are indicated with closed pairs of tags as follows:
<br>
<br>&lt;D=.i.column&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.ii.column&lt;=
<br>3. line of text
<br>4. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that the pair of tags inside the column tags and directly adjacent to the text is the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Document Div, folio
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
folio a / folio b
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.a.folio&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.b.folio&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="a" subtype="folio" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="b" subtype="folio" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Folios are indicated with closed pairs of tags as follows:
<br>
<br>&lt;D=.a.folio&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.b.folio&lt;=
<br>3. line of text
<br>4. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that the pair of tags inside the folio tags and directly adjacent to the text is the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
<div class="description">
Document Div, nested
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Divisions indicated variously
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;D=.a.folio&lt;= 1. line of text 2. line of text =&gt;=D&gt; &lt;D=.b.folio&lt;= 3. line of text 4. line of text =&gt;=D&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div n="a" subtype="folio" type="textpart"&gt;&lt;ab&gt; &lt;lb n="1"/&gt;line of text &lt;lb n="2"/&gt;line of text &lt;/ab&gt;&lt;/div&gt; &lt;div n="b" subtype="folio" type="textpart"&gt;&lt;ab&gt; &lt;lb n="3"/&gt;line of text &lt;lb n="4"/&gt;line of text &lt;/ab&gt;&lt;/div&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Document divisions can be nested so long as tag pairs no not overlap:
<br>
<br>&lt;D=.r
<br>&lt;D=.i.column&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.ii.column
<br>&lt;D=.a.fragment&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>&lt;D=.b.fragment&lt;=
<br>1. line of text
<br>2. line of text
<br>=&gt;=D&gt;
<br>=D&gt;
<br>=D&gt;
<br>&lt;D=.v&lt;=
<br>1. line of text
<br>=&gt;=D&gt;
<br>
<br>Note that no matter how nested the divisions are, the pair of tags directly adjacent to the text is always the &lt;= =&gt; pair (see Document Division, ab)
</div>
<hr>
</div>
</div>
<div class="category" id="Editorial note" style="display:;">
<div class="category_display">
Editorial note
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Editorial note-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Editorial note-examples" style="display:none;">
<div class="description">
Note
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(BGU 1,108,r reprinted in WChr 227 )
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
/*BGU 1,108,r reprinted in WChr 227 */
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;note xml:lang="en"&gt;BGU 1,108,r reprinted in WChr 227 &lt;/note&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;108" onclick="window.open(this.href);return false;">
BGU.1.108
</a>
</div>
<hr>
<div class="note">
To indicate modern editorial comment, for example that the recto of a given text has been republished elsewhere, or that a missing string should be a month name. Use sparingly.
</div>
<hr>
</div>
</div>
<div class="category" id="Handshift" style="display:;">
<div class="category_display">
Handshift
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Handshift-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Handshift-examples" style="display:none;">
<div class="description">
Handshift
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(hand 4)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
$m4 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;handShift new="m4"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10223" onclick="window.open(this.href);return false;">
P.Berl.Leihg.2.35
</a>
</div>
<hr>
<div class="note">
Handshift. Note: where there are multiple hands, you do not need to indicate the first.
</div>
<hr>
<div class="description">
Handshift (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(hand 3?)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
$m3(?) 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;handShift new="m3" cert="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/44635" onclick="window.open(this.href);return false;">
P.Polit.Iud.19
</a>
</div>
<hr>
<div class="note">
Uncertain handshift.
</div>
<hr>
</div>
</div>
<div class="category" id="Illegible" style="display:;">
<div class="category_display">
Illegible
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Illegible-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Illegible-examples" style="display:none;">
<div class="description">
gap illegible character
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
 ̣  ̣  ̣
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.3
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="3" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/o.berenike;1;6" onclick="window.open(this.href);return false;">
O.Berenike.1.6
</a>
</div>
<hr>
<div class="note">
To indicate a known number of illegible characters.
</div>
<hr>
<div class="description">
Approximate number of illegible characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
- ca.23 - 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ca.23
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="23" unit="character" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/26917" onclick="window.open(this.href);return false;">
P.Wisc.1.1
</a>
</div>
<hr>
<div class="note">
To indicate an estimated number of illegible characters.
</div>
<hr>
<div class="description">
Known number of illegible characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
- ca.43 -
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.43
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="43" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/23699" onclick="window.open(this.href);return false;">
SB.20.14241
</a>
</div>
<hr>
<div class="note">
To indicate a known number of illegible characters. Note: all strings of illegible characters greater than 8 are rendered as approximations. So, ".43" will be encoded as a piece of editorial certainty (&lt;gap reason="illegible" quantity="43" unit="character"/&gt;), but will nevertheless be displayed as an approximation: "- ca.43 -"
</div>
<hr>
<div class="description">
Range of illegible characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
- ca. 9-10 -
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.9-10
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" atLeast="9" atMost="10" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/74479" onclick="window.open(this.href);return false;">
P.Eleph.Wagner.1.288
</a>
</div>
<hr>
<div class="note">
To indicate a known range of illegible characters.
</div>
<hr>
<div class="description">
Known number of illegible lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces 5 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.5lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="5" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8291" onclick="window.open(this.href);return false;">
P.Hib.2.253
</a>
</div>
<hr>
<div class="note">
To indicate a known number of illegible lines (e.g. vestiges)
</div>
<hr>
<div class="description">
Approximate number of illegible lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces ca.20 lines 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ca.20lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="20" unit="line" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/25460" onclick="window.open(this.href);return false;">
SB.24.15920
</a>
</div>
<hr>
<div class="note">
To indicate an estimated number of illegible lines (e.g. vestiges).
</div>
<hr>
<div class="description">
Range of illegible lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces 2-3 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.2-3lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" atLeast="2" atMost="3" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/38499" onclick="window.open(this.href);return false;">
SB.20.14571
</a>
</div>
<hr>
<div class="note">
To indicate a range of illegible lines.
</div>
<hr>
<div class="description">
gap illegible character unknown
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
- ca. ? -
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
.?
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" extent="unknown" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10193" onclick="window.open(this.href);return false;">
P.Berl.Leihg.1.13
</a>
</div>
<hr>
<div class="note">
To indicate an unknown number of illegible characters.
</div>
<hr>
</div>
</div>
<div class="category" id="Inserted / added text" style="display:;">
<div class="category_display">
Inserted / added text
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Inserted / added text-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Inserted / added text-examples" style="display:none;">
<div class="description">
Text inserted / added above line
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
\ὅλων/
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
\ὅλων/
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add place="above"&gt;ὅλων&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18216" onclick="window.open(this.href);return false;">
P.Matr.2
</a>
</div>
<hr>
<div class="note">
To indicate text inserted or added above a line, as 'afterthought' or self-correction (for conventional drop-ins: \καὶ/ )
</div>
<hr>
<div class="description">
Text inserted / added below line
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
/δ\
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
//&lt;#δ=4#&gt;\\
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add place="below"&gt;&lt;num value="4"&gt;δ&lt;/num&gt;&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
To indicate text inserted or added below a line, as 'afterthought' or self-correction (see print conventional: /καὶ\ )
</div>
<hr>
<div class="description">
Text inserted / added to the left margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(added at left: αβγ)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
||left:καὶ||
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add place="left"&gt;καὶ&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/128690" onclick="window.open(this.href);return false;">
p.jena;2;10
</a>
</div>
<hr>
<div class="note">
To indicate text inserted / added to the left of a line
</div>
<hr>
<div class="description">
Text inserted / added to the right margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(added at right: αβγ)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
||right:καὶ||
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add place="right"&gt;καὶ&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
To indicate text inserted / added to the right of a line
</div>
<hr>
<div class="description">
Text added between lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ὧν (in smaller font)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&gt;) ὧ( ῾)ν(&lt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add place="interlinear"&gt;&lt;hi rend="asper"&gt;ὧ&lt;/hi&gt;ν&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/32564" onclick="window.open(this.href);return false;">
P.Panop.14
</a>
</div>
<hr>
<div class="note">
To indicate text added between two lines
</div>
<hr>
</div>
</div>
<div class="category" id="Language" style="display:;">
<div class="category_display">
Language
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Language-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Language-examples" style="display:none;">
<div class="description">
Non default language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
γενήσεται
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
~|γενήσεται|~grc 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;foreign xml:lang="grc"&gt;γενήσεται&lt;/foreign&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/23792" onclick="window.open(this.href);return false;">
SB.20.14688
</a>
</div>
<hr>
<div class="note">
Indicate text strings written in a language/script other than the document's default as follows:
<br>
<br>Greek = ~|γενήσεται|~grc 
<br>Latin = ~|comes|~la 
<br>Ancient Greek in Latin script = ~|di emu|~grc-Latn 
<br>Latin in Greek script = ~|σουσκριβερεντ|~la-Grek
<br>
<br>NOTE: You must enter a space after the language designator; so, not "~la", but "~la ".
</div>
<hr>
<div class="description">
Non default language: Latin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
comes
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
~|comes|~la 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;foreign xml:lang="la"&gt;comes&lt;/foreign&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
If the default language of a text is Greek, mark strings of Latin as follows: ~|comes|~la
</div>
<hr>
</div>
</div>
<div class="category" id="Leiden Angle Brackets &lt;  &gt;" style="display:;">
<div class="category_display">
Leiden Angle Brackets &lt;  &gt;
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Leiden Angle Brackets &lt;  &gt;-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Leiden Angle Brackets &lt;  &gt;-examples" style="display:none;">
<div class="description">
Supplied omitted
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
&lt;ἀπεγραψάμην&gt;
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;ἀπεγραψάμην&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;supplied reason="omitted"&gt;ἀπεγραψάμην&lt;/supplied&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8891" onclick="window.open(this.href);return false;">
BGU.1.117
</a>
</div>
<hr>
<div class="note">
Text omitted by scribe, inserted by modern editor. To indicate such added text, enclose it in angle brackets: e.g. &lt;ἀπεγραψάμην&gt;, ἀπ&lt;ε&gt;γραψάμην, etc.
</div>
<hr>
<div class="description">
Supplied omitted (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
&lt;οὐκ(?)&gt;
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;οὐκ(?)&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;supplied reason="omitted" cert="low"&gt;οὐκ&lt;/supplied&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/32313" onclick="window.open(this.href);return false;">
P.Oxy.50.3581
</a>
</div>
<hr>
<div class="note">
To indicate text omitted by scribe and uncertainly inserted by modern editor.
</div>
<hr>
<div class="description">
Supplied omitted
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ἀπ&lt;ε&gt;γραψάμην
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ἀπ&lt;ε&gt;γραψάμην
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
ἀπ&lt;supplied reason="omitted"&gt;ε&lt;/supplied&gt;γραψάμην
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
Note: for cases like ἀπ&lt;ε&gt;γραψάμην the DDbDP has historically entered an orthographic correction of the entire word, i.e. &lt;:ἀπεγραψάμην|orth|απγραψαμην:&gt;. Recommended practice now is to enter just the angle brackets wherever possible: ἀπ&lt;ε&gt;γραψάμην.
<br>
<br>For more on this, see the documentation entry under Orthographic Correction.
</div>
<hr>
</div>
</div>
<div class="category" id="Leiden Braces {  }" style="display:;">
<div class="category_display">
Leiden Braces {  }
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Leiden Braces {  }-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Leiden Braces {  }-examples" style="display:none;">
<div class="description">
Surplus text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
{ὀνόματος}
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
{ὀνόματος}
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;surplus&gt;ὀνόματος&lt;/surplus&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/15402" onclick="window.open(this.href);return false;">
P.Oxy.50.3583
</a>
</div>
<hr>
<div class="note">
Surplus text written by scribe, deleted by modern editor. To indicate such text enclose it in braces: e.g. {ὀνόματος}, ὀνό{μ}ματος.
</div>
<hr>
<div class="description">
Surplus text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ὁμο{μο}λογῶ.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ὁμο{μο}λογῶ.
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
ὁμο&lt;surplus&gt;μο&lt;/surplus&gt;λογῶ.
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Surplus text written by scribe, deleted by modern editor.
<br>
<br>For cases like ὁμολογῶι enter an orthographic regularization of the entire word, i.e. &lt;:ὁμολογῶ|reg|ὁμολογῶι:&gt;. But where the letter(s) is genuinely superfluous, use braces: ὁμο{μο}λογῶ.
</div>
<hr>
</div>
</div>
<div class="category" id="Leiden Double Sq Brackets 〚 〛" style="display:;">
<div class="category_display">
Leiden Double Sq Brackets 〚 〛
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Leiden Double Sq Brackets 〚 〛-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Leiden Double Sq Brackets 〚 〛-examples" style="display:none;">
<div class="description">
Deletion
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
〚τοῖς κορασίοις〛
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
〚τοῖς κορασίοις〛
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;del rend="erasure"&gt;τοῖς κορασίοις&lt;/del&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/20193" onclick="window.open(this.href);return false;">
BGU.1.34
</a>
</div>
<hr>
<div class="note">
Text deleted in antiquity. Note: this convention has been used to cover many modes of deletion (cancellation by slashes, expunction, strike-through, bracket-like marks on the papyrus, etc). Appearance of 〚...〛 does not imply one mode or another.
</div>
<hr>
<div class="description">
Deletion with slashes
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: τραπέζης Φρέμει...App: 5. Text canceled with slashes
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
〚/ τραπέζης Φρέμει. 〛
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;del rend="slashes"&gt; τραπέζης Φρέμει. &lt;/del&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/cpr;1;15" onclick="window.open(this.href);return false;">
cpr;1;15
</a>
</div>
<hr>
<div class="note">
Text deleted with slashes in antiquity: 〚/ τραπέζης Φρέμει.〛
</div>
<hr>
<div class="description">
Deletion with cross-strokes
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: (hand 4) -ca.?-….App: v.1. Text canceled with cross-strokes
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
〚X $m4  lost.?lin 〛
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;del rend="cross-strokes"&gt; &lt;handShift new="m4"/&gt; &lt;gap reason="lost" extent="unknown" unit="line"/&gt; &lt;/del&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/p.lips;1;98" onclick="window.open(this.href);return false;">
p.lips;1;98
</a>
</div>
<hr>
<div class="note">
Text deleted with cross-strokes in antiquity: 〚X $m4 lost.?lin〛
</div>
<hr>
</div>
</div>
<div class="category" id="Leiden Parentheses (  )" style="display:;">
<div class="category_display">
Leiden Parentheses (  )
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Leiden Parentheses (  )-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Leiden Parentheses (  )-examples" style="display:none;">
<div class="description">
abbreviation, στρατηγ( )
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ομυο(&nbsp;)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(|ομυο|)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;abbr&gt;ομυο&lt;/abbr&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8884" onclick="window.open(this.href);return false;">
BGU.1.110
</a>
</div>
<hr>
<div class="note">
Ancient abbreviations. Note: Leiden+ treats resolved and unresolved abbreviations differently: so,<br><br>enter (στρατηγ(ός)) for στρατηγ(ός)<br><br>but<br><br>enter (|στρατηγ|) for στρατηγ( ) 
</div>
<hr>
<div class="description">
abbreviation with markup σ[τρ]α̣τ̣ηγ(  )
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣&nbsp;&nbsp;̣]χυρι̣ο(&nbsp;)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(|[.8]χυρι̣ο|)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;abbr&gt;&lt;gap reason="lost" quantity="8" unit="character"/&gt;χυρ&lt;unclear&gt;ι&lt;/unclear&gt;ο&lt;/abbr&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8884" onclick="window.open(this.href);return false;">
BGU.1.110
</a>
</div>
<hr>
<div class="note">
For unresolved abbreviations· (|σ[τρ]α̣τ̣ηγ|) = σ[τρ]α̣τ̣ηγ(  )
</div>
<hr>
<div class="description">
abbreviation, λ(  )(?) 
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
λ(  )(?) 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(|λ(?)|)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;abbr&gt;λ&lt;certainty locus="name" match=".."/&gt;&lt;/abbr&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/33700" onclick="window.open(this.href);return false;">
P.Lips.1.40
</a>
</div>
<hr>
<div class="note">
Ancient abbreviations. Where the expansion is unknown and it is not even certain whether the character(s) on the papyrus is meant to be an expansion or not, enter:
<br>
<br>(|λ(?)|)
<br>
<br>This could indicate λ (i.e. 30) or, e.g. λ(όγος); but we cannot say for ceertain.
</div>
<hr>
<div class="description">
expan on part of word στρατηγ(ός)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Καρ(ανίδι)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Καρ(ανίδι))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;Καρ&lt;ex&gt;ανίδι&lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8922" onclick="window.open(this.href);return false;">
BGU.1.154
</a>
</div>
<hr>
<div class="note">
Ancient abbreviations. Note: Leiden+ handles στρατηγ( ) and στρατηγ(ός) differently. Where the abbreviation is expanded -- as in the case of στρατηγ(ός) -- enter as follows: (στρατηγ(ός)). For the other case, see elsewhere under Leiden Parentheses (  ).
</div>
<hr>
<div class="description">
uncertain expansion of part of a word Καρ(ανίδι(?))
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Καρ(ανίδι(?))
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Καρ(ανίδι?))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;Καρ&lt;ex cert="low"&gt;ανίδι&lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
Ancient abbreviations. For uncertain expansions, add "?" inside the expanded part of the word (στρατηγ(ός)) --&gt; (στρατηγ(ός?)).
</div>
<hr>
<div class="description">
partial expansion of part of a word Καρ(ανίδ  )
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Καρ(ανίδ  ) --&gt; Καρ(ανίδ-)???
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Καρ(ανίδ  ))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;Καρ&lt;ex&gt;ανίδ  &lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
Ancient abbreviations. Where a word is only partially expanded (for example because the termination is unknown), enter as follows:
<br>
<br>Καρ(ανίδ  )
<br>
<br>Note: leave two spaces between the last character and the closing parens.
</div>
<hr>
<div class="description">
expansion of whole word (ἔτους)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
((ἔτους))
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
((ἔτους))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;&lt;ex&gt;ἔτους&lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
For symbols that are fully expanded enter as follows: ((ἔτους)).
</div>
<hr>
<div class="description">
expansion of whole word (ἔ̣τ̣ο̣υ̣ς̣) / (ἔτους?)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(ἔτους(?))
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
((ἔτους?))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;&lt;ex cert="low"&gt;ἔτους&lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
For symbols that are fully expanded, but uncertainly read enter as follows: ((ἔτους?)). This is often represented in print by (ἔ̣τ̣ο̣υ̣ς̣) / (ἔτους?).
</div>
<hr>
<div class="description">
partial expansion of whole word (δραχμ  )
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
(ἔτ  ) --&gt; (ἔτ-)???
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
((ἔτ  ))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;expan&gt;&lt;ex&gt;ἔτ  &lt;/ex&gt;&lt;/expan&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8922" onclick="window.open(this.href);return false;">
BGU.1.154
</a>
</div>
<hr>
<div class="note">
For symbols that are partially expanded enter as follows (for example because the termination is unknown):
<br>
<br>((ἔτ  ))
<br>
<br>Note: leave two spaces between the last character and the closing parens. 
</div>
<hr>
</div>
</div>
<div class="category" id="Leiden Square Brackets [  ]" style="display:;">
<div class="category_display">
Leiden Square Brackets [  ]
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Leiden Square Brackets [  ]-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Leiden Square Brackets [  ]-examples" style="display:none;">
<div class="description">
lost character gap quantity precision low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[ -ca.5- ]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[ca.5]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" quantity="5" unit="character" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/34423" onclick="window.open(this.href);return false;">
O.Douch.2.88
</a>
</div>
<hr>
<div class="note">
To indicate an approximate number of lost characters inside lacuna, enter [ca.5], where '5' is the number of lost characters.
</div>
<hr>
<div class="description">
lost character gap quantity
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[  ̣  ̣  ̣  ̣  ̣  ̣  ̣  ̣ ] / [ -ca.43- ] 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[.8] or [.43]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" quantity="8" unit="character"/&gt; or &lt;gap reason="lost" quantity="43" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8884" onclick="window.open(this.href);return false;">
BGU.1.110
</a>
</div>
<hr>
<div class="note">
Known number of characters lost in lacuna. Note: all strings of lost characters greater than 8 are rendered as approximations. So, "[.43]" will be encoded as a piece of editorial certainty, but will nevertheless be displayed as an approximation: "[ - ca.43 - ]"
</div>
<hr>
<div class="description">
lost character gap range
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[ -ca.11-15- ]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[.11-15]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" atLeast="11" atMost="15" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/63672" onclick="window.open(this.href);return false;">
P.Oxy.46.3285
</a>
</div>
<hr>
<div class="note">
Known range of characters lost in lacuna.
</div>
<hr>
<div class="description">
lost character gap unknown quantity
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[ - ca. ? - ]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[.?]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" extent="unknown" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/o.berenike;1;6" onclick="window.open(this.href);return false;">
O.Berenike.1.6
</a>
</div>
<hr>
<div class="note">
Unknown number of characters lost in lacuna.
</div>
<hr>
<div class="description">
supplied lost words
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[ὁμο]λογῶ
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[ὁμο]λογῶ
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;supplied reason="lost"&gt;ὁμο&lt;/supplied&gt;λογῶ
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18216" onclick="window.open(this.href);return false;">
P.Matr.2
</a>
</div>
<hr>
<div class="note">
Letters lost in lacuna, restored by modern editor.
</div>
<hr>
<div class="description">
supplied lost cert low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ἡμετέρ[α μήτηρ (?) - ca. ? - ]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ἡμετέρ[α μήτηρ (?)] [.?]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
ἡμετέρ&lt;supplied reason="lost" cert="low"&gt;α μήτηρ &lt;/supplied&gt; &lt;gap reason="lost" extent="unknown" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18218" onclick="window.open(this.href);return false;">
P.Matr.5
</a>
</div>
<hr>
<div class="note">
Letters lost in lacuna, restored by modern editor; restoration uncertain
<br>
<br>Example: ἡμετέρ[α μήτηρ (?) -ca.?- ]
<br>
<br>Note that the restoration of μήτηρ is uncertain, but the lacuna after it is not. Thus, encode as follows: 
<br>
<br>ἡμετέρ[α μήτηρ (?)] [.?]
<br>
<br>in order to indicate that the one restoration is uncertain and the other certain. For even greater precision, we might enter:
<br>
<br>ἡμετέρ[α] [μήτηρ (?)] [.?]
<br>
<br>
</div>
<hr>
</div>
</div>
<div class="category" id="Leiden Underline ___" style="display:;">
<div class="category_display">
Leiden Underline ___
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Leiden Underline ___-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Leiden Underline ___-examples" style="display:none;">
<div class="description">
supplied parallel
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Πόσεις
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
|_Πόσεις_|
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;supplied evidence="parallel" reason="undefined"&gt;Πόσεις&lt;/supplied&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/p.berl.leihg;2;39" onclick="window.open(this.href);return false;">
P.Berl.Leihg.2.39
</a>
</div>
<hr>
<div class="note">
Text supplied from parallel text, other copy, or transcription of previously visible text that is now lost or illegible.
</div>
<hr>
</div>
</div>
<div class="category" id="Line Number" style="display:;">
<div class="category_display">
Line Number
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Line Number-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Line Number-examples" style="display:none;">
<div class="description">
Line rendered perpendicular to the main body of text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; 2. (perpendicular)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(2, perpendicular)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="2" rend="perpendicular"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/31065" onclick="window.open(this.href);return false;">
P.Berl.Bibl.12
</a>
</div>
<hr>
<div class="note">
Numbered line written perpendicular to main text.
</div>
<hr>
<div class="description">
line rendered inverse to the main body of text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; 8. (inverse)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(8, inverse)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="8" rend="inverse"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/35611" onclick="window.open(this.href);return false;">
P.Oxy.16.1951
</a>
</div>
<hr>
<div class="note">
Numbered line written inverse to main text.
</div>
<hr>
<div class="description">
line rendered perpendicular to the main body of text in left margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
8,ms --&gt; 8,ms (perpendicular)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(8,ms, perpendicular)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="8,ms" rend="perpendicular"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/37268" onclick="window.open(this.href);return false;">
P.Harr.1.161
</a>
</div>
<hr>
<div class="note">
Numbered line written in left margin and perpendicular to main text.
</div>
<hr>
<div class="description">
line rendered inverse to the main body of text in lower margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
16,minf --&gt; 16,minf (inverse) NOTE: getting cut off at left
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(16,minf, inverse)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="16,minf" rend="inverse"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/1462" onclick="window.open(this.href);return false;">
P.Cair.Zen.5.59838
</a>
</div>
<hr>
<div class="note">
Numbered line written in lower margin and inverse to main text.
</div>
<hr>
<div class="description">
Line written in left margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
3,ms
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
3,ms. 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="3,ms"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8223" onclick="window.open(this.href);return false;">
P.Hib.1.74
</a>
</div>
<hr>
<div class="note">
Numbered line written in left margin.
</div>
<hr>
<div class="description">
line 5 to 6
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
5/6
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
5/6. 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="5/6"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/28409" onclick="window.open(this.href);return false;">
P.Oxy.1.117
</a>
</div>
<hr>
<div class="note">
For use in rare cases in which lines are presented so as not to indicate break; not recommended.
</div>
<hr>
<div class="description">
line break
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
1. 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
1. 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="1"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/28409" onclick="window.open(this.href);return false;">
P.Oxy.1.117
</a>
</div>
<hr>
<div class="note">
To indicate line number. Every line must have a line number.
</div>
<hr>
<div class="description">
Words that wrap across lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
5
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
5.- 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="5" type="inWord"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10559" onclick="window.open(this.href);return false;">
p.col.;10;259
</a>
</div>
<hr>
<div class="note">
Words that wrap from the end of one line to the beginning of the next. Note that in Leiden+ the hyphen must be written at the start of the following line:
<br>
<br> 12. ἃς καὶ &lt;:ἀποδώσει|orth|αποδωσι:&gt; ἐν μηνὶ Πα
<br> 13.- ῦ̣[νι τοῦ] ἐνεσ[τ]ῶτος ἔτους
<br>
<br>In the PN the hyphen will be displayed in the expected location:
<br>
<br>  ἃς καὶ ἀποδώσει ἐν μηνὶ Πα-
<br>  ῦ̣[νι τοῦ] ἐνεσ[τ]ῶτος ἔτους
<br>
</div>
<hr>
<div class="description">
Line with word-wrap written inverse to main text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; 3. (inverse) with hyphen at end of preceding line
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(3.-, inverse)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;lb n="3" rend="inverse" type="inWord"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/sb;24;16170" onclick="window.open(this.href);return false;">
SB.24.16170
</a>
</div>
<hr>
<div class="note">
For lines written inverse / perpendicular to main text and containing a word-wrap, simply add hyphen to the regular convention.
</div>
<hr>
</div>
</div>
<div class="category" id="Lines lost" style="display:;">
<div class="category_display">
Lines lost
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Lines lost-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Lines lost-examples" style="display:none;">
<div class="description">
Known number of lines missing
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[7 lines missing]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
lost.7lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" quantity="7" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/20672" onclick="window.open(this.href);return false;">
P.Oxy.3.617
</a>
</div>
<hr>
<div class="note">
To indicate a known number of lost lines.
</div>
<hr>
<div class="description">
Approximate number of lines lost
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[ca 7 lines missing]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
lost.ca.7lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" quantity="7" unit="line" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/74537" onclick="window.open(this.href);return false;">
O.Kell.13
</a>
</div>
<hr>
<div class="note">
To indicate approximate number of lines lost.
</div>
<hr>
<div class="description">
Approximate range of lines lost
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[3-4 lines missing]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
lost.3-4lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" atLeast="3" atMost="4" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/3231" onclick="window.open(this.href);return false;">
P.Lille.1.29
</a>
</div>
<hr>
<div class="note">
To indicate approximate range of lines lost.
</div>
<hr>
<div class="description">
Unknown number of lines lost
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
-- -- -- -- -- -- -- -- -- --
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
lost.?lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="lost" extent="unknown" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
To indicate unknown number of lines lost. This is used to indicate "break" in the papyrus. Enter as follows:
<br>
<br>1. lost.?lin
<br>1. first line of text
<br>2. second line of text
<br>3. third line of text
<br>3. lost.?lin
</div>
<hr>
</div>
</div>
<div class="category" id="number" style="display:;">
<div class="category_display">
number
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;number-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="number-examples" style="display:none;">
<div class="description">
num with symbol &amp; value with markup
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ι[ε(?)] = SoSOL,  α[ε][̣]̣ = PN
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#ι[ε(?)]=15#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="15"&gt;ι&lt;supplied reason="lost" cert="low"&gt;ε&lt;/supplied&gt;&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10217" onclick="window.open(this.href);return false;">
P.Berl.Leihg.1.8
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
</div>
</div>
<div class="category" id="Numbers" style="display:;">
<div class="category_display">
Numbers
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Numbers-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Numbers-examples" style="display:none;">
<div class="description">
Number whole
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ιϛ
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#ιϛ=16#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="16"&gt;ιϛ&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10217" onclick="window.open(this.href);return false;">
P.Berl.Leihg.1.8
</a>
</div>
<hr>
<div class="note">
Numbers should be accompanied by their values.
</div>
<hr>
<div class="description">
Number fraction
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ιϛ
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#ιϛ=1/16#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="1/16"&gt;ιϛ&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
Fractions should be accompanied by their values, just as whole numbers.
</div>
<hr>
<div class="description">
Number with '
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
λβ´
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#λβ '=1/32#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="1/32" rend="tick"&gt;λβ&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18215" onclick="window.open(this.href);return false;">
P.Matr.1
</a>
</div>
<hr>
<div class="note">
To indicate the presence of a tick on the papyrus. This works for both fractions and whole numbers. In the PN a mouseover pop-up will alert you as to whether a number is whole or fraction. Note: the tick must be the standard ascii ('), not a Smart Quote, and not a Greek Unicode apostrophe (just as the system requires &lt;...&gt; and does not permit Greek Unicode ⟨...⟩)
<br>
<br>For example:
<br>&lt;γ '=3&gt;
<br>&lt;γ '=1/3&gt;
</div>
<hr>
<div class="description">
Uncertainly read number
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
σ̣ν̣ϛ̣´
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#σ̣ν̣ϛ̣ '=1/256#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="1/256" rend="tick"&gt;&lt;unclear&gt;σνϛ&lt;/unclear&gt;&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/72534" onclick="window.open(this.href);return false;">
O.Bodl.2
</a>
</div>
<hr>
<div class="note">
Underdot numbers as you would any other uncertainly read character.
</div>
<hr>
<div class="description">
Illegible numbers
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
&nbsp;&nbsp;̣&nbsp;&nbsp;̣
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#.2=#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num&gt;&lt;gap reason="illegible" quantity="2" unit="character"/&gt;&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/32161" onclick="window.open(this.href);return false;">
P.Oxy.64.4435
</a>
</div>
<hr>
<div class="note">
To indicate presence of an illegible number
</div>
<hr>
<div class="description">
Missing numbers
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[&nbsp;&nbsp;̣&nbsp;&nbsp;̣ ]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#[.2]=#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num&gt;&lt;gap reason="lost" quantity="2" unit="character"/&gt;&lt;/num&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/bgu;1;154" onclick="window.open(this.href);return false;">
bgu;1;154
</a>
</div>
<hr>
<div class="note">
To indicate a lost number, simply enter a lacuna where you would normally enter the Greek number and leave the value blank.
</div>
<hr>
<div class="description">
num no symbol
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
nothing 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#=4#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="4"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18216" onclick="window.open(this.href);return false;">
P.Matr.2
</a>
</div>
<hr>
<div class="note">
Numbers that are spelled out in Latin and Greek are followed by 'empty' number tags.
</div>
<hr>
<div class="description">
num fraction no symbol
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
nothing 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;#=1/8#&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;num value="1/8"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18216" onclick="window.open(this.href);return false;">
P.Matr.2
</a>
</div>
<hr>
<div class="note">
Numbers that are spelled out in Latin and Greek are followed by 'empty' number tags.
</div>
<hr>
</div>
</div>
<div class="category" id="Omitted" style="display:;">
<div class="category_display">
Omitted
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Omitted-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Omitted-examples" style="display:none;">
<div class="description">
Omitted language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Demotic 1 line
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lang: Demotic 1 lines)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="1" unit="line"&gt;&lt;desc&gt;Demotic&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/4593" onclick="window.open(this.href);return false;">
P.Hib.1.142
</a>
</div>
<hr>
<div class="note">
Lines of Demotic omitted from DDbDP or edition. 
</div>
<hr>
<div class="description">
Omitted language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Coptic ? lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lang: Coptic ? lines)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" extent="unknown" unit="line"&gt;&lt;desc&gt;Coptic&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/15004" onclick="window.open(this.href);return false;">
Stud.Pal.10.172
</a>
</div>
<hr>
<div class="note">
Lines of Coptic omitted from DDbDP or edition.
</div>
<hr>
<div class="description">
Omitted language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Demotic ? lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lang: Demotic ? lines)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" extent="unknown" unit="line"&gt;&lt;desc&gt;Demotic&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/54520" onclick="window.open(this.href);return false;">
T.Mom.Louvre.30
</a>
</div>
<hr>
<div class="note">
Unknown number of lines of Demotic omitted from DDbDP or edition.
</div>
<hr>
<div class="description">
Omitted language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Demotic 2 characters
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lang: Demotic 2 char)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="2" unit="character"&gt;&lt;desc&gt;Demotic&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/50773" onclick="window.open(this.href);return false;">
O.Wilck.457
</a>
</div>
<hr>
<div class="note">
Demotic characters omitted from DDbDP or edition.
</div>
<hr>
<div class="description">
Omitted language
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Demotic ? characters
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lang: Demotic ? char)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" extent="unknown" unit="character"&gt;&lt;desc&gt;Demotic&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/43479" onclick="window.open(this.href);return false;">
O.Leid.15
</a>
</div>
<hr>
<div class="note">
Unknown number of Demotic characters omitted from DDbDP or edition.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
19 lines untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lines: 19 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="19" unit="line"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/28475" onclick="window.open(this.href);return false;">
P.Tebt.2.574
</a>
</div>
<hr>
<div class="note">
Known number of lines left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
? lines untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lines: ? non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" extent="unknown" unit="line"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/38980" onclick="window.open(this.href);return false;">
Stud.Pal.10.178
</a>
</div>
<hr>
<div class="note">
Unknown number of lines left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
1-3 lines untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lines: 1-3 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" atLeast="1" atMost="3" unit="line"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/17940" onclick="window.open(this.href);return false;">
P.Oxy.58.3958
</a>
</div>
<hr>
<div class="note">
Range of lines left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ca.7 lines untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Lines: ca.7 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="7" unit="line" precision="low"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/25686" onclick="window.open(this.href);return false;">
P.Oxy.2.396
</a>
</div>
<hr>
<div class="note">
Estimated number of lines left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
? characters untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Chars: ? non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" extent="unknown" unit="character"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/29504" onclick="window.open(this.href);return false;">
SB.20.14952
</a>
</div>
<hr>
<div class="note">
Unknown number of characters left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
1 character untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Chars: 1 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="1" unit="character"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Known number of characters left untranscribed by editor. 
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
1-2 characters untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Chars: 1-2 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" atLeast="1" atMost="2" unit="character"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/34332" onclick="window.open(this.href);return false;">
P.Eleph.Wagner.1.365
</a>
</div>
<hr>
<div class="note">
Range of characters left untranscribed by editor.
</div>
<hr>
<div class="description">
Untranscribed
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ca.18 characters untranscribed
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(Chars: ca.18 non transcribed)
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="ellipsis" quantity="18" unit="character" precision="low"&gt;&lt;desc&gt;non transcribed&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Estimated number of characters left untranscribed by editor.
</div>
<hr>
</div>
</div>
<div class="category" id="Quotation" style="display:;">
<div class="category_display">
Quotation
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Quotation-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Quotation-examples" style="display:none;">
<div class="description">
Quotation
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
'ὁ γὰ̣ρ̣ ἐ̣λ̣εῶ̣ν̣ [πτωχόν]'
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
" ὁ γὰ̣ρ̣ ἐ̣λ̣εῶ̣ν̣ [πτωχόν] "
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;q&gt; ὁ γ&lt;unclear&gt;ὰρ&lt;/unclear&gt; &lt;unclear&gt;ἐλ&lt;/unclear&gt;ε&lt;unclear&gt;ῶν&lt;/unclear&gt; &lt;supplied reason="lost"&gt;πτωχόν&lt;/supplied&gt; &lt;/q&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/34027" onclick="window.open(this.href);return false;">
P.Gen.2.1.14
</a>
</div>
<hr>
<div class="note">
Modern mark indicating quotation.
</div>
<hr>
</div>
</div>
<div class="category" id="special" style="display:;">
<div class="category_display">
special
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;special-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="special-examples" style="display:none;">
<div class="description">
figure on papyri
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
seal
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
#seal
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;figure&gt;&lt;figDesc&gt;seal&lt;/figDesc&gt;&lt;/figure&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/p.cair.zen;1;59003" onclick="window.open(this.href);return false;">
P.Cair.Zen.1.59003
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
</div>
</div>
<div class="category" id="Special Characters" style="display:;">
<div class="category_display">
Special Characters
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Special Characters-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Special Characters-examples" style="display:none;">
<div class="description">
Paragraphos
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
——
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
----
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;milestone rend="paragraphos" unit="undefined"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/9025" onclick="window.open(this.href);return false;">
BGU.1.28
</a>
</div>
<hr>
<div class="note">
To indicate paragraphos between, say, lines 4 and 5, enter as follows:
<br>
<br>3. text
<br>4. text
<br>----
<br>5. text
<br>
<br>Note: paragraphoi should be entered 'between lines', as above, and not on their own lines.
</div>
<hr>
<div class="description">
Horizontal rule on papyrus
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
————————
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
--------
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;milestone rend="horizontal-rule" unit="undefined"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/4776" onclick="window.open(this.href);return false;">
BGU.7.1526
</a>
</div>
<hr>
<div class="note">
To indicate horizontal rule on papyrus. To indicate paragraphos between, say, lines 4 and 5, enter as follows:
<br>
<br>3. text
<br>4. text
<br>--------
<br>5. text 
<br>
<br>Note: horizontal rules should be entered 'between lines', as above, and not on their own lines.
</div>
<hr>
<div class="description">
Non-alphabetical characters or symbols (example: slanting-stroke)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
/
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*slanting-stroke*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;g type="slanting-stroke"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10227" onclick="window.open(this.href);return false;">
P.Berl.Leihg.2.38
</a>
</div>
<hr>
<div class="note">
To indicate slanting stroke(s) written on papyrus.
</div>
<hr>
<div class="description">
Uncertain non-alphabetical characters or symbols (example: check)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
 /̣
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*check?*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;unclear&gt;&lt;g type="check"/&gt;&lt;/unclear&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/8946" onclick="window.open(this.href);return false;">
BGU.1.186
</a>
</div>
<hr>
<div class="note">
Unclear ancient 'check' mark on papyrus.
</div>
<hr>
<div class="description">
Non-alphabetical character with symbol (example: Chi-rho)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
☧
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*chirho,☧*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;g type="chirho"&gt;☧&lt;/g&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
To indicate chi-rho symbol; you may indicate preferred Unicode symbol: *chirho,☧*
</div>
<hr>
<div class="description">
Uncertain non-alphabetical character with symbol (example: Chi-rho)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
☧̣
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*chirho?,☧*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;unclear&gt;&lt;g type="chirho"&gt;☧&lt;/g&gt;&lt;/unclear&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/128700" onclick="window.open(this.href);return false;">
p.jena;2;19
</a>
</div>
<hr>
<div class="note">
To indicate an uncertain chi-rho symbol; you may indicate preferred Unicode symbol: *chirho?,☧*
</div>
<hr>
<div class="description">
Filler stroke
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
―
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*filler(extension)*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;g rend="extension" type="filler"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10201" onclick="window.open(this.href);return false;">
P.Berl.Leihg.1.17
</a>
</div>
<hr>
<div class="note">
Filler strokes, usually at end of line.
</div>
<hr>
<div class="description">
Filler stroke (uncertain)
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; ―(?)
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*filler(extension)?*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;unclear&gt;&lt;g rend="extension" type="filler"/&gt;&lt;/unclear&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/28171" onclick="window.open(this.href);return false;">
BGU.2.509
</a>
</div>
<hr>
<div class="note">
Unclear filler stroke on papyrus.
</div>
<hr>
<div class="description">
S-type etous
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
((s-etous))
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*s-etous*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;g type="s-etous"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/22431" onclick="window.open(this.href);return false;">
P.Lips.1.109
</a>
</div>
<hr>
<div class="note">
S-type etous symbol.
</div>
<hr>
<div class="description">
'Parens' on papyrus
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
((parens-punctuation-opening))  ((parens-punctuation-closing)) --&gt; distinct unicode parens
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
*parens-punctuation-opening*  *parens-punctuation-closing*
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;g type="parens-punctuation-opening"/&gt;  &lt;g type="parens-punctuation-closing"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
Text marked in antiquity with opening parens, closing parens, or both. If the ancient parens indicate(s) deletion mark the affected string with ((parens-punctuation-opening)) and/or ((parens-punctuation-closing)) and fully enclose in 〚...〛. If the semantic meaning of the parens is not clearly deletion, then use ((parens-punctuation-opening)) and/or ((parens-punctuation-closing)) alone.
</div>
<hr>
</div>
</div>
<div class="category" id="Special Formatting" style="display:;">
<div class="category_display">
Special Formatting
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Special Formatting-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Special Formatting-examples" style="display:none;">
<div class="description">
Text in box
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Text: milestone01…App: ctr.11. Text in box
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
###
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;milestone rend="box" unit="undefined"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/4787" onclick="window.open(this.href);return false;">
BGU.7.1537
</a>
</div>
<hr>
<div class="note">
To indicate text written inside a 'box'.
</div>
<hr>
<div class="description">
Tall text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; render taller
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
~||x||~tall
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="tall"&gt;x&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/21513" onclick="window.open(this.href);return false;">
P.Oslo.2.26
</a>
</div>
<hr>
<div class="note">
Oversized / tall text.
</div>
<hr>
<div class="description">
Superscripted text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
superscript
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
|^Ἡρωνείνῳ^|
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="superscript"&gt;Ἡρωνείνῳ&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/31500" onclick="window.open(this.href);return false;">
P.Laur.1.3
</a>
</div>
<hr>
<div class="note">
Text written in superscript, as distinct from text added above the line, as 'afterthought' or 'self-correction' (for which use \καὶ/). In general we do not encode superscript characters that indicate abbreviation.
</div>
<hr>
<div class="description">
Subscripted text
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
subscript
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
\|τα|/
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="subscript"&gt;τα&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">

</a>
</div>
<hr>
<div class="note">
To indicate subscripted text, as distinct from text added from below the line (for which use //καὶ\\).
</div>
<hr>
<div class="description">
Supraline
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
νο  ̣--&gt; with supraline
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
¯νο.1¯
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="supraline"&gt;νο&lt;gap reason="illegible" quantity="1" unit="character"/&gt;&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/33704" onclick="window.open(this.href);return false;">
P.Lips.1.102
</a>
</div>
<hr>
<div class="note">
To indicate supralines, most often used in case of numbers (not, as rule, for expansions)
</div>
<hr>
<div class="description">
Supraline and underline
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ø --&gt; underline and supraline
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
=εὐτύχει=
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;hi rend="supraline-underline"&gt;εὐτύχει&lt;/hi&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/18651" onclick="window.open(this.href);return false;">
BGU.4.1201
</a>
</div>
<hr>
<div class="note">
To indicate text that is both underlined and supralined.
</div>
<hr>
</div>
</div>
<div class="category" id="supplied" style="display:;">
<div class="category_display">
supplied
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;supplied-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="supplied-examples" style="display:none;">
<div class="description">
supplied parallel cert low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ἀρ(τάβας(?)) δωδέκ(ατον) εἰκ(οστοτέταρτον(?)) (ἀρτάβας) ιβ´ κδ´ † Ἀγαθάμμωνapp02 †/ ((tachygraphic-marks))
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
|_(ἀρ(τάβας?)) (δωδέκ(ατον)) (εἰκ(οστοτέταρτον?)) ((ἀρτάβας)) &lt;#ιβ=frac1/12#&gt; &lt;#κδ=frac1/24#&gt; *stauros* &lt;:Ἀγαθάμμων|BL:8.441|(δ(ι)) (|μ|) κάμμονι:&gt; *stauros*/ *tachygraphic-marks*(?)_|
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;supplied evidence="parallel" reason="undefined" cert="low"&gt;&lt;expan&gt;ἀρ&lt;ex cert="low"&gt;τάβας&lt;/ex&gt;&lt;/expan&gt; &lt;expan&gt;δωδέκ&lt;ex&gt;ατον&lt;/ex&gt;&lt;/expan&gt; &lt;expan&gt;εἰκ&lt;ex cert="low"&gt;οστοτέταρτον&lt;/ex&gt;&lt;/expan&gt; &lt;expan&gt;&lt;ex&gt;ἀρτάβας&lt;/ex&gt;&lt;/expan&gt; &lt;num value="1/12" rend="fraction"&gt;ι
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/37758" onclick="window.open(this.href);return false;">
Stud.Pal.3.503
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
<div class="description">
supplied parallel lost
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
???
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
_[abc]_
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
example only - &lt;supplied evidence="parallel" reason="lost"&gt;abc&lt;/supplied&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist 
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
</div>
</div>
<div class="category" id="text special" style="display:;">
<div class="category_display">
text special
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;text special-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="text special-examples" style="display:none;">
<div class="description">
text sling in margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ν
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;|ν|&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add rend="sling" place="margin"&gt;ν&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/41055" onclick="window.open(this.href);return false;">
BGU.1.303
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
<div class="description">
text underline in margin
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
οὕτως ἔχει
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;_οὕτως ἔχει_&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add rend="underline" place="margin"&gt;οὕτως ἔχει&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/12794" onclick="window.open(this.href);return false;">
P.Prag.2.137
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
<div class="description">
text above line with cert low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Θέ̣ων̣(?) = SoSOL,  Θέ̣ων̣(?)/ = PN
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
Θέ̣ων̣?/
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;add cert="low" place="above"&gt;Θ&lt;unclear&gt;έ&lt;/unclear&gt;ω&lt;unclear&gt;ν&lt;/unclear&gt;&lt;/add&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/ddbdp/psi;4;281" onclick="window.open(this.href);return false;">
PSI.4.281
</a>
</div>
<hr>
<div class="note">
need to create detailed instructions and explanation
</div>
<hr>
</div>
</div>
<div class="category" id="Vacat" style="display:;">
<div class="category_display">
Vacat
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Vacat-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Vacat-examples" style="display:none;">
<div class="description">
character space extent unknown
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
vac.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.?
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space extent="unknown" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/10223" onclick="window.open(this.href);return false;">
P.Berl.Leihg.2.39
</a>
</div>
<hr>
<div class="note">
Vacat of unknown number of characters. It is tempting to use vac.? to replicate the modern print publication convention of separating, e.g. items from numbers in accounts and the like. Rampant use of vac.? for this purpose is discouraged. Use vac.? only where there is empty space on the physical text; if such is not verifiable against image or original do not use vac.?.
</div>
<hr>
<div class="description">
character space quantity
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac.3
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.3
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space quantity="3" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of known number of characters.
</div>
<hr>
<div class="description">
character space range
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac.2-5
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.2-5
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space atLeast="2" atMost="5" unit="character"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of known range of characters.
</div>
<hr>
<div class="description">
character space quantity precision low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac. ca.3
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.ca.3
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space quantity="3" unit="character" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of estimated range of characters.
</div>
<hr>
<div class="description">
line space extent unknown
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac. ? lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.?lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space extent="unknown" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of unknown number of lines.
</div>
<hr>
<div class="description">
line space quantity
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac. 3 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.3lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space quantity="3" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of known number of lines.
</div>
<hr>
<div class="description">
line space range
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac. 2-5 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.2-5lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space atLeast="2" atMost="5" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of known range of lines.
</div>
<hr>
<div class="description">
line space quantity precision low
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
--&gt; vac ca.3 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vac.ca.3lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;space quantity="3" unit="line" precision="low"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vacat of estimated number of lines.
</div>
<hr>
</div>
</div>
<div class="category" id="Vestiges" style="display:;">
<div class="category_display">
Vestiges
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Vestiges-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Vestiges-examples" style="display:none;">
<div class="description">
Vestiges n lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces 15 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig.15lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="15" unit="line"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/16792" onclick="window.open(this.href);return false;">
P.Stras.6.559
</a>
</div>
<hr>
<div class="note">
Vestiges of known number of lines.
</div>
<hr>
<div class="description">
Vestiges range of lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces 2-3 lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig.2-3lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" atLeast="2" atMost="3" unit="line"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/9414" onclick="window.open(this.href);return false;">
BGU.3.916
</a>
</div>
<hr>
<div class="note">
Vestiges of known range of lines.
</div>
<hr>
<div class="description">
Vestiges ca.n lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Traces ca.3 lines 
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
ex. vestig.ca.3lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
ex. &lt;gap reason="illegible" quantity="3" unit="line" precision="low"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vestiges of estimated number of lines.
</div>
<hr>
<div class="description">
Vestiges ? lines
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
-ca.?- --&gt; Traces ? lines
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig.?lin
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" extent="unknown" unit="line"/&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/16792" onclick="window.open(this.href);return false;">
P.Stras.6.559
</a>
</div>
<hr>
<div class="note">
Vestiges of unknown number of lines.
</div>
<hr>
<div class="description">
Vestiges ? characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
-ca.?- --&gt; Traces
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig 
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" extent="unknown" unit="character"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/70853" onclick="window.open(this.href);return false;">
O.Berenike.1.76
</a>
</div>
<hr>
<div class="note">
Vestiges of unknown number of characters. NOTE: You must enter a space after vestig; so, not "vestig" but "vestig ".
</div>
<hr>
<div class="description">
Vestiges ca.n characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
ca.traces - --&gt; Traces 8 char. / Traces ca.14 char.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig.14char
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" quantity="14" unit="character"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/22338" onclick="window.open(this.href);return false;">
P.Lips.1.21
</a>
</div>
<hr>
<div class="note">
Vestiges of known number of characters. Note: all vestige strings greater than 8 characters are rendered as approximations. So, "vestig.14char" will be encoded as a piece of editorial certainty, but will nevertheless be displayed as an approximation: "Traces ca.14 char."
</div>
<hr>
<div class="description">
Vestiges ca.n characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
  ̣  ̣  ̣  --&gt; Traces ca.3 char.
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
example only - vestig.ca.3char
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
example only - &lt;gap reason="illegible"  quantity="3" unit="character" precision="low"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a onclick="window.open(this.href);return false;">
not exist
</a>
</div>
<hr>
<div class="note">
Vestiges of estimated number of characters.
</div>
<hr>
<div class="description">
Vestiges range of characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
-ca.15-30- --&gt; Traces ca.15-30 characters
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
vestig.15-30char
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason="illegible" atLeast="15" atMost="30" unit="character"&gt;&lt;desc&gt;vestiges&lt;/desc&gt;&lt;/gap&gt;
</div>
<hr>
<div class="sep">
Example PN Link:
</div>
<div class="filename">
<a href="http://papyri.info/hgv/15381" onclick="window.open(this.href);return false;">
P.Oxy.50.3557
</a>
</div>
<hr>
<div class="note">
Vestiges of range of characters.
</div>
<hr>
</div>
</div>



</div>
