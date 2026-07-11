# The Dock You've Been Waiting For — Landing Page Starter Kit

**Property:** 4658 County Highway 83A W, Freeport, FL 32439
**Domain:** thedockyouvebeenwaitingfor.com
**Listed & marketed by:** Todd Siegrist · Real Estate Strategist · Dalton Wade Real Estate Group (broker of record)

Single self-contained page: `index.html` + `assets/`. Upload both, as-is, to your host's root. No build step, no dependencies.

---

## The 2 things to finish before/after launch

### 1. Set your email address (30 seconds)
The contact section uses direct **Call / Text / Email** links — no web form to manage. Call and text already work. For email, replace the placeholder with your real address:
- In `index.html`, do a **find-and-replace-all**: change every `todd@thedockyouvebeenwaitingfor.com` (it appears three times — the visible link, plus two `mailto:` buttons) to the address you want inquiries sent to.
- Prefer to skip email entirely? Delete the two email blocks and leave Call + Text.

### 2. Add the videos when they're ready (one line each)
Both video slots show a styled poster now and become live YouTube embeds the moment you add an ID. No other change needed.
- **Walkthrough (horizontal 16:9):** find `data-yt=""` on the `video-h` block, put the YouTube video ID inside the quotes → `data-yt="dQw4w9WgXcQ"`.
- **Highlight reel (vertical 9:16):** same, on the `video-v` block.

The ID is the part of a YouTube URL after `v=` (or after `youtu.be/`).

### 3. MLS link — already wired
"View the full MLS listing" points to your flexmls share URL. No action needed unless the link changes.

---

## Swapping photos
Every image lives in `assets/` with a plain-English name. To replace one, drop in your new file **using the exact same filename** — no code editing. Keep aspect ratios roughly similar for the cleanest fit.

| Slot filename | Where it appears | Current photo |
|---|---|---|
| `hero-aerial-sunset.jpg` | Full-screen hero | Golden-hour aerial: house, lawn, dock, bay |
| `dock-to-sundeck.jpg` | The Water — showpiece | Dock running out to the sundeck |
| `dock-boatlift-detail.jpg` | The Water — grid | Boat lift + stairs detail |
| `sundeck-view.jpg` | The Water — grid | View across bay from sundeck |
| `shoreline-chairs.jpg` | The Water — grid | Adirondack chairs at the shoreline |
| `aerial-sunrise-wide.jpg` | Walkthrough video poster | Wide misty sunrise aerial |
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
