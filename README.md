# Personal Landing Page — mayadkoujah.github.io

A clean, dark-themed personal landing page built with plain HTML and CSS. Designed to be shared via NFC card or QR code — one tap sends anyone directly to all your links.

---

## What This Is

This is a single-page site that acts as a central hub for your professional presence. Instead of handing someone five different links, you give them one — they tap your NFC card or scan your QR code, and everything is right there.

---

## Files in This Repo

| File | What it does |
|---|---|
| `index.html` | The landing page — all your links and info |
| `resume.pdf` | Your resume — linked directly from the page |
| `README.md` | This file |

---

## How to Update Your Resume

1. Export your updated resume as a PDF
2. **Name it exactly** `resume.pdf` (lowercase, same name)
3. Go to your GitHub repo
4. Click `resume.pdf` → click the pencil/edit icon → click **"Upload a new version"** or drag the new file in
5. Commit the change — the link on your site updates automatically, no code changes needed

---

## How to Update Your Info on the Page

1. Open `index.html` in GitHub (click the file → pencil icon to edit)
2. Find the section you want to change — links are clearly labeled in the HTML with comments
3. Edit the text or URL
4. Scroll down and click **"Commit changes"**
5. Wait 1–2 minutes and refresh your site — changes are live

---

## How to Add a Profile Photo

1. Take or choose a professional headshot
2. Name it `photo.jpg`
3. Upload it to this repo (same root level as `index.html`)
4. In `index.html`, find this line:
   ```html
   <div class="avatar">MK</div>
   ```
5. Replace it with:
   ```html
   <img class="avatar" src="photo.jpg" alt="Mayad Koujah" />
   ```
6. Commit — your initials avatar will be replaced with your photo

---

## How to Add or Remove a Link

Open `index.html` and find the `<!-- LINKS -->` section. Each link block looks like this:

```html
<a class="link" href="YOUR_URL" target="_blank" rel="noopener">
  <div class="icon icon-gh"> ... </div>
  <div class="link-label">
    Label Text
    <span class="link-sub">Subtitle text</span>
  </div>
  <span class="arrow">↗</span>
</a>
```

- To **add a link**: copy an existing block, paste it below, and change the `href`, label, and subtitle
- To **remove a link**: delete the entire `<a class="link" ...> ... </a>` block for that link

---

## How to Enable GitHub Pages (First Time Setup)

If the site is not live yet:

1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Set branch to **main**, folder to **/ (root)**
5. Click **Save**
6. Wait 2–3 minutes then visit `https://mayadkoujah.github.io`

---

## How to Program Your NFC Card

1. Download **NFC Tools** (free — iOS or Android)
2. Open the app → tap **Write** → tap **Add a record** → select **URL**
3. Enter: `https://mayadkoujah.github.io`
4. Tap **Write** then hold your phone flat against the NFC card
5. Done — test it by tapping the card with any NFC-enabled phone

---

## Tech Stack

- Plain HTML5 and CSS3 — no frameworks, no dependencies, no build tools
- Google Fonts (Inter + JetBrains Mono) loaded via CDN
- Hosted free on GitHub Pages

---

## Built By

Mayad Koujah — [mayadkoujah.github.io](https://mayadkoujah.github.io)
