# Scroll-Driven Hero Animation

Hero section ("WELCOME ITZ FIZZ") with a staggered load animation and a scroll-scrubbed car animation.

**Stack:** HTML, CSS, JavaScript, React 18 (UMD), Tailwind (CDN), GSAP + ScrollTrigger.

## Run locally
Open `index.html` in a browser (or `npx serve .`).

## Deploy (GitHub Pages)
Push to a repo, then Settings > Pages > Deploy from branch `main` / root.

## How it works
- Intro: GSAP timeline staggers letters, then stats.
- Scroll: ScrollTrigger pins the hero for 200% of viewport height with `scrub: 1`, driving car translateX, wheel rotation, road offset and headline scale.
- Only transforms/opacity are animated (no layout reflow).
