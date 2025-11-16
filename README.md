# Cedric Issel - Portfolio

Personal portfolio website showcasing AI/ML leadership experience and projects.

**Live Site:** [https://cdrc1103.github.io/](https://cdrc1103.github.io/)

## Tech Stack

- **Static Site Generator:** [Jekyll](https://jekyllrb.com/) 3.10.0
- **Theme:** [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) 4.24.0 (remote theme)
- **Hosting:** GitHub Pages
- **Language:** Ruby 3.2.0

## Project Structure

```
.
├── _config.yml           # Site configuration and theme settings
├── _data/
│   └── navigation.yml    # Site navigation menu
├── _pages/               # Main site pages
│   ├── home.md          # Landing page with splash layout
│   ├── about.md         # About/bio page
│   ├── projects.md      # Projects showcase
│   ├── experience.md    # Professional experience
│   └── contact.md       # Contact information
├── portfolio/            # Project case studies
│   └── genai-platform.md
├── assets/               # Images, CSS, JS
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## Local Development

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# View at http://localhost:4000
```
