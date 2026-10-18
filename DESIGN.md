---
name: VitaPulse Clinical Design Language
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#3d4947'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#6d7a77'
  outline-variant: '#bcc9c6'
  surface-tint: '#006a61'
  primary: '#00685f'
  on-primary: '#ffffff'
  primary-container: '#008378'
  on-primary-container: '#f4fffc'
  inverse-primary: '#6bd8cb'
  secondary: '#00687a'
  on-secondary: '#ffffff'
  secondary-container: '#57dffe'
  on-secondary-container: '#006172'
  tertiary: '#b90538'
  on-tertiary: '#ffffff'
  tertiary-container: '#dc2c4f'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#89f5e7'
  primary-fixed-dim: '#6bd8cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#005049'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#ffdadb'
  tertiary-fixed-dim: '#ffb2b7'
  on-tertiary-fixed: '#40000d'
  on-tertiary-fixed-variant: '#92002a'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xxs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system delivers a clinical-grade yet warm, patient-first telehealth and digital healthcare experience. The design dialect balances clinical authority, precision, and emotional calm, mitigating patient anxiety while conveying unwavering reliability to healthcare providers.

Targeted at diverse demographics ranging from chronic condition self-managers to urgent telehealth seekers, the visual aesthetic fuses **Modern Organic Healthcare** with **Tactile Soft-Minimalism**. Surfaces are clean and breathable, pairing crisp neutral slate foundations with soothing medical teal primaries, mint bio-accents, and high-visibility clinical triage tones.

Visual principles:
- **Calm Authority:** Eliminates visual noise; uses clear hierarchy to reduce cognitive fatigue during high-stress medical decisions.
- **Human Warmth:** Softened container geometry, generous hit-targets, and friendly micro-states balance out sterile clinical stiffness.
- **Tactile Legibility:** High-contrast typography paired with soft-cast diffused ambient shadows produces physical surface clarity optimized for mobile screens.

## Colors

The color system is anchored in chromatic reassurance and functional medical accessibility (surpassing WCAG 2.1 AA requirements across all clinical touchpoints).

- **Primary Teal (`#0D9488`):** Represents therapeutic care, stability, and medical integrity. Used for key actions, navigation active states, verified practitioner badges, and primary clinical confirmations.
- **Secondary Mint/Cyan (`#06B6D4`):** Expresses vitality, respiratory health, and digital speed. Applied to telehealth connection status rings, vital sign trend lines, active call overlays, and secondary interactive accents.
- **Tertiary Emergency Coral (`#F43F5E`):** Reserved exclusively for urgent interventions, out-of-range triage metrics, critical prescription warnings, and rapid emergency dispatch actions.
- **Neutral Slate (`#0F172A`):** Deep, clinical ink tone that avoids harsh `#000000`, delivering high-contrast, fatigue-free reading across all ambient light settings.

Surfaces rely on tinted neutral slates:
- **Base Canvas:** Pure Snow (`#FFFFFF`) to Morning Mist (`#F8FAFC`).
- **Surface Layer 1:** `#F1F5F9` for secondary card backings and input tracks.
- **Surface Tint/Container:** Muted clinical wash (`#F0FDFA` / 8% teal tint) for low-stress informational callouts.

## Typography

The type system pairs **Plus Jakarta Sans** for expressive, warm, modern display headlines with **Inter** for technical, utilitarian body clarity.

- **Plus Jakarta Sans** introduces friendly rounded geometric characteristics into titles, doctor names, and health overview headers, disarming the user while maintaining structure.
- **Inter** provides neutral, optical clarity for medication dosages, lab results, telemetry numbers, and conversational consultation transcripts.
- Strict numeric tabular lining is mandated for medical data points (heart rate, blood pressure, lab values) to guarantee vertical scanning alignment across records.

## Layout & Spacing

This mobile-first layout uses a fluid responsive column framework tailored for handheld interactions:
- **Mobile (up to 599px):** 4-column fluid layout, `margin-mobile` (16px), `gutter-mobile` (12px). All primary action targets enforce an absolute minimum physical touch zone of 48x48px.
- **Tablet / Large Handheld (600px - 1023px):** 8-column layout, `margin` (24px), `gutter` (16px), dual-pane views for simultaneous telemetry tracking and clinician chat.
- **Desktop / Web Dashboard (1024px+):** 12-column layout with a constrained reading container max-width of 1200px.

