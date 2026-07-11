# Publishing Guide — The Dock You've Been Waiting For

Everything you need to get the page live at **thedockyouvebeenwaitingfor.com**. No coding required.

The kit is two things that must stay together: **`index.html`** and the **`assets/`** folder. Wherever they go, they go side by side.

---

## Part 1 — Swap in your final photos (optional)

The site already works with the photos in `assets/`. Do this only if you want to replace one with a better shot.

**The rule:** the page finds each photo by its exact filename. To swap one, rename your new photo to match the slot name, drop it into `assets/`, and overwrite. No code editing.

**Fastest way to rename:**

1. **Turn on file extensions first** (so you don't create `photo.jpg.jpg`):
   - **Mac:** Finder → Settings → Advanced → check "Show all filename extensions."
   - **Windows:** File Explorer → View → check "File name extensions."
2. Open `assets/` next to the slot list in `README.md` ("Swapping photos"). The key ones:
   - `hero-aerial-sunset.jpg` — hero background **and** the full establishing shot below it
   - `dock-to-sundeck.jpg` — the showpiece dock photo
   - `interior-windowwall.jpg` — family-room window wall
   - `lot-wide-oaks.jpg` — the wide lot banner
   - `todd-headshot-pro.jpg` — your headshot
3. Rename your new photo to the exact slot name: click it, press **F2** (Windows) or **Return** (Mac), type the name including `.jpg`, hit enter. Say yes when asked to replace.
4. Keep them as `.jpg`, ideally under ~500 KB each. If one is huge, run it through **squoosh.app** (drag in, export) before renaming.

Trick in one line: **rename to match, drop in, overwrite.**

---

## Part 2 — Get it online

Pick one path.

### Option A — Netlify Drop (easiest, free, ~5 minutes)

Best if you don't already have web hosting.

1. Unzip the kit so you have a folder with `index.html` and `assets/` side by side.
2. Go to **app.netlify.com/drop** (make a free account when prompted).
3. **Drag the whole folder** onto the drop zone. It publishes instantly and gives you a temporary address like `random-name.netlify.app` — open it and confirm the page looks right.
4. Connect your domain: site dashboard → **Domain management** → **Add a domain** → enter `thedockyouvebeenwaitingfor.com`. Netlify shows you the DNS records to set.
5. At your domain registrar (GoDaddy, Namecheap, Google Domains, etc.), open DNS settings and add the records Netlify gave you. Save.
6. Wait 15 minutes to a few hours. Netlify adds HTTPS automatically. Done.

To update later, drag the folder onto the drop zone again — it replaces the old version.

### Option B — Your existing web host (cPanel / File Manager)

Best if the domain already comes with hosting.

1. Log into your host and open **File Manager** (or connect by FTP).
2. Go to the site's root folder — usually `public_html` (or `www`).
3. Upload **`index.html`** and the entire **`assets/`** folder there. Keep the structure exactly: `index.html` at the top level, photos inside `assets/`. Upload the unzipped contents, not the zip.
4. Visit `https://thedockyouvebeenwaitingfor.com`. If the domain already points here, it's live. If you see an old/blank page, try a private window.
5. If your host has a "Force HTTPS / SSL" toggle, turn it on.

---

## Part 3 — Test before the sign goes up

Open the **live site on your phone** (that's how buyers see it) and check:

1. The hero image loads and fills the screen; the headline is easy to read.
2. Tap **Call** and **Text** in the bottom bar → your dialer / messages open to 850-797-0627.
3. Tap **Email Todd** → a new email opens to **todd@toddrocks.com** (change this in `index.html` if you want a different inbox — find-and-replace all instances).
4. Scroll the whole page: every photo loads, no broken-image icons.
5. Tap **View the full MLS listing** → it opens flexmls.
6. Point your phone camera at the **actual QR code on your sign** and confirm it lands on the live site.

When those pass, you're ready to go.

---

## Current status / notes

- **Contact:** direct Call / Text / Email — no web form to manage.
- **Email:** wired to `todd@toddrocks.com`.
- **Video:** the walkthrough and reel sections were removed for now. When your videos are ready, they can be added back as auto-embedding YouTube slots (one line each).
- **Headshot:** `assets/todd-headshot-pro.jpg`. Drop a different image in under that name to swap.
- **Price / phone / address** are edited by find-and-replace in `index.html` (`1,000,000`, `18507970627` / `850-797-0627`, and the address text).
