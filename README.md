# Exegesis-for-Facebook

Greek Orthodox Scripture Exegesis — ready-made single HTML files hosted via **GitHub Pages** and shareable directly on Facebook.

## How it works

Each passage gets its own self-contained HTML file with:

- The original Greek Scripture text (Septuagint / Greek New Testament)
- An Orthodox patristic exegesis in Greek
- **Facebook Open Graph meta tags** so that when the link is pasted into Facebook, it renders a rich preview (title, description, image)
- A **"Share on Facebook"** button inside the page

## Live site

> Enable **GitHub Pages** on this repository (Settings → Pages → Deploy from branch `main`, folder `/`) to publish all files at:
>
> `https://iocoanton.github.io/Exegesis-for-Facebook/`

## Pages

| File | Passage |
|---|---|
| [`index.html`](index.html) | Table of contents |
| [`john-1-1-14.html`](john-1-1-14.html) | John 1:1–14 – The Word Became Flesh |
| [`genesis-1-1-5.html`](genesis-1-1-5.html) | Genesis 1:1–5 – The Creation of Light |

## Adding a new exegesis

1. Copy any existing exegesis file and rename it (e.g. `matthew-5-3-12.html`).
2. Update the **Open Graph `<meta>` tags** at the top (`og:title`, `og:description`, `og:url`).
3. Replace the Scripture text and exegesis body.
4. Update the `href` of the **Share on Facebook** button with the new page URL.
5. Add a row in `index.html` linking to the new file.
6. Commit and push — GitHub Pages will publish the updated file automatically.

## Facebook sharing

Paste any page URL into a Facebook post or Messenger message. Facebook reads the Open Graph tags and displays:

- The page title as the link headline
- The description as the preview text
- The cover image (`og-cover.png`)

To update the preview after editing a page, use the [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/) to clear the cached preview.

