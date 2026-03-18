# HTML & CSS Tasks

This repository contains 10 HTML and CSS practice tasks focused on semantic markup, responsive layout, and interactive UI patterns built without JavaScript where possible. Here are the results: https://114-vaibhav.github.io/HTML_CSS/

## Setup

No build step is required.

1. Clone or download the repository.
2. Open the project folder in your editor.
3. Open any task folder and launch its `index.html` file in a web browser.

You can also use a local static server if you prefer, but it is optional.

## Dependencies

Most tasks use only plain HTML and CSS with no package dependencies.

External assets used in the current tasks:

- `2 CSS Card Component with Hover Effects` loads an external image by URL.
- `8 CSS Accordion Component` loads Font Awesome from a CDN for the plus icon.

If you are offline, those external resources may not load unless replaced with local assets.

## Task Overview

### 1. Static Webpage Layout

Objective: Create a single-page website using semantic HTML elements such as `header`, `nav`, `main`, and `footer`.

Key focus:

- Basic typography and color styling
- Clear spacing with margin and padding
- Responsive layout adjustments with media queries

Path: `1 Static Webpage Layout/`

### 2. CSS Card Component with Hover Effects

Objective: Build a card that includes an image, a title, and a description.

Key focus:

- Card structure and content grouping
- Borders, shadows, and padding
- Hover effects with smooth transitions

Path: `2 CSS Card Component with Hover Effects/`

### 3. Responsive Grid Layout

Objective: Create a grid layout that displays multiple items.

Key focus:

- CSS Grid with three desktop columns
- Single-column mobile layout
- Consistent spacing and alignment

Path: `3 Responsive Grid Layout/`

### 4. Pure CSS Dropdown Menu

Objective: Design a navigation bar with a dropdown submenu that appears on hover.

Key focus:

- Nested `ul` menus
- `:hover`-based submenu behavior
- Responsive navigation fallback for small screens

Path: `4 Pure CSS Dropdown Menu/`

### 5. Modal Popup Using `:target`

Objective: Build a modal popup that opens and closes without JavaScript.

Key focus:

- `:target`-based visibility control
- Centered modal with overlay backdrop
- CSS transitions for open and close states

Path: `5 Modal Popup Using the  target/`

### 6. Tabbed Content Interface

Objective: Create a tabbed interface where selecting a tab shows different content sections.

Key focus:

- Hidden radio inputs and labels as tabs
- `:checked`-based content switching
- Progressive content visibility with CSS only

Path: `6 Tabbed Content Interface/`

### 7. Pure CSS Carousel

Objective: Develop a carousel or slider that can auto-slide and also support manual selection.

Key focus:

- `@keyframes` animation for automatic sliding
- Hidden radio inputs for manual controls
- Responsive slider container

Path: `7 Pure CSS Carousel/`

### 8. CSS Accordion Component

Objective: Build an accordion where sections expand and collapse on click.

Key focus:

- Checkbox hack for open and closed states
- Transition-based expand and collapse animation
- Support for multiple open sections

Path: `8 CSS Accordion Component/`

### 9. Complex Responsive Layout with Grid and Flexbox

Objective: Design a more advanced webpage layout that combines CSS Grid and Flexbox.

Key focus:

- Grid for page-level structure
- Flexbox for inner layout alignment
- Overlapping elements with `position` and `z-index`
- Sticky layout behavior and responsive reordering

Path: `9 Complex Responsive Layout with Grid and Flexbox/`

### 10. Interactive Multi-Page Website Simulator with CSS Only

Objective: Simulate a multi-page website experience using HTML and CSS only.

Key focus:

- `:target`-driven section switching
- Page-like transitions and animations
- Responsive navigation across devices
- Combined use of Grid, Flexbox, and pseudo-classes

Path: `10 Interactive Multi-Page Website Simulator with CSS Only/`

## Repository Notes

- Each task is intentionally isolated in its own folder.
- Every task should contain its own HTML and CSS files for easy review.
- This repository is suitable for browser-based practice and does not require Node.js, npm, or any framework tooling.
