# GFDSustainabilityHub

The sustainability website for **GEMS Founders School Dubai South** — student action on the UN Sustainable Development Goals, year by year.

No coding is needed to maintain this site. Everything lives in two text files and two folders.

## What's in here
- `index.html` — the website itself. You do not need to edit this.
- `data/activities.json` — the list of activities shown under "By Year Group" and "Explore by SDG".
- `data/gallery.json` — the list of showcase items in the "Sustainability Gallery".
- `images/GFDlogo.png` — the school logo shown in the header.
- `gallery-images/` — put your gallery photos in here.

## To add an activity
1. Open `data/activities.json`.
2. Copy one existing block (from `{` to `}`) and paste it as a new item.
3. Change the `yearGroup`, `phase` ("Primary" or "Secondary"), `sdg` (a number 1–17), `title`, `outcome` and `term`.
4. Save. The website updates itself.

## To add a gallery item
1. Save your photo into the `gallery-images/` folder, e.g. `y6-solar-poster.jpg`.
2. Open `data/gallery.json` and add a new item with the matching `image` path, e.g. `"gallery-images/y6-solar-poster.jpg"`.
3. Fill in `title`, `yearGroup`, `sdg` and `caption`.
4. Save. If a photo is missing, the card shows a tidy "Photo coming soon" placeholder instead of breaking.

**Privacy rule:** show the work, not the child. Label by year group and SDG only — never an individual name. This site has no forms, logins or data collection by design.

## Important for hosting
All file paths in this project are **relative** (no leading slash), so the site works correctly on GitHub Pages under the `/GFDSustainabilityHub/` address. Keep them that way.

Note: to preview locally you need to open it through GitHub Pages or a local web server — double-clicking `index.html` may show empty sections because browsers block file reading from your desktop. Once it's on GitHub Pages, everything works.
