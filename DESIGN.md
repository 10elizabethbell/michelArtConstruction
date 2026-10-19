---
name: MichelArt Construction
description: Roofing and renovation pitch site for a North Jersey contractor; the visitor re-shingles the roof.
colors:
  dusk-slate: "#1D2530"
  fresh-plaster: "#ECEDEA"
  set-plaster: "#DEE1DC"
  ink-slate: "#1D2530"
  ink-soft: "#4B5563"
  on-slate: "#F3F4F2"
  on-slate-soft: "#AFB8C4"
  promise-mist: "#DCE1E7"
  hero-glow: "#2F3B4B"
  photo-backing: "#26303D"
  m-amber: "#F4A21C"
  m-amber-hi: "#FFB43A"
  form-blue: "#2E6BE6"
  control-edge: "#7C837C"
  hairline: "#C9CDC7"
  arrow-well: "#D3D7D0"
  field-white: "#FFFFFF"
  placeholder: "#6B7280"
  danger: "#B42318"
typography:
  display:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(34px, 11.4vw, 108px)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.01em"
  display-desktop:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(40px, 7vw, 104px)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.01em"
  display-landscape:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(34px, 11svh, 56px)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(32px, 8.4vw, 64px)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.01em"
  footer-name:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(28px, 7.4vw, 52px)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.005em"
  title:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 28px)"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "0.01em"
  lead:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 21px)"
    fontWeight: 400
    lineHeight: 1.4
  lead-desktop:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1.4
  care:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(20px, 5vw, 26px)"
    fontWeight: 700
    lineHeight: 1.35
  tagline:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 700
    lineHeight: 1.55
  body:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "0.04em"
  brand-lockup:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "0.06em"
  brand-lockup-narrow:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "0.04em"
  brand-lockup-desktop:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "0.06em"
  brand-sub:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "11px"
    fontWeight: 700
    lineHeight: 1.55
    letterSpacing: "0.18em"
  brand-sub-desktop:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 700
    lineHeight: 1.55
    letterSpacing: "0.18em"
  phone:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 800
    lineHeight: 1
  phone-narrow:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 800
    lineHeight: 1
  legal:
    fontFamily: "system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.55
rounded:
  control: "10px"
  inset: "8px"
  pill: "999px"
spacing:
  pad: "clamp(16px, 5vw, 56px)"
  section: "clamp(56px, 10vw, 110px)"
  gap-sm: "10px"
  gap-md: "20px"
  split: "64px"
  max: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.m-amber}"
    textColor: "{colors.ink-slate}"
    rounded: "{rounded.control}"
    padding: "0 24px"
    height: "58px"
    typography: "{typography.label}"
  button-primary-hover:
    backgroundColor: "{colors.m-amber-hi}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-slate}"
    rounded: "{rounded.control}"
    padding: "0 24px"
    height: "58px"
  button-ink:
    backgroundColor: "{colors.ink-slate}"
    textColor: "{colors.field-white}"
    rounded: "{rounded.control}"
    height: "50px"
  service-row:
    textColor: "{colors.ink-slate}"
    padding: "14px 2px"
    height: "72px"
    typography: "{typography.title}"
  service-arrow:
    backgroundColor: "{colors.arrow-well}"
    textColor: "{colors.ink-slate}"
    rounded: "50%"
    size: "44px"
  service-arrow-hover:
    backgroundColor: "{colors.m-amber}"
  input-text:
    backgroundColor: "{colors.field-white}"
    textColor: "{colors.ink-slate}"
    rounded: "{rounded.control}"
    padding: "13px 14px"
    height: "54px"
  chip:
    backgroundColor: "{colors.field-white}"
    textColor: "{colors.ink-slate}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "46px"
  chip-selected:
    backgroundColor: "{colors.ink-slate}"
    textColor: "{colors.field-white}"
---

# Design System: MichelArt Construction

## Overview

**Creative North Star: "The Fresh Course"**

The page is a roof going on. A dusk-slate sky sits over a tired brown 3-tab roof that an automatic roofer, or the visitor's finger, re-shingles course by course in pewter architectural tabs. Everything else in the system is the trade's other materials: fresh drywall for the light sections, a white aluminium gutter that closes every dark section, and the amber of the MichelArt M as the only warm color. Corners on photos and step markers are cut at the angle of the logo's strokes.

