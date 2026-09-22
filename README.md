# TLMHoang-AI.github.io

Personal AI Engineer portfolio. Built with plain HTML/CSS/JS so it stays easy to edit.

## Edit content
- `index.html`: text, links, cards, publications.
- `styles.css`: layout, colors and responsive design.
- `script.js`: optional interactions.
- `assets/images/`: project images.
- `assets/videos/`: demo videos.
- `assets/docs/`: CV.

## Add an image
Replace a project placeholder with:
```html
<img class="media" src="assets/images/project.jpg" alt="Project preview">
```

## Add a video
```html
<video class="media" controls muted loop playsinline>
  <source src="assets/videos/demo.mp4" type="video/mp4">
</video>
```

## Add a project
Copy one complete `<article class="card">...</article>` inside `.project-grid` and edit its content.

## Local preview
```bash
python -m http.server 8000
```

## GitHub Pages
This repository is named for GitHub user Pages: `TLMHoang-AI.github.io`.
