# KJ4DIA - Amateur Radio Website

<img src="assets/images/kj4dia_logo.png" align="right" width="128" alt="KJ4DIA Logo">

[![Deploy Jekyll site to Pages](https://github.com/MichalAFerber/kj4dia.me/actions/workflows/jekyll.yml/badge.svg)](https://github.com/MichalAFerber/kj4dia.me/actions/workflows/jekyll.yml)

Personal amateur radio website built with Jekyll and the Just the Docs theme.

**Live Site:** [kj4dia.me](https://kj4dia.me)
**Author:** Michal Ferber, aka TechGuyWithABeard

## 🛠️ Local Development

### Prerequisites

- Ruby 3.0+
- Bundler (`gem install bundler`)

### Setup

1.  Clone the repository:
    ```bash
    git clone https://github.com/MichalAFerber/kj4dia.me.git
    cd kj4dia.me
    ```
2.  Install dependencies:
    ```bash
    bundle install

## Site Structure

- `index.md` - Home page with introduction
- `documents.md` - Certifications and licenses
- `links.md` - Amateur radio and emergency communications resources
- `_config.yml` - Jekyll configuration settings
- `_includes/` - Custom HTML includes (footer, header)
- `assets/` - Static assets (CSS, images, icons)

## Configuration

The site is configured via `_config.yml` with the following key settings:
- **Theme:** `just-the-docs` (via `jekyll-remote-theme`)
- **Color Scheme:** Dark mode enabled
- **Plugins:**
  - `jekyll-seo-tag`
  - `jekyll-sitemap`
  - `jekyll-include-cache`

### Running Locally

To run this site locally:

```bash
# Install dependencies
bundle install

# Serve the site locally
bundle exec jekyll serve

# The site will be available at http://localhost:4000
```

## 📦 Deployment

This site is deployed to **GitHub Pages** automatically whenever changes are pushed to the `main` branch.

- **Workflow**: `.github/workflows/jekyll.yml`
- **Source**: Static files built from this repo.

## Theme

Built with [Just the Docs](https://just-the-docs.com/) - A modern, high-performance Jekyll theme for documentation.

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
