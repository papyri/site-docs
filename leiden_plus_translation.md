# Translation Leiden+ Documentation

<button class="btn btn-primary mb-3" onclick="
  window.allExpanded = !window.allExpanded;
  $('.accordion-collapse').each(function() {
    const collapse = bootstrap.Collapse.getOrCreateInstance(this);
    window.allExpanded ? collapse.show() : collapse.hide();
  });
  this.textContent = window.allExpanded ? 'Collapse All' : 'Expand All';
">
  Expand All
</button>

<div class="accordion">
  <div id="Deletion" class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deletion-panel" aria-expanded="false" aria-controls="deletion-panel">
        Deletion
      </button>
    </h2>
    <div id="deletion-panel" class="accordion-collapse collapse">
      <div class="accordion-body">
        <dl class="row">
          <dt class="col-md-3">To get this PN preview</dt>
          <dd class="col-md-9"><code>〚eight drachmas, = 8 drachmas,〛</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Use this Leiden+</dt>
          <dd class="col-md-9"><code>〚eight drachmas, = 8 drachmas,〛</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">To create this XML</dt>
          <dd class="col-md-9"><code>&lt;del&gt;eight drachmas, = 8 drachmas,&lt;/del&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Example PN link</dt>
          <dd class="col-md-9">TBD</dd>
        </dl>
        <p>To indicate translation of text, which was deleted in the original, use double square brackets: <code>〚...〛</code>.</p>
      </div>
    </div>
  </div>
  <div id="Div" class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#div-panel" aria-expanded="false" aria-controls="div-panel">
        Div
      </button>
    </h2>
    <div id="div-panel" class="accordion-collapse collapse">
      <div class="accordion-body">
        <h3>Translation with <code>div</code> - Simple</h3>
        <dl class="row">
          <dt class="col-md-3">To get this PN preview</dt>
          <dd class="col-md-9"><code>Recto</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Use this Leiden+</dt>
          <dd class="col-md-9"><code>&lt;T=.en&lt;D=.r &lt;=text=&gt;=D&gt;=T&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">To create this XML</dt>
          <dd class="col-md-9"><code>&lt;div xml:lang="en" type="translation" xml:space="preserve"&gt;&lt;div n="r" type="textpart"&gt;&lt;p&gt;text&lt;/p&gt;&lt;/div&gt;&lt;/div&gt;
