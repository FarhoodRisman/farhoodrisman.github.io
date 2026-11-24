# Farhood Rismanchian — Personal Site

A static academic website inspired by the [al-folio](https://github.com/ZhipengHe/al-folio) theme's clean,
whitespace design — built as plain HTML/CSS with **no build step, no Jekyll/Ruby required**. Just push the
files and GitHub Pages will serve them as-is.

## Pages

- `index.html` — About: bio, current work, selected projects and publications
- `projects.html` — Applied and research projects
- `publications.html` — Full publication list
- `teaching.html` — Teaching at the University of Winnipeg and earlier
- `cv.html` — Full CV
- `assets/css/style.css` — Shared stylesheet (sidebar layout, Inter, maroon accent)

## Editing content

Every page is plain HTML — open any `.html` file in a text editor and edit the text directly. Shared look
and spacing lives in `assets/css/style.css`.

## Photo

`index.html` already uses your photo at `assets/img/Farhood-photo.jpg`. To swap it for a different image,
add the new file to `assets/img/` and update the `src` on the `<img class="avatar" ...>` line in `index.html`.

## Deploying to GitHub Pages

See the deployment guide provided alongside this folder.
