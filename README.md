# ljean-eco.github.io

Personal academic website. Plain HTML + CSS, no build step, no JavaScript.
Font: Inter (loaded from Google Fonts).

## Files

```
index.html      → home (bio, contact, affiliations)
research.html   → papers; click each title to expand the abstract
teaching.html   → past teaching
cv.html         → embeds cv.pdf for inline preview + download
style.css       → all styling
cv.pdf          → drop your CV PDF here (replace whenever updated)
photo.jpg       → drop your photo here (referenced from index.html)
```

## To edit text

Open any `.html` file in GitHub via the pencil icon. Edit. Commit.
Site refreshes within 30 seconds.

## To replace the placeholder photo

1. Upload a photo named `photo.jpg` to this folder.
2. In `index.html`, find this line:
   ```html
   <!-- Replace with: <img src="photo.jpg" alt="Léo Jean"> -->
   Photo
   ```
   Replace the word `Photo` with `<img src="photo.jpg" alt="Léo Jean">`.

## To add an abstract

In `research.html`, find the paper block. Replace this line:

```html
<p class="paper-abstract empty"></p>
```

with:

```html
<p class="paper-abstract">Your abstract text here.</p>
```

## To add a paper link

Each paper has a `<a href="#">Latest version (PDF)</a>` line. Replace the `#`
with your Dropbox / SSRN / arXiv URL.

## To add a paper

Copy any `<details class="paper">…</details>` block in `research.html`,
paste it where you want, edit the contents.

## To update the CV

Just replace `cv.pdf` with a new file of the same name. Nothing else changes.

## To add a social link

In `index.html`, find the `<div class="social">` block. Uncomment a line
(remove the `<!--` and `-->`) or add your own:

```html
<a href="https://scholar.google.com/citations?user=YOURID">Google Scholar</a>
```
