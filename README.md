# Pawan Sharma - Portfolio

A modern, dark-themed personal portfolio website for AI & business solutions.

## Live
Deployed with Netlify (free) from this repository.

## Stack
- Single self-contained `index.html` - HTML, CSS and vanilla JS, no build step
- Fonts loaded from Google Fonts (Bricolage Grotesque, DM Sans, JetBrains Mono)
- Fully responsive, accessible, respects `prefers-reduced-motion`

## Structure
- Hero, About, Skills, Selected Work, Experience, Contact
- Sticky nav with scroll-spy, mobile menu, scroll-reveal animations

## Editing
Everything lives in `index.html`. Change the text, colours (CSS variables at the
top in `:root`) and projects directly. Push to `main` and Netlify redeploys.

## Run locally
Just open `index.html` in a browser, or serve it:

    python3 -m http.server
