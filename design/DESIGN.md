# Design System Inspired by Skillbox

## 1. Visual Theme & Atmosphere

Skillbox embodies a vibrant, youth-forward educational platform with a modern, energetic personality. The design system centers on a bold periwinkle-to-violet primary axis paired with warm accent tones, creating an inviting and motivational digital environment. The visual language emphasizes approachability and growth, using generous whitespace, playful emoji-like iconography, and smooth, rounded component edges. The system balances professional credibility with friendly accessibility, making complex educational content feel attainable and exciting for learners of all ages. Gradient-influenced color transitions and soft shadows create depth without overwhelming the interface.

**Key Characteristics**
- Bold, saturated primary blues and purples as motivational anchors
- Warm orange and lime accents for secondary calls-to-action and highlights
- Soft neutral grays and whites for content-heavy areas and breathing room
- Rounded, pill-shaped buttons and cards that feel welcoming and modern
- Typography emphasizing clarity at multiple scales using Graphik font family
- Playful use of emoji and illustrated character testimonials as human connection points
- Bright lime green (`#B1FFAB`) used sparingly for success and positive affordance states

## 2. Color Palette & Roles

### Primary
- **Primary Action Blue** (`#3D3BFF`): Main call-to-action buttons, links, and interactive focus states. Used prominently in hero sections and critical conversion paths.
- **Primary Dark Purple** (`#4947FF`): Slightly lighter variant of primary blue for hover states and secondary prominence.

### Accent Colors
- **Warm Orange** (`#F59300`): Secondary highlights, promotional badges, and attention-drawing design elements.
- **Lavender Secondary** (`#A449EA`): Tertiary accent for category tags, complementary visual interest, and non-critical interactive states.
- **Light Purple** (`#BC8EF2`): Softer purple variant for backgrounds, disabled states, and supporting visual hierarchies.

### Interactive
- **Success Green** (`#3DB83D`): Success messages, completed course indicators, positive confirmations.
- **Error Red** (`#D5401F`): Error states, warnings, and destructive actions.
- **Warning Yellow** (`#FFF93D`): Alert states and cautionary information (alternate variant `#FFF947`).

### Neutral Scale
- **Pure Black** (`#000000`): Primary text, deep shadows, and highest contrast contexts.
- **Dark Gray** (`#333333`): Secondary headings and slightly reduced-emphasis text.
- **Medium Gray** (`#666666`): Tertiary text, disabled states, and subtle informational copy.
- **Light Gray** (`#B8B8B8`): Borders, dividers, and reduced-contrast interactive elements.
- **Very Light Gray** (`#E0E0E0`): Fine borders and subtle separation lines.
- **Off-White** (`#EBEBEB`): Neutral backgrounds and card separations.

### Surface & Borders
- **Pure White** (`#FFFFFF`): Primary card and surface backgrounds, main content areas.
- **Off-White Background** (`#F5F5F5`): Subtle background tint for secondary content areas.
- **Light Card Gray** (`#EBEBEB`): Default card and container backgrounds (used as component fills).

### Semantic / Status
- **Light Cyan** (`#DCF4FE`): Informational backgrounds, help text containers, and status notifications.
- **Bright Lime** (`#B1FFAB`): Success state backgrounds and positive affirmation highlights.

## 3. Typography Rules

### Font Family
**Primary:** Graphik, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif
**Secondary (Code):** 'Courier New', monospace

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|----------------|-------|
| **Display / Hero** | Graphik | 60px | 500 | 60px | Normal | Main page headings, maximum visual impact |
| **Heading 1** | Graphik | 24px | 500 | 28px | Normal | Section titles and major content divisions |
| **Heading 2** | Graphik | 20px | 500 | 24px | Normal | Subsection headings and category labels |
| **Body / Paragraph** | Graphik | 14px | 500 | 18px | Normal | Primary reading content, form labels |
| **Body Large** | Graphik | 18px | 400 | 26px | Normal | Featured text, testimonial copy, callout descriptions |
| **Button** | Graphik | 16px | 400 | 16px | Normal | Interactive element labels |
| **Caption** | Graphik | 12px | 400 | 16px | Normal | Metadata, timestamps, secondary information |
| **Code** | Monospace | 13.33px | 400 | Normal | Normal | Code blocks and technical snippets |

