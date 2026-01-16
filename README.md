# Portfolio Website

A minimalist static portfolio website for GitHub Pages showcasing my Information Security expertise.

## Features

- Clean, simplistic design
- Responsive layout for all devices
- Information Security certifications showcase
- Toptal verified talent badge
- Direct links to LinkedIn, GitHub, and Upwork

## GitHub Pages Setup

To make your site accessible at `https://[username].github.io/` (without the `/portfolio/` path):

### Option 1: Rename Your Repository (Recommended)
1. Go to your repository on GitHub
2. Click "Settings" in the repository menu
3. Scroll down to the "Repository name" section
4. Change the name from `portfolio` to `[username].github.io` (e.g., `anasizhar.github.io`)
5. Click "Rename"
6. GitHub Pages will automatically be enabled at `https://[username].github.io/`

### Option 2: Create New Repository
1. Create a new repository named `[username].github.io`
2. Move all files from the `portfolio` repository to the new one
3. Enable GitHub Pages in settings (if not automatic)

**Note:** The repository name MUST be exactly `[username].github.io` for this to work. GitHub will automatically serve the site at the root domain when the repository is named this way.

## Local Development

Simply open `index.html` in a web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

Then visit `http://localhost:8000` in your browser.
