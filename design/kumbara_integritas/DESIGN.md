---
name: Kumbara Integritas
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#3d4a42'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#6d7a72'
  outline-variant: '#bccac0'
  surface-tint: '#006c4a'
  primary: '#006948'
  on-primary: '#ffffff'
  primary-container: '#00855d'
  on-primary-container: '#f5fff7'
  inverse-primary: '#68dba9'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#006194'
  on-tertiary: '#ffffff'
  tertiary-container: '#007bb9'
  on-tertiary-container: '#fdfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#85f8c4'
  primary-fixed-dim: '#68dba9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#005137'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 24px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style
The design system powers an interactive gamified civic-education platform tailored for Indonesian primary to secondary students (SD Kelas 1-3 through SMA). The visual identity combines **tactile gamification** with **approachable civic clarity**. 

The brand personality centers on optimism, courage, upright moral agency (*kejujuran*), and shared adventure. The UI avoids bureaucratic severity, choosing instead to portray integrity as a vibrant, empowering quest. Tactile physical metaphors—soft embossed pill buttons, game-piece tokens, vibrant board cell tiles, and playful elevation—evoke natural tactile joy for younger learners, while structural cleanliness and lucid typographic hierarchies maintain respect and engagement for older secondary students.

## Colors
The system employs an uplifting, high-contrast daylight palette built upon symbolic associations:

- **Primary (Emerald & Mint - `#059669` / `#10B981`):** Represents moral clarity, anti-corruption steadfastness, growth, and victorious progression. Surfaces leverage subtle tints (`#F0FDF4`) for canvas grounding.
- **Secondary (Warm Amber & Gold - `#D97706` / `#F59E0B`):** Denotes ladders, earned virtue badges, experience points, and celebratory accomplishments.
- **Snake / Dilemma Danger (Crimson Coral - `#DC2626` / `#EF4444`):** Expresses ethical pitfalls, warning checkpoints, corruption consequence tiles, and sliding downward snakes.
- **Tertiary Accent (Cyan / Sky Blue - `#0284C7` / `#38BDF8`):** Used for knowledge prompts, rulebooks, situational dilemmas, and automated guide companions.
- **Player Character Tokens:** Jade Green (`#059669`), Sun Gold (`#F59E0B`), Ruby Red (`#EF4444`), and Ocean Blue (`#0284C7`).
- **Surfaces & Backgrounds:** Crisp dual-tone canvas foundation utilizing `#F8FAFC` (Slate Tint) and `#F0FDF4` (Mint Wash) underneath stark white (`#FFFFFF`) card planes.

## Typography
Plus Jakarta Sans provides high legibility across diverse reading capabilities—critical when accommodating elementary readers (SD Kelas 1-3) through high schoolers (SMA). 

- **Display & Headlines:** Bold and Extra-Bold weights emphasize game turn announcements, tile milestones, and dilemma verdicts without appearing cold or institutional.
- **Body:** Medium (500) and Regular (400) weights maintain comfortable line spacing for contextual scenario descriptions and ethical questions.
- **Labels:** Heavy weights (`700`) provide tactile contrast inside chips, dice HUDs, timer counters, and action triggers.

## Layout & Spacing
The layout adheres to a fixed-fluid hybrid architecture:

