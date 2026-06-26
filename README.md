# Fiber & Your Health

A patient-facing fiber education site built for use in a gastroenterology practice. Two standalone HTML files — no build step, no dependencies, no server required.

## Files

| File | Description |
|------|-------------|
| `index.html` | Main education site |
| `fiber-calculator.html` | Daily fiber intake calculator |

## What's included

### index.html

- **Dietary fiber** — benefits of increasing dietary fiber, practical meal-by-meal suggestions, collapsible fiber content chart (Mott/USDA data), link to the calculator
- **Supplemental fiber** — gel-forming vs. non-gel-forming fiber supplements
- **How psyllium works** — four mechanisms (constipation, diarrhea, blood sugar, cholesterol)
- **What to expect** — side effect explanation, the microbiome reset point
- **Psyllium husk dosing** — 4-week titration schedule, water requirements
- **Safety & interactions** — medication timing (levothyroxine, warfarin, digoxin, lithium, insulin)
- **FAQ** — 7 common patient questions including IBS-D, GLP-1 interactions, restarting after stopping
- **Fiber content chart** — full Mott Children's Hospital fiber chart rendered as a separate "page" within the site, organized by Fruits / Vegetables & Legumes / Cereals / Breads, Grains & Pasta

### fiber-calculator.html

- Age-range and sex selector with fiber targets from the Dietary Reference Intakes (DRI) table
- Searchable food database (~90 foods) with category filter
- Custom food entry for unlisted items
- Serving size stepper with real-time fiber calculation
- Fiber supplement section (psyllium/Metamucil, methylcellulose/Citrucel, wheat dextrin/Benefiber)
- Progress bar toward daily target
- Copy-to-clipboard export with date, goal status, and full meal log

## Usage

Download both files into the same folder and open `index.html` in a browser. Both files must be in the same directory for the cross-links to work. No internet connection required after initial font load (Google Fonts).

To host on GitHub Pages, push both files to the root of a repository with Pages enabled and navigate to `https://<username>.github.io/<repo>/index.html`.

## Content sources

- Fiber intake recommendations: USDA Dietary Guidelines for Americans 2020–2025; Institute of Medicine Dietary Reference Intakes
- Fiber content data: University of Michigan Mott Children's Hospital Fiber in Foods Chart; USDA FoodData Central
- Clinical references: McRorie & McKeown (2017), Gibb et al. (2015), Bijkerk et al. (2009), Lambeau & McRorie (2017), ACG/AGA IBS clinical guidelines

## Medical disclaimer

This site is for general patient education only and does not constitute medical advice. Content is based on peer-reviewed literature and consensus guidelines current as of 2026.
