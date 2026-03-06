# 👗 Clothing Store — Mobile E-Commerce App

A mobile-first e-commerce UI for clothing, built with pure HTML5 and CSS3.
No JavaScript. No frameworks. No external libraries.

## 🗂 Project Structure

```
app_de_ecommerce_de_ropa/
│
├── css/
│   ├── variables.css      # Design tokens (colors, spacing, typography, shadows)
│   ├── style.css          # Home page styles
│   ├── detail.css         # Product detail page styles
│   └── checkout.css       # Checkout page styles
│
├── storage/
│   ├── font/
│   │   └── encode_sans/   # Local font files (optional, Google Fonts used via @import)
│   └── img/               # Product and UI images
│
├── views/
│   ├── detail.html        # Product detail view
│   └── checkout.html      # Checkout view
│
└── index.html             # Home / product listing page
```

## 🎨 Design System

### Colors
| Token | Hex | Usage |
|---|---|---|
| `--color-dark` | `#292526` | Primary text |
| `--color-mid-gray` | `#787676` | Secondary text |
| `--color-light-gray` | `#A3A1A2` | Placeholder / muted |
| `--color-bg` | `#F2F2F2` | App background |
| `--color-black` | `#121111` | Buttons / nav bar |

### Typography
- **Font:** Encode Sans (Google Fonts)
- **Weights:** 300, 400, 500, 600, 700, 800

## 📱 Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Product grid, search, category filter, bottom nav |
| Detail | `views/detail.html` | Product hero, size/color selectors, add-to-cart CTA |
| Checkout | `views/checkout.html` | Cart items, payment info, order summary, pay button |

## 📐 Responsive Breakpoints

- **Default:** Mobile first (≤479px)
- **480px:** Wider phones — increased padding
- **768px:** Tablets — app card centered with shadow
- **1024px:** Desktop — larger margin

## 🚀 Getting Started

1. Clone the repo
2. Open `index.html` in any browser — no build step required
3. Navigate between pages via the UI links

```bash
git clone <your-repo-url>
cd app_de_ecommerce_de_ropa
open index.html
```

## 📝 Conventional Commits

```
feat: add product cards grid
feat: implement checkout layout
feat: add size and color selectors
style: improve responsive grid breakpoints
fix: align product rating to card footer
```

## ✅ Technical Constraints Met

- [x] HTML5 semantic markup only
- [x] CSS3 native — no frameworks
- [x] Zero JavaScript
- [x] BEM naming convention
- [x] CSS custom properties (variables)
- [x] Mobile-first responsive design
- [x] Visual navigation between all 3 pages
- [x] WCAG accessibility attributes (`aria-label`, `role`, `aria-live`)
