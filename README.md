# MorningPages.fun Landing Page

A modern, responsive landing page for [MorningPages.fun](https://morningpages.fun), an AI-powered journaling app. This landing page is designed to work seamlessly with GitHub Pages.

## Features

- 🎨 Clean, modern design with journal-inspired aesthetics
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading with vanilla HTML/CSS/JavaScript
- ♿ Accessible and semantic HTML
- 🚀 Ready for GitHub Pages deployment

## Local Development

To view the landing page locally:

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd mp-landing-page
   ```

2. Open `index.html` in your web browser, or use a local server:
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server -p 8000
   ```

3. Navigate to `http://localhost:8000` in your browser

## Deployment to GitHub Pages

### Initial Setup

1. Push this repository to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Landing page setup"
   git branch -M main
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. Go to your repository on GitHub

3. Navigate to **Settings** → **Pages**

4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`

5. Click **Save**

6. Your site will be available at `https://<your-username>.github.io/<repo-name>/` after a few minutes

### Custom Domain (Optional)

If you want to use a custom domain like `morningpages.fun`:

1. In your repository, go to **Settings** → **Pages**
2. Under **Custom domain**, enter your domain name (e.g., `morningpages.fun`)
3. Follow GitHub's instructions to configure your DNS:
   - Add a `CNAME` record pointing to `<your-username>.github.io`
   - Or add `A` records pointing to GitHub's IP addresses:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
4. Check "Enforce HTTPS" (recommended)

## Project Structure

```
mp-landing-page/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript for interactivity
├── README.md       # This file
└── .gitignore      # Git ignore rules
```

## Customization

### Colors

Edit the CSS custom properties in `styles.css`:

```css
:root {
    --color-primary: #8B6F47;
    --color-secondary: #E8DCC6;
    /* ... */
}
```

### Content

- Update text content in `index.html`
- Modify sections, features, and copy to match your needs
- Update links (currently pointing to `morningpages.fun`)

### Styling

- All styles are in `styles.css`
- Uses CSS custom properties for easy theming
- Mobile-first responsive design

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is for MorningPages.fun. All rights reserved.

