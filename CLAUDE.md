# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build & Development Commands

```bash
# Install dependencies
bundle install

# Run local development server (auto-reloads on file changes)
bundle exec jekyll serve

# Build for production (uses production URL)
bundle exec jekyll build --config _config_prod.yml

# Build for development (uses localhost URL)
bundle exec jekyll build --config _config_dev.yml
```

Note: Changes to `_config.yml` require restarting the server.

## Architecture

This is a Jekyll 4.3 static site using the Minima theme with heavy customization. The site is a UX design portfolio with blog functionality.

### Content Structure

- **`_posts/`** - Blog posts (Notes section) in Markdown with front matter: `layout: post`, `title`, `date`, `image`, `tags`
- **`_projects/`** - Portfolio case studies using `layout: project`. Projects are password-protected via client-side JS (password stored in `_layouts/project.html`)

### Layouts & Includes

- **`_layouts/default.html`** - Base layout with sidebar, Bootstrap, Google Analytics (disabled on localhost)
- **`_layouts/post.html`** - Blog post layout
- **`_layouts/project.html`** - Password-protected project layout with Rive animation support
- **`_includes/sidebar.html`** - Navigation sidebar with dark mode toggle and tilt card effects
- **`_includes/navigation.html`** - Dark mode persistence and sidebar toggle logic

### Configuration

- **`_config.yml`** - Base config (no URL set)
- **`_config_prod.yml`** - Production config with `url: "https://katychung.com"`
- **`_config_dev.yml`** - Development config with `url: "http://localhost:4000"`

Google Analytics only loads when `site.url != "http://localhost:4000"`.

### Styling & Assets

- **`assets/css/katy.css`** - Custom styles
- **`assets/vendor/bootstrap/`** - Bootstrap 5 CSS/JS
- Uses Space Grotesk and Inter fonts via Google Fonts
- FontAwesome for icons
