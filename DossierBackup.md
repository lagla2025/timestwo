# Dossier Ceremony Backup
Saved Apr 17 2026 before full rip-out. Laura decided the dossier ceremony was OTT and removed entirely in favor of a clean mini brief.

## What was removed

The dossier ceremony was a two-state animated reveal on Screens 24 and 25:
- State 1: Big manila folder with red string tied horizontally, CLASSIFIED rubber stamp angled in the corner, DOSSIER printed on the front, "Subject: Cian/Saoirse, 24/23" label.
- Tap Open → red string unspools left-to-right over 3.25s, folder flap lifts, brief content fades in.
- State 2: Tone label, name/age, three descriptors.
- Second button: "More →" navigates to full reveal (Screen 11/14).

Also removed: CLASSIFIED rubber stamps in nav bar (Screens 10, 11, 12, 14) and Jinx CTAs on Screens 18/19.

## Why it was removed

Laura's read: "the dossier is OTT. lose it." Simpler clean brief serves better, especially for the main demographic. Men likely tap the puzzle direct anyway. Women who want the ceremonial path can get a simpler brief. LinkedIn/Meta partnership will carry the "deeper sleuth" function in Phase 2.

## To restore

Copy this file's code blocks back into index.html:
1. Replace the current Screen 24 block with the backed-up block below
2. Same for Screen 25
3. Paste the animation CSS + JS block before </body>

## SCREEN 24 (Cian's dossier)

