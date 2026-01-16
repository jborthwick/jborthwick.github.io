# CLAUDE.md

## Project Overview

Personal portfolio website for Jeremy Borthwick, a product designer based in Boston. Showcases UI/UX work for clients including Ten Percent Happier, Mapkin, MapQuest, Harvard Magazine, MINI, CS Monitor, Kill Screen, Franciscan, and Saucony.

## Tech Stack

- **Static HTML** with vanilla CSS
- **GitHub Pages** for hosting (jborthwick.github.io)
- **Jekyll** for includes/partials (minimal usage)
- **Google Fonts** - Merriweather for typography

## Project Structure

```
/
├── index.html           # Main portfolio page
├── casestudy_home.html  # Case study detail page
├── default.html         # Default layout template
├── template.html        # Base template
├── _includes/           # Jekyll partials
│   ├── head.html
│   └── footer.html
├── stylesheets/
│   ├── articles.css     # Main article/portfolio styles
│   ├── normalize.css    # CSS reset
│   ├── styles.css       # Additional styles
│   └── stylesheet.css   # Base styles
├── images/              # Optimized images for web
├── images_src/          # Source images (pre-optimization)
├── docs/                # PDFs (resume, etc.)
└── movies/              # Video files
```

## Development

No build step required. Edit HTML/CSS directly.

To run locally with Jekyll:
```bash
bundle install
bundle exec jekyll serve
```

## Style Conventions

- Use `<span class="highlight">` for emphasized text within paragraphs
- Images use `article-img-large` class, with optional `series` or `long` modifiers
- Navigation links use anchor IDs (`#tenpercent`, `#mapkin`, etc.)
- Keep image filenames descriptive (e.g., `sqsphero_tph_1@2x.jpg`)

## Content Updates

- Resume PDF located at `docs/jborthwick_resume_2025.pdf`
- Portfolio sections ordered in nav by prominence/recency
- Each project section uses `<h3 id="project-id">` for navigation targeting
