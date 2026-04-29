---
name: Kinetic Zero
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#ecb2ff'
  on-secondary: '#520071'
  secondary-container: '#cf5cff'
  on-secondary-container: '#480063'
  tertiary: '#f5f5f5'
  on-tertiary: '#2f3131'
  tertiary-container: '#d9d9d9'
  on-tertiary-container: '#5d5f5f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#f8d8ff'
  secondary-fixed-dim: '#ecb2ff'
  on-secondary-fixed: '#320047'
  on-secondary-fixed-variant: '#74009f'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  h1:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
  code:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.5'
    letterSpacing: '0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  stack-xl: 64px
---

## Brand & Style
The design system is engineered for high-stakes academic performance, targeting the elite tier of Gen Z students preparing for the JEE. The aesthetic is "Technological Brutalism meets Premium Minimalism"—it is intentionally aggressive to reflect the intensity of the examination while remaining uncluttered to ensure focus. 

The emotional response is one of serious intent and digital precision. By stripping away unnecessary ornamentation and focusing on high-contrast neon accents against a void-black background, the design system creates a "flow state" environment. The style utilizes futuristic technical cues—such as monospaced accents and subtle glowing interfaces—to position the platform as a high-performance tool rather than a standard educational resource.

## Colors
The palette is anchored by an absolute black (#0A0A0A) to maximize the "infinite depth" feel of the OLED display. The primary accent is **Cyber Blue**, a high-vibrancy neon used for core actions and progress indicators. **Voltage Purple** serves as the secondary accent, utilized for gamification elements and distinction between subject matters.

Text is primarily high-contrast white to ensure maximum readability during long study sessions. Surface levels use subtle increments of grey (#141414, #1F1F1F) to create depth without breaking the dark-themed immersion. Semantic colors (red and green) are pushed to high saturation to maintain the "Neon" aesthetic while providing clear feedback.

## Typography
The design system employs a dual-font strategy. **Space Grotesk** is used for headlines and labels to provide a technical, futuristic edge. Its geometric construction feels modern and slightly aggressive, perfect for "ZEROday" branding. 

For all long-form reading and functional data, **Inter** is the workhorse. It provides the necessary clarity for complex mathematical equations and technical text. High contrast is maintained by using pure white for headings and a slightly dimmed 90% white for body copy to reduce eye strain. Letter spacing is tightened on large headings for a "compact" feel and widened on uppercase labels for a technical, mapped-out appearance.

## Layout & Spacing
This design system utilizes a strict 4px baseline grid to ensure mathematical precision in all alignments. A 12-column fluid grid is the standard for desktop views, transitioning to a 4-column grid for mobile. 

The spacing philosophy is "Internal Density, External Breathability." Elements within a card or module are tightly packed to convey high performance and efficiency, while large margins (40px+) are used between major sections to prevent cognitive overload. Gutters are kept at a generous 24px to ensure that even with "aggressive" content, the UI feels premium and organized.

## Elevation & Depth
Elevation is not achieved through traditional dropshadows but through **Tonal Layering** and **Neon Diffusion**. 

1.  **Base Layer:** The background is #0A0A0A.
2.  **Surface Layer:** Cards and containers use #141414.
3.  **Active Layer:** Elements currently in focus use a subtle 1px border of #1F1F1F or a very faint "glow" shadow using the primary accent color (0% to 10% opacity) to simulate light emission from the screen.

Shadows are "Soft & Expansive"—using large blur radii (32px+) with very low opacity to create a sense of the interface floating in a void, rather than sitting on a solid surface.

## Shapes
The shape language is dominated by "2xl" corners (1.5rem / 24px) for all primary containers and cards. This extreme roundedness creates a distinct, "liquid-hardware" look that feels premium and friendly to the touch, contrasting the aggressive typography.

Smaller elements like buttons and input fields follow this hierarchy but at a reduced scale to maintain visual balance. High-action elements (like "Start Test") may occasionally use a pill-shape to distinguish them from structural containers. Borders are strictly 1px or 2px—never thicker—to maintain the clean, futuristic aesthetic.

## Components
- **Buttons:** Primary buttons are solid Cyber Blue with black text for maximum punch. Secondary buttons are outlined with a 1px gradient or solid Voltage Purple. "Ghost" buttons use Space Grotesk in all-caps with 0.1em letter spacing.
- **Cards:** Feature #141414 backgrounds, 24px corner radii, and a very subtle 1px top-border to catch "ambient light."
- **Inputs:** Darker than the surface (#0F0F0F) with a focus state that activates a Cyber Blue outer glow and a 1px solid border.
- **Progress Bars:** Use a dual-gradient (Blue to Purple) with a "pulse" animation to signify active processing or high-performance calculation.
- **Chips/Labels:** Small, 4px rounded or pill-shaped containers with monospaced labels (Inter Medium) used for tagging difficulty levels (e.g., "HARD", "PYQ").
- **Specialty Components:** 
    - **Countdown Timers:** Large, Space Grotesk Bold digits with a faint glow to instill a sense of urgency.
    - **Leaderboard Rows:** High-gloss finishes with subtle glassmorphism (10% opacity white overlay) to highlight top-tier students.