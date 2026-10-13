# VOLT RIOT · Combat Racer

A neon street racer with weapons. Twelve colour-coded power-ups, a three-slot bay, ten segments of health, drift handling, seven AI rivals, four circuits from a storm-drain river to a seaside pier, a Combat Points series and a Dust Bowl deathmatch arena. Win fans, earn Lights.

Built with Three.js · Custom 3D cars & props. Part of [Shreyansh Sharan's portfolio](https://shreyansh-sharan.github.io/shreyanshsharan-portfolio/), split into its own site.

```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # production build in dist/
npm run lint     # oxlint
```

The site is a single page: `#/` is the game's menu, and the same query parameters the portfolio used still work
(for example `#/?auto=...` to skip the menu, `#/?join=CODE` for an invite link).

## Controls

- `W` `A` `S` `D` / arrows: drive
- `Space` Handbrake drift
- `Shift` / `J` Fire forward (hold for all Bolts)
- `K` Fire backward
- `Tab` / `Q` Cycle · `X` Discard
- `C` Look back · `R` Reset · `M` Music · `Esc` Menu

## Ads and gear

Optional AdSense and Amazon affiliate IDs come from environment variables (see `.env.example`). Leave them empty and
no ad or shop code loads.
