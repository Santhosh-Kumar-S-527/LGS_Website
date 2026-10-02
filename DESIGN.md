---
version: alpha
name: Lingaasys Design System
description: Visual specification for the Lingaasys dark industrial B2B technology theme.
colors:
  background-base: "#050708"
  background-surface: "#0B0E10"
  background-raised: "#111519"
  background-subtle: "#171C20"
  border-default: "#293036"
  border-strong: "#3B444B"
  accent-primary: "#E7430B"
  accent-bright: "#F4511E"
  accent-coral: "#F05B36"
  accent-soft: "rgba(240, 91, 54, 0.25)"
  text-primary: "#F7F8F8"
  text-secondary: "#C8CDD0"
  text-muted: "#818A90"
  text-on-dark: "#FFFFFF"
  semantic-info: "#26CAD3"
  overlay-dark: "rgba(0, 0, 0, 0.20)"
typography:
  display-hero:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: 3.5rem
    fontWeight: 300
    lineHeight: 0.98
    letterSpacing: "-0.068em"
  h1:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: 2.25rem
    fontWeight: 500
    lineHeight: 1.22
    letterSpacing: "-0.05em"
  h2:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: 1.75rem
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  h3:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: 1.5rem
    fontWeight: 700
    lineHeight: 1.54
    letterSpacing: "-0.01em"
  h4:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: 1.25rem
    fontWeight: 700
    lineHeight: 1.37
  body-lg:
    fontFamily: "Sora, sans-serif"
    fontSize: 1.25rem
    fontWeight: 400
    lineHeight: 1.54
  body-md:
    fontFamily: "Sora, sans-serif"
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.54
  body-md-semibold:
    fontFamily: "Sora, sans-serif"
    fontSize: 1rem
    fontWeight: 600
    lineHeight: 1.54
  body-sm:
    fontFamily: "Sora, sans-serif"
    fontSize: 0.875rem
    fontWeight: 400
    lineHeight: 1.7
  eyebrow:
    fontFamily: "Sora, sans-serif"
    fontSize: 0.75rem
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "0.12em"
    textTransform: uppercase
  utility:
    fontFamily: "Roboto Mono, monospace"
    fontSize: 0.6875rem
    fontWeight: 400
    lineHeight: 1.45
rounded:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  full: 9999px
spacing:
  micro: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  2xl: 64px
  3xl: 80px
  section: 120px
layout:
  desktop-width: 1920px
  container-width: 1320px
  columns: 12
  column-width: 88px
  gutter: 24px
  desktop-margin: 300px
components:
  button-primary:
    backgroundColor: "{colors.accent-primary}"
    textColor: "{colors.background-base}"
    rounded: "{rounded.full}"
    padding: "16px 32px"
    minHeight: 44px
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.text-primary}"
    borderColor: "{colors.border-default}"
    rounded: "{rounded.full}"
    padding: "16px 24px"
    minHeight: 44px
  card-feature:
    backgroundColor: "{colors.background-surface}"
    borderColor: "{colors.border-default}"
    rounded: "{rounded.lg}"
    padding: 32px
  badge-tag:
    backgroundColor: "{colors.background-subtle}"
    textColor: "{colors.text-secondary}"
    rounded: "{rounded.full}"
    padding: "8px 16px"
---

# Overview

Lingaasys uses a dark industrial B2B technology theme built around precision, practical innovation, and human progress. The design combines architectural depth, restrained orange accents, editorial typography, and documentary technology imagery.

This file documents a static visual theme. It does not define a complete interactive prototype. Any responsive, motion, carousel, or tab behavior must be validated before production.

---

# Colors

The palette uses near-black surfaces to create depth while reserving orange for actions, active states, and focused emphasis.

