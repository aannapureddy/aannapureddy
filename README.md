# Arjun Annapureddy - Personal Site

### :computer: _Cyberspace. A consensual hallucination experienced daily by billions of legitimate operators, in every nation._
##### ― William Gibson, a book :book:

For clarification it's pronounced **aar**·jn. Start off strong and sort of just clobber together the end...

This is my personal profile containing my personal work. It has no connection to my day job. This is what I do for fun.
In that spirit not every repo is moderated.

## 🚀 Live Site

Visit: [https://aannapureddy.github.io](https://aannapureddy.github.io)

## 🛠️ Technology Stack

- **Jekyll** - Static site generator
- **GitHub Pages** - Hosting and deployment
- **Minima Theme** - Clean, responsive design
- **Ruby** - Backend processing
- **GitHub Actions** - Automated deployment

## 📦 Local Development

### Prerequisites

- Ruby 3.2 or higher
- Bundler
- Node.js 18 or higher (optional, for additional tooling)

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/aannapureddy/aannapureddy.git
   cd aannapureddy
   ```

2. **Install dependencies**
   ```bash
   bundle install
   npm install  # if you want to use Node.js features
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve
   # or use npm scripts
   npm run serve
   ```

4. **Visit the site**
   Open [http://localhost:4000](http://localhost:4000) in your browser

### Available Commands

- `bundle exec jekyll serve` - Start development server
- `bundle exec jekyll build` - Build the site
- `bundle exec jekyll clean` - Clean build artifacts
- `npm run serve-drafts` - Serve with draft posts included

## 📝 Adding Content

### New Blog Posts

Create new posts in the `_posts/` directory with the format:
```
YYYY-MM-DD-title.markdown
```

Example front matter:
```yaml
---
layout: post
title: "Your Post Title"
date: 2024-01-01 12:00:00 -0600
categories: [category1, category2]
---
```

### Pages

Create new pages in the root directory with front matter:
```yaml
---
layout: page
title: Page Title
permalink: /page-url/
---
```

## 🚀 Deployment

This site automatically deploys to GitHub Pages when you push to the `main` branch. The deployment is handled by GitHub Actions.

### Manual Deployment

If you need to deploy manually:

1. Build the site: `bundle exec jekyll build`
2. Push changes to GitHub
3. GitHub Actions will automatically build and deploy

## 🎨 Customization

- **Theme**: Currently using Minima theme. You can customize it by creating `_sass/` and `_layouts/` directories
- **Styling**: Modify `assets/css/style.scss` for custom styles
- **Configuration**: Edit `_config.yml` for site-wide settings

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: This is a special repository that appears on my GitHub profile. Feel free to explore and get inspired!
