# GFDSustainabilityHub

The sustainability website for **GEMS Founders School Dubai South** — student action on the UN Sustainable Development Goals, year by year.

No coding is needed to maintain this site.

## What's in here
- `index.html` — the website itself.
- `data/activities.json` — the list of activities shown under "By Year Group" and "Explore by SDG".
- `images/GFDlogo.png` and `images/GFD_shield.png` — the school logos. The crest is embedded in the page, so the header shows even if these files move.

## To add an activity
1. Open `data/activities.json`.
2. Copy one existing block (from `{` to `}`) and paste it as a new item.
3. Change the `yearGroup`, `phase` ("Primary" or "Secondary"), `sdg` (a number 1-17), `title`, `outcome` and `term`.
4. Save. The website updates itself.

## The Sustainability Gallery (Padlet)
Student work is showcased on a shared **Padlet board**, linked from the "Sustainability Gallery" section.

To point the button at your board, open `index.html`, find `YOUR-PADLET-LINK`, and replace it with your real Padlet address (for example `https://padlet.com/yourschool/sustainability`).

**Safeguarding on Padlet:** in your Padlet settings, set posts to **require approval** so staff moderate before anything appears, and turn off **attribution** and **comments** if you prefer to keep it anonymous. The website itself collects no personal data — all contributions live on the moderated Padlet.

## Important for hosting
All paths in this project are **relative** (no leading slash), so the site works on GitHub Pages under the `/GFDSustainabilityHub/` address. To preview, open it through GitHub Pages rather than double-clicking the file.