### Principles
- Use weight 500 for headings to signal hierarchy and emphasis without excessive boldness
- Weight 400 reserves itself for body and UI text, creating distinct visual separation
- Line heights exceed font size by 1.2x–1.8x multiplier for improved readability
- 14px body text serves as baseline; scale up for featured content, down for captions
- Maintain 60px line height for 60px display text to preserve open, spacious feel
- Avoid mixing typefaces; rely on Graphik weight and size variation for contrast
- Character spacing remains normal (0) across all scales for authentic typography feel

## 4. Component Stylings

### Buttons

**Primary Button**
- Background: `#3D3BFF`
- Text Color: `#FFFFFF`
- Padding: `9px 15px`
- Border Radius: `30px`
- Font Size: `16px`
- Font Weight: `400`
- Line Height: `16px`
- Height: `40px`
- Border: `1px solid #3D3BFF`
- Hover State: Background `#4947FF`, maintain border
- Active State: Slightly increased shadow depth
- Focus State: `box-shadow: 0 0 0 3px rgba(61, 59, 255, 0.2)`

**Secondary Button**
- Background: `#EBEBEB`
- Text Color: `#000000`
- Padding: `9px 15px`
- Border Radius: `30px`
- Font Size: `16px`
- Font Weight: `400`
- Line Height: `16px`
- Height: `40px`
- Border: `none`
- Hover State: Background `#E0E0E0`
- Active State: Background `#D5D5D5`

**Ghost Button (Outlined)**
- Background: `transparent`
- Text Color: `#FFFFFF`
- Padding: `9px 15px`
- Border Radius: `30px`
- Font Size: `16px`
- Font Weight: `400`
- Line Height: `16px`
- Height: `40px`
- Border: `1px solid #FFFFFF`
- Hover State: Background `rgba(255, 255, 255, 0.1)`
- Active State: Background `rgba(255, 255, 255, 0.2)`

**Success Button**
- Background: `#3DB83D`
- Text Color: `#FFFFFF`
- Padding: `9px 15px`
- Border Radius: `30px`
- Font Size: `16px`
- Font Weight: `400`
- Line Height: `16px`
- Height: `40px`
- Hover State: Darken by 8% or apply `#2A9A2A`

**Accent Button (Orange)**
- Background: `#F59300`
- Text Color: `#FFFFFF`
- Padding: `9px 15px`
- Border Radius: `30px`
- Font Size: `16px`
- Font Weight: `400`
- Line Height: `16px`
- Height: `40px`
- Hover State: Darken to `#D87A00`

### Cards & Containers

**Standard Card**
- Background: `#FFFFFF`
- Border Radius: `12px`
- Padding: `20px`
- Border: `1px solid #E0E0E0`
- Box Shadow: `0 2px 8px rgba(0, 0, 0, 0.08)`
- Transition on hover: `box-shadow: 0 4px 16px rgba(0, 0, 0, 0.12)`

**Icon Card (Square)**
- Background: `#F5F5F5`
- Border Radius: `12px`
- Width: `68px`
- Height: `68px`
- Padding: `8px`
- Border: `none`
- Display: flex, center aligned, for icon content

**Category Badge Card**
- Background: `#FFFFFF`
- Border Radius: `16px`
- Padding: `12px 24px`
- Font Size: `14px`
- Font Weight: `500`
- Text Color: `#000000`
- Border: `1px solid #E0E0E0`
- Icon Color: Varies by category (Purple `#A449EA`, Green `#B1FFAB`, Orange `#F59300`, etc.)
- Hover State: Background `#F5F5F5`, shadow elevation increases

**Testimonial Card**
- Background: Gradient overlay or solid `rgba(0, 0, 0, 0.7)` or category color with opacity
- Border Radius: `12px`
- Padding: `16px`
- Text Color: `#FFFFFF`
- Image Content: Full-bleed background image
- Caption Font Size: `14px`
- Caption Font Weight: `500`

### Inputs & Forms

**Text Input (Default)**
- Background: `#F5F5F5`
- Text Color: `#000000`
- Font Size: `16px`
- Font Weight: `400`
- Padding: `23px 18px 10px 18px`
- Border Radius: `10px`
- Border: `1px solid #E0E0E0`
- Height: `56px`
- Line Height: `20px`
- Placeholder Color: `#B8B8B8`
- Focus State: Border color `#3D3BFF`, background `#FFFFFF`, shadow `0 0 0 3px rgba(61, 59, 255, 0.1)`
- Error State: Border `1px solid #D5401F`, background tint with light red
- Success State: Border `1px solid #3DB83D`

