# UtopLearn — Logo GSAP Animation Intro

A professional, Apple-style motion graphics intro for the UtopLearn logo built with **GSAP 3**.

## Features

- **Smooth logo reveal** — scale, blur-to-sharp, and opacity transition inspired by Apple product keynotes
- **Ambient glow** — subtle radial gradient that breathes behind the logo
- **Tagline animation** — "Improve Your English, Speak Confidently" slides in with staggered timing
- **Responsive** — adapts to mobile viewports
- **Lightweight** — single HTML file, GSAP loaded from CDN, no build step

## Quick Start

Open `index.html` in any modern browser — no server required.

```bash
# or serve locally
npx serve .
```

## Animation Sequence

1. **Logo fade-in** — scales from 0.82 → 1 while deblurring (1.6 s, `power2.out`)
2. **Ambient glow** — radial gradient fades in behind logo (1.2 s, `power2.inOut`)
3. **Reflection** — soft under-glow appears (1 s)
4. **Divider** — thin line draws inward (0.8 s, `power3.inOut`)
5. **Tagline line 1** — slides up from 30 px offset (1 s, `power3.out`)
6. **Tagline line 2** — follows with a slight stagger (1 s, `power3.out`)
7. **Breathe** — logo gently pulses once at the end (2 s, `sine.inOut`, yoyo)
