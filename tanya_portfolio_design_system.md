# Tanya Jain — Personal Portfolio
## Complete Design System · Wireframe · Architecture
### V1 — Pre-Implementation Reference

---

## PART 1: DESIGN SYSTEM

---

### 1.1 DESIGN BRIEF SYNTHESIS

**Subject:** Tanya Jain — AI & Applied Statistics student at Purdue, from Seattle; Study Abroad in Italy; journalist, marketer, teacher, researcher.

**Audience:** Recruiters, internship managers, professors, industry professionals.

**Single Job:** Prove that this person inhabits a rare and deliberate intersection — and make that intersection impossible to forget.

**What the inspiration images say collectively:**
- Pastel flowers (lilies, orchids, lotus): organic softness, femininity, refinement
- Seashells, starfish, coconuts: a travel-adjacent curiosity, tactile real-world objects
- Pink + green mood boards (Pantone references): editorial palette, intentional color pairing
- Vintage postage stamps: archival energy, global curiosity, handmade care
- Scrapbook-style collages (ring binders, pinned elements): personal archive aesthetic
- Color palettes (sage/pink/cream combos): anchors the palette precisely
- Polaroid frame with "With love": warmth, handwritten memory
- Pink pushpin: the organizational metaphor — things pinned to boards
- Pink Italy silhouette: travel identity
- Floral Vespa illustration: whimsy + Italy without being kitsch
- Crosley record player watercolor: music identity, vintage softness
- Watercolor book stack: academic + literary
- Graduation cap with pink bow: academic achievement, femininity
- Watercolor fruits: Mediterranean vibrancy, freshness
- Orange disco-ball mandarin: the aesthetic risk — the unexpected juxtaposition
- Curious George snorkeling: playful mascot energy
- Vintage concert tickets: music life, collected memories
- Fleetwood Mac ticket (detailed): archival, nostalgic, personal

**The Aesthetic Risk (one big distinctive choice):**
The site treats itself as a *curated collection* — every section is a different "room" in a private archive. The navigation bar is the door. Decorative assets are the labels and pins that identify each room. This is not a portfolio. It is an exhibition.

---

### 1.2 COLOR SYSTEM

#### Primary Palette

| Name | Hex | Role |
|---|---|---|
| Coconut Cream | `#FFFAF2` | Primary background — full page base |
| Forest Green | `#112A12` | Primary text — all body copy and headings |
| Archive Green | `#8BA888` | Primary UI green — cards, nav, accents |
| Petal Pink | `#EFCFD4` | Primary pink — hero, study abroad, interactive highlights |
| Dusty Rose | `#DDBAAE` | Secondary pink — card borders, hover states |
| Soft Lavender | `#CCB7E5` | Section background — concerts |
| Cloud Blue | `#DDEAF4` | Section background — subtle alternation |
| Honey | `#FFF1B8` | Pastel yellow accent — tags, highlights |
| Warm Cream | `#F6EAD4` | Card backgrounds, nested surfaces |

#### Section Background Map

| Section | Background Hex | Rationale |
|---|---|---|
| Navigation | `#FFFAF2` @ 85% opacity | Sticky, semi-opaque cream |
| Hero | `#FFFAF2` | Pure base |
| Data Dashboard | `#F6EAD4` | Warm nested surface, subtle step down |
| Projects | `#FFFAF2` | Clean, let postcards carry the color |
| Experiences | `#FFFAF2` | Clean, let timeline carry visual weight |
| Marketing Portfolio | `#F6EAD4` | Editorial warmth |
| Skills | `#8BA888` | Matcha green — exact PRD spec |
| Unexpected Intersections | `#FFFAF2` | Neutral — let postcard colors pop |
| Study Abroad | `#EFCFD4` | Petal Pink — exact PRD spec |
| Matcha Rankings | `#8BA888` | Archive Green — exact PRD spec |
| Concerts | `#CCB7E5` | Soft Lavender — exact PRD spec |
| Currently Learning | `#EFCFD4` | Petal Pink — exact PRD spec |
| Footer | `#112A12` | Forest Green reversed — corkboard goes dark |

#### State Colors

| State | Color | Usage |
|---|---|---|
| Hover — green elements | `#6A8A67` | Darken Archive Green 12% |
| Hover — pink elements | `#E0B5BC` | Darken Petal Pink 10% |
| Active / pressed | `#112A12` at 15% | Forest Green overlay |
| Focus ring | `#8BA888` 2px solid | All interactive elements |
| Disabled | `#DDBAAE` at 40% | Muted Dusty Rose |

---

### 1.3 TYPOGRAPHY SYSTEM

#### Typeface Roles

| Role | Typeface | Weight | Source |
|---|---|---|---|
| Name Logo | Parisienne | 400 | Google Fonts |
| Section Headers | Playfair Display | 600, 700 | Google Fonts |
| Body / UI text | Instrument Sans | 400, 500 | Google Fonts |
| Captions / Labels | Cormorant Garamond | 400, 500 italic | Google Fonts |
| Fallback body | Inter | 400 | System / Google |

#### Type Scale

```
Display (Name Logo)       Parisienne 400 — 52px / lh 1.1 / ls -0.02em
H1 (Section titles)       Playfair Display 700 — 40px / lh 1.15 / ls -0.01em
H2 (Card titles)          Playfair Display 600 — 28px / lh 1.2
H3 (Sub-section headers)  Playfair Display 600 — 20px / lh 1.3
Label (Eyebrows)          Cormorant Garamond 500 italic — 13px / lh 1.4 / ls 0.12em / uppercase
Body Large                Instrument Sans 400 — 18px / lh 1.7
Body                      Instrument Sans 400 — 16px / lh 1.7
Body Small                Instrument Sans 400 — 14px / lh 1.6
Caption                   Cormorant Garamond 400 italic — 13px / lh 1.5
Tag / Chip                Instrument Sans 500 — 11px / lh 1 / ls 0.08em / uppercase
```

