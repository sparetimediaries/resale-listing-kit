# Resale listing kit (a free Claude skill)

Turn photos of clothes you want to sell into ready-to-check listings for Vinted, Depop and similar apps.

You send Claude your photos. It sorts them by item, picks the best cover, fills in every listing field from what it can actually see, researches current asking prices on each app, tells you what's still missing (a label photo, measurements), and builds you one page to work from while you post.

**It prepares listings. It doesn't post anything for you, and it doesn't replace your review.**

## What you get

- Photos grouped by item, in posting order, with the cover picked and weak shots flagged.
- Every field filled: title, description, category, brand, size, condition, colour, material, parcel size. Anything Claude can't see is marked "check label" or left blank for you, never guessed.
- A suggested asking price and a private floor for each item, based on current listings on each app, with the searches it used and the date it checked.
- A to-do list for each item: what you must do before posting, what's worth doing, and what's optional.
- Where to list each item, and a short selling playbook.
- One page to keep open on your phone while you post, with copy buttons and "Reviewed" and "Listed" ticks.

## Install (about 2 minutes, easiest on a computer)

1. Download `resale-listing-kit.zip` from the [latest release](../../releases/latest). Don't unzip it.
2. In Claude, open **Settings > Capabilities** and check that file creation is turned on.
3. Go to **Customize > Skills**, click **+**, choose **Upload a skill**, and select the zip.
4. Start a new chat and say: "Help me list my clothes to sell on Vinted and Depop." Then send your photos.

Works on Claude's Free, Pro and Max plans. Menu names can change; if something has moved, Claude's help centre has the current steps.

## Before you post anything

These listings are drafts. Check every detail against the item in your hands: brand, size, colour, condition and any flaws. Fill in the measurements, take out anything that isn't right, and add something only you know, like how it fits or why you're selling it.

- **Prices are a guide, not a promise.** They come from asking prices on current listings, not sold prices, which most apps don't show publicly. Treat them as a ceiling.
- **You're responsible for your listings.** An honest listing with its flaws shown beats a polished one that gets returned.
- **The skill never automates the apps.** It doesn't log in, scrape or browse Vinted or Depop for you, because their terms don't allow outside tools. Where it can't find prices on the web, it gives you the exact searches to run yourself.
- **Follow each app's current rules** on photos, relisting and selling. They change, and the skill asks Claude to check them, but the final call is yours.

## What's in this repo

```
resale-listing-kit/
  SKILL.md                    the instructions Claude follows
  assets/kit-template.html    the page your kit is built from
```

## Versions

See [releases](../../releases) for the changelog. Current version: 1.4.

## Licence and disclaimer

Free to use and adapt for non-commercial purposes, with credit. See [LICENSE](LICENSE).

Not affiliated with, endorsed by or connected to Vinted, Depop, eBay or Anthropic. Provided as is, with no guarantee of results, prices or sales.

## Made by

Natalie Ryan ([@sparetimediaries](https://www.instagram.com/sparetimediaries)), as part of a series of practical experiments in making everyday life and work easier.
