# PLU Macro Scanner

Scan any food product, see full macros, calculate price after tax (Bexar County 8.25%), and get smarter substitutions based on your nutrition and diet goals.

## Features

- **Search 4M+ products** via Open Food Facts API
- **150+ curated items** with accurate macros for instant swaps
- **Smart substitutions** — like-for-like (chips → better chips, not chips → chicken)
- **Nutrition goals** — High Protein, Low Cal, High Fiber, Low Sugar, Low Fat
- **Diet filters** — Keto, Vegetarian, Vegan, Paleo, Mediterranean, Whole30, Carnivore
- **Price calculator** — Bexar County 8.25% sales tax with cost/g protein & cost/100cal
- **Generic foods** — Pizza, burgers, tacos, wings, fries, smoothies, salads & more

## Getting Started

```bash
npm install
npm run dev
```

## Deploy to Vercel

```bash
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/YOUR_USERNAME/macro-scanner.git
git push -u origin main
```

Then go to vercel.com/new → Import repo → Framework: Vite → Deploy.

## Tech Stack

- Vite + React
- Open Food Facts API (free, 4M+ products)
- No backend required (static SPA)
