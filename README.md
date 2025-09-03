# Brandon Lewis - Data Science Portfolio

Bilingual (DE/EN) portfolio hosted on GitHub Pages, built with Jekyll (core plugins only) and Bootstrap 5.

- Live: https://cyranothebard.github.io/
- EN Overview (Energy): https://cyranothebard.github.io/projects/energy-recommendation/
- DE Übersicht (Energie): https://cyranothebard.github.io/projekte/energie-empfehlungssystem/

## Structure
- `_layouts/simple.html` — base layout
- `index.html`, `en/index.html` — DE/EN homepages
- `projekte/` (DE) and `projects/` (EN) — project pages and lenses
- `blog/` — DE/EN blog listing and posts
- `ueber-mich.html`, `about/index.html` — DE/EN about
- `lebenslauf.html`, `resume.html` — DE/EN resumes

## Development
```bash
bundle install --path vendor/bundle
bundle exec jekyll serve
```

## Notes
- No unsupported plugins (e.g., jekyll-polyglot) to ensure Pages compatibility
- Language switching via simple links (`/` ⇄ `/en`)
- Analytics and advanced SEO deferred to keep maintenance low


Last rebuild trigger: 2025-09-03 11:35:26 CEST
