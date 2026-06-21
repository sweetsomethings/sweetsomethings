# Sweet Somethings 🍪 — Bakery Website

A single-page website for Ashley’s small-batch home bakery, **Sweet Somethings**.
It’s one plain `index.html` file — no build tools, no frameworks, no dependencies —
which makes it perfect for free hosting on **GitHub Pages**.

## What’s inside

- `index.html` — the entire site (HTML + CSS in one file)
- `favicon.ico`, `favicon-32.png`, `icon-192.png`, `icon-512.png`,
  `apple-touch-icon.png` — the cookie icon (cut from the logo) at every
  size browsers and phones look for
- `og-image.png` — the 1200×630 preview image shown when the link is
  texted (SMS/iMessage) or shared on social media
- Brand palette and hand-drawn SVG doodles matching the Sweet Somethings logo
- Sections: hero, badges, This Week’s Bakes, Meet Ashley, Why We Bake,
  How to Order (via TikTok DM), Fresh Batch Friday, kitchen tips, and a note from Ashley

> **Upload every file in this folder** to the repository, not just
> `index.html`, or the icons and link previews won’t work.

## How to publish on GitHub Pages (free)

1. **Create a GitHub account** (if you don’t have one) at <https://github.com> — then sign in.
1. **Use the current repository.**
  Repo: <https://github.com/sweetsomethings/sweetsomethings>
- Keep it **Public** (required for free GitHub Pages)
1. **Upload the site file.**
   On the new repo page, click **uploading an existing file**,
   drag in `index.html`, and click **Commit changes**.
1. **Turn on GitHub Pages.**
   Go to the repo’s **Settings** tab → **Pages** (left sidebar).
- Under **Source**, choose **Deploy from a branch**
- Branch: **main**, Folder: **/ (root)**
- Click **Save**
1. **Visit your site.** After a minute or two, your site is live at:
  `https://sweetsomethings.github.io/sweetsomethings/`
1. **Link previews are already configured.**
  Open Graph and Twitter image URLs in `index.html` now point to the live
  GitHub Pages site and image path.
- The favicon works immediately with no edits needed.
- Note: messaging apps cache previews, so if you text the link before
  making this edit, it can take a while (or a fresh conversation) for
  the image to appear.

### Optional nice-to-haves

- **Custom domain:** in Settings → Pages you can attach a domain like
  `sweetsomethings.com` if Ashley ever buys one.
- **Updates:** to change the menu or text, just edit `index.html` on GitHub
  (pencil icon) and commit — the site republishes automatically.
- **TikTok link:** once Ashley’s TikTok handle is final, search `index.html`
  for the “Order” section and wrap the TikTok mentions in a link, e.g.
  `<a href="https://www.tiktok.com/@yourhandle">@yourhandle</a>`.

## Editing tips

- All brand colors live at the top of the file in the `:root { ... }` block.
- “This Week’s Bakes” cards are in the `<section id="bakes">` block —
  copy a `<article class="bake-card">` to add a new item.
- No Scranton references are included anywhere on the site.