#### Type Pairing Logic

Playfair Display is a high-contrast editorial serif — it carries authority and personality.
Instrument Sans is humanist and warm — never cold or mechanical.
Cormorant Garamond is delicate and calligraphic — used only for micro-text that should feel handwritten-adjacent.
The three together create the editorial-archive register without looking academic or cold.

---

### 1.4 SPACING SYSTEM

```
Base unit: 4px

--space-1:   4px    (micro gaps — icon to label)
--space-2:   8px    (tight component internal)
--space-3:   12px   (input padding, tag padding)
--space-4:   16px   (card internal padding small)
--space-5:   20px   (standard internal padding)
--space-6:   24px   (component spacing)
--space-8:   32px   (section element spacing)
--space-10:  40px   (large component gap)
--space-12:  48px   (section internal top/bottom)
--space-16:  64px   (between major components)
--space-20:  80px   (section vertical padding)
--space-24:  96px   (hero spacing)
--space-32:  128px  (major section separation)
```

#### Layout Grid

```
Desktop (1280px):  12-column grid, 80px gutters, 24px gaps
Tablet (768px):    8-column grid, 40px gutters, 20px gaps
Mobile (375px):    4-column grid, 20px gutters, 16px gaps

Max content width: 1200px, centered
Wide breakpoint:   1440px (decorative assets extend to edge)
```

---

### 1.5 CARD STYLES

#### Postcard Card (Projects)
```
Background:     #F6EAD4 (Warm Cream)
Border:         1px solid #DDBAAE
Border-radius:  12px
Box-shadow:     2px 4px 16px rgba(17,42,18,0.06)
Padding:        24px
Rotation:       Random ±1.5deg per card (CSS custom property, seeded)
Stamp element:  Top-right corner — SVG postage stamp cutout
Pin element:    Top-center — PNG pushpin cutout at z-index above card
Hover:          translateY(-6px) rotate(0deg), shadow deepens
```

#### Timeline Scrapbook Card (Experiences)
```
Background:     White (#FFFFFF)
Border:         1px solid #EFCFD4
Border-radius:  8px left, 2px right (torn-paper right edge via clip-path)
Left accent:    4px solid #8BA888
Padding:        20px 24px
Date chip:      Cormorant Garamond italic, Honey background
Hover:          Slide right 4px, left accent deepens to Forest Green
```

#### Skill Tag (Skills / Matcha Menu)
```
Background:     rgba(255,250,242,0.15) — semi-transparent cream on green bg
Border:         1px solid rgba(255,250,242,0.3)
Border-radius:  999px (pill)
Padding:        6px 14px
Text:           Instrument Sans 500 11px, Coconut Cream color
Hover:          Background opacity 0.30, scale(1.04)
```

#### Intersection Postcard (Unexpected Intersections)
```
Background:     #F6EAD4
Border:         1.5px solid #DDBAAE
Border-radius:  10px
Padding:        28px
Header line:    Cormorant Garamond italic label, Archive Green
Closed height:  180px (shows title + teaser line)
Open height:    Auto (reveals full story, examples, photos)
Animation:      Framer Motion layout animation, ease-out 300ms
```

#### Concert Ticket (Concerts)
```
Width:          340px
Height:         120px collapsed, 240px expanded
Background:     Aged paper — Warm Cream with subtle noise texture via SVG filter
Border:         1px solid #DDBAAE
Border-radius:  6px
Left stub:      48px wide, dashed right border, Cormorant Garamond vertical text
Perforation:    SVG dashed line at stub edge
Hover:          Left stub slides left 8px (accordion effect)
```

#### Polaroid Frame (Matcha Rankings)
```
Background:     White
Border:         12px solid white
Border-bottom:  32px solid white (polaroid bottom caption area)
Box-shadow:     2px 4px 12px rgba(17,42,18,0.10)
Border-radius:  3px
Caption area:   Cormorant Garamond italic, Forest Green
Rotation:       Random ±2deg
Hover:          Straightens, elevates
```

---

### 1.6 BUTTON STYLES

#### Primary Button
```
Background:     #112A12 (Forest Green)
Text:           #FFFAF2 (Coconut Cream)
Font:           Instrument Sans 500 14px
Padding:        10px 24px
Border-radius:  999px
Hover:          #8BA888 background (Archive Green)
Active:         scale(0.97)
Transition:     background 200ms ease, transform 150ms ease
```

#### Secondary Button (Ghost)
```
Background:     transparent
Border:         1.5px solid #112A12
Text:           #112A12
Padding:        10px 24px
Border-radius:  999px
Hover:          #EFCFD4 background, border stays
```

#### Icon Button (Social links in hero)
```
Background:     #F6EAD4
Border:         1px solid #DDBAAE
Width/Height:   40px × 40px
Border-radius:  50%
Icon:           Forest Green, 18px
Hover:          #EFCFD4 background, translateY(-2px)
```

#### Tag Button (Navigation anchors)
```
Font:           Instrument Sans 500 13px
Text:           #112A12
Underline:      none
Hover:          Color shifts to #8BA888, letter-spacing subtle increase
Active section: Petal Pink underline 2px, Forest Green text
```

---

### 1.7 HOVER STATES

| Component | Default | Hover |
|---|---|---|
| Postcard card | `rotate(±1.5deg) translateY(0)` | `rotate(0deg) translateY(-6px)` shadow deepens |
| Timeline card | `translateX(0)` | `translateX(4px)` |
| Navigation link | Color: Forest Green | Color: Archive Green + underline |
| Social icon button | Static | `translateY(-2px)` |
| Skill tag | `scale(1)` | `scale(1.04)` + tooltip appears |
| Concert ticket | Stub at 0 | Stub `translateX(-8px)` |
| Polaroid | `rotate(±2deg)` | `rotate(0deg) translateY(-4px)` |
| Flip card | Shows front | Card flips 180deg on Y axis |
| Intersection card | Collapsed | Expands via Framer Motion layout |
| Stat card (dashboard) | Counter shown | Subtle tooltip with context |
| Map pin | Static | Bounce animation, postcard opens |
| Monkey divider | Hidden | Appears, swims across screen |