**Textarea**
- Inherits Text Input styles
- Min Height: `120px`
- Padding: `16px`
- Resize: vertical only

**Dropdown / Select**
- Background: `#F5F5F5`
- Text Color: `#000000`
- Border Radius: `10px`
- Padding: `16px 18px`
- Border: `1px solid #E0E0E0`
- Font Size: `16px`
- Focus State: Border `#3D3BFF`, background `#FFFFFF`
- Open State: Box shadow elevation to `0 4px 16px rgba(0, 0, 0, 0.15)`

**Checkbox / Radio**
- Size: `20px × 20px`
- Border Radius: `4px` (checkbox), `50%` (radio)
- Border: `2px solid #E0E0E0`
- Checked State: Background `#3D3BFF`, border `#3D3BFF`, checkmark `#FFFFFF`
- Focus State: Outer ring `3px rgba(61, 59, 255, 0.2)`

### Navigation

**Top Navigation Bar**
- Background: `#4A7FFF` (vibrant blue)
- Height: `64px`
- Padding: `0 24px`
- Text Color: `#FFFFFF`
- Font Size: `16px`
- Font Weight: `400`
- Link Hover: Text color `#DCF4FE` or underline `#FFFFFF`
- Logo Font Size: `18px`
- Logo Font Weight: `500`

**Navigation Link**
- Text Color: `#FFFFFF`
- Font Size: `14px`
- Padding: `8px 12px`
- Hover State: Background `rgba(255, 255, 255, 0.15)`, border-bottom `2px solid #FFFFFF`
- Active State: Border-bottom `2px solid #B1FFAB`, text `#FFFFFF`

**Breadcrumb Navigation**
- Separator Color: `#B8B8B8`
- Current Item Color: `#000000`
- Previous Item Color: `#666666`
- Font Size: `14px`
- Font Weight: `400`

### Badges & Chips

**Category Badge (Standard)**
- Background: `#FFFFFF`
- Border Radius: `16px`
- Padding: `6px 16px`
- Font Size: `14px`
- Font Weight: `500`
- Text Color: `#000000`
- Border: `1px solid #E0E0E0`
- Icon Color: Category-specific (`#A449EA`, `#F59300`, `#B1FFAB`, etc.)

**Status Badge (Success)**
- Background: `#B1FFAB`
- Border Radius: `16px`
- Padding: `4px 12px`
- Font Size: `12px`
- Font Weight: `500`
- Text Color: `#000000`
- Border: `none`

**Status Badge (Error)**
- Background: `#FFE5DB`
- Border Radius: `16px`
- Padding: `4px 12px`
- Font Size: `12px`
- Font Weight: `500`
- Text Color: `#D5401F`
- Border: `none`

**Status Badge (Warning)**
- Background: `#FFF947`
- Border Radius: `16px`
- Padding: `4px 12px`
- Font Size: `12px`
- Font Weight: `500`
- Text Color: `#000000`
- Border: `none`

### Modals & Overlays

**Modal Container**
- Background: `#FFFFFF`
- Border Radius: `12px`
- Padding: `32px`
- Box Shadow: `0 8px 32px rgba(0, 0, 0, 0.15)`
- Max Width: `520px`
- Overlay (Background): `rgba(0, 0, 0, 0.5)`

**Modal Header**
- Font Size: `24px`
- Font Weight: `500`
- Margin Bottom: `16px`
- Color: `#000000`

**Modal Close Button**
- Width: `32px`
- Height: `32px`
- Border Radius: `50%`
- Background: `#F5F5F5`
- Icon Color: `#666666`
- Hover State: Background `#E0E0E0`, icon color `#000000`

### Promotional Banner

**Top Promotional Bar**
- Background: Linear gradient from `#B1FFAB` to `#DCF4FE`
- Height: `52px`
- Padding: `12px 24px`
- Font Size: `16px`
- Font Weight: `500`
- Text Color: `#000000`
- Dismiss Button: Background `transparent`, text `#000000`, border `1px solid #000000`

## 5. Layout Principles

### Spacing System

Base unit: **4px**

