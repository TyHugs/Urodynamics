# Urodynamics Study — Patient Landing Page

**Michigan Medicine · Department of Urology**

A patient-facing landing page designed to educate, reassure, and reduce no-show and cancellation rates for urodynamics studies at Michigan Medicine.

## Overview

This single-page website guides patients through everything they need to know about their upcoming urodynamics study — what it is, what to expect, why it matters, how to prepare, what other patients say, and who will care for them.

## Features

- **Tabbed navigation** — 7 content sections accessible via sticky tabs with progress indicator
- **Simplified English mode** — One-click toggle for plain-language content throughout
- **Dark mode** — Accessibility toggle for light-sensitive users
- **Print-ready** — Dedicated print stylesheet expands all sections; companion PDF handout included
- **Share with Caregiver** — Web Share API with clipboard fallback
- **Medical term tooltips** — Hover/tap definitions for clinical terms
- **Patient testimonials** — Anonymized quotes addressing common anxieties
- **Schema.org structured data** — `MedicalProcedure` markup for SEO
- **WCAG 2.1 AA** — 18px base font, 48px touch targets, ARIA roles, keyboard navigation
- **Mobile-first responsive** — Optimized for 375px through 1440px+
- **Zero dependencies** — Single self-contained HTML file (Google Fonts CDN only)

## Files

```
index.html                          # Main landing page
urodynamics-patient-handout.pdf     # Companion 1-page printable handout
.nojekyll                           # Bypass Jekyll processing on GitHub Pages
README.md                           # This file
```

## Deployment (GitHub Pages)

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` → `/ (root)`
4. Site will be live at `https://<username>.github.io/<repo-name>/`

## Design Decisions

- **Patient persona**: Skews older (50–80+), potentially anxious, limited digital literacy, often accompanied by caregiver
- **Core objective**: Reduce no-show/cancellation rates by addressing root causes — fear, uncertainty, embarrassment
- **Branding**: Official Michigan Medicine maize & blue palette
- **Content strategy**: Empathetic, non-clinical tone using "you" throughout; validated by 10-member expert panel review

## Expert Panel Review

This page was reviewed by a simulated 10-member panel including patients, urologists, UX designers, a frontend engineer, a patient experience officer, a healthcare strategy consultant, and a cross-disciplinary synthesizer. All recommendations from the review were implemented in the current version.

## License

Internal use — Michigan Medicine, Department of Urology.
