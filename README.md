# Hammad Ahmad Warsi — Portfolio Site

A fast, dependency-free personal portfolio in a SINGLE self-contained HTML file.
No build tools, no frameworks, no backend, no trackers — and no separate CSS/JS
files that can fail to load.

## Folder structure

```
index.html                        ← everything: content, styles, script
assets/Hammad_Ahmad_Warsi_CV.pdf  ← the downloadable CV (replace to update)
```

## Editing content

- Open index.html — every section has a ==== banner comment.
- Add a case study: copy a whole <article class="case"> block and edit the
  text (update its "Entry 0X" tag number too).
- Retheme: change the CSS variables at the top of the <style> block
  (--accent is the single accent color).
- Social links: in the footer, replace the # placeholders with real URLs.
- Update the CV: replace assets/Hammad_Ahmad_Warsi_CV.pdf keeping the name.

## Viewing locally

Just double-click index.html. Everything works from a single file — only the
CV download needs the assets folder sitting next to it.

## Deploying (all free)

### GitHub Pages
1. Create a repo named  yourusername.github.io
2. Upload index.html and the assets folder to the repo root.
3. Settings → Pages → deploy from main branch, root folder.

### Netlify
Drag and drop this whole folder onto https://app.netlify.com/drop

### Vercel
Import the repo at https://vercel.com/new, preset "Other", no build command.

## Optional contact form later

The site uses a mailto: link (no backend needed). For a real form, create one
free at https://formspree.io and paste their <form> snippet into the Contact
section.
