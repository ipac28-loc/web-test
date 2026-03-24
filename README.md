# IPAC Hugo Template

> Developed for the International Particle Accelerator Conference (IPAC) series, inspired by recent editions.

This project is a premium, static website template built as a **Hugo** site. It uses vanilla HTML/CSS/JS without heavy frontend frameworks, offering top-tier performance while making content management incredibly easy via Markdown.

## Features
- **Hugo Powered**: Create and edit pages easily using standard Markdown files in the `content/` directory. No HTML knowledge required for daily updates.
- **Modern & Premium Design**: Developed with an elegant, academic yet modern color scheme with careful typography and whitespace.
- **Fully Responsive**: Works flawlessly on desktops, tablets, and mobile devices.
- **Micro-Animations**: Uses Intersection Observers for smooth fade-in animations as the user scrolls down the page.
- **GitHub Actions CI/CD**: Fully configured to automatically build and deploy to GitHub Pages upon pushing to `main`/`master` branch.

## Directory Structure
```text
ipac_template/
├── hugo.toml           # Site configuration (baseURL, etc.)
├── content/            # All markdown pages (about.md, dates.md)
├── layouts/            # HTML templates (headers, footers, homepage, baseof)
├── static/             # Assets copied directly to public/
│   ├── css/            # Main stylesheet (contains all variables and structure)
│   ├── js/             # Interactive logic (Scroll animations, mobile menu, countdown)
│   └── CNAME           # Custom domain for GitHub Pages
└── .github/workflows/  # CI/CD pipelines
```

## Running Locally

1. Install [Hugo](https://gohugo.io/installation/) (Extended version recommended).
2. Open your terminal in this project's directory.
3. Run the development server:
   ```bash
   hugo server -w
   ```
4. Access the site at `http://localhost:1313/` in your browser. Any changes to markdown files will instantly auto-reload.

## Deployment (GitHub Pages)

This template includes a pre-configured GitHub Actions workflow (`.github/workflows/hugo.yml`).

1. Push your code to the `main` or `master` branch on GitHub.
2. In your repository settings, go to **Pages** -> **Source** and select **GitHub Actions**.
3. The Action will automatically build your Hugo site and deploy it!
4. The custom domain is managed via the `static/CNAME` file. Ensure `hugo.toml` has the matching `baseURL`.

## Customizing Colors
To change the color scheme, open `static/css/style.css` and update the CSS variables under `:root`:
```css
:root {
    --clr-primary: #0f2c59; /* Main Dark Blue */
    --clr-secondary: #00b4d8; /* Highlight Blue */
    --clr-accent: #f59e0b; /* Golden Orange */
}
```
