<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Plant Power — 5th Grade Science</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=Fraunces:opsz,wght@9..144,400;9..144,600;9..144,700&family=Source+Serif+4:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    min-height: 100vh;
    background: linear-gradient(175deg, #f0faf4 0%, #e8f5e9 40%, #fff8e1 100%);
    font-family: 'Source Serif 4', Georgia, serif;
    color: #2d3436;
    line-height: 1.7;
  }
  .header {
    background: #1b4332;
    padding: 28px 20px 20px;
    text-align: center;
    position: relative;
    overflow: hidden;
  }
  .header::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0; bottom: 0;
    background: radial-gradient(circle at 20% 80%, rgba(82,183,136,0.3) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(180,234,165,0.15) 0%, transparent 50%);
  }
  .header h1 {
    font-family: 'Fraunces', serif;
    font-size: 30px;
    color: #d8f3dc;
    margin-bottom: 4px;
    position: relative;
    letter-spacing: -0.5px;
  }
  .header p {
    color: #95d5b2;
    font-size: 14px;
    position: relative;
    font-weight: 500;
  }
  .tabs {
    display: flex;
    justify-content: center;
    gap: 4px;
    padding: 12px 12px 0;
    background: rgba(27,67,50,0.04);
    border-bottom: 1px solid #d8f3dc;
  }
  .tab-btn {
    padding: 10px 18px;
    border: none;
    border-bottom: 3px solid transparent;
    background: transparent;
    border-radius: 10px 10px 0 0;
    cursor: pointer;
    font-size: 14px;
    font-weight: 500;
    color: #6c757d;
    font-family: 'Source Serif 4', serif;
    transition: all 0.2s;
  }
  .tab-btn.active {
    border-bottom-color: #2d6a4f;
    background: #fff;
    font-weight: 700;
    color: #1b4332;
  }
  .content-wrap {
    max-width: 640px;
    margin: 0 auto;
    padding: 28px 20px 40px;
  }
  .card {
    background: #fff;
    border-radius: 16px;
    padding: 28px 24px;
    box-shadow: 0 2px 20px rgba(27,67,50,0.08);
    border: 1px solid #d8f3dc;
  }
  .tab-hint {
    font-size: 12px;
    color: #95d5b2;
    margin-bottom: 16px;
    font-family: 'DM Mono', monospace;
    text-transform: uppercase;
    letter-spacing: 1.5px;
  }
  .section { display: none; }
  .section.active { display: block; }
  h2 { font-family: 'Fraunces', serif; font-size: 26px; color: #1b4332; margin-bottom: 6px; }
  h3 { font-family: 'Fraunces', serif; font-size: 20px; color: #40916c; margin-bottom: 20px; font-weight: 500; }
  h4 { font-family: 'Fraunces', serif; font-size: 18px; color: #1b4332; margin-bottom: 10px; }
  p { margin-bottom: 14px; font-size: 15px; }

  /* Vocab */
  .vocab {
    font-weight: 700;
    color: #2d6a4f;
    border-bottom: 2px dotted #95d5b2;
    cursor: pointer;
    position: relative;
    display: inline;
  }
  .vocab-tip {
    display: none;
    position: absolute;
    bottom: calc(100% + 10px);
    left: 50%;
    transform: translateX(-50%);
    background: #1b4332;
    color: #d8f3dc;
    padding: 8px 14px;
    border-radius: 10px;
    font-size: 13px;
    z-index: 100;
    box-shadow: 0 4px 20px rgba(0,0,0,.25);
    font-weight: 500;
    max-width: 260px;
    white-space: normal;
    text-align: center;
    line-height: 1.4;
  }
  .vocab-tip::after {
    content: '';
    position: absolute;
    top: 100%;
    left: 50%;
    transform: translateX(-50%);
    border: 6px solid transparent;
    border-top-color: #1b4332;
  }
  .vocab.show .vocab-tip { display: block; }

  /* Activity */
  .activity-box {
    background: #f0faf4;
    border-radius: 14px;
    padding: 20px;
    border: 1px solid #b7e4c7;
    margin-bottom: 28px;
  }
  .activity-box:last-child { margin-bottom: 0; }
  .word-bank {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 20px;
    justify-content: center;
  }
  .word-chip {
    padding: 6px 14px;
    background: #fff;
    border: 2px solid #74c69d;
    border-radius: 20px;
    font-size: 13px;
    font-weight: 600;
    font-family: 'DM Mono', monospace;
    color: #1b4332;
    cursor: pointer;
    transition: all 0.2s;
    user-select: none;
    text-transform: lowercase;
  }
  .word-chip.used {
    background: #dee2e6;
    border-color: #ced4da;
    color: #adb5bd;
    opacity: 0.5;
    cursor: default;
  }
  .word-chip.selected {
    background: #2d6a4f;
    border-color: #2d6a4f;
    color: #fff;
    transform: scale(1.05);
  }
  .diagram-wrap {
    max-width: 500px;
    margin: 0 auto;
    position: relative;
  }
  .drop-zone {
    position: absolute;
    min-width: 86px;
    min-height: 24px;
    background: rgba(255,255,255,0.85);
    border: 2px dashed #adb5bd;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 11px;
    font-weight: 600;
    font-family: 'DM Mono', monospace;
    color: #6c757d;
    padding: 2px 6px;
    cursor: pointer;
    transition: all 0.2s;
    text-transform: lowercase;
  }
  .drop-zone.correct {
    background: #d8f3dc;
    border: 2px solid #40916c;
    color: #1b4332;
  }
  .drop-zone.wrong {
    background: #ffe0e0;
    border: 2px solid #e63946;
    color: #c1121f;
  }
  .drop-zone.highlight {
    border-color: #2d6a4f;
    background: rgba(45,106,79,0.1);
  }
  textarea {
    width: 100%;
    padding: 12px;
    border-radius: 10px;
    border: 2px solid #b7e4c7;
    font-size: 14px;
    font-family: 'Source Serif 4', serif;
    resize: vertical;
    outline: none;
    margin-bottom: 18px;
    transition: border-color 0.2s;
  }
  textarea:focus { border-color: #40916c; }
  label { display: block; font-size: 14px; font-weight: 600; color: #2d6a4f; margin-bottom: 6px; }
  .btn-submit {
    padding: 10px 28px;
    background: #ced4da;
    color: #fff;
    border: none;
    border-radius: 24px;
    font-size: 15px;
    font-weight: 700;
    cursor: default;
    transition: all 0.25s;
  }
  .btn-submit.ready { background: #2d6a4f; cursor: pointer; }
  .btn-reset {
    padding: 8px 20px;
    background: transparent;
    border: 2px solid #adb5bd;
    border-radius: 20px;
    cursor: pointer;
    font-size: 13px;
    font-weight: 600;
    color: #495057;
    transition: all 0.2s;
  }
  .btn-reset:hover { border-color: #e63946; color: #e63946; }
  .result-box {
    margin-top: 16px;
    padding: 12px 16px;
    border-radius: 10px;
    font-weight: 600;
    font-size: 15px;
    text-align: center;
  }
  .result-box.perfect { background: #d8f3dc; border: 1px solid #52b788; color: #1b4332; }
  .result-box.partial { background: #fff3cd; border: 1px solid #ffc107; color: #664d03; }
  .result-box.submitted { background: #d8f3dc; border: 1px solid #52b788; color: #1b4332; }

  /* Adaptations drag-and-drop */
  .match-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0 8px;
    margin-bottom: 20px;
  }
  .match-row td {
    vertical-align: middle;
  }
  .match-statement {
    background: #fff;
    border: 1.5px solid #b7e4c7;
    border-radius: 10px;
    padding: 10px 14px;
    font-size: 14px;
    line-height: 1.4;
    width: 54%;
  }
  .match-arrow {
    text-align: center;
    padding: 0 6px;
    color: #95d5b2;
    font-size: 18px;
    width: 8%;
  }
  .match-drop {
    background: #f0faf4;
    border: 2px dashed #74c69d;
    border-radius: 10px;
    padding: 10px 12px;
    font-size: 13px;
    font-weight: 600;
    font-family: 'DM Mono', monospace;
    color: #adb5bd;
    text-align: center;
    min-height: 44px;
    width: 38%;
    cursor: pointer;
    transition: all 0.2s;
    user-select: none;
  }
  .match-drop.drag-over {
    border-color: #2d6a4f;
    background: rgba(45,106,79,0.1);
    color: #2d6a4f;
  }
  .match-drop.filled {
    background: #fff;
    border-style: solid;
    border-color: #74c69d;
    color: #1b4332;
    cursor: default;
  }
  .match-drop.correct-ans {
    background: #d8f3dc;
    border-color: #40916c;
    color: #1b4332;
  }
  .match-drop.wrong-ans {
    background: #ffe0e0;
    border-color: #e63946;
    color: #c1121f;
  }
  .adapt-bank {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    justify-content: center;
    padding: 14px;
    background: #f8f9fa;
    border-radius: 12px;
    border: 1px solid #dee2e6;
    margin-bottom: 16px;
  }
  .adapt-chip {
    padding: 8px 16px;
    background: #fff;
    border: 2px solid #74c69d;
    border-radius: 20px;
    font-size: 13px;
    font-weight: 700;
    font-family: 'DM Mono', monospace;
    color: #1b4332;
    cursor: grab;
    transition: all 0.15s;
    user-select: none;
    touch-action: none;
  }
  .adapt-chip:active { cursor: grabbing; }
  .adapt-chip.dragging {
    opacity: 0.4;
    transform: scale(0.95);
  }
  .adapt-chip.used {
    background: #e9ecef;
    border-color: #ced4da;
    color: #adb5bd;
    cursor: not-allowed;
    opacity: 0.55;
  }
  .adapt-chip.tap-selected {
    background: #2d6a4f;
    border-color: #2d6a4f;
    color: #fff;
    transform: scale(1.06);
    box-shadow: 0 2px 10px rgba(45,106,79,0.3);
  }
  .adapt-btns {
    display: flex;
    gap: 10px;
    justify-content: center;
    margin-top: 10px;
  }
  .btn-check {
    padding: 10px 28px;
    background: #2d6a4f;
    color: #fff;
    border: none;
    border-radius: 24px;
    font-size: 15px;
    font-weight: 700;
    cursor: pointer;
    transition: background 0.2s;
  }
  .btn-check:hover { background: #1b4332; }
  .btn-check:disabled { background: #ced4da; cursor: default; }
</style>
</head>
<body>

<div class="header">
  <h1>🌱 Plant Power</h1>
  <p>5th Grade Science — Life Cycles &amp; Flower Anatomy</p>
</div>

<div class="tabs">
  <button class="tab-btn active" onclick="switchTab('read1')">📖 Reading 1</button>
  <button class="tab-btn" onclick="switchTab('read2')">🌸 Reading 2</button>
  <button class="tab-btn" onclick="switchTab('activity')">✏️ Activity</button>
  <button class="tab-btn" onclick="switchTab('adaptations')">🐻 Adaptations</button>
</div>

<div class="content-wrap">
  <div class="card">

    <!-- READING 1 -->
    <div id="sec-read1" class="section active">
      <div class="tab-hint">Tap green words for definitions</div>
      <h2>Reading Passage 1</h2>
      <h3>The Life of a Plant</h3>
      <p>Welcome to the amazing world of plants! Plants are living things that go through a fascinating <span class="vocab" onclick="toggleTip(this)">life cycle<span class="vocab-tip">The stages a living thing goes through from birth to death.</span></span>. They start as tiny seeds, sprout into the soil, and grow into mature plants that eventually make new seeds of their own.</p>
      <p>To grow big and strong, plants need food, but they don't eat like humans or animals do! Instead, they use an incredible process called <span class="vocab" onclick="toggleTip(this)">photosynthesis<span class="vocab-tip">The process plants use to turn sunlight, water, and air into food.</span></span>. During photosynthesis, plants catch energy from sunlight and use it to turn water and air into their own sugary food.</p>
      <p>Plants are also very smart when it comes to surviving in their environment. They can sense changes around them and adjust how they grow, which scientists call a <span class="vocab" onclick="toggleTip(this)">response to stimuli<span class="vocab-tip">When a plant senses changes and adjusts how it grows.</span></span>. For example, if a plant is placed in a dark room with only one window, it will bend and grow toward the light!</p>
      <p>Over a very long time, plants also develop <span class="vocab" onclick="toggleTip(this)">adaptations<span class="vocab-tip">Special traits that help a plant survive in its environment.</span></span> to survive in their specific climate. A cactus, for instance, has adapted to store water so it can live in a hot, dry desert.</p>
    </div>

    <!-- READING 2 -->
    <div id="sec-read2" class="section">
      <div class="tab-hint">Tap green words for definitions</div>
      <h2>Reading Passage 2</h2>
      <h3>Inside the Flower</h3>
      <p>To keep their life cycle going and create new seeds, many plants rely on special structures. Let's zoom in and look at the <strong style="color:#2d6a4f">Parts of a Flower</strong>. Flowers aren't just pretty — every part has a very important job!</p>
      <p>The <span class="vocab" onclick="toggleTip(this)">petal<span class="vocab-tip">The colorful part of the flower that attracts insects.</span></span> is the bright, colorful part designed to attract helpful insects like bees and butterflies. At the very bottom is the <span class="vocab" onclick="toggleTip(this)">receptacle<span class="vocab-tip">The base that connects the flower to the stem.</span></span>, the base that connects the flower to the stem, and the <span class="vocab" onclick="toggleTip(this)">sepal<span class="vocab-tip">A tiny green leaf that protects the flower bud.</span></span>, which looks like a tiny green leaf that protects the flower bud before it opens.</p>
      <p>Deep inside the flower you'll find two main systems. The <span class="vocab" onclick="toggleTip(this)">stamen<span class="vocab-tip">The male part of the flower.</span></span> is the "male" part. It's made of a thin stalk called the <span class="vocab" onclick="toggleTip(this)">filament<span class="vocab-tip">The long thin stalk of the stamen.</span></span>, and a puffy top called the <span class="vocab" onclick="toggleTip(this)">anther<span class="vocab-tip">The puffy top that holds pollen.</span></span>, which produces yellow pollen.</p>
      <p>Right in the center is the <span class="vocab" onclick="toggleTip(this)">pistil<span class="vocab-tip">The female part of the flower.</span></span>, the "female" part. It has three pieces: the <span class="vocab" onclick="toggleTip(this)">stigma<span class="vocab-tip">The sticky top that catches pollen.</span></span> (a sticky top that catches pollen), the <span class="vocab" onclick="toggleTip(this)">style<span class="vocab-tip">The long tube connecting stigma to ovary.</span></span> (a long tube going down), and the <span class="vocab" onclick="toggleTip(this)">ovary<span class="vocab-tip">The bottom part where seeds are made.</span></span> (the swollen bottom where new seeds are made).</p>
    </div>

    <!-- ACTIVITY -->
    <div id="sec-activity" class="section">
      <div class="tab-hint">15-20 minute interactive review</div>
      <h2>Interactive Activity</h2>
      <h3>Plant Anatomy &amp; Cycle Review</h3>

      <div class="activity-box">
        <h4>Part 1: Tap to Label the Flower</h4>
        <p style="font-size:14px;color:#52796f;margin-bottom:16px;">
          Tap a word, then tap the label spot on the diagram where it belongs.
        </p>

        <div class="word-bank" id="wordBank"></div>

        <div class="diagram-wrap" id="diagramWrap">
          <svg viewBox="0 0 400 340" style="width:100%;display:block;">
            <!-- Stem -->
            <rect x="193" y="270" width="14" height="70" rx="4" fill="#52b788"/>
            <!-- Receptacle -->
            <ellipse cx="200" cy="270" rx="32" ry="14" fill="#74c69d" stroke="#40916c" stroke-width="1.5"/>
            <!-- Sepals -->
            <ellipse cx="158" cy="252" rx="18" ry="8" fill="#95d5b2" stroke="#40916c" stroke-width="1" transform="rotate(-30 158 252)"/>
            <ellipse cx="242" cy="252" rx="18" ry="8" fill="#95d5b2" stroke="#40916c" stroke-width="1" transform="rotate(30 242 252)"/>
            <!-- Petals -->
            <ellipse cx="200" cy="40" rx="40" ry="55" fill="#ff8fab" stroke="#ff6b8a" stroke-width="1.5" opacity="0.85"/>
            <ellipse cx="120" cy="120" rx="38" ry="58" fill="#ffb3c6" stroke="#ff6b8a" stroke-width="1.5" opacity="0.8" transform="rotate(-40 120 120)"/>
            <ellipse cx="280" cy="120" rx="38" ry="58" fill="#ffb3c6" stroke="#ff6b8a" stroke-width="1.5" opacity="0.8" transform="rotate(40 280 120)"/>
            <ellipse cx="140" cy="200" rx="35" ry="52" fill="#ffc2d1" stroke="#ff6b8a" stroke-width="1.5" opacity="0.75" transform="rotate(-20 140 200)"/>
            <ellipse cx="260" cy="200" rx="35" ry="52" fill="#ffc2d1" stroke="#ff6b8a" stroke-width="1.5" opacity="0.75" transform="rotate(20 260 200)"/>
            <!-- Pistil style tube -->
            <rect x="196" y="60" width="8" height="130" rx="3" fill="#b7e4c7" stroke="#52b788" stroke-width="1"/>
            <!-- Ovary -->
            <ellipse cx="200" cy="190" rx="22" ry="18" fill="#d8f3dc" stroke="#52b788" stroke-width="1.5"/>
            <!-- Stigma -->
            <ellipse cx="200" cy="52" rx="14" ry="10" fill="#ffd166" stroke="#e6ac00" stroke-width="1.5"/>
            <!-- Stamen left filament -->
            <line x1="130" y1="80" x2="120" y2="155" stroke="#a3b18a" stroke-width="3" stroke-linecap="round"/>
            <!-- Anther left -->
            <ellipse cx="130" cy="74" rx="10" ry="7" fill="#ffd166" stroke="#e6ac00" stroke-width="1.2"/>
            <!-- Stamen right filament -->
            <line x1="270" y1="80" x2="280" y2="155" stroke="#a3b18a" stroke-width="3" stroke-linecap="round"/>
            <!-- Anther right -->
            <ellipse cx="270" cy="74" rx="10" ry="7" fill="#ffd166" stroke="#e6ac00" stroke-width="1.2"/>
            <!-- Leader lines (drawn by JS) -->
            <g id="leaderLines"></g>
          </svg>
          <!-- Drop zones injected by JS -->
        </div>

        <div id="diagramResult"></div>
        <div style="text-align:center;margin-top:12px;">
          <button class="btn-reset" onclick="resetDiagram()">Reset Labels</button>
        </div>
      </div>

      <div class="activity-box">
        <h4>Part 2: Short Answer Check</h4>
        <label>1. Write two sentences explaining photosynthesis:</label>
        <textarea id="ans1" rows="3" placeholder="Plants use sunlight to..." oninput="checkReady()"></textarea>
        <label>2. Give one example of a plant's response to stimuli or adaptation:</label>
        <textarea id="ans2" rows="2" placeholder="A cactus has adapted to..." oninput="checkReady()"></textarea>
        <button class="btn-submit" id="btnSubmit" onclick="submitAnswers()">Submit Answers ✓</button>
        <div id="answerResult"></div>
      </div>
    </div>

    <!-- ADAPTATIONS DRAG-AND-DROP -->
    <div id="sec-adaptations" class="section">
      <div class="tab-hint">Drag words to their matching descriptions</div>
      <h2>Drag &amp; Drop</h2>
      <h3>Animal &amp; Plant Adaptations</h3>

      <div class="activity-box">
        <p style="font-size:14px;color:#52796f;margin-bottom:16px;">
          Drag each term from the bank below and drop it onto the matching description.
          On mobile, tap a term to select it, then tap the box where it belongs.
        </p>

        <!-- Word bank -->
        <div class="adapt-bank" id="adaptBank"></div>

        <!-- Matching rows -->
        <table class="match-table" id="matchTable">
          <tbody id="matchBody"></tbody>
        </table>

        <div id="adaptResult"></div>
        <div class="adapt-btns">
          <button class="btn-check" id="btnCheck" onclick="checkAdapt()">Check Answer</button>
          <button class="btn-reset" onclick="resetAdapt()">Reset</button>
        </div>
      </div>
    </div>

  </div>
</div>

<script>
// TAB SWITCHING
function switchTab(id) {
  document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
  document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
  document.getElementById('sec-' + id).classList.add('active');
  const tabMap = { read1: 0, read2: 1, activity: 2, adaptations: 3 };
  document.querySelectorAll('.tab-btn')[tabMap[id]].classList.add('active');
}

// VOCAB TIPS
function toggleTip(el) {
  document.querySelectorAll('.vocab.show').forEach(v => { if (v !== el) v.classList.remove('show'); });
  el.classList.toggle('show');
}
document.addEventListener('click', function(e) {
  if (!e.target.closest('.vocab')) {
    document.querySelectorAll('.vocab.show').forEach(v => v.classList.remove('show'));
  }
});

// DIAGRAM LABELING (tap-to-select for mobile)
const PARTS = [
  { id:'stigma', correct:'stigma', pct:[77.5,12.4] },
  { id:'style', correct:'style', pct:[77.5,33.8] },
  { id:'ovary', correct:'ovary', pct:[77.5,54.4] },
  { id:'anther', correct:'anther', pct:[7.5,15.3] },
  { id:'filament', correct:'filament', pct:[4.5,39.7] },
  { id:'petal', correct:'petal', pct:[85,73.5] },
  { id:'sepal', correct:'sepal', pct:[85,88.2] },
  { id:'receptacle', correct:'receptacle', pct:[77.5,77.9] },
  { id:'stamen', correct:'stamen', pct:[4.5,58.8] },
  { id:'pistil', correct:'pistil', pct:[77.5,44.1] },
];
const WORDS = ['anther','filament','ovary','petal','pistil','receptacle','sepal','stamen','stigma','style'];
let labels = {};
let selectedWord = null;

function buildWordBank() {
  const bank = document.getElementById('wordBank');
  bank.innerHTML = '';
  WORDS.forEach(w => {
    const chip = document.createElement('div');
    chip.className = 'word-chip';
    chip.textContent = w;
    chip.dataset.word = w;
    if (Object.values(labels).includes(w)) {
      chip.classList.add('used');
    }
    if (selectedWord === w) {
      chip.classList.add('selected');
    }
    chip.onclick = function() {
      if (Object.values(labels).includes(w)) return;
      selectedWord = selectedWord === w ? null : w;
      buildWordBank();
      updateDropZones();
    };
    bank.appendChild(chip);
  });
}

function buildDropZones() {
  const wrap = document.getElementById('diagramWrap');
  // Remove old zones
  wrap.querySelectorAll('.drop-zone').forEach(z => z.remove());
  PARTS.forEach(part => {
    const zone = document.createElement('div');
    zone.className = 'drop-zone';
    zone.id = 'dz-' + part.id;
    zone.style.left = part.pct[0] + '%';
    zone.style.top = part.pct[1] + '%';
    zone.textContent = labels[part.id] || 'tap here';
    zone.onclick = function() {
      if (selectedWord) {
        // Remove word from any other slot
        Object.keys(labels).forEach(k => { if (labels[k] === selectedWord) delete labels[k]; });
        labels[part.id] = selectedWord;
        selectedWord = null;
        buildWordBank();
        updateDropZones();
        checkDiagram();
      }
    };
    wrap.appendChild(zone);
  });
  updateDropZones();
}

function updateDropZones() {
  PARTS.forEach(part => {
    const zone = document.getElementById('dz-' + part.id);
    if (!zone) return;
    const val = labels[part.id];
    zone.textContent = val || 'tap here';
    zone.className = 'drop-zone';
    if (val) {
      zone.classList.add(val === part.correct ? 'correct' : 'wrong');
    } else if (selectedWord) {
      zone.classList.add('highlight');
    }
  });
}

function checkDiagram() {
  const total = PARTS.length;
  const correct = PARTS.filter(p => labels[p.id] === p.correct).length;
  const filled = Object.keys(labels).length;
  const box = document.getElementById('diagramResult');
  if (filled === total) {
    if (correct === total) {
      box.innerHTML = '<div class="result-box perfect">🌟 Perfect! All 10 parts labeled correctly!</div>';
    } else {
      box.innerHTML = '<div class="result-box partial">' + correct + '/10 correct — try swapping the wrong ones!</div>';
    }
  } else {
    box.innerHTML = '';
  }
}

function resetDiagram() {
  labels = {};
  selectedWord = null;
  buildWordBank();
  buildDropZones();
  document.getElementById('diagramResult').innerHTML = '';
}

// SHORT ANSWER
function checkReady() {
  const btn = document.getElementById('btnSubmit');
  const a1 = document.getElementById('ans1').value.trim();
  const a2 = document.getElementById('ans2').value.trim();
  if (a1 && a2) {
    btn.classList.add('ready');
  } else {
    btn.classList.remove('ready');
  }
}

function submitAnswers() {
  const a1 = document.getElementById('ans1').value.trim();
  const a2 = document.getElementById('ans2').value.trim();
  if (!a1 || !a2) return;
  const correct = PARTS.filter(p => labels[p.id] === p.correct).length;
  document.getElementById('answerResult').innerHTML =
    '<div class="result-box submitted" style="margin-top:16px;">🌿 Great work! Review your answers above to make sure they\'re complete. Diagram score: ' + correct + '/10</div>';
}

// ============================================================
// ADAPTATIONS DRAG-AND-DROP MATCHING
// ============================================================
const ADAPT_PAIRS = [
  { id: 'r1', statement: 'Bears adapt to the cold winter climate by sleeping more.', answer: 'Hibernate' },
  { id: 'r2', statement: 'Birds fly south for the winter.',                          answer: 'Migrate' },
  { id: 'r3', statement: 'The king snake tricks its enemies by looking like the deadly coral snake.', answer: 'Mimicry' },
  { id: 'r4', statement: 'The snow hare blends in with its surroundings.',            answer: 'Camouflage' },
  { id: 'r5', statement: "Changes in an animal's habitat are usually the cause for this.", answer: 'Adaptation' },
  { id: 'r6', statement: 'Desert plants store water in their stems and leaves.',      answer: 'Structural Adaptation' },
];
const ADAPT_TERMS = ['Hibernate', 'Adaptation', 'Mimicry', 'Migrate', 'Camouflage', 'Structural Adaptation'];

let adaptDropped = {};   // rowId → term string
let adaptSelected = null; // for tap-mode
let adaptDragTerm = null; // for drag-mode
let adaptChecked = false;

function buildAdaptBank() {
  const bank = document.getElementById('adaptBank');
  bank.innerHTML = '';
  ADAPT_TERMS.forEach(term => {
    const chip = document.createElement('div');
    chip.className = 'adapt-chip';
    chip.textContent = term;
    chip.dataset.term = term;
    const usedInRow = Object.values(adaptDropped).includes(term);
    if (usedInRow) chip.classList.add('used');
    if (adaptSelected === term) chip.classList.add('tap-selected');

    // Drag events
    chip.draggable = !usedInRow;
    chip.addEventListener('dragstart', e => {
      if (usedInRow) { e.preventDefault(); return; }
      adaptDragTerm = term;
      chip.classList.add('dragging');
      e.dataTransfer.effectAllowed = 'move';
      e.dataTransfer.setData('text/plain', term);
    });
    chip.addEventListener('dragend', () => {
      adaptDragTerm = null;
      chip.classList.remove('dragging');
    });

    // Tap/click for mobile
    chip.addEventListener('click', () => {
      if (usedInRow || adaptChecked) return;
      adaptSelected = adaptSelected === term ? null : term;
      buildAdaptBank();
      highlightDrops();
    });

    bank.appendChild(chip);
  });
}

function buildAdaptRows() {
  const tbody = document.getElementById('matchBody');
  tbody.innerHTML = '';
  ADAPT_PAIRS.forEach(pair => {
    const tr = document.createElement('tr');
    tr.className = 'match-row';

    const tdStmt = document.createElement('td');
    tdStmt.className = 'match-statement';
    tdStmt.textContent = pair.statement;

    const tdArrow = document.createElement('td');
    tdArrow.className = 'match-arrow';
    tdArrow.innerHTML = '&#8594;';

    const tdDrop = document.createElement('td');
    tdDrop.className = 'match-drop' + (adaptDropped[pair.id] ? ' filled' : '');
    tdDrop.id = 'adrop-' + pair.id;
    tdDrop.textContent = adaptDropped[pair.id] || 'drop here';

    // Drag-over / drop events
    tdDrop.addEventListener('dragover', e => {
      if (!adaptDragTerm) return;
      e.preventDefault();
      e.dataTransfer.dropEffect = 'move';
      tdDrop.classList.add('drag-over');
    });
    tdDrop.addEventListener('dragleave', () => tdDrop.classList.remove('drag-over'));
    tdDrop.addEventListener('drop', e => {
      e.preventDefault();
      tdDrop.classList.remove('drag-over');
      const term = e.dataTransfer.getData('text/plain') || adaptDragTerm;
      if (!term || adaptChecked) return;
      placeTerm(pair.id, term);
    });

    // Tap-to-place
    tdDrop.addEventListener('click', () => {
      if (!adaptSelected || adaptChecked) return;
      placeTerm(pair.id, adaptSelected);
      adaptSelected = null;
    });

    tr.appendChild(tdStmt);
    tr.appendChild(tdArrow);
    tr.appendChild(tdDrop);
    tbody.appendChild(tr);
  });
}

function placeTerm(rowId, term) {
  // Remove term from any previous slot
  Object.keys(adaptDropped).forEach(k => { if (adaptDropped[k] === term) delete adaptDropped[k]; });
  adaptDropped[rowId] = term;
  buildAdaptBank();
  buildAdaptRows();
  highlightDrops();
  document.getElementById('adaptResult').innerHTML = '';
  adaptChecked = false;
}

function highlightDrops() {
  ADAPT_PAIRS.forEach(pair => {
    const drop = document.getElementById('adrop-' + pair.id);
    if (!drop) return;
    drop.classList.remove('drag-over');
    if (adaptSelected && !adaptDropped[pair.id]) {
      drop.classList.add('drag-over');
    } else {
      drop.classList.remove('drag-over');
    }
  });
}

function checkAdapt() {
  const allFilled = ADAPT_PAIRS.every(p => adaptDropped[p.id]);
  if (!allFilled) {
    document.getElementById('adaptResult').innerHTML =
      '<div class="result-box partial" style="margin-top:12px;">Fill in all 6 boxes first!</div>';
    return;
  }
  adaptChecked = true;
  let correct = 0;
  ADAPT_PAIRS.forEach(pair => {
    const drop = document.getElementById('adrop-' + pair.id);
    if (!drop) return;
    drop.classList.remove('filled', 'drag-over');
    if (adaptDropped[pair.id] === pair.answer) {
      drop.classList.add('correct-ans');
      correct++;
    } else {
      drop.classList.add('wrong-ans');
    }
  });
  const total = ADAPT_PAIRS.length;
  const box = document.getElementById('adaptResult');
  if (correct === total) {
    box.innerHTML = '<div class="result-box perfect" style="margin-top:12px;">🌟 Perfect! All 6 correct!</div>';
  } else {
    box.innerHTML = '<div class="result-box partial" style="margin-top:12px;">' + correct + '/' + total +
      ' correct — red boxes need a new answer. Click Reset to try again.</div>';
  }
}

function resetAdapt() {
  adaptDropped = {};
  adaptSelected = null;
  adaptDragTerm = null;
  adaptChecked = false;
  buildAdaptBank();
  buildAdaptRows();
  document.getElementById('adaptResult').innerHTML = '';
}

// INIT
buildWordBank();
buildDropZones();
buildAdaptBank();
buildAdaptRows();
</script>
</body>
</html>