Spacing scale:
- **4px**: Minimal internal spacing within tight components, micro-interactions
- **8px**: Button-to-button gaps, small component padding
- **12px**: Light padding on badges and small controls
- **16px**: Standard padding for inputs, card headers, moderate spacers
- **20px**: Card and container padding, section dividers
- **24px**: Section margins, category grid gaps, navigation spacing
- **28px**: Medium-large component spacing
- **32px**: Large grid gaps, content area horizontal padding
- **36px**: Extra-large section padding
- **40px**: Maximum container horizontal breathing room
- **48px**: Inter-section spacing, hero-to-content transitions
- **52px**: Maximum vertical section separation

**Usage Context:**
- Micro-interactions and nested components: `4px–8px`
- Form fields and controls: `12px–16px`
- Cards and blocks: `16px–20px`
- Section-to-section: `24px–48px`
- Page margins: `32px–40px` (responsive down to `16px` on mobile)

### Grid & Container

**Max Width:** `1440px` (full-width desktop layouts)
**Content Max Width:** `1200px` (restricted-width content sections)
**Column Strategy:** 12-column grid system with flexible gutters

**Container Patterns:**
- Hero Section: Full viewport width, `1440px` container, vertical padding `80px–120px`
- Feature Grid: 3–5 columns on desktop, adjust to 2–3 on tablet, 1 on mobile
- Card Grid: Typically 3 columns with `24px` gap on desktop
- Sidebar Layout: Main content 70%, sidebar 30% with `32px` gap

**Section Alignment:**
- Centered sections use max-width `1200px` with `auto` margins
- Full-bleed backgrounds extend to viewport edges
- Content padding inside containers: `32px–40px` horizontal, `24px–32px` vertical

### Whitespace Philosophy

Whitespace is treated as a design element that creates visual hierarchy and improves cognitive load. Generous spacing around key interactive elements (buttons, CTAs) increases affordance and reduces decision friction. Vertical rhythm is maintained through consistent multiples of the base `4px` unit, creating implicit visual alignment. Breathing room between sections (48px–80px) prevents overwhelming users while section-internal spacing (16px–24px) creates logical groupings. The design favors open layouts with strategic density increases around conversion paths.

### Border Radius Scale

- **4px**: Minimal rounding on secondary containers, code blocks
- **8px**: Subtle rounding on form validation states, micro-controls
- **10px**: Input fields and select dropdowns
- **12px**: Primary card containers, image containers, testimonial cards
- **16px**: Badge and chip components, category icons
- **30px**: Pill-shaped buttons, large interactive elements
- **50%**: Circular buttons, avatars, full-circle icons

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| **Base (L0)** | No shadow, flat | Default card backgrounds, section separations |
| **L1 (Raised)** | `0 2px 8px rgba(0, 0, 0, 0.08)` | Standard cards, contained components |
| **L2 (Hover)** | `0 4px 16px rgba(0, 0, 0, 0.12)` | Card hover states, light modals, tooltips |
| **L3 (Focus/Modal)** | `0 8px 32px rgba(0, 0, 0, 0.15)` | Primary modals, dropdown menus, overlay cards |
| **L4 (Maximum)** | `0 12px 48px rgba(0, 0, 0, 0.2)` | Stacked modals, maximum visual separation, floating action buttons |

**Shadow Philosophy:**

Shadows are used sparingly and subtly to enhance depth without creating visual noise. The system employs soft, diffuse shadows using low-opacity black (`rgba(0, 0, 0, 0.08–0.2)`) that increase in blur radius and spread as elevation increases. All shadows use two-layer composites (small precise shadow + large diffuse shadow) to simulate natural light. Flat sections (backgrounds, hero areas) use no shadows to maintain visual minimalism. Interactive hover states increase shadow elevation by one level to signal responsiveness. Modals and overlays employ L3–L4 shadows to clearly separate them from background content.

## 7. Do's and Don'ts

### Do

- **Use the primary blue (`#3D3BFF`) for all critical CTAs** – logo, main "Select Course" buttons, primary navigation links. It has highest recognition and trust association.
- **Apply generous padding (`20px–32px`) around content cards** to create visual breathing room and improve scannability.
- **Stick to the Graphik font family exclusively**; avoid introducing new typefaces that dilute brand cohesion.
- **Organize course cards in 3-column grids on desktop** with consistent `24px` gaps; collapse to 2 columns on tablet, 1 on mobile.
- **Use lime green (`#B1FFAB`) sparingly for success states and positive completion indicators** – it has high visual impact and should reserve emphasis.
- **Maintain 1:1 aspect ratios for category badge icons** and center them within `68px × 68px` square containers.
- **Leverage emoji-like iconography and testimonial imagery** to humanize educational content and reduce perceived complexity.
- **Apply rounded pill shapes (`border-radius: 30px`) consistently to all CTAs and secondary navigation items** for a cohesive, friendly feel.
- **Use a maximum of three accent colors per page section** (primary + one secondary + one tertiary) to avoid visual chaos.

