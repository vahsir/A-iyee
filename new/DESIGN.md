---
name: Obsidian Nexus
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#1f1f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#cfc4c5'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#988e90'
  outline-variant: '#4c4546'
  surface-tint: '#c6c6c6'
  primary: '#c6c6c6'
  on-primary: '#303030'
  primary-container: '#000000'
  on-primary-container: '#757575'
  inverse-primary: '#5e5e5e'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#c6c6c6'
  on-tertiary: '#303030'
  tertiary-container: '#000000'
  on-tertiary-container: '#757575'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
typography:
  display-xl:
    fontFamily: Montserrat
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: 0.05em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.01em
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  section-gap: 120px
  stack-gap: 16px
---

## Brand & Style
The brand personality is authoritative, technical, and hyper-premium, designed to reflect the precision of high-level DevOps engineering. It targets a sophisticated audience of technical recruiters and engineering leads who value clarity, performance, and modern aesthetics.

The design style is **Neo-minimalist Glassmorphism**. It utilizes a "dark mode by default" philosophy, emphasizing deep blacks to represent the terminal and backend infrastructure, contrasted by sharp, vibrant neon accents that represent data flow and connectivity. The interface relies on heavy negative space and high-contrast typography to create an elite, curated experience that feels more like a command center than a standard portfolio.

## Colors
The palette is rooted in absolute blacks and deep slates to ensure maximum depth. 
- **Primary Black (#000000):** Used for the base canvas to allow light-emitting elements to pop.
- **Surface Slate (#121212):** Used for card backgrounds and elevated containers to create a tiered hierarchy.
- **Electric Cyan (#00F2FF):** The primary action and status color, representing "System Online" or "Success." Use sparingly for high-impact focus.
- **Neon Purple (#BD00FF):** Secondary accent for gradients and secondary CTAs, adding a sense of creative energy to the technical base.
- **Gradients:** Use a linear gradient from Cyan to Purple for high-profile visual elements like progress bars or active hover states.

## Typography
Typography is the primary driver of the premium feel. **Montserrat** is reserved for headlines to provide a bold, geometric presence, while **Inter** ensures maximum legibility for technical descriptions and body copy.

All display and headline levels must utilize generous letter spacing (tracking) to evoke a cinematic, high-end tech aesthetic. Labels and metadata should always be in uppercase with extra tracking to mimic terminal headers. Use color contrast (White vs. Slate Gray) to establish hierarchy rather than just font size.

## Layout & Spacing
The layout follows a **Fixed Grid** model for desktop to maintain the "editorial" feel of a high-end portfolio, switching to a fluid model for mobile devices.

- **Desktop:** 12-column grid with a 1280px max-width. Sections are separated by large vertical gaps (120px+) to allow the design to breathe and emphasize individual projects.
- **Alignment:** Use asymmetrical layouts for project showcases—text on one side, large visual on the other—to create visual interest.
- **Rhythm:** Elements within cards and containers should use a strict 8px base grid for padding and internal spacing.

## Elevation & Depth
Depth is achieved through **Glassmorphism and Internal Glows** rather than traditional drop shadows.

- **The Glass Effect:** Surface layers use `rgba(18, 18, 18, 0.7)` with a `backdrop-filter: blur(20px)`. This creates a frosted lens effect over the base black background.
- **Inner Glows:** Instead of external shadows, use a subtle `1px` white inner stroke with 5-10% opacity at the top edge of cards to simulate a light source from above.
- **Soft Glows:** Use "fuzz" or "aura" effects behind key elements. These are large, low-opacity (10-15%) radial gradients of Cyan or Purple positioned deep in the background to provide a sense of environmental lighting.

## Shapes
In line with the technical and precise nature of DevOps, the design system utilizes **Soft (0.25rem)** roundedness. 

While the general aesthetic feels "sharp," the 4px corner radius prevents the UI from feeling aggressive, making it appear machined and refined. Interactive elements like buttons and input fields should strictly adhere to this radius. Progress bars and decorative tags should remain perfectly square to maintain the "grid-like" technical feel.

## Components
- **Buttons:** Primary buttons use a solid Electric Cyan background with black text. Secondary buttons are "Ghost" style with a 1px border and a subtle hover glow.
- **Cards:** Utilize the Surface Slate (#121212) background. Each card must have a 1px border using `rgba(255,255,255,0.08)`. On hover, the border color transitions to the Electric Cyan.
- **Chips/Badges:** Small, rectangular badges for "Tech Stack" items. They use a dark purple background with neon purple text at a small `label-sm` font size.
- **Input Fields:** Minimalist lines or very dark containers with 1px bottom borders. The active state should trigger a subtle Cyan glow underneath the input field.
- **Data Visualizations:** Use thin, 1px lines for charts and graphs. Data points should be represented by small, glowing Cyan circles.
- **Iconography:** Use "Linear" or "Thin" icons with a 1px or 1.5px stroke weight. Icons can occasionally have a small drop-shadow glow of the same color to make them appear as "light-source" elements.