```html
<!-- ══════════════════════════════════════════════════════════
     SCREEN 24 — The Dossier (two-state reveal)
═══════════════════════════════════════════════════════════ -->
<div class="screen s2-bg" id="screen24" style="display:none;overflow:hidden;flex-direction:column;height:100%">
  <div class="status-bar" style="background:#faf7f2"><span>9:41</span><span>●●● &#9679; &#9679;&#9679;</span></div>
  <div class="intv-back-btn" onclick="backToLanding()">&#9664; Menu</div>

  <div class="s2-bar" style="padding-top:14px">
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:3px">
      <div class="s2-wordmark">Times Two</div>
      <div style="font-size:10px;color:#b8960a;font-weight:700;text-transform:uppercase;letter-spacing:1px">The Brief</div>
    </div>
    <div class="s2-rule-wrap"><div class="s2-rule-line"></div><div class="s2-rule-gap"></div><div class="s2-rule-line"></div></div>
  </div>

  <!-- Stacked body: dossier visible first, brief fades in after unspool -->
  <div class="dossier-body" id="dossier-body-24" style="flex:1;display:flex;flex-direction:column;justify-content:center;align-items:center;padding:0 24px;text-align:center;position:relative">

    <!-- State 1: dossier folder -->
    <div class="dossier-stage" id="dossier-stage-24" style="display:flex;flex-direction:column;align-items:center;transition:opacity 0.5s ease">
      
      <svg class="dossier-folder" viewBox="0 0 280 200" width="280" height="200" xmlns="http://www.w3.org/2000/svg" style="overflow:visible;display:block">
        <!-- Folder back -->
        <rect class="folder-back" x="10" y="20" width="260" height="170" rx="3" fill="#b88548" stroke="#6a4518" stroke-width="1.5"/>
        <!-- Folder tab -->
        <rect class="folder-tab" x="30" y="10" width="90" height="15" rx="2" fill="#c99a5c" stroke="#6a4518" stroke-width="1.2"/>
        <!-- Folder front/flap (this lifts on reveal) -->
        <g class="folder-flap">
          <rect x="10" y="20" width="260" height="170" rx="3" fill="#c99a5c" stroke="#6a4518" stroke-width="1.5"/>
          <!-- Horizontal rules suggesting file labels -->
          <line x1="30" y1="55" x2="260" y2="55" stroke="#6a4518" stroke-width="0.4" opacity="0.35"/>
          <line x1="30" y1="70" x2="260" y2="70" stroke="#6a4518" stroke-width="0.4" opacity="0.35"/>
          <!-- CLASSIFIED stamp in the top-right, angled -->
          <g transform="translate(195 130) rotate(-14)">
            <rect x="-75" y="-22" width="150" height="42" fill="none" stroke="#b32020" stroke-width="4" rx="2"/>
            <text x="0" y="9" text-anchor="middle" font-family="Impact, Helvetica, sans-serif" font-size="19" font-weight="900" fill="#b32020" letter-spacing="2.8">CLASSIFIED</text>
          </g>
          <!-- DOSSIER label top -->
          <text x="140" y="105" text-anchor="middle" font-family="Courier New, monospace" font-size="20" font-weight="900" fill="#6a4518" letter-spacing="5" opacity="0.9">DOSSIER</text>
          <text x="140" y="120" text-anchor="middle" font-family="Georgia, serif" font-size="8" fill="#6a4518" letter-spacing="2" opacity="0.65" font-style="italic">Subject: Cian, 24</text>
        </g>
        <!-- Red string tied across horizontally with unspool animation -->
        <g class="folder-string">
          <!-- Main string - uses stroke-dashoffset for retract animation -->
          <line class="string-line" x1="0" y1="105" x2="280" y2="105" stroke="#b32020" stroke-width="2.6" stroke-linecap="round" stroke-dasharray="280" stroke-dashoffset="0"/>
          <!-- Knot group - translates right as string retracts -->
          <g class="string-knot">
            <circle cx="140" cy="105" r="6" fill="#b32020" stroke="#7a0c0c" stroke-width="0.8"/>
            <path d="M 134 101 Q 130 95 126 97 M 146 101 Q 150 95 154 97" stroke="#b32020" stroke-width="2" stroke-linecap="round" fill="none"/>
          </g>
        </g>
      </svg>
    
      <div style="font-family:Georgia,serif;font-style:italic;font-size:11px;color:#8a7d6b;margin-top:18px;letter-spacing:0.3px">Compiled by your Wingman.</div>
    </div>

    <!-- State 2: brief content (hidden initially) -->
    <div class="brief-stage" id="brief-stage-24" style="position:absolute;top:0;left:0;right:0;bottom:0;display:flex;flex-direction:column;justify-content:center;align-items:center;padding:0 28px;opacity:0;pointer-events:none;transition:opacity 0.6s ease 0.3s">
      <div style="font-size:10px;font-weight:700;color:#9a8230;text-transform:uppercase;letter-spacing:1.6px;margin-bottom:18px">
        Cian&rsquo;s Wingman &middot; Straight shooter
      </div>
      <div style="font-family:'Playfair Display',Georgia,serif;font-size:40px;font-weight:900;color:#1a1a1a;line-height:1;margin-bottom:4px;letter-spacing:-1px">
        Cian,&nbsp;24
      </div>
      <div style="font-family:Georgia,serif;font-style:italic;font-size:16px;color:#5a5148;line-height:1.4;margin-top:14px;max-width:300px">
        Architectural grad, straight shooter, mad sports fan.
      </div>
    </div>

  </div>

  <!-- Button row (swaps between Open and More) -->
  <div style="padding:20px 24px 28px;background:#faf7f2">
    <button id="dossier-btn-24" onclick="openDossier(24, 11)" style="width:100%;padding:15px;font-family:'Zilla Slab',Georgia,serif;font-size:13px;font-weight:700;letter-spacing:3px;text-transform:uppercase;background:#1a1a1a;color:#f0ece4;border:none;border-radius:2px;cursor:pointer;transition:background 0.15s" onmouseover="this.style.background='#333'" onmouseout="this.style.background='#1a1a1a'">
      Open
    </button>
    <div style="text-align:center;font-size:10px;color:#9a8f82;margin-top:10px;font-style:italic;font-family:Georgia,serif" id="dossier-cta-sub-24">
      Your Wingman saved this for you.
    </div>
  </div>

</div>


```

## SCREEN 25 (Saoirse's dossier)

