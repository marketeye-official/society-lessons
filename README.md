# MarketEye Society Lessons

HTML lesson library for MarketEye: Traders Collective — 5 modules, 26 lessons.

## Structure

```
society-lessons/
├── index.html          # Lesson index — links to every lesson
├── module-01/
├── module-02/
├── module-03/
├── module-04/
└── module-05/
```

## Naming convention

Each lesson is a single self-contained HTML file (inline CSS/JS, images as data URIs or in an `assets/` subfolder):

```
module-0X/lesson-XX-short-title.html
```

Example: `module-01/lesson-01-what-is-a-futures-contract.html`

Lesson numbers run 01–26 across the whole course (not per module).

## Adding a lesson

1. Drop the HTML file into the right `module-0X/` folder using the naming convention.
2. Add a link to it in `index.html` under that module.
3. Commit with a message like `Add lesson 07: Reading key levels`.

## Brand rules (quick reference)

- Say "funded accounts" / "funded capital" — never "prop firm".
- No get-rich-quick framing. No gold in visuals.
- Colors: navy `#0D1117` / `#0F1923`, surface `#131E2B`, border `#1E293B`, accent cyan `#38BDF8`, CTA royal blue `#2563EB`, green `#22C55E`, red `#EF4444`.
- Fonts: Orbitron (display), Exo 2 (subheads/UI), DM Sans (body).
