<h1>
Translation Leiden+ Documentation
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
Each Translation Leiden+ Documentation Category with Examples
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
Deletion
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
〚eight drachmas, = 8 drachmas,〛
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
〚eight drachmas, = 8 drachmas,〛
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;del&gt;eight drachmas, = 8 drachmas,&lt;/del&gt;
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
To indicate translation of text, which was deleted in the original, use double square brackets: 〚...〛.
</div>
<hr>
<div class="description">
translation with div - simple
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Recto
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;T=.en&lt;D=.r &lt;=text=&gt;=D&gt;=T&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div xml:lang="en" type="translation" xml:space="preserve"&gt;&lt;div n="r" type="textpart"&gt;&lt;p&gt;text&lt;/p&gt;&lt;/div&gt;&lt;/div&gt;
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
Take care to enter your translation in the correct div. When entering a translation of an existing Greek text, SoSOL creates the divs for users. So if there is both a recto and a verso (or similar divisions such as columns), the translation windows already provides the appropriate subdivisions of the text.
</div>
<hr>
<div class="description">
gap lost unknown characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[...]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[...]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason='lost' extent='unknown' unit='character'/&gt;
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
Lacuna on papyrus. Use of square brackets to indicate partially missing words (e.g. part[ially]) is strongly discouraged.
</div>
<hr>
<div class="description">
gap illegible unknown characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
...
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
...
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason='illegible' extent='unknown' unit='character'/&gt;
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
Three dots indicate a break in the translation. Reasons include: untranslatable words or parts of words, presence of mere vestiges, or considerable repetition in the text such that it is not worth full translation.
</div>
<hr>
<div class="description">
milestone line
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Raised line number
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
((11))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;milestone unit='line' n='11'/&gt;
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
To indicate the line of the original documentary text. Indication of every line number is strongly discouraged. Instead, mark every 4th or 5th line (if any), starting with ((1)). Let ease of reading be your guide.
</div>
<hr>
<div class="description">
milestone line with rend=break
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Raised line number, starting on new line
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(((33)))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;milestone unit='line' n='33' rend='break'/&gt;
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
To indicate the line number of a new 'paragraph' or 'section' of the translation. For example, in a list of contract summaries you might start each new section with a new line: ((1)) ... (((5))) ... (((9))), etc.
</div>
<hr>
<div class="description">
note
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
In italics in parentheses
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
/*Top right sideways*/
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;note&gt;Top right sideways&lt;/note&gt;
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
To indicate an authorial note in a translation. Use sparingly.
</div>
<hr>
<div class="description">
term
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Contents of tag with mouseover defintion
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;unwatered land=abrochos&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;term target='abrochos'&gt;unwatered land&lt;/term&gt;
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
To insert a link to the (in progress) glossary. Suppose you are translating the Greek word ἄβροχος and want to link to the glossary entry. From the translation window mouse over 'Helpers', select 'Terms'; find the desired term in the glossary, click on the red transcription of the Greek word. This will insert into your translation window a sample-filled tag: <place word="" here="abrochos">. 
<br>
<br>Then, depending on what you want to appear in your translation, enter as follows: 
<br>
<br>&lt;unwatered land=abrochos&gt;
<br>
<br>Whatever you enter on the left will appear in the translation; in any case when you mouse over that word in the PN, it will display a pop-up with the definition of abrochos.
</place></div>
<hr>
<div class="description">
term with lang
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Contents of tag with mouseover defintion
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;vir egregius~la=hokratistos&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;term target='hokratistos' xml:lang='la'&gt;vir egregius&lt;/term&gt;
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
To indicate (1) Latin equivalent or (2) translitteration (rather than translation proper)
<br>
<br>(1) &lt;vir egregius~la=hokratistos&gt;
<br>(2) &lt;epistrategos-grc-Latn=epistrategos&gt;
</div>
<hr>
</div>
<div class="category" id="Deletion" style="display:;">
<div class="category_display">
Deletion
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Deletion-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Deletion-examples" style="display:none;">
<div class="description">
Deletion
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
〚eight drachmas, = 8 drachmas,〛
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
〚eight drachmas, = 8 drachmas,〛
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;del&gt;eight drachmas, = 8 drachmas,&lt;/del&gt;
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
To indicate translation of text, which was deleted in the original, use double square brackets: 〚...〛.
</div>
<hr>
</div>
</div>
<div class="category" id="Div" style="display:;">
<div class="category_display">
Div
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Div-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Div-examples" style="display:none;">
<div class="description">
translation with div - simple
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Recto
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;T=.en&lt;D=.r &lt;=text=&gt;=D&gt;=T&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;div xml:lang="en" type="translation" xml:space="preserve"&gt;&lt;div n="r" type="textpart"&gt;&lt;p&gt;text&lt;/p&gt;&lt;/div&gt;&lt;/div&gt;
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
Take care to enter your translation in the correct div. When entering a translation of an existing Greek text, SoSOL creates the divs for users. So if there is both a recto and a verso (or similar divisions such as columns), the translation windows already provides the appropriate subdivisions of the text.
</div>
<hr>
</div>
</div>
<div class="category" id="Gap" style="display:;">
<div class="category_display">
Gap
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Gap-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Gap-examples" style="display:none;">
<div class="description">
gap lost unknown characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
[...]
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
[...]
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason='lost' extent='unknown' unit='character'/&gt;
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
Lacuna on papyrus. Use of square brackets to indicate partially missing words (e.g. part[ially]) is strongly discouraged.
</div>
<hr>
<div class="description">
gap illegible unknown characters
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
...
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
...
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;gap reason='illegible' extent='unknown' unit='character'/&gt;
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
Three dots indicate a break in the translation. Reasons include: untranslatable words or parts of words, presence of mere vestiges, or considerable repetition in the text such that it is not worth full translation.
</div>
<hr>
</div>
</div>
<div class="category" id="Line numbering" style="display:;">
<div class="category_display">
Line numbering
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Line numbering-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Line numbering-examples" style="display:none;">
<div class="description">
milestone line
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Raised line number
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
((11))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;milestone unit='line' n='11'/&gt;
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
To indicate the line of the original documentary text. Indication of every line number is strongly discouraged. Instead, mark every 4th or 5th line (if any), starting with ((1)). Let ease of reading be your guide.
</div>
<hr>
<div class="description">
milestone line with rend=break
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Raised line number, starting on new line
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
(((33)))
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;milestone unit='line' n='33' rend='break'/&gt;
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
To indicate the line number of a new 'paragraph' or 'section' of the translation. For example, in a list of contract summaries you might start each new section with a new line: ((1)) ... (((5))) ... (((9))), etc.
</div>
<hr>
</div>
</div>
<div class="category" id="Note" style="display:;">
<div class="category_display">
Note
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Note-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Note-examples" style="display:none;">
<div class="description">
note
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
In italics in parentheses
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
/*Top right sideways*/
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;note&gt;Top right sideways&lt;/note&gt;
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
To indicate an authorial note in a translation. Use sparingly.
</div>
<hr>
</div>
</div>
<div class="category" id="Term" style="display:;">
<div class="category_display">
Term
</div>
<div class="toggle_button">
<a onclick="toggle_div(&#39;Term-examples&#39;);">
Examples
</a>
</div>
<div class="examples" id="Term-examples" style="display:none;">
<div class="description">
term
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Contents of tag with mouseover defintion
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;unwatered land=abrochos&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;term target='abrochos'&gt;unwatered land&lt;/term&gt;
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
To insert a link to the (in progress) glossary. Suppose you are translating the Greek word ἄβροχος and want to link to the glossary entry. From the translation window mouse over 'Helpers', select 'Terms'; find the desired term in the glossary, click on the red transcription of the Greek word. This will insert into your translation window a sample-filled tag: <place word="" here="abrochos">. 
<br>
<br>Then, depending on what you want to appear in your translation, enter as follows: 
<br>
<br>&lt;unwatered land=abrochos&gt;
<br>
<br>Whatever you enter on the left will appear in the translation; in any case when you mouse over that word in the PN, it will display a pop-up with the definition of abrochos.
</place></div>
<hr>
<div class="description">
term with lang
</div>
<hr>
<div class="sep">
To get this PN preview:
</div>
<div class="preview">
Contents of tag with mouseover defintion
</div>
<hr>
<div class="sep">
Use this Leiden+:
</div>
<div class="leiden">
&lt;vir egregius~la=hokratistos&gt;
</div>
<hr>
<div class="sep">
To create this XML:
</div>
<div class="xml">
&lt;term target='hokratistos' xml:lang='la'&gt;vir egregius&lt;/term&gt;
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
To indicate (1) Latin equivalent or (2) translitteration (rather than translation proper)
<br>
<br>(1) &lt;vir egregius~la=hokratistos&gt;
<br>(2) &lt;epistrategos-grc-Latn=epistrategos&gt;
</div>
<hr>
</div>
</div>



</div>