```html
<!-- ══════════════════════════════════════════════════════════
     SCREEN 25 — The Dossier (two-state reveal)
═══════════════════════════════════════════════════════════ -->
<div class="screen s2-bg" id="screen25" style="display:none;overflow:hidden;flex-direction:column;height:100%">
  <div class="status-bar" style="background:#faf7f2"><span>9:41</span><span>●●● &#9679; &#9679;&#9679;</span></div>
  <div class="intv-back-btn" onclick="backToLanding()">&#9664; Menu</div>

  <div class="s2-bar" style="padding-top:14px">
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:3px">
      <div class="s2-wordmark">Times Two</div>
      <div style="font-size:10px;color:#b8960a;font-weight:700;text-transform:uppercase;letter-spacing:1px">The Brief</div>
    </div>
    <div class="s2-rule-wrap"><div class="s2-rule-line"></div><div class="s2-rule-gap"></div><div class="s2-rule-line"></div></div>
  </div>

  <!-- Stacked body: dossier visible first, brief fades in after unspool -->
  <div class="dossier-body" id="dossier-body-25" style="flex:1;display:flex;flex-direction:column;justify-content:center;align-items:center;padding:0 24px;text-align:center;position:relative">

    <!-- State 1: dossier folder -->
    <div class="dossier-stage" id="dossier-stage-25" style="display:flex;flex-direction:column;align-items:center;transition:opacity 0.5s ease">
      
      <svg class="dossier-folder" viewBox="0 0 280 200" width="280" height="200" xmlns="http://www.w3.org/2000/svg" style="overflow:visible;display:block">
        <!-- Folder back -->
        <rect class="folder-back" x="10" y="20" width="260" height="170" rx="3" fill="#b88548" stroke="#6a4518" stroke-width="1.5"/>
        <!-- Folder tab -->
        <rect class="folder-tab" x="30" y="10" width="90" height="15" rx="2" fill="#c99a5c" stroke="#6a4518" stroke-width="1.2"/>
        <!-- Folder front/flap (this lifts on reveal) -->
        <g class="folder-flap">
          <rect x="10" y="20" width="260" height="170" rx="3" fill="#c99a5c" stroke="#6a4518" stroke-width="1.5"/>
          <!-- Horizontal rules suggesting file labels -->
          <line x1="30" y1="55" x2="260" y2="55" stroke="#6a4518" stroke-width="0.4" opacity="0.35"/>
          <line x1="30" y1="70" x2="260" y2="70" stroke="#6a4518" stroke-width="0.4" opacity="0.35"/>
          <!-- CLASSIFIED stamp in the top-right, angled -->
          <g transform="translate(195 130) rotate(-14)">
            <rect x="-75" y="-22" width="150" height="42" fill="none" stroke="#b32020" stroke-width="4" rx="2"/>
            <text x="0" y="9" text-anchor="middle" font-family="Impact, Helvetica, sans-serif" font-size="19" font-weight="900" fill="#b32020" letter-spacing="2.8">CLASSIFIED</text>
          </g>
          <!-- DOSSIER label top -->
          <text x="140" y="105" text-anchor="middle" font-family="Courier New, monospace" font-size="20" font-weight="900" fill="#6a4518" letter-spacing="5" opacity="0.9">DOSSIER</text>
          <text x="140" y="120" text-anchor="middle" font-family="Georgia, serif" font-size="8" fill="#6a4518" letter-spacing="2" opacity="0.65" font-style="italic">Subject: Saoirse, 23</text>
        </g>
        <!-- Red string tied across horizontally with unspool animation -->
        <g class="folder-string">
          <!-- Main string - uses stroke-dashoffset for retract animation -->
          <line class="string-line" x1="0" y1="105" x2="280" y2="105" stroke="#b32020" stroke-width="2.6" stroke-linecap="round" stroke-dasharray="280" stroke-dashoffset="0"/>
          <!-- Knot group - translates right as string retracts -->
          <g class="string-knot">
            <circle cx="140" cy="105" r="6" fill="#b32020" stroke="#7a0c0c" stroke-width="0.8"/>
            <path d="M 134 101 Q 130 95 126 97 M 146 101 Q 150 95 154 97" stroke="#b32020" stroke-width="2" stroke-linecap="round" fill="none"/>
          </g>
        </g>
      </svg>
    
      <div style="font-family:Georgia,serif;font-style:italic;font-size:11px;color:#8a7d6b;margin-top:18px;letter-spacing:0.3px">Compiled by your Wingman.</div>
    </div>

    <!-- State 2: brief content (hidden initially) -->
    <div class="brief-stage" id="brief-stage-25" style="position:absolute;top:0;left:0;right:0;bottom:0;display:flex;flex-direction:column;justify-content:center;align-items:center;padding:0 28px;opacity:0;pointer-events:none;transition:opacity 0.6s ease 0.3s">
      <div style="font-size:10px;font-weight:700;color:#9a8230;text-transform:uppercase;letter-spacing:1.6px;margin-bottom:18px">
        Saoirse&rsquo;s Wingman &middot; Cheeky
      </div>
      <div style="font-family:'Playfair Display',Georgia,serif;font-size:40px;font-weight:900;color:#1a1a1a;line-height:1;margin-bottom:4px;letter-spacing:-1px">
        Saoirse,&nbsp;23
      </div>
      <div style="font-family:Georgia,serif;font-style:italic;font-size:16px;color:#5a5148;line-height:1.4;margin-top:14px;max-width:300px">
        Product Manager, cheeky, Spelling Bee Queen.
      </div>
    </div>

  </div>

  <!-- Button row (swaps between Open and More) -->
  <div style="padding:20px 24px 28px;background:#faf7f2">
    <button id="dossier-btn-25" onclick="openDossier(25, 14)" style="width:100%;padding:15px;font-family:'Zilla Slab',Georgia,serif;font-size:13px;font-weight:700;letter-spacing:3px;text-transform:uppercase;background:#1a1a1a;color:#f0ece4;border:none;border-radius:2px;cursor:pointer;transition:background 0.15s" onmouseover="this.style.background='#333'" onmouseout="this.style.background='#1a1a1a'">
      Open
    </button>
    <div style="text-align:center;font-size:10px;color:#9a8f82;margin-top:10px;font-style:italic;font-family:Georgia,serif" id="dossier-cta-sub-25">
      Your Wingman saved this for you.
    </div>
  </div>

</div>
```

