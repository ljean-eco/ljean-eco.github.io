# leojean.github.io

Personal academic website. Plain HTML + CSS, no build step, no JavaScript.

## Files

```
index.html      → home page (bio, contact, affiliations)
research.html   → working papers and work in progress
teaching.html   → courses taught
cv.html         → embeds cv.pdf as a download + inline preview
style.css       → all styling
cv.pdf          → upload your latest CV PDF here (replace as needed)
photo.jpg       → upload your photo here (referenced from index.html)
```

## To edit text

Open any `.html` file in any text editor (or GitHub's web pencil icon).
Find the section you want to change, edit, save. Commit. Done.

## To replace the placeholder photo

1. Add a photo named `photo.jpg` (or any name) to this folder.
2. In `index.html`, find the line:
   ```html
   <!-- Replace this with: <img src="photo.jpg" alt="Léo Jean"> -->
   photo
   ```
   Replace the word `photo` with `<img src="photo.jpg" alt="Léo Jean">`.
   Delete the comment line if you want.

## To update the CV

Just replace `cv.pdf` with a new file of the same name. Nothing else changes.

## To add a paper

Copy one of the `<div class="paper">…</div>` blocks in `research.html`,
paste it where you want, edit the contents.

## To add a social link

In `index.html`, find the `<div class="social">` block. Uncomment a line
and replace the URL/text, or add your own:

```html
<a href="https://scholar.google.com/citations?user=YOURID">google scholar</a>
```

## Fonts

EB Garamond (body) + Inter Tight (nav/headings), loaded from Google Fonts.
No installation needed.
