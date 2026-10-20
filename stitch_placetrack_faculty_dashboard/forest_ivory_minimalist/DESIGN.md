---
name: Forest & Ivory Minimalist
colors:
  surface: '#f8faf1'
  surface-dim: '#d8dbd2'
  surface-bright: '#f8faf1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f5ec'
  surface-container: '#ecefe6'
  surface-container-high: '#e6e9e0'
  surface-container-highest: '#e0e4db'
  on-surface: '#191d17'
  on-surface-variant: '#414844'
  inverse-surface: '#2e322c'
  inverse-on-surface: '#eff2e9'
  outline: '#717974'
  outline-variant: '#c1c8c3'
  surface-tint: '#406656'
  primary: '#0b3326'
  on-primary: '#ffffff'
  primary-container: '#244a3b'
  on-primary-container: '#90b9a5'
  inverse-primary: '#a6d0bc'
  secondary: '#4c644f'
  on-secondary: '#ffffff'
  secondary-container: '#ceeace'
  on-secondary-container: '#526a54'
  tertiary: '#3d2914'
  on-tertiary: '#ffffff'
  tertiary-container: '#553f28'
  on-tertiary-container: '#caab8d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c2ecd7'
  primary-fixed-dim: '#a6d0bc'
  on-primary-fixed: '#002116'
  on-primary-fixed-variant: '#284e3f'
  secondary-fixed: '#ceeace'
  secondary-fixed-dim: '#b2ceb3'
  on-secondary-fixed: '#09200f'
  on-secondary-fixed-variant: '#344c38'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#e1c1a2'
  on-tertiary-fixed: '#291805'
  on-tertiary-fixed-variant: '#59422b'
  background: '#f8faf1'
  on-background: '#191d17'
  surface-variant: '#e0e4db'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  data-mono:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
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
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers an editorial, archival document-management aesthetic tailored for higher education institutions, career centers, and corporate recruiting partners. The personality balances institutional gravitas with contemporary editorial restraint: studious, dependable, pristine, and unobtrusive.