---

### 1.8 ANIMATION RULES

#### Allowed Animation Types

| Name | Properties | Duration | Easing | Usage |
|---|---|---|---|---|
| Fade up reveal | `opacity 0→1, translateY 20px→0` | 400ms | `ease-out` | Section entry, card reveal |
| Parallax drift | `translateY` at 0.2× scroll rate | Scroll-driven | Linear | Hero decorative assets |
| Float (idle) | `translateY 0→-6px→0` | 3s | `ease-in-out` infinite | Pushpin, selected decoratives |
| Counter increment | Number count up | 1200ms | `ease-out` | Dashboard counters |
| Card flip | `rotateY 0→180deg` | 400ms | `ease-in-out` | Project postcard back |
| Expand reveal | Height animation via Framer layout | 300ms | `ease-out` | Intersection cards |
| Monkey swim | `translateX -200%→110vw` | 2000ms | `ease-in-out` | Section transition |
| Ticket unfold | `scaleY 1→2, translateY` | 350ms | `spring(damping 20)` | Concert ticket |
| Spin once | `rotate 0→360deg` | 600ms | `ease-in-out` | Disco orange on hover |

#### Forbidden

- Continuous spin unless mouse is held on element
- Bounce keyframes
- Shake / wiggle
- Any animation that loops more than once unless user is actively hovering
- Heavy physics simulations

#### Scroll Behavior

```
Scroll-driven reveals:  IntersectionObserver at 15% threshold
Stagger delay:          80ms per child item
Parallax:               CSS @scroll-timeline where supported, JS fallback
Section transitions:    Monkey divider triggers via IntersectionObserver
```

---

### 1.9 DECORATIVE ASSET USAGE RULES

All assets are PNG cutouts — no white boxes, no visible bounding boxes.

#### Asset-to-Section Map

| Asset | Section | Behavior | Position |
|---|---|---|---|
| Pink lily / orchid | Hero | Static, slight parallax drift | Left column, behind license |
| Postage stamps | Hero, Projects | Pinned, subtle float | Scattered near cards |
| Pushpin (pink 3D) | Hero, Projects | Static pin holding element | Top-center of pinned cards |
| Polaroid frame | Matcha, Hero | Photo container | Layout element |
| Italy silhouette (pink) | Study Abroad | Hero graphic, behind map | Center background |
| Vespa illustration | Study Abroad | Decorative, hover float | Bottom right of section |
| Record player | Concerts | Section header element | Top left of section |
| Watercolor books | Experiences | Section marker | Near academic experiences |
| Graduation cap | Experiences | Near education entries | Right accent |
| Watercolor fruits | Footer / Unexpected Intersections | Scattered, very small | Background accents |
| Disco orange | Skills | Hover-only spin, single rotation | Next to section header |
| Seashells/starfish | Life Outside Work | Matcha section accent | Scattered small |
| Curious George | Section dividers | Swims across screen | Full-width divider |
| Concert tickets | Concerts | Primary UI component | Grid of cards |
| Pink map pin | Study Abroad map | Interactive element | On each city |

#### Sizing Rules

```
Hero flowers:            max-width 280px, positioned absolutely
Section accent assets:   max-width 120px
Card-mounted stamps:     60px × 80px
Monkey (swimmer):        120px tall, full-width travel
Pushpin:                 48px × 48px, always above card z-index
```

---

### 1.10 IMAGE TREATMENT

```
Project images:     Postcard-ratio (4:3), border-radius 6px, inside postcard card
Matcha photos:      Inside polaroid frame (square crop), 240px × 240px
Concert memory:     Inside expanded ticket, 100% width, border-radius 4px
Study abroad:       Inside postcard overlays on map, 180px × 240px portrait
General photo:      Warm photo filter: sepia(8%) saturate(1.1)
```

---

## PART 2: WIREFRAME — TOP TO BOTTOM

---

### 2.1 NAVIGATION BAR

```
[DESKTOP — Full Width Sticky]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Tanya Jain          Projects  Experiences  Portfolio  Skills  Intersections  Life
  [Parisienne, 24px]  [Instrument Sans 500, 13px — anchor links]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Background:  rgba(255,250,242,0.90) with backdrop-filter blur(12px)
Height:      64px
Border:      bottom 0.5px solid #DDBAAE
Position:    sticky top-0 z-50

MOBILE: hamburger icon (Forest Green), full-screen overlay menu on tap
        Overlay: Coconut Cream background, Playfair Display nav items at 32px
```

**Behavior:** Active section highlights its nav link (Petal Pink underline). On scroll down 80px, nav condenses to 52px height.

---

### 2.2 HERO SECTION

```
[DESKTOP — 2 Column, 60/40 split]

Column LEFT (60%)                      Column RIGHT (40%)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
                                       [TRAVEL LICENSE — primary visual]
  📌                                   ┌─────────────────────────────┐
  [pushpin PNG, top of license]        │   [Driver's License style   │
                                       │    format card — custom      │
                                       │    illustration or photo]    │
  [Pink lily PNG — large, behind]      │                              │
                                       │   TANYA JAIN                 │
                                       │   Purdue University          │
                                       │   AI & Applied Statistics    │
                                       │   Seattle, WA                │
                                       └─────────────────────────────┘
                                       [2-3 vintage stamp PNGs around license]

Column LEFT content:
┌─────────────────────────────────────┐
│ EYEBROW: Cormorant italic 13px      │
│ "AI • Statistics • Storytelling"    │
│                                     │
│ H1: Parisienne 52px                 │
│ "Tanya Jain"                        │
│                                     │
│ BODY: Instrument Sans 18px          │
│ "Artificial Intelligence &          │
│  Applied Statistics @ Purdue        │
│  Based in Seattle, Washington"      │
│                                     │
│ [Projects ●] [Experiences]          │
│ [Portfolio] [GitHub ↗] [LinkedIn ↗] │
│ [primary btn] [ghost btn × 2]       │
│ [icon btns]                         │
└─────────────────────────────────────┘

[Bottom left: scattered small stamps]
[Far right edge: partial orchid PNG, overflows]
```

