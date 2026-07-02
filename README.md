# YourMenu Website Templates — Showcase

A single-page site showcasing YourMenu's four restaurant website themes, each linking to its live demo. Built as a static site for **GitHub Pages**.

## ⚠️ One step before it looks right: add the thumbnails

The page references four screenshots. Save the images you provided into the `images/` folder using **exactly** these filenames:

| Theme      | Screenshot (in your paste order) | Save as                   |
|------------|----------------------------------|---------------------------|
| Default    | 1st — *Tommy's Tacos y Mas*      | `images/default.png`      |
| Fresh      | 2nd — *Flame & Fork*             | `images/fresh.png`        |
| Smokehouse | 3rd — *Ember & Iron*             | `images/smokehouse.png`   |
| Coastal    | 4th — *Oliva & Mare*             | `images/coastal.png`      |

`.jpg` works too — just update the `src` attributes in `index.html` to match.

## Deploy to GitHub Pages

1. Create a repo and push these files (`index.html`, `README.md`, and the `images/` folder).
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Choose the `main` branch and `/ (root)` folder, then **Save**.
4. Your site goes live at `https://<username>.github.io/<repo>/` within a minute or two.

## Live demo links

- Default — https://default.yourmenu-templates.com/
- Fresh — https://fresh.yourmenu-templates.com/
- Smokehouse — https://smokehouse.yourmenu-templates.com/
- Coastal — https://coastal.yourmenu-templates.com/

## Editing

Everything is in a single `index.html` (styles and script inline) — no build step, no dependencies. Edit theme names, descriptions, or colors directly in that file.
