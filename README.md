# Matthew Gordon — Portfolio Website

A fully static, GitHub Pages-ready personal portfolio website for Matthew Gordon, web designer and UI/UX specialist. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no build tools, no dependencies.

## Live Demo

> **REPLACE:** Update this URL after deploying to GitHub Pages.

[https://USERNAME.github.io/portfolio](https://USERNAME.github.io/portfolio)

## Screenshot

> **REPLACE:** Drop a screenshot of the live site here.

![Portfolio screenshot placeholder](assets/images/screenshot.png)

## Features

- Bold dark aesthetic with electric accent colors (hot pink, cyan, amber)
- CSS keyframe animations with staggered page-load reveals
- IntersectionObserver scroll-triggered animations
- Responsive at 375px / 768px / 1280px+ with CSS Grid & Flexbox
- Animated SVG geometric hero decoration
- Project grid with JS-powered category filtering
- Client-side form validation + Formspree integration
- Frosted glass fixed navigation with active section tracking
- Accessible: semantic HTML5, focus styles, ARIA labels, sufficient contrast
- `prefers-reduced-motion` support
- Print stylesheet

## Getting Started (Local)

1. Clone this repository:
   ```bash
   git clone https://github.com/USERNAME/portfolio.git
   cd portfolio
   ```

2. Open `index.html` in your browser. That's it — no server required.

   Or serve it locally with any static server, e.g.:
   ```bash
   npx serve .
   # or
   python3 -m http.server 8080
   ```

## Deploying to GitHub Pages

1. Push your code to a GitHub repository on the `main` branch.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `/ (root)`
4. Click **Save**.
5. Your site will be live at `https://USERNAME.github.io/REPO_NAME` within a minute or two.

> The site works directly from the root `index.html` — no configuration needed.

## Contact Form Setup (Formspree)

The contact form uses [Formspree](https://formspree.io) to handle submissions without a server.

1. Go to [formspree.io](https://formspree.io) and create a free account.
2. Click **New Form** and give it a name (e.g. "Portfolio Contact").
3. Copy your **Form ID** (looks like `xrgvwkep`).
4. In `index.html`, find this line:
   ```html
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
5. Replace `YOUR_FORM_ID` with your actual Form ID:
   ```html
   action="https://formspree.io/f/xrgvwkep"
   ```

The free Formspree tier supports 50 submissions/month.

## Personalizing the Site

Search for `<!-- REPLACE:` comments in `index.html` to find every spot that needs your real content:

| What to change | Where |
|---|---|
| Your city / location | Hero subheading, contact section |
| Availability status | Hero tag line |
| Bio paragraph | About section |
| Years of experience | About section |
| Stats (projects, clients, years) | About section |
| Project descriptions & links | Work section |
| Your photo | About section (swap `<div>` for `<img>`) |
| Social profile URLs | Footer (GitHub, LinkedIn, X/Twitter) |
| Email address | Contact section |
| Formspree Form ID | Contact form `action` attribute |
| Open Graph URL & image | `<head>` meta tags |

## File Structure

```
/
├── index.html          ← entire site (edit this)
├── README.md           ← this file
└── assets/
    ├── images/         ← add your photos here
    └── resume.pdf      ← replace with your actual resume
```

## License

MIT — free to use, modify, and redistribute.

---

Built with pure HTML, CSS & vanilla JavaScript. No frameworks. No build step.