**Interactions:**
- Pushpin has a subtle float animation (infinite, slow)
- Stamps have very gentle parallax on scroll (move up at 0.15× scroll rate)
- Lily behind license: parallax at 0.2× scroll
- License card: light drop-shadow, slight tilt -1.5deg

**MOBILE:** License stacks above. Text centers below. Buttons stack vertically.

---

### 2.3 DATA DASHBOARD

```
[Full Width, background #F6EAD4]

EYEBROW (centered): "by the numbers"
H2 (centered): "A few highlights"

┌────────────┐  ┌────────────┐  ┌────────────┐  ┌────────────┐  ┌────────────┐
│  15+       │  │  70+       │  │ 10,000+    │  │  3         │  │  7+        │
│ Articles   │  │ Students   │  │ Readers    │  │ Years in   │  │ Leadership │
│ Published  │  │ Taught     │  │ Reached    │  │ Journalism │  │ Positions  │
└────────────┘  └────────────┘  └────────────┘  └────────────┘  └────────────┘

Card style: Archive Green (#8BA888) background, Forest Green text
Numbers: Playfair Display 700 36px
Labels: Instrument Sans 400 13px

Hover each card: Tooltip slides up beneath card
  "15+ articles published across the Sammamish Independent and other outlets"
  etc.
```

**Animation:** Numbers count up from 0 when section enters viewport (IntersectionObserver).

---

### 2.4 PROJECTS SECTION

```
[Full Width, background #FFFAF2]

EYEBROW: "Technical Work"
H1: "Projects"
[Small postage stamp PNG — top right of section]

GRID: 3 columns desktop, 2 tablet, 1 mobile
Gap: 32px

Each card = Postcard style:
┌─────────────────────────────────────┐
│ [📌 pushpin at top center]          │
│ [Vintage stamp PNG top-right]       │
│                                     │
│ LABEL: "AI Research"                │
│ H2: Project Name                    │
│ TLDR: One sentence. Clear impact.   │
│                                     │
│ TECH STACK: [React] [Flask] [Redis] │
│ [pill tags, Instrument Sans]        │
│                                     │
│ IMPACT LINE: ↑ Metric or outcome    │
│                                     │
│ [GitHub ↗]  [Demo ↗]               │
└─────────────────────────────────────┘
      ↕ Click/hover to flip ↕
┌─────────────────────────────────────┐  ← BACK of card
│                                     │
│ CHALLENGES:                         │
│ What I struggled with               │
│                                     │
│ LESSONS LEARNED:                    │
│ What I took away                    │
│                                     │
│ [GitHub ↗] [Demo ↗]                │
└─────────────────────────────────────┘
```

**Cards list (5 total):**
1. AI & Safety in Systematic Review Research
2. UpTick (React, Flask, ML)
3. LLM Research Assistant (FastAPI, DAG)
4. Purdue & J&J Go/No-Go (R, Shiny)
5. Purdue EdTechDev (MicroPython, Pico)

**Interactions:**
- Hover: card straightens, lifts, reveals "flip" hint at bottom
- Click: Framer Motion `rotateY` flip to back face
- Each card has a unique stamp PNG
- Cards have randomized rotation ±1.5deg by default

---

### 2.5 SECTION DIVIDER — MONKEY #1

```
[Full viewport width, 120px tall]
Background transparent — sits between Projects and Experiences

[Curious George snorkeling PNG swims LEFT → RIGHT]
Animation: translateX(-200px → calc(100vw + 200px)) over 2s, ease-in-out
Trigger: IntersectionObserver when divider is 30% visible
After monkey exits: Next section fades up
```

---

### 2.6 EXPERIENCES SECTION

```
[Full Width, background #FFFAF2]

EYEBROW: "Career Story"
H1: "Experiences"

LEFT: Vertical timeline line (1px, #DDBAAE dashed)
      Small pink dot at each entry

RIGHT: Scrapbook timeline cards (alternating left/right on desktop)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 ●  ┌─────────────────────────────────────┐
    │ [Graduation cap PNG — small right]  │
    │ DATES: "2023 — Present"             │ ← Honey bg chip
    │ ROLE: Corporate Sponsorships        │
    │ ORG: InnovateHER                    │
    │ LOCATION: Purdue                    │
    │                                     │
    │ Description: 2-3 sentences          │
    │                                     │
    │ IMPACT: [metric or outcome]         │
    └─────────────────────────────────────┘
 ●  ┌────────────── (alternates) ────────┐
    │ ...                                 │
    └─────────────────────────────────────┘

BELOW MAIN TIMELINE:
H3: "Campus Involvement"
[Row of pill bubbles — no descriptions]
┌─────────────────┐ ┌──────────────────┐ ┌─────────────────┐
│  Women in       │ │  Building CEOs   │ │  Dataception    │
│  Science        │ │  Program         │ │  Coordinator    │
└─────────────────┘ └──────────────────┘ └─────────────────┘
[Women in Business] [Momentum]

Bubble style: #F6EAD4 bg, #DDBAAE border, Forest Green text, Cormorant italic
```

