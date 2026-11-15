# Osdy · IA para Devs

An interactive Spanish-language course about AI for developers, with 26 slides and hands-on demos of tokens, context, temperature, caching, agents, MCP, and RAG.

**[Open the course](https://osdyortiz.github.io/cursos-osdy/)**

## Run locally

Open `index.html` in a modern browser, or serve the project with Python:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Visit <http://localhost:8000>.

## Controls

- Use the arrow buttons, left/right arrow keys, or swipe to change slides.
- Press `I` to open the slide index.
- Press `V` to toggle narration and `M` to toggle music.
- Interact with the examples directly in the slides.

Narration depends on the browser's available Spanish voices. Audio starts after an interaction. Google Fonts requires an internet connection; system fonts are used as a fallback.

## Publish updates

GitHub Pages serves the repository root from the `main` branch. Update `index.html`, commit the change, and push to `main`; GitHub deploys the updated site automatically.

The course has no build step, package installation, backend, or API credentials. `.nojekyll` keeps publication static. Local tooling, task tracking, and environment files are excluded by `.gitignore`.
