# AI Ethics & Life Blog

A Jekyll-powered blog exploring artificial intelligence, ethics, and the intersection of technology with human values.

## 🚀 Quick Start

### Local Development

1. **Install Ruby** (if not already installed):
   ```bash
   # Using rbenv (recommended)
   brew install rbenv ruby-build
   rbenv install 3.2.0
   rbenv global 3.2.0
   ```

2. **Install Jekyll and Bundler**:
   ```bash
   gem install jekyll bundler
   ```

3. **Install dependencies**:
   ```bash
   bundle install
   ```

4. **Run the development server**:
   ```bash
   bundle exec jekyll serve
   ```
   
5. **View your site**: Open [http://localhost:4000](http://localhost:4000) in your browser

### Writing New Posts

Create a new blog post by adding a file to the `_posts` directory with the naming convention:

```
YYYY-MM-DD-title.md
```

Example: `2025-10-12-my-new-post.md`

Each post should start with front matter:

```yaml
---
layout: post
title: "Your Post Title"
date: 2025-10-12 16:00:00 -0000
categories: category-name
tags: [tag1, tag2, tag3]
---
```

## 📝 Content Structure

- **Posts**: Located in `_posts/` - your main blog posts
- **Pages**: Located in the root directory - static pages like About, Contact
- **Images**: Place in `assets/images/` and reference as `/assets/images/filename.jpg`

## 🎨 Theme

This blog uses the **Minima** theme, which provides:
- Clean, minimal design
- Responsive layout
- Social media integration
- RSS feed
- SEO optimization

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions. Simply push to the `main` branch and your changes will be live within minutes.

### Manual Deployment

If you need to deploy manually:
```bash
bundle exec jekyll build
# The _site/ directory contains your built site
```

## 📚 Useful Commands

- `bundle exec jekyll serve` - Run development server
- `bundle exec jekyll build` - Build production site
- `bundle exec jekyll clean` - Clean build directory

## 🔧 Configuration

Main configuration is in `_config.yml`. Key settings:
- `title` - Site title
- `description` - Site description
- `url` - Your site's URL
- `baseurl` - Subpath if hosting in a subdirectory

## 📖 Writing Tips

- Use Markdown for formatting
- Add front matter (YAML) to posts for metadata
- Use categories and tags to organize content
- Include images in `assets/images/`
- Posts are automatically listed on the home page

## 🤝 Contributing

Feel free to submit issues or pull requests if you find bugs or have suggestions for improvements.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
