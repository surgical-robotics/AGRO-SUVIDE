# AGRO-SUVIDE — Project Page

Project page for AGRO-SUVIDE, deployed at **https://surgical-robotics.github.io/AGRO-SUVIDE**

The page is currently a **placeholder**: the layout and all section skeletons are in place,
but every figure, video and paragraph still needs to be filled in.

## Status

- [ ] Paper title, author list, venue (`index.html`, hero section + all meta tags)
- [ ] Abstract
- [ ] Research questions
- [ ] Method / pipeline description
- [ ] Teaser image → `static/images/teaser.png`
- [ ] Pipeline figure → `static/images/pipeline.png`
- [ ] Social preview image (1200×630) → `static/images/social_preview.png`
- [ ] Favicon → `static/images/favicon.ico`
- [ ] Demo videos → `static/videos/*.mp4`
- [ ] Paper PDF → `static/pdfs/`
- [ ] Paper / arXiv / code links in the hero section
- [ ] BibTeX entry

## Adding media

Every placeholder box in `index.html` has a commented-out `<img>` or `<video>` tag
directly above it showing the exact markup to use. Drop the file into the right
`static/` folder, then swap the `<div class="media-placeholder">` for that tag.

Rows are Bulma `columns` blocks — add or remove `<div class="column is-one-third">`
(or `is-half`) children to change how many items sit side by side.

Keep videos small: compress before committing, and use YouTube for anything over ~10 MB.
Compress images with [TinyPNG](https://tinypng.com).

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

GitHub Pages serves `master` from the repo root. `.nojekyll` is present so that
`static/` is published as-is.

## Acknowledgments

Built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template),
adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
