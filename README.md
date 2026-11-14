# Style Studio — CSS Problem Set

A lavender-themed responsive HTML/CSS practice page by Madina Sakiyeva. No frameworks, JavaScript, external fonts or build tools are required.

## Run

Download the repository and open `index.html` in a browser. Alternatively, run `python3 -m http.server 8000` in this folder and open http://localhost:8000.

## Solutions / topic map

The supplied assignment includes key notes and learning outcomes rather than numbered exercises. The page provides a practical demonstration of each listed topic.

| Topic | Implementation |
| --- | --- |
| Element, class, ID selectors | `p`, `.highlight`, `#header` |
| Combinators | `.selector-demo p`, `.selector-demo > p`, `.selector-demo + p` |
| Box model | Content box with 24px padding, 3px border and 20px margin |
| Units | px borders, percentage widths, em text, rem spacing, vh hero, vw headings |
| Colors and fonts | HEX, RGB and HSL swatches; Arial with fallback fonts |
| Positioning | Static document flow, relative canvas, absolute badge, sticky header, fixed back-to-top link |
| Flexbox | Navigation and wrapping process row, using justify-content and align-items |
| Grid | Exercise cards and responsive six-item grid, explicit columns, rows and gap |
| Transitions | Button changes background, text color and position on hover/focus |
| Animations | Moving ball using @keyframes |
| Media queries | Two grid columns below 900px; single column below 600px |
| Accessibility | Semantic HTML, skip link, focus states and reduced-motion support |

## Files

- `index.html` — page content and examples.
- `styles.css` — styling, layouts, animation and media queries; comments identify the sections.

## Manual review

1. Open the page on desktop and follow each navigation link.
2. Resize to tablet and phone widths; confirm the grid changes to two and then one column.
3. Hover or keyboard-focus the demo button to see its transition.
4. Scroll to observe the sticky header and fixed back-to-top link.
5. Enable reduced motion in the OS/browser to disable the moving ball.
