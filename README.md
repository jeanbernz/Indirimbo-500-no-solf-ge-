# Indirimbo500 no Solfège — Play Store Upload Package

## What's in this folder

| File/Folder | Purpose |
|---|---|
| `index.html` | Your main app (with manifest + SW injected) |
| `manifest.json` | PWA Web App Manifest (required by PWABuilder) |
| `sw.js` | Service Worker (enables offline use) |
| `icons/` | All icon sizes (48px to 512px PNG) |

---

## Steps to publish on Google Play Store

### Step 1 — Host your app online (required)
PWABuilder needs a live URL. Options:
- **GitHub Pages** (free): Push this folder to a GitHub repo → Settings → Pages → Enable
- **Netlify** (free): Drag & drop this folder at netlify.com/drop
- **Firebase Hosting**, **Vercel**, etc.

### Step 2 — Go to PWABuilder
1. Open [https://www.pwabuilder.com](https://www.pwabuilder.com)
2. Enter your hosted URL (e.g. `https://yourname.github.io/indirimbo500/`)
3. Click **Start** — PWABuilder will scan and score your PWA
4. Click **Package for Stores**
5. Choose **Google Play Store**
6. Fill in:
   - Package name: `com.yourname.indirimbo500` (must be unique)
   - App version: `1.0`
   - Developer name / email
7. Click **Generate** — download the `.zip`

### Step 3 — Sign & upload the APK/AAB
The PWABuilder zip contains a signed AAB + instructions. You'll need:
- A Google Play Developer account ($25 one-time fee at play.google.com/console)
- Upload the AAB in the Play Console under "Internal testing" first, then promote to production

### Step 4 — Play Store listing
Required assets for your listing:
- **Feature graphic**: 1024×500 px banner image
- **Screenshots**: At least 2 phone screenshots (use your app icons or take real screenshots)
- **Short description**: max 80 characters
- **Full description**: max 4000 characters

---

## Icon files included

| File | Size | Use |
|---|---|---|
| icon-48x48.png | 48×48 | MDPI |
| icon-72x72.png | 72×72 | HDPI |
| icon-96x96.png | 96×96 | XHDPI |
| icon-144x144.png | 144×144 | XXHDPI |
| icon-192x192.png | 192×192 | Launcher / PWA |
| icon-256x256.png | 256×256 | XXXHDPI |
| icon-512x512.png | 512×512 | Play Store listing |

---

## Suggested Play Store description

**Short (80 chars):**
Indirimbo Zo Guhimbaza Imana 500 — Indirimbo z'Itorero SDA mu Kinyarwanda

**Full:**
Indirimbo500 ni porogaramu ikusanya indirimbo zo guhimbaza Imana (500) z'itorero SDA mu rurimi rw'ikinyarwanda. Shaka indirimbo byihuse, bibone amashusho y'indirimbo, hifashishijwe indirimbo mfunze. Gira amahitamo y'indirimbo zawe zikunzwe kandi ukoreshe porogaramu no mu gihe nta murongo uri.
