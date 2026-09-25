# SpendWise Dashboard Shell

SpendWise is a responsive personal finance dashboard shell built for the Week 4 CSS Grid and Flexbox assignment. It is a visual foundation only, so the figures and transactions are realistic static content rather than connected data.

## What is included

- `index.html` contains the accessible dashboard structure: navigation sidebar, header, summary metrics, six spending category cards, and a recent activity list.
- `style.css` contains the complete visual system, including the responsive layout, CSS custom properties, card interactions, and optional dark theme.
- `about.md` contains the assignment brief and requirements.

## Layout choices

The page uses CSS Grid for the app shell, summary metrics, and category card collection. Flexbox handles the sidebar navigation, header actions, card internals, transaction rows, and small alignment details. No absolute positioning is used for the page layout.

The category cards use a compact information hierarchy: a color-coded category mark, transaction context, total spend, percentage of monthly spending, and a small progress bar. Hover and keyboard focus states move cards upward by 3px and add a shadow within 180ms.

## Theme and responsiveness

All primary colors are declared as custom properties in `:root`, including brand, accent, surface, background, primary text, and secondary text colors. A `prefers-color-scheme: dark` media query overrides those variables for a dark theme without duplicating the component styles.

At widths below 768px, the sidebar becomes a horizontal navigation strip and all dashboard content collapses into a single column. The layout can be checked in browser DevTools with a mobile device preset.

## How to view

Open `index.html` directly in a browser. An internet connection is used only for the Google Fonts import; the page structure and styling remain local.
