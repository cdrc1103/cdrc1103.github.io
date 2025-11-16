# Cedric Issel - Portfolio

Personal portfolio website showcasing AI/ML leadership experience and projects.

**Live Site:** [https://cdrc1103.github.io/](https://cdrc1103.github.io/)

## Tech Stack

- **Static Site Generator:** Jekyll 3.10.0
- **Hosting:** GitHub Pages
- **Style:** Custom Agency-style theme

## Project Structure

```
.
├── _config.yml              # Site configuration
├── _data/
│   ├── experiences.yml      # Professional experience data
│   └── template.yml         # Site template configuration
├── _includes/               # HTML components
│   ├── header.html
│   ├── about.html
│   ├── experience.html
│   ├── portfolio_grid.html
│   ├── modals.html
│   ├── contact.html
│   └── footer.html
├── _layouts/
│   └── default.html         # Main page layout
├── _posts/                  # Portfolio projects (8 markdown files)
├── css/                     # Stylesheets (Bootstrap, Font Awesome)
├── js/                      # JavaScript (jQuery, Bootstrap)
├── img/                     # Images
├── index.html               # Home page
└── style.css                # Custom styles
```

## Local Development

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# View at http://localhost:4000
```

## Content Management

- **Portfolio Projects:** Add markdown files to `_posts/` with front matter (title, subtitle, layout, modal-id)
- **Experience:** Edit `_data/experiences.yml`
- **Personal Info:** Update `_config.yml`
