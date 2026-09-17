---
name: Orbital Spectral HUD
colors:
  surface: '#10141a'
  surface-dim: '#10141a'
  surface-bright: '#353940'
  surface-container-lowest: '#0a0e14'
  surface-container-low: '#181c22'
  surface-container: '#1c2026'
  surface-container-high: '#262a31'
  surface-container-highest: '#31353c'
  on-surface: '#dfe2eb'
  on-surface-variant: '#b9cac2'
  inverse-surface: '#dfe2eb'
  inverse-on-surface: '#2d3137'
  outline: '#84948d'
  outline-variant: '#3b4a44'
  surface-tint: '#00e0b3'
  primary: '#bbffe6'
  on-primary: '#00382b'
  primary-container: '#00f0c0'
  on-primary-container: '#006852'
  inverse-primary: '#006b54'
  secondary: '#ffb95f'
  on-secondary: '#472a00'
  secondary-container: '#ee9800'
  on-secondary-container: '#5b3800'
  tertiary: '#ffeded'
  on-tertiary: '#67001b'
  tertiary-container: '#ffc7c9'
  on-tertiary-container: '#b80538'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#32fece'
  primary-fixed-dim: '#00e0b3'
  on-primary-fixed: '#002118'
  on-primary-fixed-variant: '#00513f'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#ffdadb'
  tertiary-fixed-dim: '#ffb2b7'
  on-tertiary-fixed: '#40000d'
  on-tertiary-fixed-variant: '#92002a'
  background: '#10141a'
  on-background: '#dfe2eb'
  surface-variant: '#31353c'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system embodies the high-stakes precision of orbital remote sensing and industrial mission control. Built for planetary methane plume tracking, continuous pipeline telemetry, and industrial leak detection, the interface evokes the calm, focused atmosphere of an aerospace control room. The visual atmosphere is strictly dark-mode, tactical, and utilitarian—favoring razor-sharp information density, unambiguous status signaling, and zero decorative bloat.

Stylistically, this system blends aerospace Heads-Up Display (HUD) optics with modern mission-critical operational consoles:
- **Telemetry-Driven Clarity:** Visual weight follows diagnostic priority; raw coordinates, PPM-m concentrations, and spectral flux metrics supersede generic graphical abstractions.
- **Luminous HUD Accents:** Bioluminescent spectral teals and sharp sensor greens emerge against an abyssal carbon backdrop, directing ocular focus without fatiguing operators over 12-hour monitoring shifts.
- **Instrument Precision:** Hairline vector grids, orthographic coordinate markers, and bounded target reticles evoke optical targeting and aerial spectrometry apparatus.

## Colors
The palette relies on absolute darkness punctured by radiant emissions of chromatic spectral light. High dynamic contrast ensures instantaneous threat identification across dense spatial data sets.

- **Primary (`#00f0c0`):** Luminescent Methane Teal. Used for nominal telemetry signals, focal mission targets, active plume vectors, active crosshairs, and primary system confirmation states.
- **Secondary (`#f59e0b`):** Warning Amber. Dictates threshold exceedances, optical drift warnings, degraded sensor states, and moderate fugitive emissions.
- **Tertiary (`#f43f5e`):** Critical Flare Coral. Reserved exclusively for acute hazard containment breaches, supercritical leak rates, emergency orbital tasks, and failure overrides.
- **Neutral Surface Matrix (`#05080c` to `#161e2b`):** Deep obsidian space vacuum. 
  - Base canvas sits at `#05080c`.
  - Console deck / container panels anchor at `#0a0e14`.
  - Elevated instrument modules and active overlays occupy `#101721`.
  - Muted structural outlines and reticles use `#1e293b`.
- **Text & Telemetry Light:** Pure white (`#ffffff`) for raw numerical telemetry readings, subdued sensor silver (`#94a3b8`) for baseline structural captions and secondary data legends.

## Typography
Typographic treatment follows a dual-axis structural model: technical-geometric prose paired with rigid monospaced instrumentation.

- **Display & Section Headers (`Space Grotesk`):** Delivers clean, geometric tension reminiscent of aerospace flight displays. Always set tight with zero faux-futuristic slant; all caps should be reserved strictly for tier-1 terminal status banners and mission designations.
- **Interface & Prose (`Inter`):** Handles dense narrative incident reports, operator debrief logs, and parameter documentation. Neutral, high x-height, and immune to ocular fatigue.
- **Telemetry & Instrument Readouts (`JetBrains Mono`):** Every numerical metric, GPS coordinate, timestamp (UTC), spectral wavelength value, and sensor identifier is set in monospace. Tabular numbers ensure absolute visual stability without horizontal jitter during live high-frequency data streams.

## Layout & Spacing
The layout operates on an uncompromising 4px baseline sub-grid configured for multi-monitor workstation setups, tactical consoles, and field telemetry tablets.

