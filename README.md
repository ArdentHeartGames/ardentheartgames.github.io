# ardent-heart-games.github.io

Official website for Ardent Heart Games - home of the Ardent Heart Editor.

## About

This is a static site built with Jekyll and hosted on GitHub Pages. It provides information about the Ardent Heart Editor, a lightweight, feature-rich game editor built with Electron and Vue.js for creating games in TypeScript and PixiJS (with ThreeJS support coming soon).

The editor will be available as **free-to-play** exclusively on Steam starting with the Early Access launch in Q1 2026. It is free for solo developers and indie teams (10 or fewer members).

## Site Structure

- **index.md** - Homepage with overview
- **about.md** - Detailed information about the editor, technology stack, and requirements
- **features.md** - Comprehensive feature list and current components
- **roadmap.md** - Development roadmap and milestones
- **updates.md** - Project updates and status

## Local Development

### Prerequisites

- Ruby 4.x
- Bundler

### Setup

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Build the site:
   ```bash
   bundle exec jekyll build
   ```

3. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser

### Configuration

The site configuration is in `_config.yml`. Key settings include:

- Site title and description
- Navigation menu items
- Theme (using Minima theme)

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch. The site will be available at `https://ardentheartgames.github.io`.

## Contributing

To update content:

1. Edit the relevant Markdown files
2. Test locally using `bundle exec jekyll serve`
3. Commit and push your changes
4. GitHub Pages will automatically rebuild and deploy

## License

Content on this site is © Ardent Heart Games.
