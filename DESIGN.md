---
name: MindPulse
colors:
  surface: '#fcf9f1'
  surface-dim: '#dcdad2'
  surface-bright: '#fcf9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3eb'
  surface-container: '#f0eee6'
  surface-container-high: '#ebe8e0'
  surface-container-highest: '#e5e2db'
  on-surface: '#1c1c17'
  on-surface-variant: '#424843'
  inverse-surface: '#31312c'
  inverse-on-surface: '#f3f1e9'
  outline: '#727973'
  outline-variant: '#c2c8c1'
  surface-tint: '#466552'
  primary: '#345341'
  on-primary: '#ffffff'
  primary-container: '#4c6b58'
  on-primary-container: '#c7ead2'
  inverse-primary: '#adcfb8'
  secondary: '#8f4d20'
  on-secondary: '#ffffff'
  secondary-container: '#fea772'
  on-secondary-container: '#773a0e'
  tertiary: '#694244'
  on-tertiary: '#ffffff'
  tertiary-container: '#84595b'
  on-tertiary-container: '#ffd9da'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c8ebd3'
  primary-fixed-dim: '#adcfb8'
  on-primary-fixed: '#022112'
  on-primary-fixed-variant: '#2f4d3c'
  secondary-fixed: '#ffdbc9'
  secondary-fixed-dim: '#ffb68c'
  on-secondary-fixed: '#321200'
  on-secondary-fixed-variant: '#723609'
  tertiary-fixed: '#ffdada'
  tertiary-fixed-dim: '#efb9bb'
  on-tertiary-fixed: '#301215'
  on-tertiary-fixed-variant: '#633c3e'
  background: '#fcf9f1'
  on-background: '#1c1c17'
  surface-variant: '#e5e2db'
  background-light: '#FAF7F2'
  background-dark: '#1C1E1B'
  sage-light: '#9CB89F'
  amber-warm: '#E0996B'
  accent-gold: '#F2C94C'
  accent-blue: '#8DA9B8'
typography:
  headline-lg:
    fontFamily: Inter Tight
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: 0
  headline-lg-mobile:
    fontFamily: Inter Tight
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter Tight
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-mono:
    fontFamily: IBM Plex Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  stat-lg:
    fontFamily: IBM Plex Mono
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system for this privacy-first behavioral sensing app is built on the philosophy of **"Calm Precision."** It aims to evoke a sense of professional reliability, extreme privacy, and gentle observation without ever feeling clinical or invasive. The target audience includes engineers and recruiters who value technical transparency and thoughtful product design.

The design style is **Modern / Minimalist with Tactile Accents**. It avoids the generic "SaaS" look by using a warm, grounding palette and a "Flat Elevation" approach that relies on whitespace and grid structure rather than heavy shadows. The visual identity is anchored by abstract, geometric line-art that mirrors the app's function: monitoring subtle shifts in human rhythm. It feels like an engineering portfolio pieceâ€”precise, honest, and high-qualityâ€”but with a warm, human soul.

## Colors

The palette is designed to be "lively but calm." It uses earthy, natural tones to distance the app from the clinical blues of traditional health tech.

- **Primary (Deep Sage):** Used for key actions, primary branding, and representing "stable" states.
- **Secondary (Terracotta):** Used for highlighting changes, secondary actions, and "drift" indicators.
- **Neutral (Warm Charcoal):** Used for typography to ensure readability without the harshness of pure black.
- **Accents (Golden Amber & Dusty Sky Blue):** These are strictly reserved for illustrations, icons, and decorative background moments to provide warmth and variety.

The system supports a native dark mode where the background shifts to a charcoal-green and the primary sage/amber tones are lightened to maintain accessible contrast levels.

## Typography

This design system uses a restrained, widely used font stack that balances product clarity with technical credibility:

1.  **Inter Tight (Headlines):** A widely used, subtle companion to Inter. It keeps headlines compact and polished without making the brand feel loud.
2.  **Inter (Body):** Chosen for its exceptional legibility in long-form descriptions, navigation, and privacy details.
3.  **IBM Plex Mono (Technical):** Used sparingly for stats, labels, and system status indicators. This preserves the engineered feel without overpowering the page.

Maintain generous line-heights for body text to ensure a relaxed reading experience. Keep headline letter spacing neutral for a calm, modern product feel.

## Layout & Spacing

The layout is built on a **12-column fluid grid** with a fixed maximum container width of 1200px for desktop. It prioritizes "Vertical Rhythm" and "Generous Whitespace" to prevent cognitive overload.

- **Grid:** Use 8px base units for all internal padding and component dimensions.
- **Section Breaks:** Use large vertical gaps (80px - 120px) between major narrative sections to allow the content to breathe.
- **Mobile:** Reflow to a single-column layout with 16px side margins.
- **Alignment:** Content is generally left-aligned to feel grounded and professional; centered layouts should be used sparingly (e.g., Hero eyebrow or Closing CTA).

## Elevation & Depth

To maintain a "Calm" and "Privacy-First" aesthetic, this design system avoids the use of heavy ambient shadows or skeumorphic depth.

- **Flat Layers:** Use tonal shifts for depth. Secondary containers use a slightly darker (or lighter in dark mode) version of the background color rather than a shadow.
- **Subtle Borders:** 1px solid borders in a low-contrast version of the primary or charcoal color are used to define card boundaries.
- **Background Texture:** Use subtle, low-contrast gradients and abstract line-art (the "drift line" motif) in the background to create a sense of environmental depth without adding visual "weight."
- **Focus States:** High-contrast terracotta outlines are used for interactive elements to ensure accessibility without breaking the flat aesthetic.

## Shapes

The shape language is "Soft Geometry." All containers, cards, and buttons use a consistent **12px border radius**.

- **Consistency:** Avoid mixing radius values. 12px (rounded-lg equivalent in this system) is the standard for almost everything.
- **Geometric Illustrations:** Icons and illustrations should be constructed from basic shapes (circles, lines, arcs) but with "hand-drawn" imperfections or subtle line weights to keep them from feeling too cold or robotic.
- **Visual Motif:** The recurring "drift line" should be a smooth, continuous vector pathâ€”never jagged.

## Components

### Buttons
- **Primary:** Solid Deep Sage (#4C6B58) with Off-White text. 12px radius. No shadow.
- **Secondary:** Ghost style with a 1px Sage border or subtle Terracotta text.
- **Behavior:** On hover, primary buttons darken slightly; secondary buttons gain a very light tint background.

### Cards
- Used for "What it Notices" and "Privacy" sections.
- Background: Transparent with a 1px #2B2B26 (at 10% opacity) border. 
- Padding: 32px (lg) to emphasize the content.

### Stat Chips
- Small IBM Plex Mono labels.
- Background: Soft Golden Amber (low opacity) or dusty Sky Blue.
- Used near the Hero and in the "What it Says" table to highlight data points.

### Input Fields & Controls
- Flat 1px borders.
- Labels in IBM Plex Mono (all-caps, small).
- Checkboxes/Radios: Use the Deep Sage for the "Checked" state.

### Illustrations
- Abstract, geometric, line-based. 
- Use the Accent colors (Amber/Blue) to break up the Sage/Terracotta dominance.
- Avoid literal icons; use metaphors for movement, rhythm, and charging.