### Don't

- **Do not use black (`#000000`) text on dark backgrounds** – maintain minimum contrast ratio of 4.5:1 (WCAG AA) or use light gray (`#EBEBEB`) or white.
- **Avoid mixing border radius styles** – commit to either pill buttons or slightly rounded (12px) for consistency; don't mix both approaches on the same surface.
- **Do not reduce padding below `8px` on interactive elements** – maintain touch-friendly sizes (minimum `40px` height for buttons).
- **Avoid shadows stronger than L2 on cards in grid layouts** – it creates visual fluttering; reserve L3+ for modals only.
- **Don't use more than two font weights** (400 regular, 500 semibold); avoid 600, 700, or 900 weights that introduce inconsistency.
- **Do not place promotional banners below the fold** – keep them at top of page (L1 above navigation) to maximize visibility and urgency.
- **Avoid cluttering category grids with more than 12 visible items** – implement pagination or lazy-loading to maintain cognitive load.
- **Don't apply category-specific accent colors (`#A449EA`, `#F59300`) to non-badge UI elements** – reserve them for category chips and icon highlights only.
- **Avoid using disabled states without clear affordance** – always provide explanatory tooltip or text indicating why an element is disabled.

## 8. Responsive Behavior

### Breakpoints

| Breakpoint | Width | Device | Key Changes |
|------------|-------|--------|-------------|
| **Mobile** | 320px–479px | Phone | Single-column layouts, full-width containers, simplified navigation (hamburger menu), reduced padding to `12px–16px` |
| **Tablet (Small)** | 480px–767px | Small tablet | 2-column grids, side navigation drawer, padding `16px–20px`, modal width `90vw` |
| **Tablet (Large)** | 768px–1023px | Large tablet | 3-column grids possible, side navigation still acceptable, padding `20px–24px`, improved spacing |
| **Desktop** | 1024px–1439px | Small–medium desktop | 3–4 column grids, top navigation, full lateral navigation options, padding `24px–32px`, max-width content containers |
| **Large Desktop** | 1440px+ | Large monitor | 4–5 column grids possible, spacious horizontal padding `32px–40px`, max-width fixed to `1440px` |

### Touch Targets

- **Minimum touch target size:** `44px × 44px` (iOS guideline) or `48px × 48px` (Android guideline)
- **Button height:** `40px` minimum; `48px` recommended for critical CTAs
- **Form input height:** `56px` (accommodates label + input)
- **Link/text clickable area:** Padding of at least `8px` around text
- **Icon-only buttons:** `40px × 40px` minimum with `4px` internal padding
- **Spacing between touch targets:** Minimum `16px` to avoid accidental taps

### Collapsing Strategy

**Navigation (Mobile):**
- Top navigation collapses into hamburger menu (`☰`) at `<768px`
- Menu items stack vertically in a slide-out drawer
- Drawer background: `#FFFFFF` with `#000000` text
- Drawer width: `280px–320px`
- Dismiss via overlay tap or close button

**Grid Layouts (Responsive):**
- Desktop (1024px+): 3 columns, `24px` gap
- Tablet (768px–1023px): 2 columns, `20px` gap
- Mobile (<768px): 1 column, `16px` gap

**Modals & Forms (Mobile):**
- Modal max-width: `90vw` on mobile, `520px` on desktop
- Padding reduces to `24px` on mobile from `32px` desktop
- Header font size: `20px` mobile, `24px` desktop
- Input width: 100% of container on mobile, auto on desktop

**Images & Hero Sections:**
- Hero section height: `40vh` on mobile, `60vh` desktop
- Hero text size: `36px` (display) mobile, `60px` desktop
- Image aspect ratio: Maintain 16:9; crop content for mobile if necessary
- Background images: Use `background-size: cover` with media query adjustments

**Promotional Banners:**
- Stack horizontally on desktop with flex layout
- Stack vertically or collapse to icon-only on mobile (<480px)
- Font size reduces to `12px` on mobile from `16px` desktop
- Padding: `8px 12px` mobile, `12px 24px` desktop

## 9. Agent Prompt Guide