The visual direction merges **Minimalism** with an archival, print-inspired **Documentary Structure**:
- Ivory backdrop (#F7F5EF) paired with crisp white document cards (#FFFFFF) creates a physical, archival paper quality without resorting to faux textures.
- Deep Forest Green (#244A3B) and Sage accents ground the UI in academic permanence, replacing the tech-industry default of vivid electric blues.
- The interface emphasizes high-density clarity: dense tabular data, fine hairline dividers (1px solid #E6E2D9), muted semantic badging, and crisp editorial typography.
- Avoid all hyper-modern glassmorphic blurs, vivid saturated gradients, heavy elevations, or bulbous rounded corners. Every visual element serves document verification, audit tracking, and student progression monitoring.

## Colors

The palette relies on organic, academic pigments: forest foliage, archival rag ivory, botanical sage, and warm terracotta parchment tones.

### Color Tokens & Assignments

- **Background Canvas (`#F7F5EF`)**: Warm unbleached ivory paper tone. Used strictly for full-bleed page backdrops, outer application canvas, and primary sidebar containers.
- **Surface Crisp (`#FFFFFF`)**: Pure sheet white. Used for main content cards, data tables, modals, flyouts, and dropdown surfaces to maintain crisp contrast against ivory.
- **Primary Deep Forest (`#244A3B`)**: The authoritative brand anchor. Applied to primary CTAs, active table selection states, persistent navigation icons, and title emphasis.
- **Secondary Sage (`#78927A`)**: Mid-tone botanical green for secondary controls, focused interactive strokes, and sub-navigation indicators.
- **Pale Sage Fill (`#EDF2EA`)**: Subtle tinted background for active rows, badge backdrops, table hover fills, and selection highlights.
- **Terracotta Accent (`#D8B89A`)**: Muted warm earth tone for tertiary markers, highlight callouts, document revision flags, and date anchors.
- **Text Primary Charcoal (`#343832`)**: High-legibility deep carbon gray for all primary headings, body copy, and dense data labels. Replaces pure `#000000` for a softened editorial reading rhythm.
- **Text Secondary Subdued (`#777A73`)**: Warm slate-gray for metadata, timestamps, input placeholders, table headers, and breadcrumb trails.
- **Border & Rule (`#E6E2D9`)**: Precise 1px hairline divider for table borders, grid separators, container strokes, and control boundaries.

### Semantic Status Colors
Status badges use low-saturation tinted surfaces with darkened, high-contrast foreground text:
- **Success / Verified**: Background `#E4EFE3`, Foreground `#205737`
- **Pending / In Review**: Background `#FFF0D9`, Foreground `#8F5B16`
- **Error / Rejected**: Background `#F8E5E2`, Foreground `#982C24`
- **Neutral / Draft**: Background `#EDF2EA`, Foreground `#343832`

## Typography

Typography is strictly driven by **Inter**, configured for structured document hierarchies, tabular numerical clarity, and compact administrative utility.

- **Tabular Numerics**: Tabular lining figures (`font-variant-numeric: tabular-nums`) are globally enforced across data grids, registration IDs, GPA scores, and audit timestamps to ensure aligned columns.
- **Editorial Proportion**: Headings remain restrained in size (maximum 32px on desktop), prioritizing vertical real estate for records, candidate cards, and approval queues.
- **Uppercase Metadata**: `label-sm` is reserved for table headers, metadata caps, and section dividers. It uses 600 weight with wide tracking (+0.04em) and muted text coloring (`#777A73`) to introduce clear document-style section divisions.
- **Data Scannability**: High weight contrast (Regular 400 for standard values, Medium 500 for student names, Semibold 600 for status markers and IDs) enables swift review of candidate registries.

## Layout & Spacing

This design system uses a structured **12-column fluid grid** nested inside a constrained administrative workspace frame:
- **Maximum Container Width**: 1440px on high-resolution screens; centered with auto-margins when viewport expands beyond 1440px.
- **Grid Layout**: 12 columns with 1rem (16px) gutters on desktop and tablet, collapsing to a single-column stacked flow on mobile (breakpoint: 768px).
- **Workspace Splitting**: Administrative layouts rely on an asymmetric 260px fixed collapsible navigation sidebar paired with a fluid central document workspace and an optional 360px contextual slide-over drawer for student placement details.
- **Compact Spacing Rhythm**: Vertical gaps favor information density over expansive empty voids. Table rows maintain a compact 40px to 48px height, while form card padding utilizes `space-lg` (1.25rem / 20px) to keep data inputs within a single viewport scroll wherever possible.

## Elevation & Depth

Visual depth is built through **tonal layering** and **crisp hairline borders**, completely eschewing prominent drop shadows, glowing neons, and blurred glass layers.

- **Hairline Framing**: Primary structural distinction is achieved via `1px solid #E6E2D9` borders applied across all surface containers, table header separators, input fields, and action toolbars.
- **Tonal Contrast**: The canvas background `#F7F5EF` provides natural separation under `#FFFFFF` surfaces. Nested elements (such as filter trays or highlighted rows) use the pale sage tone `#EDF2EA` rather than dark drop shadows.
- **Subtle Surface Elevation**:
  - **Flat State (Cards, Tables, Panels)**: No shadow (`box-shadow: none`), framed solely by 1px solid `#E6E2D9`.
  - **Elevated Interactive State (Dropdowns, Popovers, Active Hover Cards)**: Soft archival shadow: `0 2px 8px -2px rgba(52, 56, 50, 0.05), 0 1px 3px -1px rgba(52, 56, 50, 0.04)` combined with `1px solid #E6E2D9`.
  - **Modal / Placement Drawer Overlay**: Focused directional elevation: `0 8px 24px -4px rgba(52, 56, 50, 0.08), 0 2px 6px -2px rgba(52, 56, 50, 0.04)`. Backdrop scrim uses `#343832` tinted to 30% opacity with no background blur.

## Shapes

The shape system employs disciplined, soft geometric radii to maintain an orderly binder/ledger feel.

- **Standard Base Radii**: 8px (`0.5rem`) for buttons, text inputs, status badges, toolbars, and nested list items.
- **Container Radii**: 12px (`0.75rem`) for main document cards, placement detail sheets, data table shells, and dialog modals.
- **Pills**: Badges and counter chips utilize fully rounded ends (`rounded-full` or 9999px) strictly for status metadata chips to contrast cleanly against the rectangular geometry of data grids.
- **No Sharp Angles**: 0px corners are avoided to keep the interface approachable; conversely, extreme bulbous curves (>12px on structural cards) are forbidden to protect the academic document character.

## Components

### Buttons
- **Primary**: Solid Forest Green background (`#244A3B`), white text (`#FFFFFF`), 8px border-radius, 10px vertical by 16px horizontal padding. Hover state subtly transitions to `#1B382D`. Active state: `#142921`. Focus-visible ring: 2px solid `#78927A` offset by 2px ivory.
- **Secondary**: White background (`#FFFFFF`), Charcoal text (`#343832`), 1px solid border (`#E6E2D9`), 8px radius. Hover state transitions to Pale Sage fill (`#EDF2EA`) with a border shift to `#78927A`.
- **Tertiary / Ghost**: Transparent fill, Charcoal text (`#343832`), 8px radius. Hover state: Pale Sage (`#EDF2EA`).
- **Destructive**: Pale Error fill (`#F8E5E2`), Error text (`#982C24`), 1px solid border (`#E6C8C4`). Hover: `#F0D4CF`.

### Status Badges & Chips
- Compact pills (height: 22px to 26px), inline-flex alignment, horizontal padding 8px, font-size 11px, weight 600, uppercase with slight letter spacing (+0.04em).
- **Approved / Placed**: Background `#E4EFE3`, text `#205737`, 1px solid border `#D2E4D0`.
- **Pending / Shortlisted**: Background `#FFF0D9`, text `#8F5B16`, 1px solid border `#F4DEC0`.
- **Rejected / Withdrawn**: Background `#F8E5E2`, text `#982C24`, 1px solid border `#ECC5BF`.
- **Draft / Inactive**: Background `#EDF2EA`, text `#777A73`, 1px solid border `#E6E2D9`.

### Data Tables & Registries
- Outer container wrapped in pure white (`#FFFFFF`) with 12px corner radii and 1px solid `#E6E2D9` border.
- **Header Row**: Background `#F7F5EF`, 38px height, 1px solid bottom divider (`#E6E2D9`). Header labels use `label-sm` (11px, 600 weight, uppercase, `#777A73`).
- **Body Rows**: Pure white background, alternating zebra striping is omitted in favor of clean 1px hairline dividers (`#E6E2D9`). Row hover transitions to `#EDF2EA` at 50% opacity. Height fixed at 44px for compact, dense data scannability.
- **Selected Row**: Subtle Pale Sage fill (`#EDF2EA`) with a 2px left border accent in `#244A3B`.

### Form Inputs & Select Fields
- Height: 38px. Background: `#FFFFFF`. Border: 1px solid `#E6E2D9`. Radius: 8px. Text: `#343832`. Placeholder: `#777A73`.
- Focus state: Border transitions to `#244A3B` with a soft 1px ambient glow (`rgba(36, 74, 59, 0.15)`). Error state: Border `#982C24`.
- Labels are positioned strictly above inputs using `label-md` in `#343832`, accompanied by a subdued requirement indicator.

### Selection Controls (Checkboxes & Radios)
- Checkboxes: 16px by 16px, 4px border-radius, 1px solid border `#777A73`, background `#FFFFFF`. When checked: `#244A3B` background with a crisp white checkmark icon.
- Radios: 16px by 16px, circular, 1px solid `#777A73`. When selected: `#244A3B` ring containing a 6px centered white dot.

### Cards & Document Summaries
- Background `#FFFFFF`, 12px border-radius, 1px solid `#E6E2D9`, zero drop-shadow.
- Card headers feature an integrated 1px bottom border separating actions and titles from student academic transcripts, placement metrics, or company dossiers.
- Card padding remains consistent at 20px (`space-lg`).

### Outline Iconography
- Icons adhere to a strict 1.5px stroke weight, 18px or 20px bounding box, using the Phosphor or Feather outline aesthetic.
- Icon color defaults to `#777A73` in passive states and `#244A3B` when active or hovered.