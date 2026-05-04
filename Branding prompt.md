
Prompt 130 tokens

BRAND: financial models 
AUTHOR:Roman Zajic
COLORS: primary #005A5A | mid #008282 | accent #50C1C1 | light #95DFDB | amber #E1A01E | danger #C41E3A | bg #F0FAFA | card #FFFFFF | border #D0ECEB. Dark: bg #012D2C | card #032F2E | text #95DFDB
TYPE: "Segoe UI", system-ui, sans-serif | mono: "Segoe UI Mono", Cascadia Mono | 15px/1.6 | headings 600w
UI: radius 10px | shadow rgba(1,45,44,.10) | max-width 960px | btn-primary: #005A5A bg/#95DFDB text | badges: teal=input, amber=output, red=error | metric cards: left-border accent, amber for output cells
VOICE (Precision·Rigour·Transparency·Accessibility): ✓ specific figures+currency+period, name methodology, active voice ✗ vague amplifiers (significant/robust/strong), unqualified forward-looking statements

Prompt 700 tokens

## financial models

### COLORS
Teal-900:#005A5A | Teal-700:#008282 | Teal-400:#50C1C1 | Teal-100:#95DFDB | Amber:#E1A01E | Red:#C41E3A | Ink:#012D2C
Light: text=#005A5A muted=#008282 bg=#F0FAFA card=#FFFFFF border=#D0ECEB
Dark:  text=#95DFDB muted=#50C1C1 bg=#012D2C card=#032F2E border=#0A5050
Contrast: white/teal-900(8.05 AAA) | teal-900/white(8.05 AAA) | ink/teal-100(9.81 AAA) | ink/amber(6.55 AA)

### TYPOGRAPHY
UI: "Segoe UI",system-ui,sans-serif | weights: 400 body · 600 headings/labels/buttons
Mono: "Segoe UI Mono","Cascadia Mono",ui-monospace | tabular-nums | use for ALL financial values, table cells, outputs
Scale: xl=28px/600 | lg=20px/600 | md=16px/400 | sm=14px/400 | xs=12px/muted | mono=14px
Base: 15px body / line-height:1.6 / -webkit-font-smoothing:antialiased

### SPACING (4px base)
4 icon-gap | 8 badge-pad | 12 btn-v-pad | 16★ card/input-base | 20 card-comfortable | 24 section-gap | 32 panel-pad | 48 page-rhythm | 64 hero-pad
Radius: cards/inputs=10px | buttons=6px | badges=999px | phase-tags=4px | status=7px

### BUTTONS (font-weight:600 transition:130ms border:1px)
Primary:   bg=#005A5A text=white | hover bg=#008282 | dark: bg=#50C1C1 text=#012D2C hover bg=#95DFDB
Outline:   bg=transparent text=var(--text) border=#D0ECEB | hover border+text=#008282 | dark hover #50C1C1
Danger:    bg=#C41E3A text=white | hover bg=#A01830
Sizes: sm=12px/6·14px | default=14px/9·20px | lg=16px/12·28px | radius:6px | disabled opacity:0.4

### BADGES (11px/600 radius:999px pad:3·9px)
Input:   bg=#95DFDB text=#005A5A
Output:  bg=#E1A01E text=#012D2C
Error:   bg=#FDEAED text=#C41E3A
Positive:bg=#E8F5EE text=#1A7A4A
Neutral: bg=surface-in border=#D0ECEB text=muted

### INPUTS (14px radius:6px pad:9·12px border:#D0ECEB width:100%)
Hover: border=#008282 | Focus: border=#008282 + ring 0 0 0 3px rgba(0,130,130,.15)
Error: border=#C41E3A | Placeholder: #7A9E9E | Mono-input: font-mono tabular-nums text-right
Dark focus: border=#50C1C1 ring rgba(80,193,193,.20)

### CARDS (radius:10px shadow:0 1px 4px rgba(1,45,44,.10) border:#D0ECEB)
Standard:   bg=white pad:20px | title 16px/600 | body 14px/muted/lh:1.55 | footer border-top pad-top:12px
Output card:border-left:3px #E1A01E | light bg:#FFFCF2
Metric card:border-left:3px #008282 | label 11px/600/uppercase/ls:0.06em | value mono/28px/600/lh:1.1 | delta 14px/600
Metric output:border-left:#E1A01E light-bg:#FFFCF2 | dark border-left:#50C1C1

### DELTA COLORS
Up:   light #0F6B3A | dark #3DD68C
Down: light #B01831 | dark #F87171

### STATUS BANNERS (14px radius:7px pad:12·16px)
ok:   light bg:#E8F5EE text:#1A7A4A | dark bg:#0B2E1B text:#5EC98A border:#1A4A2E
warn: light bg:#FDF3D7 text:#7A5000 | dark bg:#231800 text:#C89A40 border:#3D2D00
err:  light bg:#FDEAED text:#C41E3A | dark bg:#2E0A10 text:#E06070 border:#4A1520
info: bg=surface-in text=var(--text) border=#D0ECEB

### TABLES (14px border-collapse font=UI)
thead: 11px/600/uppercase/ls:0.06em bg=surface-in border-bottom:2px #D0ECEB | numeric cols: right-align
tbody: td pad:10·16px | hover bg=surface-in | numeric: font-mono tabular-nums text-right
Output col: light bg:#FDF3D7 text:#012D2C | dark bg:#0A3D3D text:#95DFDB | font:mono/600

### NAVBAR (h:52px bg=#005A5A sticky)
Brand: 16px/600 color=#95DFDB | Links: 13px/500 rgba(149,223,219,.75) hover-bg rgba(149,223,219,.10) radius:5px

### VOICE — Precision · Rigour · Transparency · Accessibility
✓ Specific figures with currency + period: "£55.4m FY2025"
✓ Name model type and methodology explicitly
✓ Active voice: "the model projects £55.4m revenue"
✓ State assumptions; cite sources; show working; explain the why
✗ Vague amplifiers: significant / robust / strong
✗ Forward-looking statements without caveats
✗ Charts or UI elements substituting for absent data