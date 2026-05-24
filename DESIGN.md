# Design System: La Azteca (Blue & White Palette)

This is the Google Stitch design system manifest for **La Azteca — Joyería Fina .925**. It defines the visual styles, color tokens, and typography system to ensure consistency across the application.

## Typography

- **Display/Headers:** `Space Grotesk`, sans-serif (Bold, clean, geometric)
- **Body Text:** `Inter`, sans-serif (High legibility, modern, elegant)
- **Monospace/Numbers:** `JetBrains Mono`, monospace (For prices, codes, and weight details)

## Color Palette (Tokens)

All components should strictly use the following color variables:

| Token Name | Hex Value | HSL | Semantic Description |
| :--- | :--- | :--- | :--- |
| `color-base` | `#080F21` | `hsl(222, 60%, 8%)` | Deep midnight blue background |
| `color-surface` | `#0F1A36` | `hsl(223, 56%, 14%)` | Dark navy surface for cards, navigation, and modals |
| `color-surface-light`| `#1A2B54` | `hsl(222, 53%, 22%)` | Slate blue for interactive hover states or borders |
| `color-accent-blue` | `#38BDF8` | `hsl(199, 89%, 60%)` | Icy sky blue (Primary branding accent, glows, and badges) |
| `color-accent-dark` | `#0284C7` | `hsl(201, 96%, 39%)` | Darker blue accent for solid states and borders |
| `color-cobalt` | `#2563EB` | `hsl(221, 83%, 53%)` | Vibrant cobalt blue (Secondary highlights, links) |
| `color-white` | `#F8FAFC` | `hsl(210, 120%, 98%)` | Crisp white for headings and primary readable text |
| `color-muted-blue` | `#94A3B8` | `hsl(215, 16%, 65%)` | Muted ice/slate blue for description text, subtitles |

## Border and Shadows

- **Border Radius:**
  - Standard cards and sections: `16px` (`rounded-2xl`)
  - Buttons and inputs: `12px` (`rounded-xl`)
  - Small badges: `8px` (`rounded-lg`)
- **Shadows:**
  - Standard shadow: `0 10px 30px -10px rgba(8, 15, 33, 0.5)`
  - Glow effect: `0 0 30px rgba(56, 189, 248, 0.15)` for cards on hover.
  - Text glow: `text-shadow: 0 0 20px rgba(56, 189, 248, 0.3)`

## Component Conventions

1. **Buttons:**
   - **Primary:** Gradient from `color-accent-blue` to `color-cobalt`, text color `color-base` (dark) for high contrast and modern aesthetics.
   - **Secondary:** Transparent with `color-surface-light` background, border in `rgba(56, 189, 248, 0.1)`, text color `color-white`.
2. **Glassmorphism:**
   - Use `rgba(15, 26, 54, 0.7)` as background with `backdrop-filter: blur(20px)` and border in `rgba(56, 189, 248, 0.1)`.
