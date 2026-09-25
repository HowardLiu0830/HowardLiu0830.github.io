# Personal website — Yaowenqi (Howard) Liu

Plain static HTML, no build step. Double-click `index.html` to view it;
edit `index.html` in any text editor and refresh the browser.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole page: bio, Education, Publications |
| `stylesheet.css` | All styling (fonts, colors, layout, badges) |
| `images/profile.png` | Profile photo (currently a blank white placeholder) |
| `images/favicon.*` | Tab icon (white circle) |

## Adding a paper

Copy one `<div class="pub">` block in `index.html` and edit it. Order on the page
is manual — first-author papers on top, then other accepted papers, preprints last.

Badge options:

```html
<span class="badge badge--accepted">ICLR 2026</span>   <!-- blue: accepted -->
<span class="badge badge--preprint">Preprint</span>    <!-- grey -->
<span class="badge badge--award">Oral</span>           <!-- gold -->
```

To add a thumbnail on the left of an entry, put an image in `images/` and add
this as the first child of the `<div class="pub">`:

```html
<div class="pub__thumb"><img src="images/paper.png" alt=""></div>
```

## Publishing

Nothing is online until this folder is pushed to a GitHub repository named
`HowardLiu0830.github.io` with GitHub Pages enabled.
