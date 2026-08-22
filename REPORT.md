# Week 2 Internship Report — Responsive Web Design

## Project Overview
This project extends the Week 1 wireframe implementation into a responsive static webpage. The goal is to ensure the interface adapts gracefully across desktop, tablet, mobile and small-mobile viewports.

## Methods Used
Semantic HTML5 provides structure. CSS Grid is used for multi-column layouts, while Flexbox handles navigation, buttons and alignment. Fluid values such as percentages, `min()`, `clamp()` and flexible grid tracks reduce dependence on fixed dimensions.

## Responsive Strategy
At desktop widths, the hero uses two columns, services use three columns and the footer uses four columns. At 900px, services and the footer reduce to two columns. At 650px and below, major sections become single-column layouts. At 400px and below, navigation spacing and the newsletter form are further adapted.

## Testing
Recommended viewport tests are 1440px, 1280px, 1024px, 768px, 430px, 390px and 375px widths. Testing should check horizontal overflow, text readability, image scaling, navigation wrapping, card stacking and footer behavior.

## Challenges and Solutions
The main challenge was preserving visual hierarchy while reducing horizontal space. CSS Grid column definitions were changed at responsive breakpoints rather than using fixed positioning. Fluid typography with `clamp()` allows headings to scale between minimum and maximum values. The local SVG image remains contained by its responsive image container.

## Conclusion
The project demonstrates semantic HTML, CSS Grid, Flexbox, fluid sizing and media queries, providing a practical foundation for responsive frontend development.
