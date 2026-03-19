# Times Two — Master Brief
### Synthesised from design sessions, February 2026
### Laura Glassman · Trinity College Dublin MSc Capstone + NVC

---

## THE IDEA IN ONE SENTENCE

Times Two matches people based on what they actually read, play, and listen to — not what they say about themselves. It lives inside the publisher ecosystem, not alongside it. The content is the profile.

---

## THE ORIGIN STORY / FRAMING

Dating used to start in the classifieds. Someone placed a notice — a few lines, a box number, a self-description distilled to its essence. Strangers read it on the train, circled one with a red pen, wrote a letter.

The mechanism was always content-based. You revealed yourself through what you wrote. The reader self-selected through what they chose to respond to.

Times Two is the same impulse, rebuilt for a digital publisher ecosystem. The classified ad is replaced by a reading history. The box number is replaced by a match signal. The red pen circle is replaced by an algorithm that noticed something you didn't.

**"Dating started in the classifieds. We just updated the algorithm."**

This line is the brand in one sentence. Use it everywhere.

---

## THE CORE INSIGHT (MOST IMPORTANT)

### Stated identity vs. revealed identity

Every existing dating platform is built on **stated identity** — what people *say* about themselves. Photos that perform. Bios that curate. Prompts that invite self-promotion. The result is a presentation, not a person.

Times Two is built on **revealed identity** — what people *actually* do. What they read at 7am on a Tuesday. Which Connections category they always save for last. Whether they finish long reads or just save them. Whether they listened to the same Daily episode on the same morning commute.

You cannot game revealed identity the way you can game a bio. The algorithm sees behaviour, not performance.

This is the theoretical core. This is what links to the academic literature. This is the mechanism your capstone research is testing.

---

## THE RESEARCH DESIGN (CAPSTONE)

### Study design
Qualitative user research comparing two introduction mechanisms for the same person:
- **Condition A:** Traditional Hinge-style profile (photo, prompts, self-written bio)
- **Condition B:** Content-based activity feed (what the person has read, played, listened to this week)

**Key methodological decision:** The same person (Saoirse/Cian, gender-flipped by participant) is introduced both ways. This isolates the *introduction mechanism* as the variable, not the person being introduced.

### Interview structure (30-35 minutes)
1. Baseline — dating app experience, content habits
2. Traditional mockup — 7-8 minutes
3. Content-based mockup — 8-10 minutes
4. Direct comparison — behavioural intent, message substance, depth trajectory
5. Mechanism articulation — why does one work differently?
6. Data & trust — comfort with opt-in behavioural data
7. Validity tests — edge cases, scalability, platform context

### Key research questions
- Does shared content consumption create faster conversational readiness?
- Does revealed identity feel more or less authentic than stated identity?
- What is the expected depth trajectory of conversations started each way?
- What are the trust and governance expectations around behavioural data used for matching?
- Does the publisher context (NYT/Guardian) affect willingness to engage?

### The mechanism probe (critical for theory)
*"When you look at the content that someone has engaged with, what does that tell you about them? How is that different from what a bio tells you?"*

This is where your most theoretically interesting data will emerge. Students will articulate the stated/revealed identity distinction without you naming it — and that articulation is your qualitative evidence.

### What to measure
- Time taken to articulate a first message (each condition)
- Specificity of opening message (generic vs. content-specific)
- Expected conversation trajectory (1 exchange vs. sustained)
- Comfort with data use (opt-in framing as variable)
- Preference and stated adoption likelihood

### Profile assignment
- Female participants see: **Cian** (male profile)
- Male participants see: **Saoirse** (female profile)

---

## THE PROTOTYPE

### Structure (7 screens)
1. **Screen 1 — Hinge profile** (research stimulus only, not part of Times Two product)
2. **Screen 2 — Activity feed** (the Times Two core experience)
3. **Screen 3 — Chat** (conversation started via content overlap)
4. **Screen 4 — Concierge / Echo** (The Desk match notification)
5. **Screen 5 — NYT Onboarding** (PERSONALS classifieds easter egg)
6. **Screen 6 — Guardian Onboarding** (Guardian-specific version)
7. **Screen 7 — Pitch Panel** (investor/partner facing, scrollable)

### Key design decisions and rationale

**The activity feed over the profile**
The feed shows what someone did this week — not who they say they are. Cards show: article read, game played, podcast listened to. Each card shows whether the overlap is shared (✓ dark text) or Saoirse-only (› grey text). The distinction is quiet, not alarmed.

**The lead card (Echo / Match signal)**
One elevated card at the top of the feed — full editorial treatment, the item that triggered the match notification. The algorithm surfaces *one* thing, not everything. Scarcity makes it feel curated, not surveilled.

**The Desk / Echo mechanic**
Working name: "The Desk" (Ann Landers for the 21st century). When the algorithm notices a meaningful overlap — same article, same day, same city, minutes apart — it sends a notice. Not a match. Not a like. A *notice*. The language is deliberately understated.

*"The Desk caught an echo. Cian read the same article you saved on Tuesday — 4 minutes apart, 0.3 miles from each other. He sent a note."*