Density is low and phone-first: one column, big uppercase headlines, wide touch targets (44px minimum, 58px for primary actions), and sections that alternate dark slate and light plaster. Type is heavy and plain, set in the platform's own sans so it reads like a jobsite sign rather than a brochure.

The system rejects the contractor default of a stock house photo under a trust headline; the only photographs are the crew's own work, and the hero is the roof itself.

**Key Characteristics:**
- Dusk-slate and fresh-plaster grounds alternate; there are no black grounds.
- Amber comes only from the logo and marks the one primary action, the headline accent and small icon accents.
- Blue appears only on form controls, as their hover and focus state.
- Canvas shingles: the hero roof and an eave strip that closes each dark section.
- Corners cut at the logo angle (22px by 12px on photos, 12px by 7px on step markers).
- Heavy uppercase (900) display type at tight leading (0.98).

## Colors

A two-ground palette of dusk slate and plaster, with one warm accent taken from the logo and one cool accent kept to the form.

### Primary
- **M Amber** (m-amber): the primary button fill, the accent word in the hero headline, the step-number digits, the footer tagline, the phone and contact icons, the outlined Facebook button, the global focus outline on dark grounds, and the service arrow on hover. **M Amber Hi** (m-amber-hi) is its hover only.

### Secondary
- **Form Blue** (form-blue): the hover and focus edge of text inputs, chips and form buttons, with a 3px ring at 25% opacity (rgba(46,107,230,.25)). It never fills anything.

### Neutral
- **Dusk Slate** (dusk-slate): the dark ground for the hero, Recent Work and the footer; also the browser theme color. The hero lifts it with a radial glow (hero glow at the bottom center fading to slate at 62%).
- **Ink Slate** (ink-slate): the same value as text and fills on light grounds: body text, the 2px rule over the service list, step-marker blocks, selected chips, the ink button.
- **Fresh Plaster** (fresh-plaster): the light ground for What We Build and How a Job Goes; also the background of the sent-message preview.
- **Set Plaster** (set-plaster): the slightly deeper light ground of the quote section, so the form reads as its own room.
- **On Slate** (on-slate) and **On Slate Soft** (on-slate-soft): primary and secondary text on dark grounds.
- **Promise Mist** (promise-mist): the hero lead line only, a step between on-slate and on-slate-soft so the promise reads under the headline without competing.
- **Hero Glow** (hero-glow): the lighter slate at the bottom center of the hero's radial gradient, lifting the sky toward the roof.
- **Photo Backing** (photo-backing): the slate well behind each photo tile, visible while images load.
- **Ink Soft** (ink-soft): secondary text on light grounds (step descriptions, notes, ledes, "(optional)").
- **Control Edge** (control-edge): 2px borders on inputs, chips and the sent panel (3.9:1 on white).
- **Hairline** (hairline): 1px dividers between service rows.
- **Arrow Well** (arrow-well): the resting disc behind each service arrow.
- **Field White** (field-white): input, chip and sent-panel fills.
- **Placeholder** (placeholder): input placeholder text.
- **Danger** (danger): error text and invalid field edges.

### Named Rules
**The Logo Amber Rule.** Amber is the color of the M and nothing else warm appears in the interface. One amber fill per screen region: the primary action.

**The Form-Only Blue Rule.** Blue appears only as the hover/focus edge of form controls. It never fills a button and never appears outside the quote form.

