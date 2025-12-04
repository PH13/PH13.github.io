# Peter Hagen - Portfolio Website

Modern portfolio website built with Astro and TailwindCSS, showcasing data engineering, AI/ML, quantitative methods, and GovCon analytics work.

## 🚀 Deployment

This site is automatically deployed to GitHub Pages via GitHub Actions when you push to the repository.

### First-time Setup

1. **Enable GitHub Pages in repository settings:**
   - Go to Settings → Pages
   - Under "Source", select "GitHub Actions"

2. **Push your changes:**
   ```bash
   git add .
   git commit -m "Deploy new Astro site"
   git push origin gh-pages
   ```

3. **Monitor deployment:**
   - Go to the "Actions" tab in your GitHub repository
   - You should see the "Deploy to GitHub Pages" workflow running
   - Once complete, your site will be live at https://phizou.github.io/

### Manual Deployment

If you need to deploy manually:

```bash
npm run build
# The dist/ folder contains the built site
```

## 🛠️ Development

```bash
npm install
npm run dev      # Start dev server at localhost:4321
npm run build    # Build for production
npm run preview  # Preview production build locally
```

## 📁 Project Structure

- `src/` - Astro source files (pages, components, layouts)
- `src/content/` - Markdown content (projects, notes)
- `public/` - Static assets (images, PDFs, data files)
- `dist/` - Built site (generated, don't commit)

## 📝 Adding Content

- **New Project:** Add a `.md` file to `src/content/projects/`
- **New Note:** Add a `.md` file to `src/content/notes/`
- See existing files for frontmatter structure