**Experiences (main):**
1. Corporate Sponsorships — InnovateHER
2. Undergraduate TA — The Data Mine
3. Software Engineering Intern — EduVerse
4. Service & Alumni Committee Head — Alpha Kappa Psi
5. Editor, Education Beat — Sammamish Independent

---

### 2.7 MARKETING PORTFOLIO SECTION

```
[Full Width, background #F6EAD4]

EYEBROW: "Storytelling & Brand"
H1: "Marketing Portfolio"

LAYOUT: Editorial magazine grid
  Large feature card (spans 2 columns) + smaller cards in 3-column grid

[Large card — Journalism feature]
┌──────────────────────────────────────────────────┐
│  [Large image / mockup placeholder]              │
│                                                  │
│  JOURNALISM                                      │
│  "Education Beat: Three Years of Stories"        │
│  10,000+ readers reached                         │
└──────────────────────────────────────────────────┘

[Smaller cards]
┌──────────────┐ ┌──────────────┐ ┌──────────────┐
│ Social Media │ │  Campaign    │ │  Brand       │
│              │ │  Strategy    │ │  Storytelling│
└──────────────┘ └──────────────┘ └──────────────┘

Categories available as filter tabs:
[All] [Journalism] [Social Media] [Campaign] [Analytics] [Brand] [Copywriting] [Content]

Clicking any card → Modal opens:
┌────────────────────────────────────────────────────────┐
│ [X close]                                              │
│                                                        │
│ H2: Project Name                                       │
│ CATEGORY tag | DATE tag                                │
│                                                        │
│ [Visuals / mockups]                                    │
│                                                        │
│ Description — what, why, how                           │
│ Metrics — numbers, reach, outcomes                     │
│ Deliverables — what was made                           │
│ Reflection — what I learned                            │
└────────────────────────────────────────────────────────┘
Modal: backdrop-filter blur(8px), #FFFAF2 card, Framer Motion scale in
```

---

### 2.8 SKILLS SECTION

```
[Full Width, background #8BA888 (Archive Green)]

EYEBROW: "Capabilities" [Coconut Cream color]
H1: "Skills" [Coconut Cream color, Playfair Display]

[Disco orange PNG — top right of section header]
  → On hover: single 360deg rotation (Framer Motion)

LAYOUT: Matcha menu aesthetic — left labels, right skill pills

┌─────────────────────────────────────────────────────────┐
│  AI & Machine Learning          [NLP] [LLMs] [RAG]     │
│                                 [scikit-learn] [HuggingFace] │
├─────────────────────────────────────────────────────────┤
│  Statistics & Analytics         [R] [Shiny] [Pandas]   │
│                                 [Regression] [MMM]      │
├─────────────────────────────────────────────────────────┤
│  Programming Languages          [Python] [JavaScript]  │
│                                 [TypeScript] [SQL] [R]  │
├─────────────────────────────────────────────────────────┤
│  Marketing                      [SEO] [Copywriting]    │
│                                 [Campaign Strategy]     │
├─────────────────────────────────────────────────────────┤
│  Research                       [Systematic Review]    │
│                                 [Academic Writing]      │
├─────────────────────────────────────────────────────────┤
│  Tools                          [React] [FastAPI]      │
│                                 [Framer] [Figma]        │
└─────────────────────────────────────────────────────────┘

Hover each skill pill:
→ Tooltip slides up: "Used in [Project Name]" or "Confidence: Expert / Growing"
```

---

### 2.9 SECTION DIVIDER — MONKEY #2

```
Same monkey animation — swims RIGHT → LEFT this time (mirrored)
Between Skills and Unexpected Intersections
```

---

### 2.10 UNEXPECTED INTERSECTIONS SECTION

```
[Full Width, background #FFFAF2]

EYEBROW: "Why I'm Different"
H1: "Unexpected Intersections"

LAYOUT: 3 expandable postcard cards, stacked (not grid)

Card 1: AI × Marketing
┌──────────────────────────────────────────────────────────┐
│  LABEL: "Intersection 01"            [Collapsed]        │
│  H2: "AI × Marketing"                         ▼         │
│  TEASER: "What happens when algorithms meet audience..." │
└──────────────────────────────────────────────────────────┘

On click (Framer Motion expand):
┌──────────────────────────────────────────────────────────┐
│  H2: "AI × Marketing"                         ▲         │
│                                                          │
│  STORY: 2-3 paragraphs                                   │
│  EXAMPLES: Bullet list or mini cards                     │
│  PROJECTS: Linked                                        │
│  LESSONS LEARNED: Final paragraph                        │
└──────────────────────────────────────────────────────────┘

Card 2: Journalism × Technology
Card 3: Technical Communication × Travelling
```

---

### 2.11 SECTION DIVIDER — MONKEY #3

```
Between Unexpected Intersections and Life Outside Work
Same swim animation — LEFT → RIGHT
```

---

### 2.12 LIFE OUTSIDE WORK — STUDY ABROAD

```
[Full Width, background #EFCFD4 (Petal Pink)]

EYEBROW: "Italy, 2024"
H1: "Study Abroad"

LAYOUT: Left column (text + map), Right accent (Italy silhouette)

LEFT:
  [React Leaflet map — custom styled, muted cream tiles]
  Pins at: Rome, Sorrento, Positano, Capri

  Clicking a pin → Postcard overlay appears:
  ┌────────────────────────┐
  │ [Photo placeholder]    │
  │ CITY NAME              │
  │ Memory / favorite spot │
  │ Note in Cormorant      │
  └────────────────────────┘

RIGHT ACCENT:
  [Pink Italy silhouette PNG — large, 400px tall]
  [Vespa illustration PNG — bottom right, 200px]
  [Small stamp PNGs scattered]

BELOW MAP:
  AI & Safety Research Feature
  ┌───────────────────────────────────────────┐
  │  Research Focus: AI & Safety in           │
  │  Systematic Review                        │
  │  [Key Takeaways — 3 bullet points]        │
  │  [Link to paper / GitHub]                 │
  └───────────────────────────────────────────┘
```

