# 🕰️ Heure Bleue (The Blue Hour)

Heure Bleue is a curated, bilingual vintage shop built with the [Zola](https://www.getzola.org/) static site generator. It specializing in 90s apparel, historical coinage, and unique collectibles.

## ✨ Features

- **Multilingual Support**: Fully localized in English and Italian (🇮🇹/🇬🇧).
- **Adaptive Navigation**: A unique "ribbon" navigation system that shifts from a top bar on mobile to a vertical sidebar on desktop.
- **Instagram-Style Gallery**: Responsive product sliders with horizontal swipe support and navigation arrows.
- **Brand Integration**: Custom CSS palette extracted directly from the brand's logo for a cohesive aesthetic.
- **Snipcart Ready**: Pre-configured templates for seamless e-commerce integration.
- **Responsive Design**: Mobile-first architecture that adapts to any screen size.

## 🛠️ Tech Stack

- **SSG**: [Zola](https://www.getzola.org/)
- **Styling**: Sass (SCSS) with a custom neutral palette.
- **Deployment**: GitHub Actions & GitHub Pages.
- **E-commerce**: [Snipcart](https://snipcart.com/) (integration in progress).

## 🚀 Getting Started

### Prerequisites
- Install [Zola](https://www.getzola.org/documentation/getting-started/installation/) (0.19.0 or higher).

### Local Development
1. Clone the repository.
2. Run the development server:
   ```bash
   zola serve
   ```
3. Visit `http://127.0.0.1:1111` in your browser.

## 📦 Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions whenever changes are pushed to the `main` branch.

**Live Site:** [https://eliblaster.github.io/heurebleue/](https://eliblaster.github.io/heurebleue/)

## 📁 Project Structure

- `content/`: Markdown files for products, about page, and homepage.
- `sass/`: Custom SCSS styles including the brand palette.
- `templates/`: Tera templates for site layout and product pages.
- `static/`: Brand assets and logo.

---
*© 2026 Heure Bleue Shop*
