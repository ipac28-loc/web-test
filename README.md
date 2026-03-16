# IPAC Static Website Template

> Created by Gemini 3.1 Pro (High)

This is a premium, static website template designed specifically for the International Particle Accelerator Conference (IPAC) series, inspired by IPAC'23, IPAC'24, and IPAC'25.

## Features
- **Vanilla HTML/CSS/JS**: No heavy frameworks or build tools required. Extremely easy to edit and deploy directly to any web server (Apache, Nginx, GitHub Pages, etc.).
- **Modern & Premium Design**: Developed with an elegant, academic yet modern color scheme with careful typography and whitespace.
- **Fully Responsive**: Works flawlessly on desktops, tablets, and mobile devices.
- **Micro-Animations**: Uses Intersection Observers for smooth fade-in animations as the user scrolls down the page.
- **Dynamic Countdown**: A clean countdown widget for the conference start date.
- **Secondary Pages Included**: `committees.html` acts as a template for standard text and grid-heavy secondary pages.

## Directory Structure
```
ipac_template/
│
├── css/
│   └── style.css       # Main stylesheet (contains all variables and structure)
│
├── js/
│   └── main.js         # Interactive logic (Scroll animations, mobile menu, countdown)
│
├── index.html          # Main landing page (Hero, Important Dates, News, Sponsors, etc.)
├── committees.html     # Secondary page template showing a grid of cards
└── README.md           # This file
```

## How to Deploy
Because this is a static site:
1. Copy the entire `ipac_template` directory to your web server's public html folder (e.g., `/var/www/html/`).
2. Update the placeholder text inside the `.html` files (e.g., dates, city names, committee members).
3. Replace the placeholder Unsplash images with your actual conference photography.
4. Update the `futureDate` variable in `js/main.js` to your actual conference opening date.

## Customizing Colors
To change the color scheme, open `css/style.css` and update the CSS variables under `:root`:
```css
:root {
    --clr-primary: #0f2c59; /* Main Dark Blue */
    --clr-secondary: #00b4d8; /* Highlight Blue */
    --clr-accent: #f59e0b; /* Golden Orange */
}
```
