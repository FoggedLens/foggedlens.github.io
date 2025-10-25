# DeFlock Blog

A Jekyll-powered blog hosted on GitHub Pages, available at [blog.deflock.me](https://blog.deflock.me).

## Overview

This is a Jekyll blog using the Minimal Mistakes theme. Blog posts are written in Markdown and stored in the `_posts/` directory. When changes are pushed to the `master` branch, GitHub Pages automatically builds and deploys the site.

## Local Development Setup

### Prerequisites

Before you can run the blog locally, you'll need:

1. **Ruby** (version 3.0.0 or higher recommended)
2. **Bundler** (Ruby gem manager)
3. **Git** (for version control)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/FoggedLens/foggedlens.github.io.git
   cd foggedlens.github.io
   ```

2. **Install Ruby dependencies:**
   ```bash
   bundle install
   ```
   
   If you encounter Ruby version conflicts, you may need to update your Ruby version or use a Ruby version manager like `rbenv` or `rvm`.

### Running the Development Server

1. **Start the Jekyll development server:**
   ```bash
   bundle exec jekyll serve
   ```

2. **Access your local site:**
   Open your browser and navigate to: `http://localhost:4000`

3. **Development features:**
   - The site will automatically rebuild when you make changes to files
   - Live reload functionality shows changes immediately in your browser
   - Press `Ctrl+C` to stop the server

### Alternative Commands

- **Serve with live reload and incremental builds:**
  ```bash
  bundle exec jekyll serve --livereload --incremental
  ```

- **Serve on a different port:**
  ```bash
  bundle exec jekyll serve --port 4001
  ```

- **Build the site without serving:**
  ```bash
  bundle exec jekyll build
  ```

## Project Structure

```
├── _config.yml          # Jekyll configuration
├── _posts/              # Blog posts (Markdown files)
├── _layouts/            # Page templates
├── _includes/           # Reusable components
├── _sass/               # Sass/CSS files
├── _data/               # Data files (YAML, JSON, CSV)
├── assets/              # Images, documents, and other assets
├── about.markdown       # About page
├── index.markdown       # Homepage
└── Gemfile             # Ruby dependencies
```

## Writing Blog Posts

1. **Create a new post:**
   - Add a new Markdown file in `_posts/`
   - Use the naming convention: `YYYY-MM-DD-title.md`
   - Example: `2025-01-15-my-new-post.md`

2. **Post front matter:**
   ```yaml
   ---
   layout: single
   title: "Your Post Title"
   date: 2025-01-15
   categories: [category1, category2]
   tags: [tag1, tag2]
   ---
   ```

3. **Write your content in Markdown below the front matter**

## Adding Pages

To add new pages (like the DeFlock Mobile App User Guide):

1. Create a new `.markdown` or `.md` file in the root directory
2. Add front matter with layout, title, and permalink
3. Write your content in Markdown

Example:
```yaml
---
layout: single
title: "Page Title"
permalink: /page-url/
---

# Your page content here
```

## Deployment

- **Automatic deployment:** Push changes to the `master` branch
- **GitHub Pages** automatically builds and deploys to [blog.deflock.me](https://blog.deflock.me)
- **Build status** can be checked in the GitHub repository's Actions tab

## Troubleshooting

### Common Issues

1. **Ruby version conflicts:**
   - Update Ruby to version 3.0.0 or higher
   - Use a Ruby version manager like `rbenv` or `rvm`

2. **Bundle install fails:**
   ```bash
   bundle update
   gem update bundler
   ```

3. **Jekyll serve fails:**
   - Make sure you're in the project directory
   - Try running `bundle exec jekyll clean` first
   - Check that all dependencies are installed with `bundle install`

4. **Port already in use:**
   ```bash
   bundle exec jekyll serve --port 4001
   ```

### Getting Help

- Check the [Jekyll documentation](https://jekyllrb.com/docs/)
- Review [Minimal Mistakes theme docs](https://mmistakes.github.io/minimal-mistakes/)
- Look at existing posts in `_posts/` for examples

## Contributing

1. Create a new branch for your changes
2. Write your blog post or make modifications
3. Test locally with `bundle exec jekyll serve`
4. Create a pull request to the `master` branch
5. Once merged, changes will automatically deploy

---

**Live Site:** [blog.deflock.me](https://blog.deflock.me)  
**Repository:** [github.com/FoggedLens/foggedlens.github.io](https://github.com/FoggedLens/foggedlens.github.io)