</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Example PN link</dt>
          <dd class="col-md-9">TBD</dd>
        </dl>
        <p>Take care to enter your translation in the correct <code>div</code>. When entering a translation of an existing Greek text, SoSOL creates the <code>div</code>s for users. So if there is both a recto and a verso (or similar divisions such as columns), the translation windows already provides the appropriate subdivisions of the text.</p>
      </div>
    </div>
  </div>
  <div id="Gap" class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#gap-panel" aria-expanded="false" aria-controls="gap-panel">
        Gap
      </button>
    </h2>
    <div id="gap-panel" class="accordion-collapse collapse">
      <div class="accordion-body">
        <h3>Gap Lost Unknown Characters</h3>
        <dl class="row">
          <dt class="col-md-3">To get this PN preview</dt>
          <dd class="col-md-9"><code>[...]</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Use this Leiden+</dt>
          <dd class="col-md-9"><code>[...]</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">To create this XML</dt>
          <dd class="col-md-9"><code>&lt;gap reason='lost' extent='unknown' unit='character'/&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Example PN link</dt>
          <dd class="col-md-9">TBD</dd>
        </dl>
        <p>Lacuna on papyrus. Use of square brackets to indicate partially missing words (e.g. <code>part[ially]</code>) is strongly discouraged.</p>
        <h3>Gap Illegible Unknown Characters</h3>
        <dl class="row">
          <dt class="col-md-3">To get this PN preview</dt>
          <dd class="col-md-9"><code>...</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Use this Leiden+</dt>
          <dd class="col-md-9"><code>...</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">To create this XML</dt>
          <dd class="col-md-9"><code>&lt;gap reason='illegible' extent='unknown' unit='character'/&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Example PN link</dt>
          <dd class="col-md-9">TBD</dd>
        </dl>
        <p>Three dots indicate a break in the translation. Reasons include: untranslatable words or parts of words, presence of mere vestiges, or considerable repetition in the text such that it is not worth full translation.</p>
      </div>
    </div>
  </div>
  <div id="Line-Numbering" class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#line-numbering-panel" aria-expanded="false" aria-controls="line-numbering-panel">
        Line numbering
      </button>
    </h2>
    <div id="line-numbering-panel" class="accordion-collapse collapse">
      <div class="accordion-body">
        <h3>Milestone line</h3>
        <dl class="row">
          <dt class="col-md-3">To get this PN preview</dt>
          <dd class="col-md-9"><code>Raised line number</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Use this Leiden+</dt>
          <dd class="col-md-9"><code>((11))</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">To create this XML</dt>
          <dd class="col-md-9"><code>&lt;milestone unit='line' n='11'/&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Example PN link</dt>
          <dd class="col-md-9">TBD</dd>
        </dl>
        <p>To indicate the line of the original documentary text. Indication of every line number is strongly discouraged. Instead, mark every 4th or 5th line (if any), starting with <code>((1))</code>. Let ease of reading be your guide.</p>
        <h3>Milestone line with <code>rend='break'</code></h3>
        <dl class="row">
          <dt class="col-md-3">To get this PN preview</dt>
          <dd class="col-md-9"><code>Raised line number, starting on new line</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Use this Leiden+</dt>
          <dd class="col-md-9"><code>(((33)))</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">To create this XML</dt>
          <dd class="col-md-9"><code>&lt;milestone unit='line' n='33' rend='break'/&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Example PN link</dt>
          <dd class="col-md-9">TBD</dd>
        </dl>
        <p>To indicate the line number of a new 'paragraph' or 'section' of the translation. For example, in a list of contract summaries you might start each new section with a new line: <code>((1)) ... (((5))) ... (((9)))</code>, etc.</p>
      </div>
    </div>
  </div>
  <div id="Note" class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#note-panel" aria-expanded="false" aria-controls="note-panel">
        Note
      </button>
    </h2>
    <div id="note-panel" class="accordion-collapse collapse">
      <div class="accordion-body">
        <h3>Milestone line</h3>
        <dl class="row">
          <dt class="col-md-3">To get this PN preview</dt>
          <dd class="col-md-9"><code>In italics in parentheses</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Use this Leiden+</dt>
          <dd class="col-md-9"><code>/*Top right sideways*/</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">To create this XML</dt>
          <dd class="col-md-9"><code>&lt;note&gt;Top right sideways&lt;/note&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Example PN link</dt>
          <dd class="col-md-9">TBD</dd>
        </dl>
        <p>To indicate an authorial note in a translation. Use sparingly.</p>
      </div>
    </div>
  </div>
  <div id="Term" class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#term-panel" aria-expanded="false" aria-controls="term-panel">
        Term
      </button>
    </h2>
    <div id="term-panel" class="accordion-collapse collapse">
      <div class="accordion-body">
        <h3>Term</h3>
        <dl class="row">
          <dt class="col-md-3">To get this PN preview</dt>
          <dd class="col-md-9"><code>Contents of tag with mouseover definition</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Use this Leiden+</dt>
          <dd class="col-md-9"><code>&lt;unwatered land=abrochos&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">To create this XML</dt>
          <dd class="col-md-9"><code>&lt;term target='abrochos'&gt;unwatered land&lt;/term&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Example PN link</dt>
          <dd class="col-md-9">TBD</dd>
        </dl>
        <p>To insert a link to the (in progress) glossary. Suppose you are translating the Greek word ἄβροχος and want to link to the glossary entry. From the translation window mouse over 'Helpers', select 'Terms'; find the desired term in the glossary, click on the red transcription of the Greek word. This will insert into your translation window a sample-filled tag: <code>&lt;place word="" here="abrochos"&gt;</code>.</p>
        <p>Then, depending on what you want to appear in your translation, enter as follows:<br>
        <code>&lt;unwatered land=abrochos&gt;</code><br>
        <p>Whatever you enter on the left will appear in the translation; in any case when you mouse over that word in the PN, it will display a pop-up with the definition of <code>abrochos</code>.</p>
        <h3>Term with <code>lang</code></h3>
        <dl class="row">
          <dt class="col-md-3">To get this PN preview</dt>
          <dd class="col-md-9"><code>Contents of tag with mouseover definition</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Use this Leiden+</dt>
          <dd class="col-md-9"><code>&lt;vir egregius~la=hokratistos&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">To create this XML</dt>
          <dd class="col-md-9"><code>&lt;term target='hokratistos' xml:lang='la'&gt;vir egregius&lt;/term&gt;</code></dd>
        </dl>
        <dl class="row">
          <dt class="col-md-3">Example PN link</dt>
          <dd class="col-md-9">TBD</dd>
        </dl>
        <p>To indicate (1) Latin equivalent or (2) translitteration (rather than translation proper)</p>
        <p>
          (1) <code>&lt;vir egregius~la=hokratistos&gt;</code><br>
          (2) <code>&lt;epistrategos-grc-Latn=epistrategos&gt;</code>
        </p>
      </div>
    </div>
  </div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    // Function to open panel based on hash
    function openPanelFromHash() {
      const hash = window.location.hash;
      if (hash) {
        const panelId = hash.substring(1).toLowerCase() + '-panel';
        const targetPanel = document.getElementById(panelId);

        if (targetPanel) {
          // Use Bootstrap's Collapse API to show the panel
          const collapse = bootstrap.Collapse.getOrCreateInstance(targetPanel);

          // Listen for the panel to finish opening, then scroll
          targetPanel.addEventListener('shown.bs.collapse', function() {
            document.querySelector(hash).scrollIntoView();
          }, { once: true });

          collapse.show();
        }
      }
    }

    // Open panel on initial load
    openPanelFromHash();

    // Listen for hash changes (when user clicks browser back/forward or changes URL)
    window.addEventListener('hashchange', openPanelFromHash);
  });
</script>