---

### 2.13 LIFE OUTSIDE WORK — MATCHA RANKINGS

```
[Full Width, background #8BA888]

EYEBROW: "The Important Stuff"
H1: "Matcha Rankings"

LAYOUT: Horizontal scroll row of Polaroid cards on desktop
        Stack on mobile

Each Polaroid:
┌──────────────────┐
│ ┌──────────────┐ │  ← Polaroid white frame
│ │ [Photo]      │ │
│ └──────────────┘ │
│                  │
│  Café Name       │  ← Caption area (Cormorant italic)
│  City, Country   │
│  ★★★★☆  4.2/5   │
│  "Oat, no syrup" │
└──────────────────┘

Rating shown as filled Archive Green stars on Coconut Cream background

Each polaroid rotates ±2deg randomly.
Hover: Straightens, lifts.
Click: Opens full matcha notes overlay.
```

---

### 2.14 LIFE OUTSIDE WORK — CONCERTS

```
[Full Width, background #CCB7E5 (Soft Lavender)]

EYEBROW: "Live Music"
H1: "Favorite Concerts"

[Record player PNG — header left accent]

LAYOUT: Grid of vintage concert ticket cards, 3 columns desktop

Each Ticket:
┌─────┬────────────────────────────────────┐
│     │  ARTIST NAME                       │
│ STB │  Venue, City                       │
│ 01  │  Month DD, YEAR                    │
│     │  "My favorite song that night"     │
└─────┴────────────────────────────────────┘

STB = Stub area (left 48px, Cormorant vertical text)

Hover: Stub slides left (accordion)
Click: Ticket expands to show:
  - Larger memory text
  - Optional photo
  - Favorite song highlighted
  - Memory paragraph
```

---

### 2.15 LIFE OUTSIDE WORK — CURRENTLY LEARNING

```
[Full Width, background #EFCFD4]

EYEBROW: "Always Growing"
H1: "Currently Learning"

LAYOUT: 3 pinned notebook paper cards

Each Card (notebook paper aesthetic — faint horizontal lines, torn top):
┌──────────────────────────────────────────┐
│ 📌  [pushpin top]                        │
│                                          │
│ H3: AI Answer Engine Optimization        │
│                                          │
│ Why I'm interested: ...                  │
│ Current resources: ...                   │
│ Potential applications: ...              │
└──────────────────────────────────────────┘

Notebook lines: CSS repeating-linear-gradient
Paper texture: Very subtle
```

---

### 2.16 FOOTER

```
[Full Width, background #112A12 (Forest Green — dark)]

EYEBROW: "Get in Touch"  [Coconut Cream]
H2: "Let's work together."  [Coconut Cream, Playfair Display]

LAYOUT: Corkboard-style — scattered cards pinned to dark green

[Email card — polaroid style, white bg]
  tanyajain@purdue.edu

[LinkedIn card — polaroid style]
  /in/tanya-jain

[GitHub card — polaroid style]
  github.com/tanyajain

[Resume card — polaroid style, with pink pushpin]
  Download Resume ↓

[Location tag]
  📍 Seattle, WA

Bottom bar:
  "Tanya Jain" [Parisienne]        "Made with care. © 2025"

[Small scattered flower PNGs at corners — barely visible on dark bg]
```

---

### 2.17 SECTION TRANSITION SUMMARY (TOP → BOTTOM)

```
Hero
  ↓ [fade up on scroll]
Data Dashboard
  ↓ [fade up on scroll]
Projects
  ↓ [MONKEY SWIM LEFT→RIGHT]
Experiences
  ↓ [fade up on scroll]
Marketing Portfolio
  ↓ [fade up on scroll]
Skills
  ↓ [MONKEY SWIM RIGHT→LEFT]
Unexpected Intersections
  ↓ [MONKEY SWIM LEFT→RIGHT]
Life Outside Work:
  → Study Abroad
  → Matcha Rankings
  → Concerts
  → Currently Learning
  ↓ [fade up on scroll]
Footer
```

---

## PART 3: FILE ARCHITECTURE

---

### 3.1 COMPLETE FILE STRUCTURE

