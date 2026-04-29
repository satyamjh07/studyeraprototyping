---
name: Standardized Assessment System
colors:
  surface: '#fbf9fa'
  surface-dim: '#dbd9db'
  surface-bright: '#fbf9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f4'
  surface-container: '#efedef'
  surface-container-high: '#e9e8e9'
  surface-container-highest: '#e4e2e3'
  on-surface: '#1b1c1d'
  on-surface-variant: '#43474c'
  inverse-surface: '#303032'
  inverse-on-surface: '#f2f0f2'
  outline: '#74777d'
  outline-variant: '#c4c6cd'
  surface-tint: '#4e6073'
  primary: '#162839'
  on-primary: '#ffffff'
  primary-container: '#2c3e50'
  on-primary-container: '#96a9be'
  inverse-primary: '#b5c8df'
  secondary: '#006397'
  on-secondary: '#ffffff'
  secondary-container: '#5cb8fd'
  on-secondary-container: '#00476e'
  tertiary: '#362308'
  on-tertiary: '#ffffff'
  tertiary-container: '#4e381c'
  on-tertiary-container: '#c1a17d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e4fb'
  primary-fixed-dim: '#b5c8df'
  on-primary-fixed: '#091d2e'
  on-primary-fixed-variant: '#36485b'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#92ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#ffddb7'
  tertiary-fixed-dim: '#e3c19b'
  on-tertiary-fixed: '#291802'
  on-tertiary-fixed-variant: '#5a4225'
  background: '#fbf9fa'
  on-background: '#1b1c1d'
  surface-variant: '#e4e2e3'
typography:
  section-title:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  question-text:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 26px
  option-text:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  palette-number:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
  timer-display:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 24px
    letterSpacing: -0.02em
  button-label:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  header-height: 60px
  sidebar-width: 300px
  gutter: 1rem
  container-padding: 1.5rem
  stack-gap: 0.75rem
---

## Brand & Style

The design system is engineered for high-stakes academic and professional assessments, prioritizing cognitive ease and zero-distraction environments. The brand personality is institutional, authoritative, and strictly functional, mirroring the rigor of national-level testing agencies (NTA). 

The design style follows a **Corporate / Modern** aesthetic with a heavy emphasis on utility. It utilizes a structured, high-contrast interface that eliminates decorative elements in favor of information density and task focus. The UI is designed to evoke a sense of calm reliability, ensuring that the candidate's entire focus remains on the content of the examination rather than the interface itself.

## Colors

This design system utilizes a logic-driven color palette where hue is directly tied to candidate progress and system status. 

- **Primary & Neutral**: The foundation relies on a white background (#FFFFFF) for the core workspace to ensure maximum contrast with text. Neutral light grays are used for structural containers and backgrounds to reduce eye strain during long sessions.
- **Functional Status Palette**: 
    - **Green (#2ECC71)**: Confirms a committed action (Answered).
    - **Red (#E74C3C)**: Highlights an incomplete task (Not Answered).
    - **Purple (#8E44AD)**: Indicates a pending decision (Marked for Review).
    - **Grey (#BDC3C7)**: Represents untouched items (Not Visited).
- **Interactive UI**: A deep slate (#2C3E50) is used for headers and primary navigation to provide a solid visual anchor.

## Typography

The design system exclusively uses **Inter** to leverage its exceptional legibility in digital environments. 

- **Readability**: Question text is set at 16px with a generous 1.6x line height to prevent fatigue.
- **Hierarchy**: Section titles are bold and clearly separated from the workspace. 
- **Functional UI**: Small labels, such as those in the question palette, use a slightly heavier weight (600) to remain legible at smaller sizes. 
- **Timer**: The countdown timer uses a tabular numeric setting to prevent text jumping as numbers change.

## Layout & Spacing

The layout follows a **Fixed Grid** model for the main workspace to maintain a consistent reading line length, while using a split-screen approach for the exam interface.

- **Top Navigation Bar**: A fixed-position bar containing the exam title, section switcher (tabs), and the countdown timer.
- **Two-Column Body**:
    - **Main Area (Left)**: Scrollable region containing the current question and options. It features wide internal margins to keep the content centered and focused.
    - **Sidebar (Right)**: A sticky palette containing the question number grid, candidate info, and legend.
- **Spacing Rhythm**: A 4px/8px base unit is used. Elements within a question (options, images) are tightly grouped (stack-gap), while major sections are separated by larger gutters.

## Elevation & Depth

To maintain a distraction-free environment, this design system avoids shadows and complex depth. Visual hierarchy is achieved through **Bold Borders** and **Tonal Layers**.

- **Containers**: The main question area and sidebar are enclosed in subtle 1px solid borders (#DCDDE1).
- **Active State**: The currently active question in the palette is indicated by a thicker 2px primary-colored border rather than a shadow.
- **Depth**: A light gray background (#F8F9FA) behind the main white content cards provides a subtle "lift" without the use of artificial blurs or lighting effects.

## Shapes

The design system adopts a **Soft** shape language (4px radius) to provide a modern feel while retaining a serious, geometric structure.

- **Buttons & Inputs**: Use a consistent 4px radius.
- **Question Palette**: Individual question numbers are typically squares with 4px rounding or hexagons (as per traditional NTA style), ensuring clear differentiation between status types.
- **Selection Indicators**: Radio buttons and checkboxes follow standard OS shapes but use the primary brand colors for active states.

## Components

- **Buttons**:
    - *Primary (Save & Next)*: High-contrast solid fill (#2C3E50), white text.
    - *Secondary (Clear Response)*: Ghost style with 1px border.
    - *Warning (Submit)*: Located far from navigation buttons to prevent accidental clicks.
- **Question Palette**: A grid of numbered boxes. Each box changes color based on the status (Green, Red, Purple, Grey). The active question is highlighted with a high-contrast border.
- **Option Selection**: Radio buttons for single-choice and checkboxes for multi-choice. The entire row should be clickable, with a subtle gray hover state to indicate interactivity.
- **Section Tabs**: Located in the top bar. Active sections are indicated by a solid bottom border (3px) and bold text.
- **Status Legend**: A persistent footer in the sidebar explaining the color coding of the question palette using small iconographic swatches.
- **Question Card**: A clean container for the question text, followed by a vertical stack of options. Images must be contained within a bounded box to prevent layout shifts.