## Animation CSS + JS

```html
<style>
  /* Dossier two-state reveal animation */
  .dossier-stage { transition: opacity 0.5s ease 3.6s; }
  .dossier-folder { overflow: visible; }

  /* String: stroke-dashoffset animates the line retracting, knot moves right off-screen */
  .string-line { transition: stroke-dashoffset 3.25s ease-in-out, opacity 0.3s ease 2.9s; }
  .string-knot { transition: transform 3.25s ease-in-out, opacity 0.3s ease 2.9s; transform-origin: 140px 105px; }

  /* Folder flap lifts AFTER string is gone */
  .folder-flap {
    transform-origin: 10px 20px;
    transition: transform 0.8s cubic-bezier(0.22, 1, 0.36, 1) 3s;
  }

  /* Revealed state */
  .screen.dossier-revealed .string-line { stroke-dashoffset: 280; opacity: 0; }
  .screen.dossier-revealed .string-knot { transform: translateX(150px) rotate(25deg); opacity: 0; }
  .screen.dossier-revealed .folder-flap { transform: perspective(500px) rotateX(-160deg); opacity: 0.25; }
  .screen.dossier-revealed .dossier-stage { opacity: 0; pointer-events: none; }
  .screen.dossier-revealed .brief-stage {
    opacity: 1 !important;
    pointer-events: auto !important;
    transition: opacity 0.6s ease 3.9s !important;
  }
</style>
<script>
  function openDossier(screenNum, revealTarget) {
    var screen = document.getElementById('screen' + screenNum);
    var btn = document.getElementById('dossier-btn-' + screenNum);
    var cta = document.getElementById('dossier-cta-sub-' + screenNum);
    if (!screen || !btn) return;

    if (!screen.classList.contains('dossier-revealed')) {
      // First tap: trigger the unspool animation
      screen.classList.add('dossier-revealed');
      // After the animation plays, swap the button to "More"
      setTimeout(function() {
        btn.innerHTML = 'More &nbsp;&rarr;';
        btn.setAttribute('onclick', 'show(' + revealTarget + ')');
        if (cta) cta.textContent = 'The full file.';
      }, 4700);
    } else {
      // Shouldn't happen (onclick rewritten above) but safety fallback
      show(revealTarget);
    }
  }

  // Reset dossier state each time these screens are shown
  (function(){
    var oldShow = window.show;
    window.show = function(n) {
      oldShow(n);
      // When entering 24 or 25, reset to dossier-closed state
      if (n === 24 || n === 25) {
        var s = document.getElementById('screen' + n);
        if (s) {
          s.classList.remove('dossier-revealed');
          var btn = document.getElementById('dossier-btn-' + n);
          var cta = document.getElementById('dossier-cta-sub-' + n);
          if (btn) {
            btn.innerHTML = 'Open';
            var target = (n === 24) ? 11 : 14;
            btn.setAttribute('onclick', 'openDossier(' + n + ', ' + target + ')');
          }
          if (cta) cta.textContent = 'Your Wingman saved this for you.';
        }
      }
    };
  })();
</script>
```

## Key decisions baked in (for future reference)

- String animation: stroke-dashoffset 280 over 3.25s ease-in-out
- Knot translate: translateX(150px) rotate(25deg)
- Flap lift: rotateX(-160deg) at 3s delay, 0.8s duration
- Total ceremony: ~4.7 seconds
- CLASSIFIED stamp: Impact font, -12deg angle, 108x52 viewBox, 104w rect
- "Check it out" CTAs (keep these! upgraded from "Curious? x2")
  - Saoirse (cheeky): "Go on. Check it out."
  - Cian (straight shooter): "Check it out."

## Version range when this lived

v42 (Apr 17 2026) through v48 — dossier was live in the prototype for this window.