- **Board Arena:** The 100-cell snakes and ladders game grid retains an enforced 1:1 aspect ratio container capped at `720px` width on desktop and automatically scale-fits viewport width with `margin` safe zones on mobile.
- **Game Controls & Drawer:** Off-canvas or bottom-docked sheets on mobile viewports (<768px), transitioning to a persistent right-hand utility sidebar on desktop (>1024px).
- **Rhythm:** Spacing follows an 8px base rhythm (`space-xs` = 4px, `space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px, `space-xl` = 32px) maintaining consistent component padding and board tile gaps.

## Elevation & Depth
Depth conveys playfulness and tactile physical presence through layered surfaces and directional ambient lighting:

- **Tactile Game Buttons & Dice:** 3D extrusion effect created with solid dual-tone bottom borders (e.g., `box-shadow: 0 4px 0 #047857` on a `#059669` emerald button), producing an immediate physical compression feel on `:active` states (`transform: translateY(3px)`).
- **Board Cells:** Soft recessed borders (`1px solid #E2E8F0`) with faint ambient drop shadows (`0 2px 4px rgba(15, 23, 42, 0.04)`) to simulate physical wooden or thick cardboard game-board segments.
- **Modals & Drawers:** High elevation ambient diffusion (`0 16px 36px -8px rgba(15, 23, 42, 0.16)`) coupled with a subtle frosted glass backdrop (`backdrop-filter: blur(8px); background-color: rgba(255, 255, 255, 0.92)`).
- **Player Tokens:** Elevated discs using a circular colored ring with dual shadows: a crisp bottom rim for thickness and a soft ambient ground shadow (`0 6px 12px rgba(0, 0, 0, 0.18)`).

## Shapes
A rounded geometric shape language (`roundedness: 2`) reinforces friendliness, safety, and modern app playfulness:

- Base interactive items, dilemma option buttons, and board cell frames use `rounded-md` (0.5rem / 8px).
- Modals, achievement card overlays, and character status containers use `rounded-lg` (1rem / 16px) or `rounded-xl` (1.5rem / 24px).
- Pill-shaped caps are reserved for badges, round counters, dynamic score counters, and turn indicators (`border-radius: 9999px`).
- Dice roller units utilize soft cubic curves (`12px` border radius) to suggest physical rounded-corner dice.

## Components

### 3D-Styled Dice Roller Button
- **Structure:** Rounded cube (64x64px on mobile, 80x80px on desktop) styled with a bold top gradient and a 4px solid base rim that shifts down on press.
- **States:** Idle (subtle floating bounce animation), Rolling (rotational spin with particle blur), Disabled (slate muted surface with no bottom rim offset).

### 100-Cell Snakes & Ladders Board
- **Grid:** 10x10 alternating serpentine layout numbered 1 through 100.
- **Tiles:** Light mint (`#F0FDF4`) alternating with soft vanilla (`#FFFFFF`); Special Ladder starting cells outlined in Amber (`#F59E0B`); Snake mouth dilemmas tagged in Vivid Crimson (`#EF4444`).
- **Overlays:** Vector SVG ladders anchored between rung-origin and rung-destination cells; animated smooth curves for downward snake slides.

### Player Token Avatars
- **Style:** Circular disc tokens with white outer rims, housing the 4 student avatar colors:
  - Ruby Red (`#EF4444`)
  - Ocean Blue (`#0284C7`)
  - Sun Gold (`#F59E0B`)
  - Jade Green (`#059669`)
- **Active Turn Highlight:** Pulsing ring glow (`0 0 0 4px rgba(16, 185, 129, 0.35)`).

### Moral Quiz & Dilemma Modal Cards
- **Structure:** Frosted white modal backdrop (`rounded-xl`) with thematic top banners (Red for Corruption Trap, Amber for Honesty Ladder Opportunity, Blue for Integrity Trivia).
- **Options List:** Vertical stack of interactive cards with clear letter tags (A, B, C) featuring feedback animations:
  - Correct/Ethical: Emerald border, green icon tag, and encouraging microcopy.
  - Dilemma Trap: Red border shake effect with constructive reflective guidance.

### Badge Achievements & XP Counter
- **Pill Counters:** Rounded status pills displaying integrity points (*Poin Kejujuran*) and active player turn orders.
- **Badges:** Hexagonal or circular icons encased in gold and amber borders with micro-animations upon unlock.

### Game Control Drawer & HUD
- **Bottom Bar (Mobile):** Fixed navigation bar housing audio toggles, rules drawer trigger, player avatar list, and the central interactive dice trigger.
- **Drawer:** Slide-up sheet containing tier selector (SD 1-3, SD 4-6, SMP, SMA), current anti-corruption learning glossary, and restart game actions.