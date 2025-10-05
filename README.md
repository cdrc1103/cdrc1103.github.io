# Cedric Issel - Professional Portfolio

A professional portfolio website built with Jekyll and the Minimal Mistakes theme, showcasing AI/ML leadership experience and projects in Generative AI and Financial Services.

**Live Site:** [https://cdrc1103.github.io](https://cdrc1103.github.io)

## About

This portfolio website highlights:
- **AI & Data Science Management** experience
- **Generative AI** projects with measurable business impact
- **Leadership** in cross-functional teams
- **Production ML Systems** in Financial Services
- Current job search focus: **Singapore**

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

### Prerequisites

- Ruby 3.2.0 or higher
- Bundler gem

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/cdrc1103/cdrc1103.github.io.git
   cd cdrc1103.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run local server**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site**
   - Open your browser to [http://localhost:4000](http://localhost:4000)
   - The site will auto-rebuild on file changes

### Build for Production

```bash
bundle exec jekyll build
```

The production-ready site will be generated in the `_site/` directory.

## Configuration

### Site Settings

Edit [_config.yml](_config.yml) to customize:
- Site title, description, and URL
- Author information and bio
- Social media links (LinkedIn, GitHub, Email)
- Theme skin (default, dark, air, etc.)
- SEO settings

### Navigation

Edit [_data/navigation.yml](_data/navigation.yml) to modify the main navigation menu.

### Content Pages

- **Home Page:** [_pages/home.md](_pages/home.md) - Splash layout with hero section
- **About:** [_pages/about.md](_pages/about.md)
- **Projects:** [_pages/projects.md](_pages/projects.md)
- **Experience:** [_pages/experience.md](_pages/experience.md)
- **Contact:** [_pages/contact.md](_pages/contact.md)

### Portfolio Projects

Add new project case studies in the `portfolio/` directory. Each project should have:
- Front matter with title, excerpt, header images
- Sidebar metadata (role, duration, team size)
- Detailed project description

## Features

- **Responsive design** optimized for all devices
- **Minimal Mistakes theme** with professional styling
- **Portfolio collection** for project showcases
- **SEO optimized** with jekyll-seo-tag
- **Pagination** for scalable content
- **Category & tag archives**
- **Social media integration**

## Deployment

This site is configured for **automatic deployment** via GitHub Pages:

1. Push changes to the `main` branch
2. GitHub Actions automatically builds and deploys
3. Site is live at `https://cdrc1103.github.io`

### Manual Deployment

If needed, you can deploy manually:
```bash
git add .
git commit -m "Update content"
git push origin main
```

## Key Sections

### Home Page
- Hero section with call-to-action buttons
- Feature highlights (Generative AI, Leadership, MLOps)
- Key achievements with metrics
- Recent projects preview
- Job search status (Singapore focus)

### Projects
- Portfolio collection showcasing:
  - Gen AI Platform for Financial Services
  - Additional projects (add more in `portfolio/`)

### Experience
- Professional background
- Leadership roles
- Technical expertise

## Customization Tips

1. **Add your photo:** Place image at `/assets/images/bio-photo.jpg`
2. **Add header images:** Use `/assets/images/header-bg.jpg` for hero sections
3. **Update resume:** Place PDF at `/assets/resume.pdf`
4. **Customize colors:** Modify theme skin in `_config.yml`
5. **Add projects:** Create new `.md` files in `portfolio/` directory

## Performance

- Static site generation for fast load times
- SCSS compression enabled
- Jekyll caching for faster builds
- Optimized for GitHub Pages CDN

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Contributing

This is a personal portfolio site. If you'd like to use this as a template:

1. Fork the repository
2. Update `_config.yml` with your information
3. Customize content in `_pages/` and `portfolio/`
4. Deploy to your own GitHub Pages

## License

Content is © 2025 Cedric Issel. Site structure and code are based on the [Minimal Mistakes theme](https://github.com/mmistakes/minimal-mistakes), licensed under MIT.

## Contact

- **LinkedIn:** [cedric-issel](https://linkedin.com/in/cedric-issel)
- **GitHub:** [@cdrc1103](https://github.com/cdrc1103)
- **Email:** cedric.issel@gmail.com

---

**Status:** Actively maintained | Open to opportunities in Singapore

*Built with love using Jekyll and Minimal Mistakes*
