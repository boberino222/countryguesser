# 🌍 Country Guesser

A progressive-clue geography quiz game. You get one clue at a time — guess the country with as few clues as possible.

## Clues include:
- Region / Subregion / Hemisphere
- Population
- Languages & Currency (filtered to avoid giveaways)
- Time zone (shown as "same time zone as X and Y")
- Landlocked status
- National dish
- Borders (neighbor country names)
- Country silhouette shape
- Capital city
- Flag

## Play it

```bash
npm install
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173).

## Deploy

```bash
npm run build
```

The `dist/` folder is a static site — deploy it anywhere (Vercel, Netlify, GitHub Pages, etc.).

## Built with

- React + Vite
- Country data sourced from [REST Countries API](https://restcountries.com/) (embedded, no API calls needed)
- Country outlines from [world.geo.json](https://github.com/johan/world.geo.json)
