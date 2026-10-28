# Responsive Pricing Table

Pynexia UI/UX Design Internship — Week 1 project.

A three-plan pricing comparison (Free, Pro, Enterprise) with a monthly / annual billing toggle, designed with a bright, friendly visual system and built as a responsive high-fidelity prototype in HTML + CSS + a little JavaScript.

## Design decisions
- **Hierarchy:** the recommended "Pro" plan is lifted with a gradient border, a "Most popular" tag and a filled call-to-action; other plans use outlined buttons.
- **Readability:** large tabular price numerals, short feature lists with check / dash icons so plans can be compared at a glance.
- **Colour:** light, airy background with a violet-to-pink brand gradient; text contrast kept above WCAG AA.
- **Pricing psychology:** annual toggle shows a "Save 20%" badge and the yearly total under each price.
- **Auto-layout / constraints (Figma concept):** CSS Grid mirrors Figma auto-layout — 3 columns on desktop, 2 on tablet (Enterprise spans full width), 1 on mobile.
- **Accessibility:** the toggle is a real `role="switch"` button with `aria-checked`, visible focus rings.

## Breakpoints
Desktop > 960px · Tablet 641–960px · Mobile ≤ 640px

## View
Open `index.html` in a browser.

Author: Junaideen Risny Suha
