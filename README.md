# RebotGames website

Single-page Astro site for RebotGames, showcasing the studio and our current game, **Megabait**.

Live at [rebotgames.com](https://rebotgames.com).

## Commands

| Command         | Action                                      |
| :--------------- | :------------------------------------------ |
| `npm install`    | Install dependencies                        |
| `npm run dev`     | Start local dev server at `localhost:4321`  |
| `npm run build`   | Build production site to `./dist/`          |
| `npm run preview` | Preview the build locally                   |

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and publishes it via GitHub Pages. The custom domain is configured via `public/CNAME` and the repo's Pages settings.

## Content

Placeholder copy/assets for the studio bio and Megabait section live in `src/components/` and `public/images/` — swap these in as real content becomes available.
