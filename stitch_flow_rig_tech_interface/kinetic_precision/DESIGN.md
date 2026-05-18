---
name: Kinetic Precision
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
  on-surface-variant: '#e3bfb3'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#aa897f'
  outline-variant: '#5b4138'
  surface-tint: '#ffb59c'
  primary: '#ffb59c'
  on-primary: '#5c1900'
  primary-container: '#ff5f1f'
  on-primary-container: '#561700'
  inverse-primary: '#ab3600'
  secondary: '#c6c6cb'
  on-secondary: '#2f3034'
  secondary-container: '#45474b'
  on-secondary-container: '#b4b5ba'
  tertiary: '#c6c6cb'
  on-tertiary: '#2f3034'
  tertiary-container: '#939398'
  on-tertiary-container: '#2b2c30'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcf'
  primary-fixed-dim: '#ffb59c'
  on-primary-fixed: '#390c00'
  on-primary-fixed-variant: '#832700'
  secondary-fixed: '#e2e2e7'
  secondary-fixed-dim: '#c6c6cb'
  on-secondary-fixed: '#1a1c1f'
  on-secondary-fixed-variant: '#45474b'
  tertiary-fixed: '#e3e2e7'
  tertiary-fixed-dim: '#c6c6cb'
  on-tertiary-fixed: '#1a1b1f'
  on-tertiary-fixed-variant: '#46464b'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  data-mono:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  gutter: 16px
  margin: 24px
---

## Brand & Style

The visual identity of this design system is rooted in the aesthetics of aerospace engineering and high-performance mechanical tools. It targets professional cinematographers and technicians who require gear that feels like an extension of their own precision. The design system evokes a sense of "zero-latency" reliability, utilizing a high-contrast environment to ensure legibility under intense set lighting or dark studio conditions.

The style is a hybrid of **Industrial Minimalism** and **Technical Brutalism**. It prioritizes structural integrity over decorative softness, using sharp edges, rigid containment, and physical metaphors like brushed metal surfaces and CNC-machined bevels. Every pixel is intended to feel intentional and engineered, moving away from the "organic" trends of consumer software toward a professional-grade instrumentation interface.

## Colors

This design system utilizes a high-contrast dark mode as its native state. **Deep Black (#000000)** serves as the foundation, providing an infinite-depth canvas that minimizes screen glare for operators. **Safety Orange (#FF5F1F)** is reserved strictly for interactive highlights, critical status indicators, and primary call-to-actions, mimicking the physical "Record" and "Release" buttons on gimbal hardware.

The **Brushed Steel** palette (#8E8E93, #D1D1D6) is used to define structural elements and secondary information. Subtle metallic gradients are applied to headers and containers to simulate light catching on machined aluminum edges. Neutral grays are utilized to create a clear hierarchy in data-heavy environments, ensuring that secondary telemetry doesn't distract from core gimbal metrics.

## Typography

The typography strategy focuses on immediate data acquisition. **Inter** is the primary typeface, chosen for its exceptional legibility and neutral, industrial character. It handles all functional UI text and body copy. 

For technical data, telemetry, and readout values, the design system employs **Space Grotesk**. This font’s geometric construction and technical flair provide a "heads-up display" (HUD) feel. Upper-case labeling with increased letter spacing is used for all technical descriptors to mimic engraved equipment plates. Numerical data should always use tabular lining to ensure that real-time values do not cause visual layout shifts as numbers change.

## Layout & Spacing

This design system adheres to a **Fixed Grid** model. A 12-column grid is used for desktop telemetry dashboards, while a 4-column grid is used for mobile controller interfaces. Gutters are kept tight at 16px to maintain a dense, "cockpit" feel, maximizing the information displayed on screen.

Spacing follows a strict 4px base-unit system. Alignment is always rigid; elements must snap to the grid to maintain the "engineered" aesthetic. Padding within data cards is minimized to allow for high-density information display, while external margins are generous to prevent the UI from feeling cluttered or unrefined.

## Elevation & Depth

Elevation in this design system is communicated through **Tonal Layering** and **Structural Outlines** rather than soft shadows. Surfaces are stacked using varying shades of black and dark gray to indicate hierarchy. 

To simulate a physical, mechanical build, the design system uses:
1. **Inner Bevels:** 1px borders with a metallic gradient to simulate the edge of a machined part.
2. **Sunken Layers:** Data-heavy cards use a slight "inset" shadow to appear recessed into the control panel.
3. **High-Contrast Outlines:** Active or focused elements are defined by a 1px Safety Orange border.
4. **Metallic Gradients:** Top-level navigation or "Master" control headers use a subtle linear gradient (#D1D1D6 to #8E8E93) to indicate a tactile surface that is raised above the matte telemetry panels.

## Shapes

The shape language is strictly **Sharp (0px)**. To reinforce the precision-engineered feel, all buttons, cards, inputs, and containers utilize right angles. This choice mirrors the physical chassis of high-end camera rigs and gimbal stabilizers.

Where "softness" is required for clarity (such as circular status LEDs), the design system uses perfect circles to maintain a geometric, mathematical rigor. Interactive zones are defined by hard borders, and "pill" shapes are avoided entirely to distance the interface from consumer-grade software aesthetics.

## Components

### Buttons
Primary buttons are solid Safety Orange with black text. Secondary buttons use a "Steel" stroke (1px) with no fill. All button states (hover, active) must be instantaneous to reflect the "zero-latency" brand promise.

### Data-Heavy Cards
Cards act as "modules." They feature a 1px Steel border and a header section with a subtle metallic gradient. Information within is organized into rows using thin, low-opacity dividers to maintain readability without adding visual bulk.

### Technical Toggles
Instead of rounded switches, toggles are designed as rectangular "rocker" switches. The "on" state is indicated by a Safety Orange indicator light (small square or circle) and a high-contrast border around the active side of the toggle.

### Analytics & Graphs
Graphs use ultra-thin lines (1px) in Brushed Steel Light. The data points or "live" telemetry paths are highlighted in Safety Orange. Background grids for graphs should be subtle, using a 10% opacity steel color.

### Technical Readouts
A specialized component for displaying sensor data (e.g., Pan/Tilt/Roll degrees). These feature the **Space Grotesk** font in a large size, with the unit of measurement (e.g., "DEG") displayed in small caps in the top right corner of the container.