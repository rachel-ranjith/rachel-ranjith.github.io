# Rachel Ranjith — Personal Website

A minimal, elegant personal website built with vanilla HTML, CSS, and JavaScript.

## Structure

```
├── index.html          # Homepage
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # Navigation & interactions
├── pages/
│   ├── articles.html   # Published writing
│   ├── society.html    # Club & org involvement
│   ├── achievements.html
│   ├── experience.html # Work history
│   └── projects.html   # Portfolio projects
└── assets/
    ├── images/
    │   └── profile.jpg # Your photo
    └── docs/
        └── resume.pdf  # Your CV
```

## Setup

1. Replace placeholder content with your own
2. Add your profile photo to `assets/images/profile.jpg`
3. Add your resume PDF to `assets/docs/resume.pdf`
4. Update social links in `index.html`
5. Push to GitHub and enable Pages

## Customization

Colors and fonts can be adjusted in `css/style.css` via CSS variables at the top:

```css
:root {
    --color-black: #0a0a0a;
    --color-cream: #f5f0e8;
    --font-display: 'Cormorant Garamond', serif;
    --font-body: 'Outfit', sans-serif;
}
```

## Deployment

This site is designed for GitHub Pages:

1. Push to a repo named `username.github.io`
2. Go to Settings → Pages
3. Select "Deploy from a branch" → main → / (root)
4. Your site will be live at `https://username.github.io`

## License

Feel free to use this as a template for your own site.