```
tanya-portfolio/
├── README.md
├── package.json
├── next.config.ts
├── tailwind.config.ts
├── tsconfig.json
├── postcss.config.js
│
├── public/
│   ├── assets/
│   │   ├── flowers/
│   │   │   ├── pink-lily.png
│   │   │   ├── orchid-pink.png
│   │   │   ├── lotus-white.png
│   │   │   ├── cherry-blossom.png
│   │   │   └── hibiscus-pink.png
│   │   ├── stamps/
│   │   │   ├── stamp-indonesia.png
│   │   │   ├── stamp-nippon.png
│   │   │   ├── stamp-china.png
│   │   │   ├── stamp-ethiopia.png
│   │   │   └── stamp-generic.png
│   │   ├── illustrations/
│   │   │   ├── pushpin-pink.png
│   │   │   ├── italy-silhouette-pink.png
│   │   │   ├── vespa-floral.png
│   │   │   ├── record-player.png
│   │   │   ├── books-watercolor.png
│   │   │   ├── graduation-cap.png
│   │   │   ├── monkey-snorkeling.png
│   │   │   ├── orange-disco.png
│   │   │   └── polaroid-frame.png
│   │   ├── shells/
│   │   │   ├── scallop.png
│   │   │   ├── starfish-blue.png
│   │   │   └── coral-pink.png
│   │   ├── fruits/
│   │   │   ├── lemon.png
│   │   │   ├── strawberry.png
│   │   │   └── grapefruit.png
│   │   └── profile/
│   │       ├── travel-license.jpg  ← Primary hero visual
│   │       └── headshot.jpg
│   │
│   ├── fonts/                       ← Self-hosted fallback
│   └── og-image.jpg                 ← Open Graph image
│
├── src/
│   ├── app/
│   │   ├── layout.tsx               ← Root layout, fonts, metadata
│   │   ├── page.tsx                 ← Single page — all sections
│   │   ├── globals.css              ← CSS variables, base styles
│   │   └── fonts.ts                 ← next/font declarations
│   │
│   ├── components/
│   │   ├── layout/
│   │   │   ├── Navigation.tsx       ← Sticky nav, anchor links, mobile menu
│   │   │   ├── MobileMenu.tsx       ← Full-screen overlay mobile nav
│   │   │   ├── SectionWrapper.tsx   ← Standard section padding + reveal
│   │   │   └── MonkeyDivider.tsx    ← Animated monkey swimmer
│   │   │
│   │   ├── hero/
│   │   │   ├── HeroSection.tsx      ← 2-column layout container
│   │   │   ├── TravelLicense.tsx    ← License card component
│   │   │   ├── HeroText.tsx         ← Name, title, CTA buttons
│   │   │   └── HeroDecorations.tsx  ← Flowers, stamps, pushpin
│   │   │
│   │   ├── dashboard/
│   │   │   ├── DataDashboard.tsx    ← Stats section container
│   │   │   ├── StatCard.tsx         ← Individual stat with counter
│   │   │   └── AnimatedCounter.tsx  ← Count-up number animation
│   │   │
│   │   ├── projects/
│   │   │   ├── ProjectsSection.tsx  ← Grid container
│   │   │   ├── ProjectCard.tsx      ← Postcard card with flip
│   │   │   ├── ProjectCardBack.tsx  ← Flip back face
│   │   │   └── TechBadge.tsx        ← Pill tag for tech stack
│   │   │
│   │   ├── experiences/
│   │   │   ├── ExperiencesSection.tsx
│   │   │   ├── TimelineCard.tsx     ← Scrapbook card
│   │   │   ├── TimelineLine.tsx     ← Dashed vertical line
│   │   │   └── ClubBubble.tsx       ← Pill for campus clubs
│   │   │
│   │   ├── marketing/
│   │   │   ├── MarketingSection.tsx
│   │   │   ├── PortfolioGrid.tsx    ← Editorial magazine grid
│   │   │   ├── PortfolioCard.tsx    ← Individual piece card
│   │   │   ├── CategoryFilter.tsx   ← Tab filter bar
│   │   │   └── PortfolioModal.tsx   ← Framer Motion modal
│   │   │
│   │   ├── skills/
│   │   │   ├── SkillsSection.tsx    ← Matcha menu on green bg
│   │   │   ├── SkillCategory.tsx    ← Row: label + pills
│   │   │   ├── SkillPill.tsx        ← Individual skill with tooltip
│   │   │   └── DiscoOrange.tsx      ← Hover-spin decorative
│   │   │
│   │   ├── intersections/
│   │   │   ├── IntersectionsSection.tsx
│   │   │   └── IntersectionCard.tsx ← Expandable postcard
│   │   │
│   │   ├── life/
│   │   │   ├── LifeSection.tsx      ← Container for all Life subsections
│   │   │   ├── study-abroad/
│   │   │   │   ├── StudyAbroadSection.tsx
│   │   │   │   ├── ItalyMap.tsx     ← React Leaflet map
│   │   │   │   ├── MapPin.tsx       ← Custom pin component
│   │   │   │   ├── PostcardOverlay.tsx ← City postcard popup
│   │   │   │   └── ResearchFeature.tsx ← Paper highlight card
│   │   │   ├── matcha/
│   │   │   │   ├── MatchaSection.tsx
│   │   │   │   ├── PolaroidCard.tsx ← Matcha entry
│   │   │   │   └── StarRating.tsx
│   │   │   ├── concerts/
│   │   │   │   ├── ConcertsSection.tsx
│   │   │   │   └── TicketCard.tsx   ← Concert ticket with expand
│   │   │   └── learning/
│   │   │       ├── LearningSection.tsx
│   │   │       └── NotebookCard.tsx  ← Pinned notebook card
│   │   │
│   │   ├── footer/
│   │   │   ├── Footer.tsx           ← Dark corkboard footer
│   │   │   └── ContactCard.tsx      ← Polaroid contact item
│   │   │
│   │   └── ui/
│   │       ├── Button.tsx           ← Primary / Ghost / Icon buttons
│   │       ├── Badge.tsx            ← Category / date badges
│   │       ├── Tooltip.tsx          ← Hover tooltip
│   │       ├── Modal.tsx            ← Base modal with backdrop
│   │       ├── DecorativeAsset.tsx  ← Wrapper for PNG cutouts
│   │       └── SectionLabel.tsx     ← Eyebrow + H1 pair
│   │
│   ├── data/
│   │   ├── projects.ts              ← All 5 project entries
│   │   ├── experiences.ts           ← All 5 experiences + clubs
│   │   ├── marketing.ts             ← Marketing portfolio pieces
│   │   ├── skills.ts                ← Skill categories + items
│   │   ├── intersections.ts         ← 3 intersection stories
│   │   ├── studyAbroad.ts           ← City pins + postcards
│   │   ├── matcha.ts                ← Matcha entries
│   │   ├── concerts.ts              ← Concert entries
│   │   └── learning.ts              ← Currently learning cards
│   │
│   ├── hooks/
│   │   ├── useScrollReveal.ts       ← IntersectionObserver hook
│   │   ├── useActiveSection.ts      ← Nav highlight tracking
│   │   ├── useCountUp.ts            ← Animated number counter
│   │   └── useParallax.ts           ← Scroll parallax values
│   │
│   ├── lib/
│   │   ├── cn.ts                    ← clsx + tailwind-merge utility
│   │   └── constants.ts             ← Site-wide constants
│   │
│   ├── styles/
│   │   └── animations.css           ← Keyframes for CSS-only animations
│   │
│   └── types/
│       ├── project.ts               ← Project type definition
│       ├── experience.ts            ← Experience type definition
│       ├── marketing.ts             ← Marketing piece type
│       ├── skill.ts                 ← Skill + category type
│       ├── concert.ts               ← Concert entry type
│       └── matcha.ts                ← Matcha entry type
```

