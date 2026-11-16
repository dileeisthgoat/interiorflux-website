# InteriorFlux design system

The site has **two designs**: a light theme (called "a" in the code) and a dark theme (called "b"). A moon/sun button in the header switches between them. The choice is saved in the browser, and first-time visitors get whichever their device uses. Pictures of every page in both themes are in `previews/`.

## Colours

### Brand colours (same in both themes)
| Name | Hex | Used for |
|---|---|---|
| Teal | #0F4C4A | Main brand colour, buttons, headings (light), the dark band |
| Terracotta | #D9734E | Accent: logo dot, "Flux" in the logo, big circle in the hero |
| Sand | #F4EEE6 | Soft background tints, button on the teal band |

### Light theme
| Role | Value |
|---|---|
| Page background | #FFFFFF |
| Text | #222222 |
| Headings and links | #0F4C4A |
| Alternate section background | rgba(244,238,230,.55) |
| Card background | rgba(244,238,230,.62) (white at 66% on alternate sections) |
| Button | #0F4C4A with white text |
| Lines and borders | rgba(15,76,74,.18) |
| Header glass | rgba(255,255,255,.74) |

### Dark theme
| Role | Value |
|---|---|
| Page background | #0A0A0A |
| Text | #F4EEE6 |
| Headings | #FFFFFF |
| Alternate section background | rgba(255,255,255,.035) |
| Card background | rgba(255,255,255,.07) |
| Button | #0F4C4A with white text |
| Lines and borders | rgba(255,255,255,.16) |
| Header glass | rgba(10,10,10,.7) |

Both themes show two soft blurred colour glows behind the page: teal at the top left and terracotta at the bottom right (stronger in dark mode).

## Typography
- Font: **Poppins** from Google Fonts, weights 400 and 600, with Arial as the fallback
- Heading 1: 40px, semibold, line height 1.2
- Heading 2: 24px, semibold
- Heading 3 and body: 16px (headings semibold, body regular, line height 1.5)
- Small text and captions: 12px
- Big statistics: 40px semibold
- Text blocks are limited to about 65 characters wide

## Shape and spacing
- Page width: 1120px, with 24px side padding
- Section padding: 72px top and bottom
- Cards: 20px rounded corners, 28px padding
- Buttons: 14px rounded corners, 12px by 24px padding, 600 weight. The "ghost" button has a transparent background and an outline
- Small pills (quick links): fully rounded
- FAQ items: 16px corners
- Grids: 2 columns or 3 columns with a 24px gap. They become one column on small screens (under 860px for three columns, under 760px for two)
- The menu turns into a "Menu" button below 900px

## Look and effects
- **Frosted glass:** the header, cards, FAQ items, toggles and the input bar use a 18px background blur
- **Hero artwork:** a white "sample quote" card, a solid terracotta circle and a frosted glass panel that move at slightly different speeds as you scroll
- **Page headers:** a terracotta circle and a rounded teal square sit at the top right
- **Scrolling words:** the audience list (Homeowners, Remote owners and so on) rolls upward in a loop and pauses on hover
- **Reveal on scroll:** sections fade up and headings appear word by word
- **Counting numbers:** the three statistics count up when they come into view
- **Reading bar:** a thin line under the header fills as you scroll down the page
- **How it works:** the three steps stay in view while you scroll, with a progress line down the side and a matching sample panel that changes with each step
- **Theme switch:** colours fade over about half a second
- **Reduced motion:** all of the movement above is switched off for visitors who ask their device for less motion
- **Focus outlines:** 3px, for keyboard users

## Logo
Files are in `logo/`.
- The mark is a rounded teal square with a white "F" shape, overlapped by a frosted square and a terracotta circle
- Wordmark: "Interior" in regular weight and "**Flux**" in semibold terracotta (white in dark mode)
- Light version: teal mark, teal "Interior", terracotta "Flux"
- Dark version: white mark and text
- `favicon.svg` is the light mark, ready to use as the browser tab icon
- The full logo files use the Poppins font for the words. If Poppins is not installed on the computer that opens them, they fall back to Arial. Install Poppins, or open them in a browser online, to see them correctly

## Icons
Files are in `icons/`. Six simple outline icons (1.75px lines, rounded ends, teal): budget audit, quote verification, milestone tracking, CAPEX chart, contract shield and check circle.

## Photos
In `website/assets/`: `home.jpg` (apartment living area), `work.jpg` (office) and `report.jpg` (sample report page).

## Previews
In `previews/`. Each page in light and dark at desktop width (`light-home.png`, `dark-home.png` and so on). Pricing has three versions each, one per audience. `light-mobile-home.png` and `dark-mobile-home.png` show the phone layout. These were rendered with the Poppins font unavailable offline, so text may look slightly different from the live site.