A rhythmic 4px base module coordinates spacing tokens. Standard card internals use `space-lg` (24px) for prominent content sections and `space-md` (16px) for compact metric cards.

## Elevation & Depth

Visual hierarchy uses a **Tactile Tonal Layering** model with ambient, colored soft-focus shadows rather than stark grayscale drop-shadows.

- **Level 0 (Flat Canvas):** `#F8FAFC` base background with zero elevation.
- **Level 1 (Card & Content Containers):** Pure white `#FFFFFF` surface resting on a dual-layer soft ambient shadow tinted with slate and primary teal: `0 4px 20px -2px rgba(13, 148, 136, 0.05), 0 2px 6px -1px rgba(15, 23, 42, 0.04)`. Outlined with a sub-pixel border of `1px solid rgba(226, 232, 240, 0.8)`.
- **Level 2 (Active Telehealth Floating Controls, Pill Badges & Interactive Sheets):** `0 12px 32px -4px rgba(15, 23, 42, 0.08), 0 4px 12px -2px rgba(13, 148, 136, 0.08)`.
- **Level 3 (Emergency Modals & Critical Alerts):** Deep safety elevation using `0 24px 48px -8px rgba(244, 63, 94, 0.16), 0 8px 16px -4px rgba(15, 23, 42, 0.06)`.
- **Micro-State Tactile Response:** Active button presses depress elevation by 2px and shift ambient blur inward, mimicking a physical tactile key switch.

## Shapes

The design system incorporates generous curvature to evoke biological forms, safety, and approachability. 

- **Cards & Primary Modules:** Enforce a signature `24px` (`1.5rem` / `rounded-xl`) corner radius. This curved silhouette softens large clinical data sets and differentiates cards from standard enterprise software.
- **Pill Badges, Action Buttons, and Chip Elements:** Use full `9999px` circular pill radii for fast visual recognition.
- **Inputs & Action Trays:** Enforce `12px` to `16px` (`rounded-lg`) corner radii for structured textual containment.

## Components

### Buttons
- **Primary Action Button:** Fully rounded pill (`9999px`), solid `#0D9488` background, `#FFFFFF` text. Micro-states: Hover transitions to `#0F766E`; pressed state scales to `0.98` with an inset shadow.
- **Emergency Button:** Pill-shaped, `#F43F5E` background with a subtle ambient coral breathing glow (`0 0 0 4px rgba(244, 63, 94, 0.2)`).
- **Secondary Ghost Button:** Translucent teal tint (`rgba(13, 148, 136, 0.08)`), `#0D9488` text, zero border, pill-shaped.

### Cards (Clinical & Telehealth)
- Built on `24px` border-radius with pure white fill and Level 1 soft-cast teal-tinted shadows.
- Distinct inner padding of `20px` to `24px`.
- Feature dedicated slots for physician avatars with a 3px status halo (Green: Available, Amber: In Consultation, Slate: Offline).

### Badges & Status Chips
- Pill geometry with `label-sm` or `label-md` typography.
- **Normal Metric:** Subtle cyan wash (`#ECFEFF`), `#0E7490` text.
- **Verified Clinical Chip:** Teal wash (`#F0FDFA`), `#0F766E` text, featuring a checkmark glyph.
- **Critical Alert:** Light rose wash (`#FFF1F2`), `#E11D48` text.

### Form Fields & Inputs
- Enclosed with a `14px` border radius, `#F8FAFC` background, and `1.5px` border in `#E2E8F0`.
- Focus State: Changes to `#FFFFFF` surface with `#0D9488` border and a 3px ring of `rgba(13, 148, 136, 0.15)`.
- Dynamic floating labels using `label-sm` typography prevent context loss during symptom logging.

### Selection Controls (Checkboxes & Radios)
- Checkboxes feature `6px` softened corners; radio buttons are concentric circles.
- Active state fills with `#0D9488` presenting a crisp `#FFFFFF` indicator.
- 44px invisible tap targets ensure effortless selection for patients with motor challenges.

### Healthcare-Specific Components
- **Vital Telemetry Tile:** 24px rounded card housing metric value, unit, trend graph, and a pill badge showing delta change.
- **Prescription Dose Tracker:** Horizontal pill card containing time-of-day icon, dosage label, and a tactile single-tap completion ring.
- **Telehealth Video Overlay Drawer:** Frosted glass overlay (`backdrop-filter: blur(16px); background: rgba(255, 255, 255, 0.85)`) housing call controls, mute toggles, and chat expansion pills.