**PERSONALS classifieds**
The easter egg on the onboarding screens. Aged newsprint aesthetic, three columns of personal ads, a red hand-drawn lipstick circle around the circled listing (WELL-READ, 24 — that's you). Caption: *"Dating started in the classifieds. We just updated the algorithm."*

Ad headlines are double entendres — they map to the app's content categories AND describe a personality type:
- **QUEEN BEE** (Spelling Bee + personality)
- **OP**inionat**ED** (Op-Ed section + personality, caps spell OP-ED)
- **HOME COOK** (Cooking section + personality)
- **ATHLETIC** (Sports section + personality)
- **WELL-READ** (the circled listing — the user)
- **CULTURE VULTURE, NIGHT OWL, LONG-DISTANCE, EARLY EDITION** (supporting cast)

**Font:** Zilla Slab — heavy slab serif, closest available to NYT's Cheltenham, editorial weight
**Colour:** Warm newsprint (`#F4EFE5`), dark navy (`#1a1a2e`), no red in the UI (red reserved for the lipstick circle only)
**Buttons:** Newspaper grey tones — inactive charcoal, active warm newsprint

**Guardian version**
Same mechanics, different publisher skin. Navy `#052962` instead of NYT black. Guardian-specific content categories: LONG READ, FOOTBALL MAD, CLIMATE CURIOUS, COMMENTATOR, PODCAST DEVOTEE, WEEKEND COOK (Ottolenghi is a verb), EARLY EDITION. The Guardian headline: *"The Guardian ran personals for 40 years. We just made them smarter."*

**Easter eggs (for fellow obsessives)**
- VIVID — the notorious Wordle answer that ended thousands of streaks (Saoirse lost her 312-day streak on it)
- JUKEBOX — a real NYT Spelling Bee pangram
- BLANCHED — the queen word Saoirse and Cian both found
- STARE — a known optimal Wordle opener
- Wordle scores stated as "got it in 3" not "3/6" (the /6 is what journalists write, not players)
- Connections: "purple group last" — the trap category, always hardest
- The Daily at 1.4x — the knowing detail about how people actually listen
- Browser tab title: "Times Two — ✦ BLANCHED ✦" (today's queen word)
- Box numbers in the classifieds = real Wordle answer numbers from infamous days

---

## THE COMMERCIAL PITCH

### For The New York Times — three arguments stacked

**① Retention**
A subscriber who meets someone meaningful through their NYT account has an emotional anchor no price promotion can replicate. You cannot churn out of something that introduced you to your partner. The subscription becomes load-bearing in the user's life.

**② Student LTV — the sleeper argument**
17M+ students access NYT free through academic institutions. Most live in the Games tab — Wordle, Connections, Spelling Bee. They are digitally native, fluent in dating apps, and largely unaware of the broader NYT ecosystem.

Times Two meets them exactly where they are. When the free tier expires and they're 24 and employed, the NYT is no longer a homework resource. It's the place where something real happened. That's a fundamentally different conversion conversation. The LTV window over a 40-year subscription relationship is enormous.

**③ New demographic pipeline**
Gen Z is the hardest demographic for legacy publishers to acquire. Times Two gives them a social reason to stay in the ecosystem — and to come back daily. Connections is already more popular with Gen Z than Spelling Bee (which skews older). The games tab is already the acquisition layer. Times Two is the retention layer on top of it.

### For The Guardian — a different story

The Guardian paradox: deeply loyal readers, progressive brand identity, strong international reach — but has never found a digital product that matches the warmth of the print experience.

Times Two is on-brand in a way few features could be. The Guardian reader self-selects for values, curiosity, and engagement with ideas. That's exactly the matching signal you need.

Unlike NYT (which has games infrastructure already built), The Guardian gets to *pioneer* something. *"We built a feature that turns reading together into meeting each other"* — that's a Guardian front page story in itself. It's a digital transformation narrative they can tell publicly, which matters for their supporter model.

### The paywall as a pre-qualification filter (THE KEY INSIGHT FOR THE PITCH)

Most dating platforms start with nothing. They try to infer values, education, curiosity, and political orientation through profile fields that people game.

NYT and Guardian subscribers arrive **pre-qualified by the act of subscribing**. The paywall is an inadvertent filter. Someone paying £$20+/month for news and ideas in 2026 — when free content is everywhere — is already signalling:

- **Education** — implied, not stated
- **Urban orientation** — the readership skews heavily metropolitan
- **Political disposition** — broadly progressive, empirically-minded
- **Curiosity** — paying to be informed, not just entertained
- **Financial intentionality** — not wealthy necessarily, but deliberate

None of this needs to be collected. It's already true by virtue of the subscription existing.

**This is the inversion of the Match.com problem.** Match has width but no depth — a huge pool about whom you know almost nothing except desire. NYT has a smaller pool about whom you already know quite a lot before they say a single word. The common ground exists *before the first message*. Times Two makes it visible.

The pool is smaller. It's also pre-sorted in ways no algorithm could replicate from scratch.

---

## THE DATA ARCHITECTURE (TECH PITCH)

### What you need (and don't need)

**You do NOT need:**
- Integration with NYT's ad-targeting martech stack (DFP, first-party segments, demographic enrichment)
- Third-party data licensing (Experian, Acxiom)
- Cross-platform behavioural tracking

**You DO need:**
- One read-only OAuth scope — the subscriber's own activity data
- Article read history (already logged in NYT accounts)
- Game completions and scores (Wordle, Spelling Bee, Connections — all logged)
- Podcast listen history (The Daily play history)
- Subscription metadata: city, age range, tenure

### The architecture

Times Two sits as a **consent-gated API layer**. The subscriber explicitly opts in, grants read-only access to their own activity data, and that data is processed *only* for matching. It never flows back to NYT's ad system.

Think "Sign in with NYT" but for your reading fingerprint.

### The matching algorithm (three signals)

1. **Content overlap** — article slugs, game completions, podcast episode IDs. Two people who completed the same Connections puzzle on the same day and read the same three articles this week are a strong signal. You don't need to know why — the overlap is the evidence.

2. **Timing + proximity** — if both engaged within hours of each other and their city matches, that's the serendipity layer. *"You were both reading this on Tuesday morning in Dublin."* Not surveillance — coincidence, surfaced.

3. **Subscription metadata** — age range, city, tenure. Already held by NYT. Used with subscriber consent for their benefit, not the advertiser's.

### The data USP (say this in every pitch)

*"Every other platform tracks you for their benefit. This one works for yours."*

Under GDPR and CCPA, this is the cleanest possible basis for data processing: a subscriber consenting to their own data being used *for their own benefit*. The publisher's brand stays clean. The user has genuine agency. The regulator has nothing to object to.

The pitch to NYT's product team is not "give us your martech stack." It is: **"We need one OAuth scope: read-only access to reading history. Everything else we build."** That's a much easier yes.

---

## THE BROADER VISION

### The Times Two ecosystem (the full picture)

```
PERSONALS classifieds (the historical anchor)
        ↓
Times Two matching engine (content overlap + proximity + timing)
        ↓
The Desk / Echo notifications (Ann Landers for the 21st century)
        ↓
Chat (conversation scaffolded by shared content)
        ↓
Modern Love (NYT's most beloved franchise — editorial layer)
        ↓
Wedding Announcements (aspiration + social proof layer)
        ↓
"How We Met" UGC feed (the TikTok layer — user-generated origin stories)
```

Times Two is not a dating feature. It is the **top of a content funnel that NYT already has the bottom of**. Modern Love has run since 2004. Wedding Announcements since the 1850s. The infrastructure exists. The acquisition mechanism is missing. Times Two is that mechanism.

Every successful match is a potential Modern Love essay, a potential Wedding Announcement, a potential 30-second video. **The content creates itself.** NYT becomes the place where the story starts *and* where it gets told.

### The wedge thesis (for VC pitch)

Dating is the test case. The mechanism is domain-agnostic.

If shared content consumption creates faster, more meaningful connection in the highest-stakes context (dating — where people are most motivated and most critical), the transfer to other domains is straightforward:

- **Workplaces** — colleagues reading the same industry thinking who've never been introduced. The algorithm surfaces the overlap. Serendipitous collaboration, without the awkward "we should grab coffee sometime" email.
- **Politics & civic life** — finding genuine common ground across apparent divides based on what people *actually* engage with, not what they claim to believe. Depolarisation through revealed shared interest.
- **Academia** — researchers in adjacent fields who cite the same papers but have never met.
- **Communities** — any platform with a logged content consumption layer (Spotify, Substack, Letterboxd, Goodreads) could run the same mechanic.

**The beachhead is dating. The market is any platform where shared intellectual identity creates value.**

---

## THE VIDEO (30-60 seconds)

### Concept
Movie scenes of meeting-via-content, meeting-via-shared-obsession. The montage makes the argument emotionally before the pitch makes it rationally.

### Scene list (suggested)
- **You've Got Mail** — two people whose entire relationship is built around books and a bookshop. The AOL inbox *is* the content feed.
- **Notting Hill** — he's a bookshop owner. First conversation is about a travel book.
- **Before Sunrise** — they meet on a train. The entire film is two people connecting entirely through conversation and shared curiosity.
- **Sleepless in Seattle** — a radio show (audio content) as the matching mechanism.
- **High Fidelity** — the mixtape as love language. Top 5 lists as personality disclosure.
- **Amélie** — she builds a relationship by leaving content trails for someone to follow.
- **(500) Days of Summer** — shared cultural references as the foundation of connection.
- **The Holiday** — bonding over film scores, him humming, her recognising.

### Structure
- Open: the PERSONALS classifieds — *"It started here"*
- Montage: 8-10 clips, 3-4 seconds each, music underneath
- Land: the prototype / the tagline
- Close: *"Dating started in the classifieds. We just updated the algorithm."*

### Production
Could be cut in CapCut or iMovie in an afternoon with the right clips. Needs a music track that's editorial without being generic — something piano-based, slightly nostalgic, not sentimental.

---

## THE PITCH DECK STRUCTURE (VC VERSION)

Suggested arc for the NVC pitch:

1. **The hook** — open with the classifieds. Show the PERSONALS page. *"This is how dating worked for 150 years."*
2. **The problem** — dating apps have width but no depth. The pool is huge, the signal is noise. Stated identity is gameable. (Match.com critique — huge pool, shallow signal, "available" is unverified)
3. **The insight** — revealed identity is more honest than stated identity. What you read at 7am tells the truth.
4. **The solution** — Times Two. Content is the profile. The publisher ecosystem is the pool.
5. **The pre-qualification argument** — the paywall as an inadvertent filter. Smaller pool, pre-sorted by values.
6. **The product** — prototype walkthrough. The activity feed. The Desk. The Echo.
7. **The ecosystem play** — Times Two → Modern Love → Wedding Announcements → UGC feed. NYT already has the bottom of this funnel.
8. **The commercial model** — publisher partnership (not B2C), OAuth API layer, retention + LTV + new demographic arguments.
9. **The data USP** — your data, working for you. GDPR-clean. No martech.
10. **The wedge** — dating is the test. The mechanism scales to workplaces, politics, academia.
11. **The market** — publisher subscriber bases globally. NYT 10M+ subscribers. Guardian 1M+ supporters. Substack, The Atlantic, The Economist...
12. **The ask** — [TBD — seed round? Development partnership? Research commercialisation?]

---

## NAMING NOTES

### The app: Times Two
- Double meaning: NYT ("Times") + the mathematical doubling + "it takes two"
- Works for Guardian version too (less obvious, but the concept holds)
- Clean, short, memorable

### The matching mechanic / bot
- Under discussion. Candidates: **The Desk** (current working title), **Echo**, **The Notice**, **The Brief**
- Ann Landers register — dry, precise, wise, never gushing
- *"The Desk caught an echo."* — current favourite formulation
- NOT: Love Doctor, Cupid, anything with heart emojis

### The match notification
- NOT "Match Signal" (too technical)
- NOT "Match" (Tinder-poisoned)
- Candidates: **Echo**, **Notice**, **Overlap**, **Thread**, **Parallel**
- Current working: **✦ Echo**

### Key copy lines (use these)
- *"Dating started in the classifieds. We just updated the algorithm."*
- *"The content is the profile."*
- *"Your data, working for you."*
- *"The Desk caught an echo."*
- *"The pool is smaller. It's also pre-sorted."*
- *"What you read at 7am tells the truth."*

---

## DELIVERABLES TRACKER

| Deliverable | Status | Deadline |
|-------------|--------|----------|
| HTML prototype (6 screens) | ✅ In progress | Interviews |
| Cian profile (Screen 1B + 2B) | ⏳ Awaiting photo | Interviews |
| Pitch panel (Screen 7) | ✅ Done | — |
| Capstone report (8,000 words) | ⏳ Not started | TBD |
| NVC submission | ⏳ Not started | TBD |
| VC pitch deck | ⏳ Not started | Next month |
| 30-60 sec video | ⏳ Not started | Next month |
| Interview guide | ✅ Done (PDF) | Interviews |

---

## PROTOTYPE SESSION LOG — for continuity across API interruptions

### File location
`/Users/lauraglassman/Desktop/TimesTwoPrototype/index.html`
Single-file HTML. ~2.4MB due to inline base64 images. Too large to read in one pass — use Python scripts for targeted edits, grep for structure inspection.

### Screen status (as of 24 Feb 2026)
| Screen | Description | Status |
|--------|-------------|--------|
| Screen 1 | Saoirse — Hinge-style traditional profile | ✅ LOCKED |
| Screen 2 | Saoirse — Activity feed (Times Two core) | ✅ LOCKED |
| Screen 3 | Chat | 🔄 Pending review |
| Screen 4 | Concierge / Echo / The Desk | 🔄 Pending review |
| Screen 5 | NYT onboarding (PERSONALS classifieds) | 🔄 Pending review |
| Screen 6 | Guardian onboarding | 🔄 Pending review |
| Screen 7 | Pitch panel (investor/partner facing) | 🔄 Pending review |
| Screen 8 | Cian — Hinge-style traditional profile | ✅ LOCKED |
| Screen 9 | Cian — Activity feed (♀ participants) | 🔄 Pending review |

### Design rules (locked — do not revisit)
- **Locked screens (1, 8) are not to be touched under any circumstances**
- Hinge-authentic design language — no cartoonish buttons, no emojis in UI chrome
- Minimal and clean — avoid over-engineering
- Brand colours: warm newsprint `#faf7f2`, dark navy `#1a1a2e`, gold `#f9df6d`, no red in UI (red reserved for lipstick circle on classifieds screens only)
- Font: Zilla Slab for wordmarks/headlines, Georgia as fallback serif
- **NO em dashes in any copy we control — ever. Smacks of AI. Titles of third-party content are exempt.**
- Subtext labels: parentheses and colons are fine. Exclamation marks sparingly. No em dashes, no trailing full stops.
- Filed label format: `Filed: you finished this` (colon, lowercase y — label:value, dry and warm)

### Screen 2 locking protocol
Once Laura confirms screen 2 is done, mark as LOCKED. Same process for all screens — review, confirm, lock, move on. No backsliding.

### Screen 9 — Cian activity feed (brief)
Same structural rules as screen 2 (Saoirse). Same three-register typography. Same thumbnail quality standard. But:
- Cian's own content — his reads, his games, his listens. Not a mirror of Saoirse.
- ×2 overlaps must match Saoirse's ×2 cards exactly (same articles/games — they're matched)
- His Filed cards = his solo world (things she hasn't read)
- His rec cards = content he engaged with that becomes "Saoirse's rec" on her feed
- His voice in the concierge/lead card copy should feel different from hers — same system, different person

### Typography system (screen 2 activity feed — locked)
Three distinct registers for subtext below each card. Never mix them:

| State | CSS class | Style | Example |
|-------|-----------|-------|---------|
| ×2 shared overlap | `act-shared-label` | Plain, `#555`, normal weight | "You both saved this yesterday" — no parens, recency is the main info |
| Cian's / Saoirse's rec | `act-rec-label` | Italic, `#888` | "Cian's rec (listened this am)" — parens for recency, it's secondary to the label |
| Filed (solo) | `act-filed-label` | Italic, dimmer `#aaa` | "Filed: you finished this" — colon, lowercase y, dry and warm |
| Lead card concierge | `lead-shared-text` | Bold, `#1a1a2e` | "Noted Cian read this 2 days ago" — no punctuation, authoritative |

**Logic:** concierge voice = authoritative (bold). Recs and filed = intimate (italic). Shared facts = neutral (plain).

### Bottom navigation (screen 2 — locked)
Four tabs: Profile | Activity | Chat | Matches
- Active tab: rose/red `#E63F5A`
- ×2 appears as icon above "Matches" label — same icon row as other tabs, Zilla Slab bold, `#888` when inactive
- Do NOT add a notification dot or pill — the ×2 text IS the icon

### Known technical gotchas
- `saoirse-2-JVbYYGOn.jpg` and `cian-cafe.jpg` are actually PNG files despite .jpg extensions — must embed as `data:image/png;base64`
- Carousel requires `min-width:100%` on `.s1-photo-slide` (not width on track)
- Overlay and dots must sit OUTSIDE the scrolling wrap (inside `s1-photo-outer`) to stay fixed
- File too large to read fully in one pass — always use Python or grep for targeted edits

### Session work log
| Date | Changes made |
|------|-------------|
| Feb 2026 | Screens 1 and 8 built and locked (Hinge-style profiles, Saoirse and Cian) |
| Feb 2026 | Screen 2 activity feed built — lead card, 6 content cards, bottom nav |
| 24 Feb 2026 | Screen 2: fixed Spelling Bee card label from `act-rec-label` to `act-shared-label` (was wrong class — it's a ×2 card not a rec) |
| 24 Feb 2026 | Screen 2: added ×2 icon above Matches in bottom nav |
| 24 Feb 2026 | Typography system audited and confirmed consistent across all 7 screen 2 cards |
| 24 Feb 2026 | Screen 2: replaced The Daily thumbnail with blue-to-yellow gradient logo SVG (matches actual show art) |
| 24 Feb 2026 | Screen 2: replaced Connections thumbnail with accurate 4×4 yellow/green/blue/purple grid SVG |
| 24 Feb 2026 | Screen 2: replaced Cooking/Salmon thumbnail with styled salmon-in-pan SVG |
| 24 Feb 2026 | Screen 2: stripped all punctuation from subtext labels across all 7 cards |
| 24 Feb 2026 | COPY RULE LOCKED: no em dashes ever in any copy we control. No punctuation in subtext labels. Dialogue/quoted text exempt. |
| 24 Feb 2026 | Screen 2: restored sensible punctuation — parens on rec cards, plain on x2 cards, colon on Filed |
| 24 Feb 2026 | Screen 2: Spelling Bee subtext changed to "Both today!" — short, earned exclamation |
| 24 Feb 2026 | Screen 2: fixed Matches bottom nav alignment (icon size/line-height) |
| 24 Feb 2026 | Screen 2: rebuilt Cooking thumbnail multiple times — settled on ramen bowl SVG (dark moody, golden broth, egg, nori, steam) |
| 24 Feb 2026 | Screen 2: Cooking card title changed to "Spicy Miso Ramen, 30 Min" to match thumbnail |
| 24 Feb 2026 | Screen 2: Cooking subtext updated to "Cian's rec (saved yesterday)" |
| 24 Feb 2026 | Screen 2: ×2 above Matches nudged down via margin-top to align with other nav icons |
| 24 Feb 2026 | Screen 2: lead card "Culture" category label kept in gold — intentional distinction from grey chips on smaller cards |
| 24 Feb 2026 | Thumbnail design rule: use brand/logo style for media (The Daily), game UI for games (Connections), food photography style for cooking. No crude graphics or clip art. |
| 24 Feb 2026 | Screen 2: Cooking thumbnail replaced with real photo (truffle fries, Unsplash). Title: "Truffle Fries, Three Ways". Subtext: "Cian's rec (saved this week)". Marked as good enough for now — can swap photo later. |
| 24 Feb 2026 | Screen 2: FINAL LOCKED. All thumbnails real photos or high-quality SVGs. Typography system consistent. Bottom nav aligned. |
| 24 Feb 2026 | Screen 2: rec label (`act-rec-label`) animated with slow dark-red heartbeat pulse — colour `#8a2a2a` → `#c04040`, scale 1.0 → 1.06, 4s cubic-bezier cycle, GPU-accelerated via `will-change:transform`. Only rec labels animate. Shared and Filed labels are static. |

---

*Document compiled from design sessions, February 2026*
*Times Two · Laura Glassman · Trinity College Dublin MSc*

---

## CROSSPLAY — STRATEGIC SIGNAL (Added Feb 2026)

### What it is
NYT's new two-player game mechanic allowing subscribers to be matched randomly with unknown players (or friends/family) for shared gameplay. Launched early 2026.

### Why it matters for Times Two — the disciplined read

**What CrossPlay proves (ecosystem signals):**

1. **NYT is comfortable designing relational mechanics.** They are no longer purely broadcast + solo ritual. A two-person game means they're willing to let subscribers interact inside the ecosystem. That's a brand and product threshold crossed.

2. **Stranger pairing inside a trusted publisher context is not taboo.** This is the psychological barrier you'd expect publishers to resist. NYT just walked through it voluntarily.

3. **Social stickiness beyond content consumption is a strategic priority.** Games → shared play → lightweight interaction → retention. They're testing the same logic you're building on.

4. **"Publishers would never..." is no longer a viable objection.** CrossPlay kills the most likely investor/partner pushback before you have to answer it.

**What CrossPlay is NOT (stay disciplined):**

CrossPlay is:
- Game-first, interaction-native
- Synchronous (play together in real time)
- Task-based (solve together)
- Random or pre-selected matching

Times Two is:
- Identity inference through shared engagement signals
- Asynchronous (artifact overlap, not live play)
- Conversation catalyst, not gameplay
- Algorithmically curated matching based on content overlap

**These are adjacent, not identical. Different layer of the stack.**

### How to use this in the pitch/capstone

One sentence, placed observationally, not triumphantly:

*"Recent NYT product experiments — including CrossPlay, a synchronous two-player game mechanic launched in early 2026 — suggest publishers are actively exploring relational extensions of their content ecosystems. Times Two operates at a different but complementary layer: asynchronous identity inference rather than live shared play."*

That's it. Calm. Strategic. It strengthens your commercial logic without overstating the connection.

### The founder question
Does CrossPlay make your idea stronger or does it make you feel late?

**Answer: stronger.** CrossPlay validates the strategic direction (publishers exploring relational adjacency) without replicating your specific mechanism (content overlap as identity signal and conversation catalyst). You're still testing something distinct. The ecosystem is moving toward you, not past you.



---

## THE ONION — FUTURE PUBLISHER WEDGE

Filed for later but worth documenting now.

The Onion superfan is a very specific and highly matchable personality type: satirically literate, politically aware, finds sincerity through irony. Two people who both read the same Onion piece aren't just sharing a laugh — they're sharing a worldview. That's a remarkably strong compatibility signal.

Why The Onion works as a future partner:
- No paywall → broader accessible user base from day one
- Strong community identity → users already self-select into a tribe
- Would probably find "we're building a dating layer inside your ecosystem" genuinely funny and interesting — exactly the energy you want from a first partner conversation
- The ironic register is itself a personality filter: people who get the joke are already pre-sorted

Demographic: younger, ironic, politically aware. Complements NYT and Guardian without overlapping.

Status: Future Laura's problem. Do not pitch before Guardian pilot is live.

---

## GUARDIAN SYMBOL — DESIGN PRINCIPLE (TBD)

When the Guardian version is built, the match symbol needs to be completely distinct from ×2.

Design brief:
- Less mathematical, more humanist
- Should feel earned rather than calculated
- Guardian's brand is warmth and conscience, not precision
- ×2 is a mark of overlap. The Guardian mark should feel more like recognition — two people arriving at the same place through different paths

Specific symbol: TBD. Do not default to a mathematical or geometric mark. Think about what "shared conscience" looks like visually.

Status: Future Laura's problem. Resolve before Guardian pilot screen design begins.

---

## AGE-DEMOGRAPHIC SUBTEXT DIFFERENTIATION

The activity feed subtext (the small labels under card headlines) should speak directly to different age groups rather than using a single universal register.

Core principle: same three-state system (×2 / Filed / [Name]'s rec), different tone and language by demographic.

Proposed register variants:

| Demo | Register | Example subtext |
|---|---|---|
| Gen Z (18–26) | Playful, ironic, self-aware | "you both went there. weird." / "filed. not everyone finishes." |
| Millennial (27–40) | Warm, understated, slightly dry | "Filed — you finished this. Not everyone does." |
| 40+ | Editorial, authoritative, clean | "Noted — you both read this." |

Implementation note: demographic register could be set at onboarding (age input) or inferred from subscription metadata. Does not require martech access — subscriber age is part of basic account data available via OAuth.

Status: Concept stage. Test in interviews whether participants notice or respond to copy tone. Do not build until mechanism is validated.

---

## MASTHEAD SUBTEXT — TIMES TWO HEADER OPTIONS

The "Times Two" wordmark sits at the top of the activity feed screens (Screens 2 and 9). Below it, a subtext line. Currently reads "Lately" — weak, needs replacing.

The double rule sits below the masthead, above the profile row, mimicking a newspaper nameplate.

Options under consideration:

| Option | Register | Notes |
|---|---|---|
| ×2 | Brand / mathematical | Bookends the brand top to bottom — wordmark + symbol. Clean, ownable. My current pick. |
| Fresh Print | Gen Z / playful | Nod to "hot off the press." Ironic but warm. Strong personality. |
| Today's Edition | Editorial | Newspaper-authentic but slightly formal. |
| Introduced | Concierge | Signals this person has been surfaced for you. Quiet, purposeful. |
| This Morning | Intimate | Real, understated. Slightly too soft. |
| Just In | Newsy | Edges toward breaking-news cliché. |

Bookending argument: "Times Two" at top + "×2" as subtext + ×2 in the nav at bottom creates a consistent brand signal from masthead to footer. The user sees the mark three times without being told what it means — they feel it first.

Decision: pending user testing / Laura's instinct. Lean toward ×2 or Fresh Print.

Status: Active design decision. Resolve before Screen 2 and 9 are locked.

---

## The Editorial Intelligence Layer

### The concept
Times Two sits on editorially valuable data that no other platform can produce from inside a publisher ecosystem. A lightweight internal dashboard surfaces this for NYT writers, editors, and video teams — opt-in only, never exposing private messages.

### What the dashboard surfaces
- **Couples pipeline**: Matched pairs with high message velocity (frequency = signal that something real is happening) + the content overlap that sparked the match. Writer sees the story angle instantly, without reading a single private message.
- **Tastemaker scores**: Users whose Featured stars (the ★ mechanic) consistently predict what trends in the next 48 hours. Weekly digest to NYT culture and video teams. These are your early critics, contributors, and potential columnists.
- **Opt-in story leads**: Users who flagged "I'd share my story" at signup. Editorial team contacts them directly. Warm leads, not cold calls.

### The Oracle as editorial first draft
The Oracle's match narrative is essentially the Modern Love lede, already written. Editorial prompt to the couple: "This is how we'd describe how you met. Would you want to tell the rest?" Low friction, high conversion to submitted essays.

### The opt-in framing (critical)
"Your story might be featured in Modern Love" is a feature, not a warning. It's aspirational for the right demographic. Frame it as an honour at signup — not data extraction. Consent is built into the product architecture from day one.

### The content flywheel made operational
1. Users match through shared content
2. Dashboard flags high-velocity couples + tastemakers
3. Editorial team makes warm contact
4. Couple submits Modern Love essay or appears in NYT video
5. That content attracts more users to Times Two
6. NYT gets authentic, inexpensive, emotionally resonant material for its growing video vertical

### Pitch line (canonical)
"Times Two doesn't just create couples. It creates content. The story writes itself — and the NYT is where it lives."

### NVC slide suggestion
Dedicated slide: "The Editorial Intelligence Layer" — show the flywheel diagram + dashboard concept + Oracle-as-first-draft mechanic. Positions Times Two not just as a matching product but as a content generation engine native to the NYT ecosystem.

---

## The Daily Oracle Loop (product rhythm)

### How the Oracle cadence works
The Oracle is present every day but the ×2 reveal is earned, not automatic.

**Every day:** Feed updates. New cards, new Oracle observations. The daily ritual — your content mirror, always fresh. The user never opens to an empty experience.

**Sometimes:** A breadcrumb card appears. The Oracle hints at someone else without naming them. "Most people stopped at the headline. Not everyone." Tension builds without a reveal.

**When the signal is strong enough:** The Oracle card appears. The elliptical reveal. Tap ×2 to see who. Never more than one reveal at a time — the logic of the product depends on singularity. Two simultaneous reveals breaks the spell.

### The typical arc
- Day 1-3: Feed updates, Oracle observes, no reveal
- Day 4: A breadcrumb — someone else was here
- Day 6: The Oracle card. "The article you read on Tuesday. He read it Wednesday."
- You tap ×2. Or you don't.

### The key design principle
The waiting is the product. The Oracle is not a notification system. It is a narrator. The daily feed is always worth opening — with or without a reveal.

### Frequency rule
Never more than one ×2 reveal active at a time. Quality gate, not time gate. The Oracle surfaces a match when the signal is genuinely interesting, not on a fixed schedule. Could be daily, could be every few days. The unpredictability is intentional — "the Oracle noticed something" is a completely different emotional register from "your daily match."

---

## Selective Disclosure — Game Scores and Content Privacy

### The problem (raised in user research)
A participant flagged that she would not want bad game scores or failed attempts disclosed to a potential match. Valid concern — performance anxiety is exactly what Times Two is designed to reduce, not introduce through a different door.

### The design response
**User-controlled curation via the Featured mechanic.**
The ★ star on each card is not just an algorithmic signal — it is the user's editorial choice about what represents them. You star what you're proud of. You leave unstarred what you'd rather not lead with.

The Oracle draws primarily from starred content for match signals. Unstarred content informs the algorithm quietly but does not surface in the ×2 reveal or Oracle copy.

**Practical implications:**
- Wordle in 6? Don't star it. It stays in your history but doesn't become a talking point.
- Wordle in 2? Star it. The Oracle notices.
- DNF on Connections? Never surfaces unless you choose it.
- Genius on Spelling Bee before 8am? The Oracle sees you — if you let it.

### The pitch framing
This is opt-in curation, not algorithmic scraping. The user decides what their content profile says about them. That's a fundamentally different relationship with data than any other platform offers — and it directly addresses the AI surveillance kill criterion.

**Pitch line:** "The algorithm sees everything. The Oracle only says what you've chosen to show."

---

## NYT Watch Tab — Strategic Context (March 2026)

### What it is
NYT launched a TikTok-style vertical video feed inside the main NYT app. Short-form clips under 3 minutes, editorially curated (not algorithmically), spanning News, Opinion, Cooking, Wirecutter, Athletic, and Podcasts. Launched ad-free; vertical video advertising beta planned early 2026.

### Why it matters for Times Two
- Watch is a new content signal layer — completing a 1:52 Watch clip on Holi at midnight is revealed preference, exactly like finishing a 4,000-word article
- Content types now include: article, recipe, game, podcast, AND video — the feed becomes richer and more Gen Z native
- NYT Watch is their TikTok response — Times Two is the dating layer on top of that ecosystem
- Video consumption across NYT platforms more than doubled YoY — nearly 200M minutes in September 2025 alone
- Watch is curated by editors not algorithms — same trust signal that makes Times Two credible

### The pitch angle
"NYT already built the TikTok. Times Two is the first product that puts it to work for human connection."

### Prototype implementation
Watch card added to screens 10 (Saoirse) and 15 (Cian) — Holi festival thumbnail, play button overlay, duration badge, Watch category pill. Holi is March 14 2026 — NYT Watch will almost certainly cover it. Card is timed perfectly.

### Oracle copy for Watch cards
Treat exactly like article completion — depth signal is completion rate, not just a view.
- *"Watched it twice. The Oracle noticed."*
- *"Most people swiped past it. You didn't."*

---

## Interview 2 — Wissam (March 4, 2026)

### Profile
Early-to-mid 20s, undergraduate or recent graduate. Not currently using dating apps (last active Sept/Oct). Used Tinder, Bumble, Hinge. Has Trinity NYT subscription, accesses on laptop only, not a games user. Primary news sources: Instagram and Al Jazeera. Raised primarily by women — emotionally mature, culturally self-aware.

### Key Validated Findings

**Additive model confirmed from male perspective.**
He explicitly named missing elements unprompted: religion, languages spoken, hobbies, education, geolocation. Content signals are "silver" in his hierarchy — necessary but not sufficient without bio layer. Two-stage model: content as curiosity trigger, bio as qualification gate.

**Content dramatically improved conversational readiness.**
On traditional profile: wouldn't match, no common ground. On Times Two: immediately generated three specific openers across different card types — Connections score, Cities piece, Spelling Bee word. Zero hesitation.

**Authenticity perception strongly confirmed.**
"It's very difficult to fake it because this is what they have actually been reading." Contrasted with performative traditional profiles unprompted.

**Data inversion landed clearly.**
Independently articulated the you-are-the-product problem: "Usually if something is free, you're the product." Positioned Times Two as the inversion without being prompted.

**Nod validated unprompted.**
Noticed the Nod button in the nav bar without being directed to it. Asked about it directly. His own unprompted suggestion for what dating apps should do differently matched the Nod concept exactly.

### The Hijab Moment — Most Striking Qualitative Finding
When shown the Love is Blind concept (deferred photo reveal), he connected it unprompted to Islamic courtship practice: "The person actually interacts with the woman and understands how she thinks, how she talks, her mind and everything. And then when they get married, he sees her hair."

This is your most powerful qualitative moment from either interview. It reframes Love is Blind mode not as a gimmick but as something with genuine cross-cultural precedent. Use it in both the capstone findings and the NVC deck.

### The Bypass Problem — Key Challenge to Thesis
He predicted male power-user behaviour: "They just keep tapping, click see the person, check everything, go back." The content-first sequence may be structurally vulnerable to users who learn to route around it.

**Design response:** ×2 as reward not gate. Make the reveal feel earned — users who engage with content get a richer, more specific Oracle reveal. Bypass users get a blander experience. Incentive structure, not enforcement.

Address this explicitly in the capstone as a validity challenge — the fact that he flagged it unprompted makes it credible and shows research rigour.

### Oracle "Fortune Cookie" Failure Signal
He found the two-sentence Oracle format cryptic and hard to decode. "This feels like a fortune cookie. You're trying to decipher what the person is behind those two sentences."

**Note:** Wissam is not a games user and gets news from Instagram — he is at the outer edge of the target user profile. Do not adjust Oracle copy based on this data point alone. Get more data in interview 3. The fix if needed is specificity — name the actual thing, not gesture at it mysteriously.

### Dispatch — Missed Entirely
He did not notice the Daily Dispatch / Personals block at the top of the feed until it was pointed out. However once explained, he immediately made the full-circle connection and loved the concept. Signals the Dispatch needs stronger visual presence — more like a newspaper clipping, less like a caption.

### Exact Quotes (canonical)
- Authenticity: "It's very difficult to fake it because this is what they have actually been reading, what they are interested in. This is actually the person you're dealing with."
- Conversational readiness: "That would be jackpot. I would go straight to the stuff we both have in common."
- Data inversion: "People feel like their information is not just being taken. They're getting something out of it. Usually if something is free, you're the product."
- Love is Blind / hijab: "This actually reminds me of my own religion. The person actually interacts with the woman and understands how she thinks, how she talks, her mind and everything. And then when they get married, he sees her hair."
- Oracle: "This feels like a fortune cookie. You're trying to decipher what the person is behind those two sentences. A friend is just straightforward."
- Closing: "I find it just very interesting. I feel like the connection someone would make in Times Two would be more genuine and more concrete. And I wish it is actually an app so I can try it out."

### Comparison with Interview 1 (Saoirse/female participant)
| | Interview 1 (female) | Interview 2 Wissam (male) |
|---|---|---|
| Content trust | High | High |
| Additive layer needed | Yes | Yes, named specifics |
| Oracle voice | Responded well | Found cryptic |
| Love is Blind | Validated (control) | Validated (cultural resonance) |
| Bypass risk | Not raised | Raised explicitly |
| Dispatch noticed | Yes | No — needs visual fix |
| Closing sentiment | Positive | "I wish it is actually an app" |


---

## The Wingman (formerly The Oracle)

### Renaming rationale
"The Oracle" didn't land in interviews. Nobody understood its role. "Wingman" is instantly understood. Everyone has had one. Everyone wants one. A wingman looks out for you, is at the ready to make introductions, and puts you forward when you don't do it yourself.

### The Wingman arc
1. **Discover** -- your feed, your content, daily updates
2. **Introduce** -- the wingman reveals a match based on shared signals
3. **Connect** -- conversation starters drawn from shared content
4. **Close** -- the wingman suggests meeting up and books the venue

No other dating app does step 4. They all abandon you after the match. The wingman stays with you from first signal to first coffee.

### Voice rules (updated from Oracle)
- Direct, warm, conspiratorial
- "I saw something you should know about" register
- Not mysterious. Not coy. Pays attention and has your back.
- Still no em dashes. Still no "someone" or "a match" or transactional dating language.
- Navigation prompts remain visually subordinate captions, not Wingman voice.

### The Cafe Feature
The wingman suggests meeting IRL when the chat has momentum. Not generic. Content-specific:
- Cooking matches: "You both saved NYT Cooking recipes. There's a cooking class at Bread 41 this Saturday."
- Athletic matches: match tickets, sports bar, 5K run
- Culture matches: gallery opening, film screening, book launch
- Audio matches: podcast live event, talk at a bookshop
- Games matches: pub quiz night, board game cafe
- Travel matches: weekend trip suggestion

The wingman doesn't say "go for coffee." It says "go do the thing you both already love doing."

### Venue partnerships (revenue line)
Referral/affiliate fees from restaurants, cafes, bars, experience venues. TimeOut, Eater, Yelp, OpenTable, Resy. Highest-intent dining moment in existence: two people about to have a first date. Not advertising. The wingman being good at its job.

### Post-date check-in
The wingman doesn't track GPS. It knows a date was proposed (cafe feature used). 48 hours after the proposed meetup, it checks in:
"How was it?"
Three options: Great / Not for me / We didn't go
- "Great" triggers the flywheel nudge later
- "Not for me" closes the loop gracefully, no ghosting
- "We didn't go" resets without judgment

### Match persistence and fading
After the wingman reveals a match, both users can see each other's feeds. The feed is a living thing. New articles, game scores, recipes, every day. That's the getting-to-know-you phase happening through content.

If neither person reaches out:
- Day 1: Wingman reveals the match
- Days 2-5: Both can see feeds, conversation starters available
- Day 5: Gentle nudge. "Still curious about Cian? He's not going anywhere yet."
- Day 7: "This match is fading. Want to say something before it goes?"
- Day 8: Match fades. "Sometimes the timing isn't right."

Matches don't expire. They fade. Like running into someone at a coffee shop and never saying hello.

### Why users stay on the app (unlike Hinge/Bumble)
People leave other apps because the app served its purpose: you got a number. Times Two gives reasons to stay:
- Your feed updates daily
- Their feed updates daily
- Shared content keeps growing
- The app is an ongoing window into someone you're getting to know
- The wingman facilitates the full arc, not just the introduction

## The Content Flywheel (closed loop)

### UGC Meet Cute Videos
Not TikTok-style self-presentation (that's performance, the exact problem Times Two solves). Instead: couples telling their story.

"We both saved the same tomato soup recipe on a Friday night. Neither of us knew. Three months later, we made it together."

30-second videos that do more for Times Two than any ad campaign. Modern Love in miniature.

Three content types:
1. **Meet cutes** -- how we met (the origin story)
2. **Meet ups** -- first date moments (the cooking class, the gallery)
3. **How I met your mother** -- couples further along, looking back

All opt-in. All real. All coming from inside the product.

### How the flywheel trigger works
The wingman names it after the fact, not before:
1. Cafe feature used, date happens
2. Wingman checks in: "How was it?"
3. User says "Great"
4. Weeks/months later, wingman: "How was Bread 41? If that was your meet cute, the NYT might want to hear about it."
5. User opts in to share story
6. Story becomes NYT content (Modern Love, Vows, video series)
7. Content attracts next couple

The couple lived it. The wingman recognises it. The NYT publishes it.

### Journalist opt-in
Settings toggle (not onboarding): "Would you be open to sharing your story with NYT if things go well?"
Quiet. No pressure. The wingman surfaces it at the right moment, not on day one.

### The pitch line
"Every couple that meets through Times Two is a story. Every story is content. Every piece of content brings the next couple."

## Daily Matches (user preference)
Users can select 1, 2, or 3 introductions per day via onboarding.
Default: 1. Scales with pool size.
Reality check: at launch, pool size won't support 3 quality matches daily. 1 per day isn't a limitation. It's quality control. Scarcity is the value proposition (validated by Tessa).
The wingman introduces someone when the signal is strong enough. Some days that's one. Some days that's none.

## Interview 6 Insights (Mar 2026)
- Female, 38, impatient, wants more than 1 match per day
- Requested: match name and age more prominent on home screen
- Requested: AI-assisted chat prompt connecting to shared content
- Requested: cafe/meet-up feature for getting face-to-face quickly
- Very Trumpy, doesn't want to match on news content -- validates content world opt-out design
- Still loves the app despite political content concerns


## The Wingman's Three Paths to IRL

Not everyone will tap "Suggest coffee." The wingman needs multiple routes:

1. **Suggest coffee** -- the direct route. For people who are ready. User-initiated.
2. **The wingman just does it** -- after enough chat momentum, the wingman drops a venue card unprompted. "You've both been talking about that cooking piece. There's a class at Bread 41 this Saturday. Just saying." Neither person had to ask. The wingman broke the ice.
3. **Shared event surfacing** -- the wingman notices a relevant event (book launch, gallery opening, podcast live recording) and drops it into both feeds simultaneously. "This is happening Thursday. You'd both like it." Not framed as a date. Framed as content. But they both know.

The wingman doesn't wait to be asked. A real wingman at a bar doesn't stand there until you tap them on the shoulder. They see the moment and they move.

## Anti-Ghosting: The Wingman Sign-Off

Ghosting is the number one complaint in dating. Nobody's solved it because they've left it to the humans. Humans hate giving rejection. The wingman takes the hit.

User taps a "not for me" button. The wingman sends on their behalf:

"Hey. Saoirse's Wingman here. She's enjoyed getting to know you but doesn't feel this is the right match. She wanted you to know rather than leave you wondering. Good luck out there."

What this solves:
1. The ghoster doesn't ghost because tapping a button is easier than feeling guilty for weeks
2. The ghosted gets an answer instead of refreshing the chat at 2am
3. The platform gets clean data. A closed match is a signal. A ghost is noise.

Full wingman arc: introduced you, facilitated chat, suggested coffee, and if it doesn't work out, closes the door kindly. Beginning to end. No loose threads.

## The Ad

The ad is the meet cute story. One couple. One sentence. One recipe.

"We both saved the same tomato soup recipe on a Friday night. Neither of us knew. Three months later, we made it together."

Put it on a subway poster, an Instagram story, the NYT homepage. No app screenshots. No feature list. Just the story. Every couple generates a new ad.


## Anti-Ghosting: The Full Thinking (corrected)

### The problem
Ghosting is the number one complaint in dating apps. Nobody has solved it because they've left it to humans, and humans hate giving rejection. The instinct was to have the wingman send a polite sign-off on the user's behalf. But that's lazy and cowardly. Outsourcing rejection to an AI is just ghosting with a middleman.

### The correction
The wingman doesn't send the message. The wingman gets YOU to send it. That's the difference between a coward's tool and a conscience.

Here's how it actually works: you haven't opened the chat in 3 days. The wingman nudges you privately. Not the other person. You.

"You haven't replied to Cian in a few days. If you're not feeling it, let him know. A quick honest message goes a long way."

Then it offers a gentle template you can edit:

"Hey Cian, I've really enjoyed chatting but I don't think we're the right fit. Wishing you the best."

You can rewrite it. You can send it as-is. But it comes from YOUR name. Your chat bubble. Your integrity. The person on the other end gets a real human message, not a system notification. That's closure, not a corporate email.

### Why this matters for the product
The wingman's role is having your back AND being your conscience. It introduced you. It helped you talk. It suggested coffee. And if it's not working, it makes sure you do the right thing. That's the full arc. Not just matching. Not just connecting. Teaching people how to treat each other well. No other dating app even attempts this.

### Why the first instinct was wrong
Having the wingman send "Saoirse's Wingman here, she's not feeling it" would feel like getting dumped by a chatbot. It removes the human element entirely. The whole thesis of Times Two is that real behaviour beats performance. A real goodbye beats an automated one too.

## The Wingman as Conscience (design principle)

The wingman is not a concierge. It's not a butler. It's not an assistant. It's the friend who tells you what you need to hear, not what you want to hear. It has your best interests at heart, which sometimes means pushing you to do hard things:

- Send that first message (you've been staring at the chat for 2 days)
- Say yes to coffee (you keep finding reasons not to)
- Be honest when it's not working (instead of disappearing)
- Share your story if it worked out (the flywheel needs you)

Each of these is a nudge, not an action. The wingman never acts FOR you. It acts ON you. That's the distinction that keeps the product human.


## Why Wingman, Not Oracle (the full thread)

### The problem with the Oracle
The Oracle had pomposity baked into its DNA. "The Oracle noticed." "The Oracle sees you." Fortune cookie register. Cryptic. All-knowing. That's a god talking down. It sat above the user, dispensing wisdom. Nobody in interviews understood what it was or what it did. The name created distance where the product needs intimacy.

### Why Wingman works
The Wingman stands beside you. It's your pal. It's at the bar with you going "that person over there just ordered the same weird drink you always get. Go say hi."

Same data. Same intelligence underneath. Completely different relationship with the user. The Oracle made you feel watched. The Wingman makes you feel backed.

### The gender question
"Wingman" is gendered in origin but the word has outgrown it. Everyone's had a wingman. Everyone's been a wingman. It's a role, not a gender. Nobody hears "wingman" and thinks "only men." They think "someone who has my back." If it ever needs revisiting, "Wing" works on its own. But for now, Wingman is immediate, warm, and universally understood.

### What changes with the rename
- Voice shifts from mysterious/cryptic to direct/warm/conspiratorial
- "The Oracle noticed something" becomes "Your Wingman saw something you should know about"
- The relationship shifts from being observed to being supported
- The user isn't a subject of the Oracle's attention. They're a friend the Wingman is looking out for.
- All the same intelligence, matching logic, and content signals remain. The wrapper changes. The soul changes with it.


## The Wingman Brief -- Build Spec (confirmed Mar 2026)

### The cardinal rule
**The Wingman has an opinion. It takes a position on whether this match is worth the user's time.** Every other app gives you data and says "you decide." The Wingman says "I've been paying attention. This one's worth it." That is the fundamental difference. A Wingman that doesn't have opinions is just a search engine.

### What it is
The brief is the Wingman's match reveal. Three lines. First person. Spoken directly to the user about their match. It is not a summary. It is not a data readout. It is the Wingman talking to a friend.

### The formula
Every line has three layers: **observation + synthesis + opinion.**
- Observation: what the match did
- Synthesis: why it means something
- Opinion: what the Wingman thinks about it

**Not this:** "He saved a recipe on Friday night."
**This:** "Friday night. Marcella Hazan's tomato sauce. No occasion. Just because. You'd get along."

**Not this:** "He plays Connections every day."
**This:** "Connections. Every day. No mistakes. The kind of discipline you pretend to have."

**Not this:** "He finished the same long-read article that you also finished."
**This:** "He finished the same long-read you couldn't put down. Neither of you knew. That doesn't happen often."

### Voice rules
- Short sentences. Present tense.
- A little dry. Occasionally a gentle dig at the user. The Wingman knows you well enough to be cheeky.
- Not sycophantic. Not robotic. Opinionated.
- First person. The Wingman says "I" and addresses the user as "you."
- Never neutral. The Wingman has a take.
- Duolingo owl energy: knows you better than you know yourself, slightly passive-aggressive, impossible to ignore.

### Structure
- Three lines maximum. Each line covers one content signal.
- End on the Wingman's verdict. One short sentence that is a push, not a summary.
- Verdicts: "You'd get along." / "This one's worth it." / "Don't overthink it." / "Trust me on this one."

### What the Wingman never does in a brief
- Lists things
- Uses bullet points
- Says "both of you" repeatedly
- Describes behaviour without interpreting it
- Stays neutral
- Sounds like a system notification or a LinkedIn summary

### The test
Read the brief aloud. Does it sound like a person talking to a friend, or a database query? If it sounds like LinkedIn, rewrite it.

### Example briefs (canonical)

**Saoirse's brief on Cian:**
"He finished the same long-read you couldn't put down. Neither of you knew. That doesn't happen often.
Connections. Every day. No mistakes. The kind of discipline you pretend to have.
Marcella Hazan's tomato sauce. No occasion. Just because. You'd get along."

**Cian's brief on Saoirse:**
"She saved the Cities piece you've been putting off. She actually read it. Twice.
Spelling Bee Genius. You got to Amazing. She's ahead of you.
Don't overthink it."


## The Wingman as Self-Improvement Engine (confirmed Mar 2026)

### The gap no app fills
No dating app in history offers a learning loop. They all treat dating like a slot machine: pull the lever, see what comes out, repeat. Nobody helps you get better at this. No course correction. No reflection. No growth.

### What the Wingman does differently
The Wingman reflects your own patterns back at you. Not as a therapist. Not as a coach. As the friend who knows you better than you know yourself and is not afraid to say it.

**Pattern recognition examples:**
- "You've passed on three people who shared Culture content with you this month. But your longest conversations all started from Culture. Worth thinking about."
- "You keep matching on Games but never mention them in chat. That's your best material. Use it."
- "Last three times someone suggested coffee, you said 'not yet.' The Wingman thinks you're ready. Trust the process."
- "You tend to go quiet around day 3. That's when the other person starts wondering. A quick message goes a long way."

### The Wingman's full role (expanded)
Not a concierge. Not a butler. Not an assistant. The friend who tells you what you need to hear, not what you want to hear:
- **Matchmaker:** introduces you when the signal is strong enough
- **Briefer:** gives you three lines on your match, with opinions
- **Opener:** suggests a game challenge or conversation starter
- **Closer:** suggests meeting up at the right moment
- **Conscience:** nudges you when you're ghosting or stalling
- **Mirror:** reflects your dating patterns so you can learn from them
- **Cheerleader:** celebrates when it works out, nudges the flywheel

### Why this is a moat
No other app can do this because no other app has the data depth. Hinge sees swipes. Bumble sees messages. Neither can see that you read a 4,000-word piece at 11pm on a Tuesday and saved it. The depth of the content signal IS the depth of the Wingman's insight. The richer the reading data, the smarter the Wingman gets. That is a compounding advantage, not just a feature.

### Voice reference
Duolingo's owl: knows you better than you know yourself. Slightly passive-aggressive. Makes you feel something. The Wingman is the dating version of that. Not annoying. Not preachy. Just relentlessly, affectionately honest.


## Wingman Personalisation (confirmed Mar 2026)

### The paradox
A wingman at a bar is YOUR friend. Biased in your favour. Times Two's Wingman matches both people. It wrote her brief on him AND his brief on her. That is not a wingman. That is a matchmaker pretending to be a wingman.

### The resolution: experienced loyalty
The Wingman's intelligence is bilateral (it knows both people). The EXPERIENCE is singular (you only see your side). You never see the other person's brief. You never know how the Wingman framed you to them. That asymmetry preserves trust.

**Design rule:** The user never sees the other person's brief. Ever. The Wingman's loyalty is experienced as one-sided even though its knowledge is not.

### What makes YOUR Wingman yours
The Wingman is personalised through YOUR data, not the match's. It knows:
- What content worlds you go deep on (completion, saves, return visits)
- Your habits (daily Wordle player, weekend Cooking browser, Wirecutter deep-diver)
- What's working in your conversations (which openers lead to longer chats, where conversations stall)
- What you're NOT doing (stalling on coffee, going quiet, ignoring game challenges)
- Whether you're snacking or investing (headline scanning vs finishing a 4,000-word piece)

So Saoirse's Wingman and Cian's Wingman emphasise different things. Same match, different briefs, because each Wingman is calibrated to what matters to THAT user.

### The surveillance line (hard rule)
Times Two tracks WHAT, not WHEN. No timestamps. No session times. No "morning reader" or "late-night diver" language. That reads as surveillance even if technically benign.

Acceptable signals:
- What you read (content, not timing)
- How deep you went (completion rate, not time spent)
- What you saved (deliberate action)
- Game scores (already shared socially by millions)
- Return visits to content (you came back to the same piece)
- Browse depth (six Wirecutter reviews in one session = nesting signal)

Not acceptable:
- Time of day
- Session duration
- App open frequency
- Location
- Device type

### Signal hierarchy (what the Wingman actually uses)
Foundation principle: the Wingman runs on passive behaviour. The stuff you do without thinking about it. The moment you require active curation, you reintroduce the performance problem you are trying to solve.

1. **Completion** (strongest) -- finished a long piece. That is investment, not snacking. Entirely passive. NYT already tracks this.
2. **Game scores** (strong) -- Wordle in 2, Connections no mistakes. Daily. Habitual. Already shared socially by millions. People are PROUD of these. Most natural, least effortful signal in the stack. Also doubles as conversation opener.
3. **Return visits** (solid) -- came back to the same section. Daily Spelling Bee player. Weekend Cooking browser. Habit signal, entirely passive.
4. **Browse depth** (solid) -- Wirecutter deep-dive on toasters. Six product reviews in one session. Someone in a life moment. Passive.
5. **Saves** (weak) -- requires a deliberate tap. Some people do it. Most don't. Bonus signal, not foundation.
6. **Featured/starred** (weakest) -- almost nobody will do this. Cherry on top for engaged users. Cannot be the foundation.

The Wingman works on signals 1-4 without the user lifting a finger. Signals 5-6 are bonuses. The product must never depend on active user curation.

### Tone picker (onboarding, Screen 20)
Users choose their Wingman's voice at setup. Four options:

**Straight shooter** -- Direct. No fluff. "This one's worth it. Go."
**Gentle nudge** -- Warm. Encouraging. "I think you'd really like this person. Take a look when you're ready."
**Cheeky friend** -- Snarky. Duolingo owl energy. "Connections. Every day. No mistakes. The kind of discipline you pretend to have."
**Hype person** -- All enthusiasm. "OK this is a GOOD one. Trust me."

The tone changes. The intelligence doesn't. Same data, same matching logic, different wrapper. Like choosing a voice for your GPS. The route is the same. The vibe is yours.

Over time the Wingman adapts: if you consistently ignore gentle nudges but act on snarky ones, it drifts snarky. The tone calibrates to what makes you respond.

### The snacking vs investing distinction
The Wingman knows the difference between someone who scans headlines and someone who goes deep. If someone only dips in for Wordle and nothing else, the Wingman's brief reflects that honestly. Not every user generates rich signals. The Wingman works with what it has and is transparent about depth.

"He does Wordle. Every day. That's about it for now." is a valid brief. It is honest. It respects the user's attention. It does not invent depth that isn't there.

### Data access reality check (pinned for CTO conversation)
- **Available via standard publisher APIs/OAuth:** saved articles, game scores (shared), subscription tier, content section preferences
- **Available via publisher partnership integration:** completion rates, scroll depth, return visits, browse depth
- **MVP signals (Phase 1):** saves + game scores + content sections. Enough for the Wingman brief.
- **Deep signals (Phase 2):** completion rates + browse depth + return patterns. Requires partnership-level data sharing agreement with each publisher. This is why it is B2B SaaS, not a scraper.
- Akshay's granularity question (INTV #15): can we track these movements in a granular way? Answer: yes, with publisher partnership. No, with standard OAuth alone. The business model IS the answer to the data access question.


## AI-Assisted Chat Prompts (the full thinking)

### The problem
You've been matched. You're staring at the chat. The cursor blinks. You type "hey." You delete it. You type "hi, how are you?" You delete it. You close the app. This happens millions of times a day across every dating platform. The blank chat box is where momentum goes to die.

### What the wingman does
The x2 button sits in the chat input bar. Tap it and the wingman generates a conversation starter based on your shared content. Not a generic icebreaker. Something specific.

You both saved the same recipe? "That tomato soup recipe. Have you actually made it yet?"
You both finished the same long read? "The ending of that Middle Manager piece. Did you see it coming?"
You both play Wordle every morning? "Wordle in 2. Was it skill or a lucky opener?"

### Why this isn't a crutch
The wingman doesn't write the conversation. It starts it. One line. Then you're on your own. And the line works because it's drawn from something real you both did. It's not "what's your favourite travel destination?" It's specific, personal, and based on genuine shared behaviour.

### Design principle
The wingman finishes a sentence you were already thinking. That's a completely different emotional register from a suggested opener. More intimate. Less scripted. The user reads it and thinks "yes, that's exactly what I wanted to ask." Not "the app wrote this for me."

### In the prototype
The x2 button is a small gold-bordered circle in the chat input row on screen 3. Sits to the left of the text input. Tapping it would (in the real product) populate the input field with a starter. In the prototype it's static but shows the concept.

## The Cafe Feature (the full thinking)

### The problem
People match. They chat. They stall. Nobody wants to be the one to say "so should we actually meet?" That moment of vulnerability is where most connections die quietly. The chat fizzles. Both people move on. Both people wished someone had said something.

### What the wingman does
The wingman has been watching the chat momentum. After a few days of back and forth, it drops a card into the conversation:

"You two have been going back and forth. Want me to suggest coffee?"

Two buttons: "Suggest coffee" and "Not yet."

If you tap Suggest coffee, the wingman drops a venue card into the chat. But here's the key: it's not generic. It's content-specific.

### Content-specific venue matching
- You both saved NYT Cooking recipes → "There's a cooking class at Bread 41 this Saturday."
- You both follow The Athletic → "Ireland v France at the Aviva this weekend. Two seats?"
- You both read Culture pieces → "There's an opening at IMMA on Thursday night."
- You both play Games → "Quiz night at The Long Hall. Tuesday. Just saying."
- You both listen to The Daily → "Live podcast recording at Liberty Hall. This Friday."

The wingman doesn't say "go for coffee." It says "go do the thing you both already love doing." That's a fundamentally different kind of first date. No small talk. No awkward silence. You're already doing your thing, together.

### Revenue line hiding in a feature
Every venue suggestion is a potential referral. TimeOut, Eater, Yelp, OpenTable, Resy. They all want to reach two people who are about to have a first date. That's the highest-intent dining moment in existence. And it doesn't feel like an ad. It feels like the wingman being good at its job.

### Three paths to IRL (expanded)
Not everyone will tap "Suggest coffee." The wingman has three routes:

1. **User taps Suggest coffee** — direct, user-initiated. For people who are ready.
2. **The wingman just does it** — after enough chat momentum, drops a venue card unprompted. "You've both been talking about that cooking piece. There's a class at Bread 41 this Saturday. Just saying." Neither person had to ask. The wingman broke the ice.
3. **Shared event surfacing** — the wingman notices a relevant event and drops it into both feeds simultaneously. "This is happening Thursday. You'd both like it." Not framed as a date. Framed as content. But they both know.

The wingman doesn't wait to be asked. A real wingman at a bar doesn't stand there until you tap them on the shoulder. They see the moment and they move.

### In the prototype
Screen 3 (chat) has a wingman café card sitting in the message flow after the last message. Gold-bordered card with "Your Wingman" label, the suggestion copy, and two buttons (Suggest coffee / Not yet). Static in the prototype but demonstrates the concept clearly.

## Live Events and Community (the full thinking)

### The insight
Times Two doesn't have to stay digital. The same content signals that match two people can curate a room of twenty. The product extends naturally into real life through live events that feel like community, not speed dating.

### Three formats

**1. Singles Supper Clubs**
Curated dinners for 8-12 people who share content signals. A table of Wordlers. A table of Cooking subscribers. A table of Athletic readers. Everyone has something in common before they sit down. Not speed dating. A dinner party where the guest list was quietly curated by the Wingman.

Content-specific tables:
- Games table: Wordle, Connections, Spelling Bee players
- Cooking table: recipe savers, Friday night cooks
- Culture table: longform readers, Modern Love subscribers
- Athletic table: rugby, football, tennis followers
- The Daily table: morning listeners, news junkies

Revenue: ticket sales, venue partnerships, sponsorship. High-margin, low-tech, executable immediately.

**2. Meet Cute Meetups**
Larger, lower-stakes gatherings built around shared content moments. A gallery opening for people who saved the same Culture piece. A pub quiz for Games players. A listening party for Daily subscribers. The Wingman doesn't pair you with one person. It puts you in a room with people who engage with the same things you do.

These are not branded as dating events. They are branded as community events powered by Times Two. The romantic potential is implicit, not explicit. That distinction matters for female attendance and overall comfort.

**3. Meet Cute Storytime**
The Moth meets Modern Love. Couples who met through Times Two get up on stage and tell the story. No notes. Just the truth. "We both saved the same soup recipe on a Friday night. Neither of us knew. Three months later, we made it together."

Live audience. Recorded. Published on the publisher's platform. Becomes a podcast episode, a video, a Modern Love essay. Feeds the content flywheel directly.

Reference: The Moth (NPR's live storytelling series, founded 1997, sold-out events globally). Same DNA: real people, true stories, live audience. Times Two provides a built-in pipeline of stories that The Moth has to discover. We already know who met and how.

### Why this matters strategically

**Revenue from day one.** Supper clubs and meetups can run before the app is built. A curated dinner at TCD next month needs nothing but a sign-up form and a reservation. This is a proof point that costs almost nothing to create.

**Community creates retention no algorithm can.** If your social life runs through Times Two events, you don't cancel. The emotional anchor is even stronger than matching with a partner. You belong to something.

**Every event is content.** Photos, videos, stories. The storytime recordings become podcast episodes. The supper club recaps become newsletter content. The meetup photos become social proof. All of it feeds the flywheel.

**Solves the cold-start problem.** At launch, the matching pool is small. Events put people in the same room before the algorithm has enough signal to pair them one-to-one. Community buys time for the product to mature.

**Publisher brand extension.** NYT already runs live events (Modern Love live, Times Talks, Cooking festivals). Times Two events slot into existing infrastructure. Guardian Live is an established brand. This is not a new capability for publishers. It is a new reason to use it.

**Venue partnership revenue.** Every event needs a venue. Restaurants, galleries, theatres, cooking schools, sports bars. Referral fees from venue bookings are pure margin. The Wingman suggests the venue. The event fills the seats. The venue pays for the lead.

### The flywheel extension
1. Users match through shared content (digital)
2. Users attend events together (physical)
3. Their story becomes content (flywheel)
4. That content attracts more users (growth)
5. More users create better events (community)
6. Better events create more stories (flywheel accelerates)

The digital flywheel and the physical flywheel feed each other. Neither works as well alone.

### Pre-launch validation opportunity
A singles supper club at TCD could run in April 2026. No app required. Curate attendees by asking three questions: What NYT Games do you play? What do you read? What do you listen to? Group tables by overlap. Document everything. That dinner is a proof point for the NVC pitch and a data point for the capstone.

### Pitch line
"The app gets them talking. The events get them together. The stories bring everyone else."


## Interview Findings -- Interviews 14-16 (March 19, 2026)

### Interview 14: Meg, 31 (American, New York, cybersecurity, Blackstone/Oracle background)

**Profile:** Never used a dating app personally. Proxy experience through close friends in their mid-30s in New York. Married, trailing spouse in Dublin. MSc cohort. Came in as a reporter and left as a prospective user of the community product.

**Key findings:**
- **Mission Impossible brief concept (Wingman UX):** "Wingman, top three things, go." Wants a fast, scannable, actionable brief at the match reveal. Not a scroll. Three bullet points. Each one a different content signal. You read it, you know enough to decide. This reshapes the match reveal design.
- **Wingman as two-way self-improvement channel:** The Wingman should check in after dates, collect feedback, help the user iterate on what is and isn't working. A data capture layer that serves the user, not the platform. Thinks about the feedback loop, not just the matching mechanic.
- **Proxy-to-convert story:** Has never used a dating app and has no intention of starting, but said "I would use this" for the community/friend-matching layer. That is the product's second revenue case validated by a non-dater in a single interview.
- **Profile dishonesty pattern (via friend Jenny):** Men presenting as open-minded and progressive to attract more matches, arriving as the opposite. The incentive structure of the app produces dishonesty. You can curate a bio. You cannot curate your reading history.
- **Jenny's dating approach:** Mid-30s NYC women wait for the guy to message first. When contact happens, they want it direct. "Here's when I'm free, let's get a drink." No small talk, no pen pal phase. Validates the Wingman cafe feature's urgency.
- Confirmed Guardian as similar demo to NYT. Mentioned Irish Times as local consideration.
- Offered to help with technical requirements documentation. Suggested CTO-type co-founder over just an engineer. Recommended $50-60K to pilot.

**CAPSTONE HIGHLIGHTS (Meg):**
- **Jenny's dishonesty pattern is one of the cleaner articulations of the incentive misalignment the content-based model solves. Worth a line in the methodology.**
- **The Wingman feedback loop idea emerged independently from a participant with a technical background. Worth noting as a product direction in the discussion.**


### Interview 15: Akshay, 25 (Indian, Dubai/UAE, TCD MSc, coder/app builder)

**Profile:** Tech-forward. Hackathon regular. Used Bumble and Hinge, never paid for either. Used dating apps as personal development (improving communication) rather than as a matching tool. Analytical, not bitter, about the structural asymmetry men face.

**Key findings:**
- **5% vs 15-20% improvement framing:** Traditional profiles show 5% of the real person. Times Two shows 15-20%. His reasoning: media consumption is subconscious and habitual. You cannot curate it the way you curate a bio. It is closer to the real person by definition. Most quantified articulation of the improvement case in the sample.
- **AdSense inversion (independently arrived at):** "They harvest your data to sell you things. This harvests your data to find you a better person." Cleaner than most versions of the data inversion argument. Made the connection without prompting.
- **Blind matching validated (male):** Completely fine without the photo. Said directly that someone could become more attractive through the quality of the conversation. Counter-example to the gendered photo-timing split.
- **AI companions as counter-argument:** Four of the top twenty most-used AI tools globally are AI companions. People substituting artificial connection for real connection. Times Two is the counter-argument.
- **Time Left validation:** Pointed to Time Left (supper club app) as the model that actually works for him. No dating intent, lower pressure, more genuine interaction. Independently validates the community events layer.
- **Demographic pushback (25-35 beachhead):** 18-21 year olds are not reading the NYT even with free academic access. The realistic target for organic adoption is 25-35 working professionals consuming premium content on commutes. University pilot is proof of concept, not primary market.
- **Wingman clarity:** The Wingman's job is the introduction. Once it has done that, it has done everything it can. The brief has to be done well. A poorly written brief would be worse than no brief.
- Dubai context: significant escort/fake profile problem on Tinder. Dublin is better. Adds texture to global category dysfunction.

**CAPSTONE HIGHLIGHTS (Akshay):**
- **"Media consumption is subconscious and therefore more honest than a self-curated bio" is the best single-sentence articulation of the core thesis in the entire interview sample. Write it into the capstone verbatim.**
- **Time Left comparison is footnote evidence for the community events thesis. A product with no dating intent that produces better social outcomes than a dating app validates that lower-stakes group formats produce more genuine interaction.**
- **25-35 working professionals as real beachhead (not students) should be addressed directly in the methodology. The university pilot is proof of concept and lifetime value capture. The real market is the cohort that comes next.**
- **Blind matching counter-example breaks the gendered photo-timing split. The split may be personality-driven rather than gender-driven. Worth a note in the findings -- Alex wanted photos immediately, Akshay doesn't. Both male.**


### Interview 16: Ahijah (TCD MSc cohort)

**Key findings:**
- **Game as conversation opener:** The games layer is not just a match signal. It is an interaction mechanism. Send a game challenge rather than an opening line. The interaction starts in the shared activity. No performance, no small talk. This is now reflected in the prototype (Screen 3 chat) and pitch deck.
- **"What you engage with every day is truly who you are":** His articulation of the revealed-preference thesis. What you say in a bio is what you think you like. What you actually click on, read, finish, play is a different signal entirely. Sharper than any prior version. Now in the pitch.
- **Daily ritual as identity signal:** The fact that someone does Connections every morning at 7am says something about discipline, routine, playfulness. Things no bio captures.
- **Competition as flirtation:** A game challenge is inherently playful. Creates stakes without vulnerability. Low-risk first interaction. If she sends a Wordle challenge and he bombs it, they laugh. If she sends "hey, you're cute" and he doesn't reply, she feels rejected. The game absorbs the social risk.

**CAPSTONE HIGHLIGHTS (Ahijah):**
- **"What you engage with every day is truly who you are" should be quoted in the capstone as a participant articulation of the revealed-preference argument.**
- **Game-as-opener is a design insight with theoretical weight: it removes performative self-presentation from the first interaction entirely. The shared activity replaces the audition.**


### Cross-Interview Pattern Update (Interviews 14-16)

**Wingman design converging across participants:**
- Meg: Mission Impossible brief. Fast, scannable, three things.
- Akshay: The brief has to be done well. Quality condition.
- Both independently: the Wingman's job is the introduction + feedback loop.
- Ahijah: game challenge as the opener the Wingman facilitates.

**Blind matching -- gendered split may be personality, not gender:**
- Alex (male): wants photo immediately, non-negotiable.
- Akshay (male): completely fine without photo, person can become more attractive through conversation.
- Previous female participants: generally willing to defer photo reveal.
- Conclusion: the split is not cleanly gendered. Both positions exist within male participants. Worth reframing in capstone as individual variation rather than gender pattern.

**Community events validated independently by third participant:**
- Interview 1: scarcity as feature
- Tessa: daily limits, match expiry
- Akshay: Time Left (supper club app with no dating intent) as the thing that actually works
- Meg: "I would use this" for friend matching, not dating

**Profile dishonesty problem -- strongest articulations:**
- Meg/Jenny: men presenting as progressive, arriving as the opposite
- Akshay: profiles show 5% of real person
- Ahijah: what you say vs what you do are different signals
- All three independently validate the content-over-bio thesis from different angles

