---
name: Optima Editorial
colors:
  surface: '#fcf8fd'
  surface-dim: '#dcd9de'
  surface-bright: '#fcf8fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f2f7'
  surface-container: '#f0edf2'
  surface-container-high: '#eae7ec'
  surface-container-highest: '#e4e1e6'
  on-surface: '#1b1b1f'
  on-surface-variant: '#46464f'
  inverse-surface: '#303034'
  inverse-on-surface: '#f3eff4'
  outline: '#777680'
  outline-variant: '#c7c5d0'
  surface-tint: '#565a8d'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#121646'
  on-primary-container: '#7c80b5'
  inverse-primary: '#bec2fc'
  secondary: '#745b1b'
  on-secondary: '#ffffff'
  secondary-container: '#ffdc8e'
  on-secondary-container: '#795f1f'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#360f02'
  on-tertiary-container: '#b4745d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bec2fc'
  on-primary-fixed: '#121646'
  on-primary-fixed-variant: '#3e4274'
  secondary-fixed: '#ffdf9b'
  secondary-fixed-dim: '#e4c278'
  on-secondary-fixed: '#251a00'
  on-secondary-fixed-variant: '#5a4302'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59c'
  on-tertiary-fixed: '#360f02'
  on-tertiary-fixed-variant: '#6c3926'
  background: '#fcf8fd'
  on-background: '#1b1b1f'
  surface-variant: '#e4e1e6'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
  button:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system is built for the high-end luxury real estate market, where the interface serves as a sophisticated frame for architectural photography. The brand personality is authoritative yet welcoming, blending the timelessness of editorial publishing with the precision of modern digital luxury.

The design style is **Minimalist-Editorial**. It prioritizes generous negative space, high-contrast typography, and a "quiet" UI that recedes to let imagery take center stage. Layouts should feel like a premium physical magazine—structured, intentional, and uncluttered. We avoid trendy gradients or heavy shadows in favor of structural clarity and refined proportions.

## Colors

The palette is anchored by a deep **Primary Navy**, providing a sense of stability and heritage. The **Background Light** is a warm, gallery-inspired off-white that feels more premium and less clinical than pure white. 

**Accent Gold** is used sparingly for primary actions and status indicators, signifying exclusivity. Use the Navy for deep-immersion sections (e.g., footers, luxury property showcases) and the Light mode for standard browsing and data-heavy interfaces. Secondary text remains desaturated to maintain a clear visual hierarchy without competing with the primary content.

## Typography

The typography strategy employs a classic serif/sans-serif pairing. **Libre Caslon Text** provides an authoritative, editorial voice for headlines and property titles. It should be set with slightly tight letter-spacing for large displays to evoke a bespoke wordmark feel.

**Hanken Grotesk** is the functional workhorse for body copy and UI elements. It is clean and modern, ensuring that technical property details remain highly legible. Use `label-caps` for eyebrows, categories, and small metadata to add a layer of organized sophistication.

## Elevation & Depth

This design system avoids traditional drop shadows. Depth is achieved through **Tonal Layering** and **Line Work**.

- **Surfaces:** Use subtle shifts between the warm off-white and pure white to define containers.
- **Outlines:** Use very fine, low-contrast borders (1px) in a slightly darker version of the background color to define input fields or card boundaries.
- **Glassmorphism:** Use a light backdrop blur (12px to 20px) on navigation bars when scrolling over imagery to maintain the "frame" feel without obscuring the photography.

## Shapes

To maintain a sophisticated and architectural aesthetic, the shape language is **Soft (0.25rem)**. Buttons and input fields should have minimal rounding to feel precise and intentional. Circular shapes are reserved exclusively for icon buttons or avatars to provide a controlled point of contrast against the predominantly rectangular grid.

## Components

### Buttons
- **Primary:** Solid Gold background with Navy text. No border. Sharp or 4px radius. 
- **Secondary:** Transparent background with a Navy or White 1px border.
- **Tertiary:** Text-only with a fine 1px underline that expands on hover.

### Cards
Property cards should be "frameless." The image occupies the full width of the card with no padding. Text content follows below with generous top-padding. No heavy shadows; use a 1px soft border if placed on a background of the same color.

### Input Fields
Minimalist bottom-border-only or thin 4-sided strokes. Floating labels in `label-caps` style. No background fill for inputs on light backgrounds.

### Imagery
The most important "component." All imagery should be high-resolution, color-corrected for warmth, and use a consistent aspect ratio (typically 4:3 or 16:9). Use a "ken burns" subtle zoom effect on hover for property cards to add a sense of life.

### Navigation
The header should be transparent on homepages (overlaying hero images) and transition to a solid or blurred off-white on scroll. Use high-contrast Navy text for navigation links.