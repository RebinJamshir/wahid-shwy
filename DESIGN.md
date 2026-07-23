---
name: Vibrant Cafeteria
colors:
  surface: '#fff7ff'
  surface-dim: '#e0d7e1'
  surface-bright: '#fff7ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf1fb'
  surface-container: '#f4ebf5'
  surface-container-high: '#eee5ef'
  surface-container-highest: '#e8e0ea'
  on-surface: '#1e1a21'
  on-surface-variant: '#4b4451'
  inverse-surface: '#332f36'
  inverse-on-surface: '#f7eef8'
  outline: '#7d7483'
  outline-variant: '#cec3d3'
  surface-tint: '#7943b0'
  primary: '#430078'
  on-primary: '#ffffff'
  primary-container: '#5b2392'
  on-primary-container: '#cb99ff'
  inverse-primary: '#dcb8ff'
  secondary: '#745b00'
  on-secondary: '#ffffff'
  secondary-container: '#fdcc10'
  on-secondary-container: '#6e5700'
  tertiary: '#422600'
  on-tertiary: '#ffffff'
  tertiary-container: '#603a00'
  on-tertiary-container: '#dca563'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#efdbff'
  primary-fixed-dim: '#dcb8ff'
  on-primary-fixed: '#2b0052'
  on-primary-fixed-variant: '#602897'
  secondary-fixed: '#ffe08a'
  secondary-fixed-dim: '#f1c100'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574400'
  tertiary-fixed: '#ffddb9'
  tertiary-fixed-dim: '#f5bc78'
  on-tertiary-fixed: '#2b1700'
  on-tertiary-fixed-variant: '#653e03'
  background: '#fff7ff'
  on-background: '#1e1a21'
  surface-variant: '#e8e0ea'
  surface-dark: '#222222'
  surface-light: '#F6F6F6'
  pure-white: '#FFFFFF'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
  headline-md:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  title-lg:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 20px
  button-text:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin: 40px
  section-gap: 80px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system is built to evoke the high-energy, sensory experience of a modern cafeteria. It prioritizes appetite appeal and social energy over corporate structure. The style is **High-Contrast & Bold**, utilizing a saturated palette and heavy typography to create a sense of urgency and excitement around the food.

The aesthetic is "Food-First," meaning every layout decision serves to frame and elevate professional photography. We avoid thin lines and fragile layouts in favor of chunky, tactile elements that feel satisfying to interact with. The emotional response should be one of immediate hunger and approachable friendliness.

## Colors
The palette is dominated by the tension between **Deep Purple** and **Vibrant Yellow**.
- **Deep Purple (#5B2392):** Used for structural grounding. It serves as the primary container for navigation, footers, and hero text to provide a sophisticated, premium backdrop.
- **Vibrant Yellow (#F7C600):** This is the high-energy "action" color. It is reserved for Call to Action (CTA) buttons, interactive highlights, and critical icons.
- **Neutrals:** We use a "Soft White" strategy, utilizing `#FFFFFF` for main content cards to ensure food photography pops, and `#F6F6F6` for section backgrounds to provide subtle depth without losing the clean, airy feel.

## Typography
We use a combination of **Montserrat** (as a proxy for the bold, geometric energy of Poppins) and **Inter** for maximum legibility.
- **Headlines:** Use Montserrat ExtraBold. These should be large and impactful, often appearing in Purple over light backgrounds or White over Purple backgrounds.
- **Body:** Use Inter. It provides a clean, neutral balance to the aggressive headlines, ensuring that ingredient lists and descriptions are easy to scan.
- **Hierarchy:** Display sizes are intended for Hero sections. Headlines are for section starts. Labels should be used for categories or "snack tags" above titles.

## Layout & Spacing
This design system uses a **Fixed Grid** for desktop to maintain the "editorial food magazine" feel.
- **Grid:** A 12-column system with a maximum width of 1280px.
- **Margins/Gutters:** Generous 40px external margins ensure the content feels framed rather than cramped.
- **Rhythm:** We follow an 8px base unit. Section spacing is aggressive (80px+) to allow the food photography room to "breathe."
- **Desktop Strategy:** Content should never feel "stretched." Use centered containers for text-heavy sections and wide-bleed layouts only for hero photography.

## Elevation & Depth
The design system employs **Ambient Shadows** to create a tactile, "physical" presence for menu items.
- **Shadow Profile:** Use very soft, diffused shadows (0px 10px 30px rgba(0,0,0,0.08)). Shadows should never feel "muddy" or black; they should feel like natural sunlight hitting a plate on a table.
- **Tonal Layering:** Depth is primarily created through color blocking. Dark purple sections act as the "base" layer, with white cards "floating" slightly above them using the soft shadow profile.
- **Interactive Depth:** On hover, cards should scale slightly (1.02x) and the shadow should become slightly more diffused to simulate the element lifting off the page.

## Shapes
We embrace a **Rounded** aesthetic to mirror the organic nature of food and the friendly brand voice.
- **Corner Radius:** All main containers and cards use a consistent 16px (1rem) radius.
- **Buttons:** Use 16px or fully pill-shaped corners to ensure they feel "soft" and clickable.
- **Consistency:** Avoid mixing sharp corners with rounded ones. Even the "simple line icons" should have rounded caps and joins to match the UI language.

## Components
- **Buttons:** Primary buttons are Vibrant Yellow with Deep Purple text. They are large (min-height 56px) with Montserrat Bold type. No borders; just flat color with a soft shadow.
- **Food Cards:** The hero of the UI. White background, 16px rounded corners, soft shadow. The image should take up the top 70% of the card. Text is kept to a minimum (Title, Price, and a small "Add" icon).
- **Chips/Tags:** Used for dietary labels (e.g., "Spicy," "Vegan"). These use low-saturation versions of the brand colors or simple outlines to not compete with the primary CTA.
- **Input Fields:** Large, 16px rounded corners with a 2px Deep Purple border when focused. Backgrounds should be the "Surface Light" neutral.
- **Navigation:** Deep Purple background with White text. Use the Vibrant Yellow for the active state indicator or a "Order Now" button in the corner.
- **Lists:** Clean, horizontal layouts for checkout or "Quick Add" sidebars, utilizing generous 16px padding between items.
