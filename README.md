# Farhood Rismanchian — Academic Portfolio Site

A static academic website inspired by the [al-folio](https://github.com/ZhipengHe/al-folio) theme's clean,
whitespace design — built as plain HTML/CSS with **no build step, no Jekyll/Ruby required**. Just push the
files and GitHub Pages will serve them as-is.

## Pages

- `index.html` — About / bio, selected publications, skills
- `cv.html` — Full CV (education, experience, grants, awards, presentations)
- `publications.html` — Full publication list (journal articles, conference papers, preprints, technical reports)
- `projects.html` — Project portfolio
- `assets/css/style.css` — Shared stylesheet

## Editing content

Every page is plain HTML — open any `.html` file in a text editor and edit the text directly. Shared look
and spacing lives in `assets/css/style.css`.

## Photo

`index.html` already uses your photo at `assets/img/Farhood-photo.jpg`. To swap it for a different image,
add the new file to `assets/img/` and update the `src` on the `<img class="avatar" ...>` line in `index.html`.

## Deploying to GitHub Pages

See the deployment guide provided alongside this folder.