- Background Base (#050708): Main page canvas.
- Background Surface (#0B0E10): Standard section and card surface.
- Background Raised (#111519): Elevated sections such as testimonials.
- Background Subtle (#171C20): Supporting surfaces and tags.
- Accent Primary (#E7430B): Primary actions, active states, and brand marks.
- Accent Bright (#F4511E): Hover states, arrows, and stronger highlights.
- Accent Coral (#F05B36): Secondary warm accent. Use only where a distinct coral role is required.
- Text Primary (#F7F8F8): Headings and primary labels.
- Text Secondary (#C8CDD0): Body copy and descriptions.
- Text Muted (#818A90): Metadata, captions, and low-emphasis content.
- Text On Dark (#FFFFFF): Icons and labels requiring pure white.
- Border Default (#293036): Dividers, card borders, and separators.
- Border Strong (#3B444B): Emphasized boundaries.
- Semantic Info (#26CAD3): Informational marks only.

Third-party logos may retain their original brand colors. Photographs and image fills are not mapped to interface color styles.

---

# Typography

Typography combines Space Grotesk for expressive headings and Sora for readable body and interface copy.

- Display Hero: Space Grotesk Light, 56px, 98% line height.
- Heading 1: Space Grotesk Medium, 36px, 122% line height.
- Heading 2: Space Grotesk Medium, 28px, 120% line height.
- Heading 3: Space Grotesk Bold, 24px.
- Heading 4: Space Grotesk Bold, 20px.
- Body Large: Sora Regular, 20px.
- Body Medium: Sora Regular, 16px.
- Body Medium Semibold: Sora Semibold, 16px.
- Body Small: Sora Regular, 14px.
- Eyebrow: Sora Bold, 12px, uppercase.
- Utility: Roboto Mono Regular, 11px.

Use the scale 12, 14, 16, 20, 24, 36, 56, and optional 72. Avoid introducing unsupported sizes such as 18px, 21.5px, or 28px without adding an approved semantic role.

---

# Layout

- Reference desktop width: 1920px.
- Centered content width: 1320px.
- Desktop margins: 300px.
- Grid: 12 columns, 88px columns, 24px gutters.
- Standard section padding: 120px vertical and 300px horizontal.
- Insights section may use 80px vertical padding for a denser editorial rhythm.
- Major sections connect with no external gap and use background surfaces for separation.
- Use the spacing scale consistently: 4, 8, 16, 24, 32, 48, 64, 80, and 120.

Responsive layouts were not supplied. Recommended mobile behavior is to stack media above copy, collapse multi-column card layouts, remove nonessential image overlap, and maintain 20px page margins with 16px gutters.

---

# Elevation and Depth

- Prefer 1px borders over heavy shadows.
- Card shadow: 0 18px 48px rgba(0, 0, 0, 0.40).
- Accent glow: 0 0 32px rgba(231, 67, 11, 0.24).
- Use glow effects only for important focal elements.
- Use a dark image overlay whenever text sits over photography.

---

# Shapes

- 4px: Micro details and compact internal elements.
- 8px: Small controls and compact cards.
- 16px: Standard cards and containers.
- 24px: Featured cards and large image crops.
- Full pill: Primary buttons, secondary buttons, filters, and tags.

Avoid introducing arbitrary radii such as 30px, 36px, 40px, or 50px unless required by an approved asset.

---

# Components

## Header and Utility Bar

- Slim enterprise descriptor bar above the main navigation.
- Main navigation contains logo, page links, and the Talk To Us action.
- Use semantic navigation landmarks and visible focus states.
- Sticky behavior is not defined by the static theme.

## Hero

- Full-bleed architectural image with the focal subject positioned to the right.
- Display headline, supporting copy, dual CTAs, four metrics, and partner logo row.
- Preserve readable contrast using a stable dark overlay.
- Partner logos retain approved brand colors.

## About

- Overlapping documentary image pair, company statement, and four-step supporting navigation.
- On small screens, use one primary image above the copy and simplify the overlap.

## Solutions

- Category tabs for AI and ML, Web Apps, Mobile Apps, Cloud, Data, Automation, and UX/UI.
- One active category controls the image, heading, description, and feature list.
- Production implementation should use tab, tablist, and tabpanel semantics.

## Industries

- One featured card followed by compact cards.
- Cards include image, numeric index, accent rule, and industry label.
- Use one reusable card component with featured and compact variants.

## Careers and Values

- Two job opportunity cards using structured content.
- Four values: Curious, Committed, Human, and Forward.
- Use reusable job-card and value-item components.

## Insights

- One featured article plus two supporting articles.
- Article model: category, title, image, date, summary, and URL.
- Reflow to one column on mobile.

## Testimonial

- Quote, name, role, organization, and avatar.
- Display carousel controls only when multiple approved testimonials exist.

## CTA and Footer

- Full-width photographic CTA with a dark readability overlay.
- Send Message action followed by structured footer navigation and legal metadata.

---

# Accessibility

- Meet WCAG 2.2 AA.
- Normal text requires at least 4.5:1 contrast.
- Large text requires at least 3:1 contrast.
- Interactive targets should be at least 44 by 44px.
- All controls require visible focus states.
- Do not use color as the only state indicator.
- Solutions tabs require keyboard arrow navigation and aria-selected states.
- Carousel controls require accessible names and 44px hit areas.
- Images require meaningful alt text unless decorative or redundant.
- Respect prefers-reduced-motion for transitions or carousels.

Known items to correct before production:

- Utility bar text contrast is approximately 1.49:1.
- See All Details contrast is approximately 3.79:1.
- Talk To Us contrast is approximately 3.79:1.
- Learn More, Explore More, Apply Now, Read More, and View Open Positions need larger clickable areas.

---

# Do's and Don'ts

## Do

- Use orange only for actions, active states, and purposeful emphasis.
- Use the mapped Lingaasys color and typography styles.
- Maintain the centered 1320px content grid.
- Use real people and practical technology imagery.
- Keep card styling restrained with clean borders and limited glow.
- Use reusable components for repeated cards, tabs, buttons, and controls.

## Don't

- Do not replace third-party logo colors with Lingaasys orange.
- Do not introduce additional near-white, orange, border, or dark-surface values.
- Do not use low-contrast muted text on dark surfaces.
- Do not use neon AI imagery, holograms, or impossible interfaces.
- Do not add unsupported font sizes, spacing values, or corner radii.
- Do not rely on the static theme as the final interaction specification.

---

# Content QA

Correct these items before implementation:

- soulutions to solutions
- oppurtunities to opportunities
- thats to that
- Healtchare to Healthcare
- Lets to Let’s
- Remove spaces before commas.
- Review Technology driver outcomes for grammar.
- Review duplicate navigation and article placeholder content.