- **Structure:** 12-column adaptive fluid grid for primary workstation consoles, scaling into high-density modular docking bays. The viewport prioritizes continuous real-time viewport maps/spectral streams flanked by persistent left/right diagnostic rails.
- **Docking Rails:** Fixed-width operational toolbars (280px to 380px) on desktop, transitioning into collapsible telemetry sheets on tablet screens.
- **Breakpoints:**
  - **Desktop / Multi-display (1440px+):** Full multi-panel ops center layout with side-by-side spectral telemetry, sensor controls, and continuous event stream.
  - **Tablet / Tactical Screen (768px - 1439px):** Split-view HUD, map-dominant mode with drawer-based metric instrumentation; margins pinch to 1.5rem.
  - **Mobile / Field Device (< 768px):** Single-column stacked telemetry cards, persistent bottom alarm drawer, and full-bleed target visualization viewport.

## Elevation & Depth
Depth is rendered through luminance and optical containment rather than soft drop shadows. Physical depth metaphors are rejected in favor of tactical optical layering:

- **Tonal Layers:** Elevation is governed by dark surface shifts:
  - Base Void (`#05080c`): Background canvas and unmapped areas.
  - Sub-deck (`#0a0e14`): Primary layout panels and instrument trays.
  - HUD Card / Surface (`#101721`): Interactive modules and inspection targets.
  - Active Overlay (`#162232`): Modals, dropdown drawers, and context cross-sections.
- **Hairline Bounding:** Surfaces are framed by subtle 1px low-contrast borders (`rgba(148, 163, 184, 0.12)`). Active, selected, or alerting panels shift border colors directly to primary teal, warning amber, or critical coral.
- **Luminescent Glow:** High-priority status nodes emit concentrated, tight bioluminescent blurs (e.g., `box-shadow: 0 0 12px rgba(0, 240, 192, 0.35)` or `0 0 16px rgba(244, 63, 94, 0.45)`), creating an illuminated instrument panel aesthetic in dark monitoring rooms.

## Shapes
The system utilizes subtle, clipped micro-radii to maintain an engineered, tactical aesthetic. Broad pill shapes and soft organic curves are strictly avoided for functional containers to preserve the look of machined physical hardware.

- **Containers & Panels:** Soft 4px (`rounded-sm` / radius `1`) corners maintain structural discipline across dense dashboard arrangements without the harsh visual fatigue of raw 0px corners.
- **HUD Reticles & Targeting Brackets:** Sharp corner cutouts or interior tick marks applied via SVG pseudo-elements to evoke optics calibration markers.
- **Status Pills:** Small, specialized radius treatment reserved strictly for micro status pills and coordinate chips to differentiate interactive nodes from structural data framing.

## Components

### Action Buttons
- **Primary Tactical Button:** Background `#00f0c0` with `#05080c` high-contrast bold typography. On hover, triggers a tight luminescent teal halo (`box-shadow: 0 0 16px rgba(0, 240, 192, 0.4)`).
- **Secondary Ghost Control:** Dark surface (`#101721`) with 1px border (`#1e293b`), typography in `#00f0c0` or `#ffffff`. On hover, border illuminates to `#00f0c0`.
- **Destructive/Hazard Override:** Dark surface framed by 1px `#f43f5e`, text in `#f43f5e`. Emits a faint pulse under active emergency override states.

### Status Indicators & Pills
- **Telemetry Badges:** Rendered in `JetBrains Mono` uppercase with an illuminated 6px circular ping indicator. 
- **States:** Nominal (`#00f0c0`), Elevated (`#f59e0b`), Critical Breach (`#f43f5e`), Inactive/Calibrating (`#64748b`). Backgrounds use a 10% alpha fill of the corresponding indicator color with a matching 1px border at 30% alpha.

### Input Fields & Controls
- **Telemetry Parameter Inputs:** Dark sunken fill (`#070a0f`), 1px structural boundary (`#1e293b`), monospace metric suffix (e.g., `PPM`, `KG/HR`, `LAT/LONG`) pinned to the trailing edge in `#64748b`. Focused states drop the border to `#00f0c0` with no browser-native outline.
- **Checkboxes & Radios:** Sharp, square 4px bounding boxes. Active states feature an illuminated solid core with zero inset beveling.

### Cards & Telemetry Pods
- **HUD Monitoring Panels:** Deep obsidian base with 1px hairline border. The top-left corner features an optional bracket-style monospace technical readout (e.g., `// SENSOR-ARRAY-04 //`).
- **Telemetry Callouts:** Oversized numerical figures set in `Space Grotesk` or `JetBrains Mono` flanked by unit markers and sparkline trend vectors rendered in high-contrast luminous teal or hazard coral.

### Specialized Mission Ops Components
- **Radar / Coordinate Grid:** Hairline concentric rings and Cartesian crosshairs rendered at `rgba(255, 255, 255, 0.05)` over real-time spatial plume layers.
- **Plume Severity Bar:** Stepped segmented linear gauge displaying emission volume across 5 discretized blocks instead of continuous gradients, preserving instant diagnostic evaluation.