**The No Black Ground Rule.** The darkest ground is dusk slate (#1D2530). Pure or near-black section grounds are out.

## Typography

**Display Font:** the platform system sans (system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif)
**Body Font:** the same stack

**Character:** One family at two extremes: 900-weight uppercase for anything that names a thing, 400-weight sentence case for anything that explains. It reads like painted signage on a work truck.

### Hierarchy
- **Display** (900, clamp(34px, 11.4vw, 108px), 0.98, uppercase, -0.01em): the hero headline only, capped at 12ch on phones; one word carries amber. **Display Desktop** (clamp(40px, 7vw, 104px), from 1024px) drops the width cap; **Display Landscape** (clamp(34px, 11svh, 56px)) sizes by height on landscape phones so the promise and buttons stay on the first screen.
- **Headline** (900, clamp(32px, 8.4vw, 64px), 0.98, uppercase): section titles; balanced wrapping.
- **Footer Name** (900, clamp(28px, 7.4vw, 52px), 1, uppercase, -0.005em): the business name closing the page; one step below headline.
- **Title** (900, clamp(20px, 5.4vw, 28px), 1.05, uppercase, +0.01em): service row names; step titles use clamp(21px, 5.4vw, 26px) at 1.1.
- **Lead** (400, clamp(17px, 4.6vw, 21px), 1.4; **Lead Desktop** 22px from 1024px): the hero promise line only, in promise mist, 32ch (40ch on desktop).
- **Care** (700, clamp(20px, 5vw, 26px), 1.35): the single closing brand line under the steps, 30ch.
- **Tagline** (700, 18px): the amber footer tagline under the footer name.
- **Body** (400, 17px, 1.55): all running text, held to 32 to 44ch; secondary notes and form hints at 16px.
- **Label** (800, 16 to 17px, uppercase, +0.02 to +0.04em): buttons and form labels.
- **Brand Lockup** (900, 15px, +0.06em; 14px at +0.04em below 380px; 18px from 1024px) over **Brand Sub** (700, 11px, +0.18em, on-slate-soft; 12px from 1024px): the two-line header wordmark beside the logo. The sub-line is part of the logo lockup, not a heading device.
- **Phone** (800, 16px, tabular figures; 15px below 380px): the header phone number.
- **Legal** (400, 14px, on-slate-soft): the copyright line, and the floor: nothing outside the brand lockup is smaller than 14px; form text is 16px or more so iOS does not zoom.

### Named Rules
**The Shout-or-Speak Rule.** Uppercase comes with weight 800 to 900; sentence case comes with 400 to 700. No light uppercase, no heavy sentence-case paragraphs.

## Layout

A single column inside a 1180px container with fluid side padding (clamp(16px, 5vw, 56px), never less than the safe-area inset). Sections run full bleed and alternate dark and light grounds, each padded clamp(56px, 10vw, 110px) top and bottom.

At 1024px and up, light sections with a title and a list (services, quote) split 5fr / 7fr with a 64px gap; the services headline sticks at 40px from the top. The work grid is two columns on phones (the first and last photo span both) and three equal columns from 760px. Steps go to three columns from 900px. Hero actions stack full width on phones and sit side by side from 640px. A landscape-phone rule (max-height 500px) shrinks the headline so the promise and both buttons stay on the first screen.

The hero is the full first viewport (min(100svh, 920px), 1000px on desktop): header row, copy, then the roof canvas filling the rest down to its gutter. The phone number sits only in the top-right of the header; there is no sticky bottom bar.

## Elevation & Depth

Flat. Depth comes from ground changes (slate against plaster) and from the shingle canvases, which carry their own drawn shadows: the course above shading each tab, rake shadows beside the hip caps, and a lift shadow under any tab the pointer raises. The only CSS shadow is a soft drop under the amber primary button.

### Shadow Vocabulary
- **Amber lift** (`box-shadow: 0 6px 14px -8px rgba(6,10,16,.55)`): under the primary amber button only.
- **Form ring** (`box-shadow: 0 0 0 3px rgba(46,107,230,.25)`): focus and hover state of form controls; a state, not elevation.

### Named Rules
**The Drawn Depth Rule.** Shadows belong to the shingles. Interface surfaces stay flat; only the primary action gets a lift.

## Shapes

Controls are gently rounded (10px): buttons, inputs, the sent panel. Insets nested inside a rounded panel step down to 8px (the composed-message preview in the sent panel). Chips are full pills. The only circle is the service arrow well. Everything that is a material rather than a control (photos, step-number blocks) has square corners with two opposite corners cut at the angle of the M's strokes: top-right and bottom-left, 22px across by 12px deep on photos, 12px by 7px on step markers. Borders are 2px on controls and on the rule over the service list, 1px on row dividers.

## Components

### Buttons
Big, blunt, uppercase.
- **Shape:** gently rounded (10px), 58px tall, 24px side padding, 22px icon left of the label, 2px border.
- **Primary:** amber fill, ink-slate text, amber lift shadow. Hover goes to amber hi. Active nudges down 1px.
- **Ghost:** transparent with a 60%-white border on slate; hover turns border and text amber.
- **Outlined amber:** transparent with an amber border and amber text (62px tall) for the link out to more work; hover fills amber with ink text.
- **Ink and line:** ink-slate fill with white text, or white fill with ink border, at 50px tall, used for secondary actions inside the form's confirmation panel.
- **Inside the form:** buttons swap the amber focus outline for the blue edge and ring, matching the other controls.

### Chips
- **Style:** white pill, 46px tall, 2px control-edge border, 700 weight sentence case.
- **State:** selected fills ink slate with white text; hover and focus edge in form blue; invalid edge in danger red. Multi-select checkboxes underneath.

### Service Rows
A full-width list of links, each 72px minimum, title-weight uppercase name on the left and a 44px arrow disc on the right, separated by 1px hairlines under a 2px ink rule. The row itself never changes on hover or focus (no background, no shadow, no outline). Only the arrow responds: the disc turns amber and slides 3px right; on keyboard focus it also takes a 3px ink outline.

### Inputs / Fields
- **Style:** white fill, 2px control-edge border, 10px radius, 54px minimum height (textarea 110px), 17px text, labels in uppercase 800 above.
- **Focus:** border goes form blue with the 3px blue ring; hover previews the blue border.
- **Error:** border and message in danger red; message 700 weight, 16px, below the field.

### Navigation
No menu. The header is the logo mark plus a two-line wordmark on the left (MICHELART at 900, CONSTRUCTION in tracked 700 small caps in on-slate-soft) and the phone number on the right in 800 tabular figures with an amber phone icon. Hover turns the number amber.

### Photo Tiles
The crew's own photographs, 4:5 crops (3:2 for the wide framing shot on phones), corners cut at the logo angle, 10px gaps (14px from 760px), sitting on dusk slate.

### Step Markers
A numbered ordered list; each number sits in a 44px ink-slate block with amber 900-weight digits and the logo-angle corner cut.

### Shingle Roof (signature)
A canvas trapezoid roof filling the bottom of the hero. It starts as a tired brown 3-tab roof (algae streaks, curled corners, moss, the odd missing tab showing felt) and an automatic roofer lays pewter architectural tabs bottom course first, left to right; a finger or cursor re-shingles everything within its reach and lifts new tabs on a spring. A finished roof holds, tears off and starts again. Hip and ridge caps are drawn as real cap pieces; the plane darkens toward the ridge; a white gutter with a drip edge closes it. All behavior is set in the `ROOF` tunables object; `ROOF.STILL` (and prefers-reduced-motion) draws one finished roof with no motion, for older audiences. The canvas swallows touch drags so the roof can be worked without scrolling.

### Eave Strip (signature)
A 64px canvas strip with a single course of new pewter tabs above a drip edge and white gutter. It closes the bottom of each dark section (after Recent Work, and at the top of the footer, flipped). Tabs lift under the pointer and flutter in a passing gust; still when `ROOF.STILL` is set.

## Do's and Don'ts

### Do:
- **Do** alternate dusk slate (#1D2530) and plaster grounds, and close each dark section that meets a light one with an eave strip.
- **Do** keep amber to the M's roles: the primary action, one headline word, step digits, icons, the tagline.
- **Do** keep form-blue (#2E6BE6) to the hover/focus edge of form controls.
- **Do** set anything that names a thing in 900-weight uppercase at 0.98 leading, and everything that explains in 400-weight sentence case at 17px.
- **Do** cut photo and marker corners at the logo angle (top-right and bottom-left) instead of rounding them.
- **Do** keep touch targets at 44px minimum and primary actions at 58px.
- **Do** let only the arrow respond on service rows.
- **Do** honor `ROOF.STILL` and prefers-reduced-motion in any new canvas.

### Don't:
- **Don't** use black or near-black section grounds.
- **Don't** fill buttons blue or use blue outside the form.
- **Don't** add a second warm accent beside amber.
- **Don't** put a stock house photo in the hero; the roof is the hero and the photos are the crew's own.
- **Don't** add a sticky bottom call bar or repeat the phone number elsewhere on the first screen; it lives top-right.
- **Don't** highlight a whole service row on hover (no background, shadow or outline on the row).
- **Don't** add CSS shadows to cards or panels; depth belongs to the shingles.
- **Don't** set text below 14px outside the brand lockup, or form text below 16px.