### Quick Color Reference

- **Primary CTA:** Primary Action Blue (`#3D3BFF`)
- **Secondary CTA:** Secondary Button (`#EBEBEB` background, `#000000` text)
- **Success Indicator:** Success Green (`#3DB83D`) or Bright Lime (`#B1FFAB`)
- **Error/Destructive:** Error Red (`#D5401F`)
- **Warning:** Warning Yellow (`#FFF93D`)
- **Background (Main):** Pure White (`#FFFFFF`)
- **Background (Secondary):** Off-White (`#F5F5F5`)
- **Heading Text:** Pure Black (`#000000`)
- **Body Text:** Pure Black (`#000000`) or Dark Gray (`#333333`)
- **Placeholder / Disabled Text:** Light Gray (`#B8B8B8`)
- **Divider / Border:** Very Light Gray (`#E0E0E0`)
- **Navigation:** Navigation Blue (`#4A7FFF`)
- **Accent (Tertiary):** Lavender Secondary (`#A449EA`) or Warm Orange (`#F59300`)

### Iteration Guide

1. **Start with the primary blue (`#3D3BFF`) as the hero color** for all conversion-critical UI: hero CTAs, logo background, active navigation states, form focus rings. This color has the highest trust and recognition in educational contexts.

2. **Apply consistent padding multiples of `16px` or `24px`** to all containers; never use non-standard spacing like `18px` or `22px`. This maintains a disciplined rhythm and simplifies responsive scaling.

3. **Use a 3-column card grid on desktop** (with `24px` gap), reducing to 2 columns on tablet and 1 column on mobile. Implement this via CSS Grid with `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))` for automatic responsiveness.

4. **Set all button border-radius to `30px`** for pill-shaped CTAs and secondary navigation; reserve `12px` for cards and `10px` for inputs. This distinction prevents ambiguity between button and container components.

5. **Maintain font weight discipline: 500 for headings, 400 for body text.** Do not introduce 600, 700, or lighter weights; the typographic hierarchy lives in size changes, not weight variation.

6. **Apply shadows only on hover or elevation states:** baseline cards use no shadow, hover states get L1 (`0 2px 8px rgba(0, 0, 0, 0.08)`), modals get L3+ (`0 8px 32px rgba(0, 0, 0, 0.15)`). Never apply shadows to full-viewport backgrounds or hero sections.

7. **Reserve lime green (`#B1FFAB`) and orange (`#F59300`) for non-critical UI:** category badges, success states, secondary highlights. Primary conversion paths must use primary blue to maintain cognitive consistency.

8. **Implement form inputs with a 23px top padding and 10px bottom padding** to accommodate floating labels; border-radius `10px`, background `#F5F5F5`, border `1px solid #E0E0E0`. Focus state shifts border to `#3D3BFF` and background to `#FFFFFF`.

9. **Set navigation bar background to vibrant blue (`#4A7FFF`)** with white text; use 16px font size and 8px–12px link padding. On mobile, collapse into a hamburger-triggered slide-out drawer (280px wide, white background, black text).

10. **Test all interactive elements for minimum 44px–48px touch target size;** this applies to buttons, form inputs, navigation links, and icon-only controls. Use padding (not just font size) to achieve these dimensions.

11. **Apply category-specific accent colors only to badge icons and category chips;** do not paint backgrounds or large UI surfaces with `#A449EA` or `#F59300`. These are highlight accents, not primary surface colors.

12. **Organize testimonial/user story cards as image overlays** with dark gradient or solid semi-transparent overlay (`rgba(0, 0, 0, 0.6–0.7)`) and white text. Border-radius `12px`, padding `16px`, font-size `14px` weight 500 for captions.

13. **Use the Graphik font family exclusively with system fallback:` Graphik, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`.` Never substitute with other sans-serifs; maintain brand typographic integrity.

14. **Responsive collapse strategy:** Hero display text `60px` desktop → `36px` mobile; heading-1 `24px` desktop → `18px` mobile; padding `32px–40px` desktop → `16px–20px` mobile; 3-column grids → 1-column grids. Use CSS media queries at `768px` and `1024px` breakpoints.

15. **For promotional banners at page top,** use lime-to-cyan gradient background (`#B1FFAB` to `#DCF4FE`), black text, padding `12px 24px`, height `52px`. Include a dismiss button with white background on click and full-width layout. Always place above navigation (z-index +1 above nav).