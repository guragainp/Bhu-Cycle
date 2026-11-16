# Bhu Cycle

**Bhu** means earth and soil. Bhu Cycle is better decision-making support for farmers, showing how each crop shapes the next with NASA Earth data.

Built for the 2026 NASA Space Apps Challenge, *Field Shift: Adapting Farms with NASA Data*.

**Live site:** https://guragainp.github.io/Bhu-Cycle/

## What it does

1. **Your conditions.** Enter your location (Lincoln, Illinois for now). Bhu Cycle reads the last 30 days of NASA POWER data and compares soil moisture, temperature and rain with what is usual for the time of year.
2. **Crop effects.** Tap a crop to see what it does to the soil: nitrogen, organic matter, cover, structure and water.
3. **Plan your next crop.** Pick your last crop and when you want to plant. Bhu Cycle recommends crops that fit the local temperature record, ranks them by how well they follow the last crop, and explains the expected effect on soil, weather and water.
4. **Seed estimate.** Enter your plot size to see roughly how much seed each recommended crop needs.
5. **Farmer forum (demo).** Tap "Connect with other farmers nearby" to browse questions from neighbors, filter by topic, ask your own question, reply, and mark answers as helpful. The farmers and posts are examples, and anything you post is saved only in your browser.

## Data sources

- [NASA POWER](https://power.larc.nasa.gov/) Daily and Climatology APIs: temperature, rainfall, soil wetness (fetched live in the browser)
- USDA NRCS soil survey of Logan County, Illinois: local soil type

## Running it

It is a single static file with no build step. Open `index.html` in a browser, or serve the folder with any static server.

## AI disclosure

The code was written with AI assistance (Claude, by Anthropic). The concept, feature decisions and design direction are the team's own. Bhu Cycle supports, and does not replace, farmer judgment and local expertise.
