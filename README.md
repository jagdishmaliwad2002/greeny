# 🌿 Greeny – Fresh & Organic

A responsive organic grocery store homepage built with plain HTML, CSS and JavaScript. No frameworks, no build step, no dependencies.

**Created by Jagdish Maliwad**

---

## Preview

Open `index.html` in any modern browser. Product photos are embedded inside the file, so it works on its own.

## Features

- **Full homepage layout:** header, hero, feature strips, category cards, offer banner, best sellers, kids banner, newsletter and footer
- **69 real products:** 20 berries, 16 apples, 13 leafy greens, 20 cabbage-family vegetables
- **Live search:** filters products as you type
- **Category filters:** dropdown, chips and category cards (Berries, Apples, Leafy Greens, Cabbage, Exotic Berries, Asian Greens)
- **Best Sellers / View all:** shows 6 top products, with a button for the full catalog
- **Shopping cart:** slide-out drawer with quantity controls, remove, subtotal and free-delivery progress (free over $49)
- **Wishlist:** heart toggle with a header counter
- **Newsletter:** email validation with confirmation message
- **Extras:** sticky header, mobile menu, back-to-top button, toast notifications
- **Responsive:** desktop, tablet and mobile layouts

## Project Structure

```
index.html     # the whole site (HTML + CSS + JS + embedded photos)
README.md      # this file
```

## Tech Stack

- HTML5
- CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (ES6)
- Google Fonts: Poppins, Caveat

## Customising

| What | Where |
|------|-------|
| Colors | CSS variables at the top of `<style>` (`--g`, `--gd`, `--gl` …) |
| Products | `RAW` array in the `<script>` section |
| Prices and ratings | `P` mapping (placeholder values) |
| Free-delivery limit | `drawCart()` function (default `49`) |

## Notes

- Product photos were cropped from reference charts, so their resolution is limited. Replace them with your own high-resolution photos for production use.
- Prices, ratings and review counts are placeholder values.
- Checkout, login and video buttons are demo only. Connect a backend to make them real.

## License

Free to use and modify for learning and personal projects.

---

© 2026 Jagdish Maliwad. All rights reserved.