---

### 3.2 KEY TYPE DEFINITIONS

```typescript
// types/project.ts
export interface Project {
  id: string
  title: string
  tldr: string
  techStack: string[]
  impact: string
  label: string         // e.g. "AI Research"
  githubUrl?: string
  demoUrl?: string
  challenges: string
  lessonsLearned: string
  stampAsset: string    // filename from /public/assets/stamps/
  rotation: number      // -1.5 to 1.5 degrees
}

// types/experience.ts
export interface Experience {
  id: string
  role: string
  organization: string
  dateRange: string
  location: string
  description: string[]
  impact?: string
  decorativeAsset?: string  // e.g. "graduation-cap.png"
}

// types/concert.ts
export interface Concert {
  id: string
  artist: string
  venue: string
  city: string
  year: number
  favoriteSong: string
  memory: string
  photoUrl?: string
  stubColor: string    // background for stub element
}

// types/matcha.ts
export interface MatchaEntry {
  id: string
  cafeName: string
  location: string
  drinkOrdered: string
  rating: number       // 0-5
  notes: string
  photoUrl: string
  rotation: number     // -2 to 2 degrees
}
```

---

### 3.3 ANIMATION UTILITIES

```typescript
// Framer Motion variants used across site

// Fade up reveal (scroll-triggered)
export const fadeUpVariant = {
  hidden: { opacity: 0, y: 20 },
  visible: { opacity: 1, y: 0, transition: { duration: 0.4, ease: 'easeOut' } }
}

// Stagger container
export const staggerContainer = {
  hidden: {},
  visible: { transition: { staggerChildren: 0.08 } }
}

// Card flip
export const flipVariants = {
  front: { rotateY: 0 },
  back: { rotateY: 180 }
}

// Monkey swim
export const monkeySwim = {
  initial: { x: '-200px' },
  animate: { x: 'calc(100vw + 200px)' },
  transition: { duration: 2, ease: 'easeInOut' }
}

// Expand card
export const expandCard = {
  collapsed: { height: 180 },
  expanded: { height: 'auto' },
  transition: { duration: 0.3, ease: 'easeOut' }
}

// Disco orange spin (once on hover)
export const spinOnce = {
  rotate: [0, 360],
  transition: { duration: 0.6, ease: 'easeInOut' }
}
```

---

### 3.4 TAILWIND CONFIG EXTENSIONS

```typescript
// tailwind.config.ts extensions needed:

colors: {
  cream:    { DEFAULT: '#FFFAF2', warm: '#F6EAD4' },
  forest:   '#112A12',
  archive:  '#8BA888',
  petal:    '#EFCFD4',
  dusty:    '#DDBAAE',
  lavender: '#CCB7E5',
  cloud:    '#DDEAF4',
  honey:    '#FFF1B8',
},
fontFamily: {
  parisienne: ['Parisienne', 'cursive'],
  playfair:   ['Playfair Display', 'serif'],
  instrument: ['Instrument Sans', 'sans-serif'],
  cormorant:  ['Cormorant Garamond', 'serif'],
},
```

---

### 3.5 DEPENDENCIES

```json
{
  "dependencies": {
    "next": "^14.x",
    "react": "^18.x",
    "react-dom": "^18.x",
    "framer-motion": "^11.x",
    "react-leaflet": "^4.x",
    "leaflet": "^1.x",
    "clsx": "^2.x",
    "tailwind-merge": "^2.x"
  },
  "devDependencies": {
    "typescript": "^5.x",
    "tailwindcss": "^3.x",
    "@types/react": "^18.x",
    "@types/leaflet": "^1.x",
    "autoprefixer": "^10.x",
    "postcss": "^8.x"
  }
}
```

---

## PART 4: NON-NEGOTIABLE IMPLEMENTATION RULES

---

1. **No purple gradients, glassmorphism, or floating blobs** — any of these triggers a full redesign of the offending component.

2. **All PNG assets must have transparent backgrounds** — if any asset has a white bounding box visible, it is unusable.

3. **Decorative assets are UI components** — every flower, stamp, pin has a defined position, z-index, and animation rule. Nothing is "just placed for aesthetics."

4. **Projects and Experiences sections carry the most visual weight** — decorative elements must not overpower them.

5. **Personality enhances; it does not overpower** — the monkey divider appears exactly 3 times. The disco orange spins once. The pushpin floats gently. Restraint is the rule.

6. **Mobile-first** — every component is designed for 375px first, then expanded to desktop. No horizontal overflow.

7. **Section backgrounds alternate meaningfully** — the color map in 1.2 is final. Sections must not have identical backgrounds unless intentionally grouped.

8. **Font loading** — all four typefaces (Parisienne, Playfair Display, Instrument Sans, Cormorant Garamond) are loaded via `next/font/google` with `display: swap` and proper subset specification.

9. **Framer Motion `layout` prop** — used on all expanding cards to ensure natural, physics-free layout animations.

10. **Leaflet map** — must use a custom tile style (muted cream palette, not the default blue OpenStreetMap). Recommend Stamen Toner Lite or a custom Mapbox style.

11. **The emotional target**: When a recruiter finishes scrolling, they think: *"This is one of the most thoughtful student portfolios I've ever seen."* Not because it's flashy. Because it is completely, unmistakably Tanya.

---

*Design System V1 — Ready for Implementation*
*Next step: Build components in order: layout → hero → dashboard → projects*
