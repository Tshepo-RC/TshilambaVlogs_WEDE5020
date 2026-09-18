<<<<<<< HEAD
# Tshilamba Vlogs

A five-page website for **Tshilamba Vlogs**, a South African streetwear clothing brand, built as part of the WEDE5020 Portfolio of Evidence.

## Pages

| Page | File |
|---|---|
| Home | `index.html` |
| About Us | `about.html` |
| Products | `Products.html` |
| Inquiry | `inquiry.html` |
| Contact Us | `contactus.html` |

## Technologies

- Semantic HTML5
- CSS3 (external stylesheet: `style.css`)
- Responsive design using Flexbox, CSS Grid and media queries
- Embedded Google Map on the Contact Us page

## Project Structure


## Part 2 — CSS Styling and Responsive Design

An external stylesheet (`style.css`) was created and linked to all five HTML pages. It is organised into sections: reset/base, colour scheme & custom properties, typography, layout, components, and responsive media queries.

**Colour scheme:** near-black (`#111111`) and off-white/cream tones for a clean, minimal streetwear look, with a single warm accent colour (`#d98c2b`) used sparingly for links, buttons and highlights.

**Typography:** a small type scale built with `rem` units and `clamp()` for headings so text scales fluidly between screen sizes.

**Layout:** the header/nav and footer use Flexbox; multi-item content (featured products, product categories, "Our Values", "Why Choose Us") uses CSS Grid (`repeat(auto-fit, minmax(...))`) so the number of columns adapts to the available width. Forms use a two-column CSS Grid that collapses to one column on smaller screens.

**Responsiveness:** two breakpoints are used — `max-width: 48rem` (tablet, ~768px) and `max-width: 30rem` (mobile, ~480px). Relative units (`rem`, `%`, `vw`) are used throughout instead of fixed pixel values.

**Map:** the Contact Us page includes an embedded Google Map (via iframe) pinned to the business address, styled to be fully responsive at all breakpoints.

**Testing:** the site was tested using browser developer tools' device toolbar across desktop, tablet and mobile viewport widths, and resized manually in the browser window to confirm the grid and flex layouts reflow correctly at each breakpoint.

## Changelog

### [1.1.0] — Part 2: CSS Styling and Responsive Design

**Added**
- New external stylesheet `style.css`, linked from all five HTML pages.
- Colour scheme and typography scale defined with CSS custom properties (`:root` variables).
- Flexbox layout for the header/navigation and footer.
- CSS Grid card layout (`.card-grid`) for Featured Products, the Products page categories, and the About Us "Our Values" section.
- New hero section on `index.html` using the previously unused `hero.jpg` asset, styled with Flexbox.
- Two responsive breakpoints (`48rem`/tablet and `30rem`/mobile) with media queries that stack the navigation, reflow the hero and card grids to fewer columns, and collapse forms to a single column.
- Styled form inputs, labels, buttons, and the contact `address` block.
- `.button` class for consistent call-to-action styling.
- Embedded, responsive Google Map on the Contact Us page pinned to the business address (7 Bank Lane, Pretoria Central).

**Fixed (from Part 1 feedback)**
- Corrected broken navigation links across all five pages: links previously pointed to `aboutus.html` and `products.html`, which did not match the actual file names (`about.html` and `Products.html`).
- Fixed a malformed `viewport` meta tag in `about.html` (`name="v/iewport"` → `name="viewport"`).
- Added `class="full-width"` to the message/textarea and button rows of the Inquiry and Contact Us forms so they span the full width of the two-column form grid.

### [1.0.0] — Part 1: Initial Website Structure
- Initial five-page semantic HTML structure: Home, About Us, Products, Inquiry, Contact Us.
- Navigation, footer, product listings and two contact/inquiry forms added.

## References

- Mozilla Developer Network (MDN). *CSS Grid Layout.* https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout
- Mozilla Developer Network (MDN). *Flexbox.* https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout
- Mozilla Developer Network (MDN). *Using media queries.* https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries
- W3Schools. *CSS Tutorial.* https://www.w3schools.com/css/
=======
# TshilambaVlogs_WEDE5020
>>>>>>> 24416be81a33e1c0852f208450d7b9f22ecb9466
