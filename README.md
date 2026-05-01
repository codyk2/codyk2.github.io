# Cody Kandarian — Personal Site

A single-file portfolio. Big type, smooth scroll-driven motion, and a few photos from outside of the keyboard.

**Live:** _add your deploy URL after Vercel/Netlify import_

## What's in here

- `index.html` — the entire site (HTML, CSS, and JS in one file)
- `images/` — portrait and race photos referenced from the page
- `resume.pdf` — drop your resume here so the nav link resolves

## Stack

- Plain HTML / CSS / JS — no build step.
- [GSAP 3](https://gsap.com/) + ScrollTrigger from CDN, for the wordmark shrink + nav dock-on-scroll choreography.
- Fonts: [Archivo Black](https://fonts.google.com/specimen/Archivo+Black) (display), [Allura](https://fonts.google.com/specimen/Allura) (signature loader), [General Sans](https://www.fontshare.com/fonts/general-sans) + [Gambetta](https://www.fontshare.com/fonts/gambetta) from Fontshare (editorial body / heading pair).

## Run locally

Just open `index.html` in any browser. No server needed.

```bash
open index.html
```

## Deploy

Drop the folder into [Vercel](https://vercel.com/new), [Netlify Drop](https://app.netlify.com/drop), or enable GitHub Pages on this repo — any of them serve a static `index.html` for free.
