# Irfan RP Portfolio

Personal portfolio website for Irfan RP, focused on DevOps, cloud platform engineering, automation, and reliability.

## Overview

This is a static website built with HTML, CSS, and vanilla JavaScript. It highlights:

- DevOps-focused profile and experience
- Skills across cloud, Kubernetes, Terraform, CI/CD, observability, and security
- Featured DevOps project summaries
- Contact form integration and social links

## Key Features

- Responsive layout for desktop and mobile
- Light and dark theme toggle with localStorage persistence
- Smooth scrolling navigation and active section highlighting
- Animated cards (skills, projects, stats)
- Colored DevOps/cloud skill logos
- Custom DevOps SVG favicon

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome icons
- Devicon CDN assets (selected technology logos)

## Local Development

### 1) Install dependencies

```bash
npm install
```

### 2) Run local server

```bash
npm run dev
```

Default dev URL: http://localhost:3000

You can also run:

```bash
npm run start
```

## Available Scripts

- `npm run start` : Start static server with live reload
- `npm run dev` : Start live server on port 3000
- `npm run build` : Placeholder (no build step required)
- `npm run lint` : Run HTMLHint, Stylelint, and ESLint
- `npm run format` : Format HTML, CSS, and JS with Prettier
- `npm run validate` : Validate HTML document structure

## Project Structure

```text
.
├── .github/workflows/deploy.yml
├── favicon-devops.svg
├── index.html
├── styles.css
├── script.js
├── robots.txt
├── sitemap.xml
├── package.json
├── README.md
└── LICENSE
```

## Deployment Notes

- Hosted as a static site (GitHub Pages compatible)
- Includes GitHub Actions workflow for mirroring updates from Gitea and pushing to this repository

## Customize Content

- Update profile text, project items, and contact links in `index.html`
- Update styling and theme variables in `styles.css`
- Update interactions and animations in `script.js`

## License

This project is licensed under the MIT License. See `LICENSE` for details.