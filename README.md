# The Dock You've Been Waiting For — Landing Page Starter Kit

**Property:** 4658 County Highway 83A W, Freeport, FL 32439
**Domain:** thedockyouvebeenwaitingfor.com
**Listed & marketed by:** Todd Siegrist · Real Estate Strategist · Dalton Wade Real Estate Group (broker of record)

Single self-contained page: `index.html` + `assets/`. Upload both, as-is, to your host's root. No build step, no dependencies.

---

## To finish before/after launch

### Email — already set
The contact section uses direct **Call / Text / Email** links — no web form to manage. Email is wired to **todd@toddrocks.com**. To change it, find-and-replace all instances of `todd@toddrocks.com` in `index.html`.

### Video — removed for now
The walkthrough and highlight-reel sections were removed at your request; they can be added back as auto-embedding YouTube slots when your videos are ready.

### Headshot
The agent photo uses `assets/todd-headshot-pro.jpg` (currently `Todd_Siegrist_Headshot_2026.jpg`). To use a different one, drop your preferred image into `assets/` under that exact filename.

### MLS link — already wired
"View the full MLS listing" points to your flexmls share URL. No action needed unless the link changes.

---

## Swapping photos
Every image lives in `assets/` with a plain-English name. To replace one, drop in your new file **using the exact same filename** — no code editing. Keep aspect ratios roughly similar for the cleanest fit.

| Slot filename | Where it appears | Current photo |
|---|---|---|
| `hero-aerial-sunset.jpg` | Full establishing shot (first photo, below the hero) | Golden-hour aerial: house, lawn, dock, bay |
| `dock-to-sundeck.jpg` | The Water — showpiece | Dock running out to the sundeck |
| `dock-boatlift-detail.jpg` | The Water — grid | Boat lift + stairs detail |
| `sundeck-view.jpg` | The Water — grid | View across bay from sundeck |
| `shoreline-chairs.jpg` | The Water — grid | Adirondack chairs at the shoreline |
| `aerial-sunset-dock.jpg` | The Water — 2nd showpiece | Dusk aerial of dock + sundeck |
| `aerial-topdown-lot.jpg` | Land & House — parcel overview | Straight-down drone of the whole lot |
| `lifestyle-redfish.jpg` / `lifestyle-trout.jpg` | Life on the Water | Seller catches (redfish, trout) |
| `lifestyle-sunset.jpg` / `lifestyle-dusk.jpg` / `lifestyle-goldenhour.jpg` | Life on the Water | Seller sunset/dusk shots |
| `interior-windowwall.jpg` | The View | Family room window-wall |
| `interior-bedroom-bayview.jpg` | The View | Bedroom slider to bay |
| `dock-from-water.jpg` | Reel video poster | Dock from the water |
| `lot-wide-oaks.jpg` | Land & House — banner | Level lot under oaks |
| `garage-detached.jpg` | Land & House | Detached 2-car garage |
| `workshop-storage.jpg` | Land & House | Workshop / storage building |
| `todd-headshot-pro.jpg` | Meet Todd | Your professional headshot |
| `toddrocks-logo-white.png` | Header / footer / overlay | Todd Rocks wordmark |
| `daltonwade-logo-white.png` | Footer | Dalton Wade (broker of record) |
| `favicon.png` | Browser tab icon | Todd Rocks mark |

Unused photos from your set (extra dock/yard/interior shots) can be dropped in by renaming them to any slot above.

---

## Notes
- **Phone/text:** 850-797-0627 is wired into every call button, the sticky mobile bar, and the tap-to-text links. Change it by find-replacing `18507970627` (tel/sms) and the displayed `850-797-0627`.
- **Price:** shown as $1,000,000 with "open to all reasonable offers." Search `1,000,000` to adjust.
- **Design system:** dark base, water-blue (#0099FF) + sunset-gold (#C7A95B) accents, Newsreader / IBM Plex Sans / IBM Plex Mono — consistent with your other pages, tuned warmer for a lifestyle audience.
- Removed from the earlier plan: the trust-documents block (survey / inspections), since those are stale — no dead weight pointing buyers at old paperwork.


## Notes on this version
- The opening screen is now **typographic only** (dark blue diagonal gradient, no photo) — the aerial appears as the first full-width image just below it.
- **All photos click through to their full-resolution version** in a new tab (they open the file straight from `assets/`, so the bigger the source file you drop in, the better the enlarged view).
- "Deepwater" was removed from the hero spec strip pending a measured depth. The wording elsewhere can be updated once you confirm the depth at the lift at low tide.


## Second page: comps.html — "The case for the price"

A standalone pricing-evidence page at `comps.html`. Upload it alongside `index.html` (same folder, same `assets/`). It's linked from the main page in three places: the hero buttons, a "Is it priced right?" band after the owner-financing section, and the footer.

**Comp photo placeholders.** Each of the five comps uses a labeled placeholder image. Drop in the real photo using the exact filename to replace it:

| Filename | Comp |
|---|---|
| `comp-red-barn.jpg` | 315 Red Barn Road |
| `comp-waterview.jpg` | 24 Waterview Place |
| `comp-4560-83a.jpg` | 4560 W Co Hwy 83A |
| `comp-bay-harbour.jpg` | 969 Bay Harbour Blvd |
| `comp-sunset-harbour.jpg` | 10 S Sunset Harbour |

**Sources:** the comps page links directly to each property's MLS record. The raw CMA PDF is intentionally not published.

**To change the price** on this page, find-and-replace `1,000,000`. Value-range figures live in the hero verdict block and the closing CTA.


## Copy notes (current version)

- **Depth language:** no "deepwater" anywhere. The dock reads as "more than enough water for the boats the lift is built to hold." Update if/when you measure at low tide.
- **Sun angles:** at this latitude, summer sunrise/sunset fall behind the shoreline (≈60° / 300°); only in the cooler months do they track out over the bay (≈119° / 241°). Copy therefore claims "sun on the water all day" (true year-round from a due-south exposure) and stays soft on sunrise.
- **Financing:** no specific terms published — "favorable terms" and "serious offer backed by considerable cash" only.
- **Costs:** homeowners ~$4,800/yr and flood ~$3,000/yr are published in the Land & House section, with a note that taxes reassess on sale.
