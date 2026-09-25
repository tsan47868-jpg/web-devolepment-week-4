## Rebuild the Tracker's Layout with Flexbox and Grid
# Description
Due Date: End of Week 4 (Friday, 17:00 EAT)

Submission Format:
Submit your GitHub repository link containing:

index.html
style.css
README.md explaining what you built and what each part does.


SpendWise Dashboard Shell (CSS Grid & Flexbox)

Build the SpendWise Dashboard Shell, which will serve as the foundation of your capstone project. This week focuses on creating a clean, responsive dashboard layout using modern CSS techniques. You are not required to add functionality—only build the visual structure using realistic static content.

1. Build the dashboard layout

Create the main dashboard structure containing:

A Sidebar/Navigation Menu

A Header

At least six category cards displaying realistic static financial information (e.g., Food, Transport, Rent, Entertainment, Savings, Utilities).

Your layout should resemble a modern dashboard interface.

2. Use CSS grid and flexbox

Structure your dashboard using modern layout techniques.

Your implementation should include:

CSS Grid for the overall page layout.

Flexbox for arranging content inside the header, sidebar items, and each dashboard card.

Do not use absolute positioning for the page layout.

3. Create a theme using CSS custom properties

Define your application's color palette using CSS variables on the :root selector.

At a minimum, include variables for:

Brand color

Accent color

Surface/background color

Primary text color

Secondary text color

Use these variables consistently throughout your stylesheet.

4. Make the dashboard responsive

Add a media query that adapts the layout for smaller screens.

Your responsive design should:

Collapse the layout into a single-column layout below 768px.

Be verified using the browser's DevTools Device Toolbar.

5. Add card Micro-interactions

Enhance the user experience by adding subtle hover and keyboard focus animations to the dashboard cards.

Your animation should:

Last 250ms or less

Use transform, box-shadow, or both

Apply to both hover and focus states

Stretch Goal: Dark theme

Implement a dark theme by overriding only your :root CSS variables inside a:

@media (prefers-color-scheme: dark)