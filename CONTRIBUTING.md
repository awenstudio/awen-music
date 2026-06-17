# Contributing to Awen Music

Thanks for your interest in improving Awen Music! This is an actively
maintained, early-stage open-source project and contributions are welcome.

## Ways to contribute

- **Report bugs / request features** — open an [issue](https://github.com/awenstudio/awen-music/issues).
- **Add matrix data** — new cells for Environment / Nature / Time / Mood /
  Instrument / Style / BPM live in `src/data.js`.
- **Improve prompts** — the offline prompt/album engine also lives in `src/data.js`.
- **Translations** — all UI copy lives in `src/i18n.js` (currently 中文 / EN).
- **Docs** — improvements to `README.md` and `HANDOFF.md` are always helpful.

## Running it locally

No build step, no install. From the `src/` folder:

```bash
python3 -m http.server 8000
# open http://localhost:8000/Awen%20Study%20Matrix.html
```

Opening the HTML via `file://` will not load the `.jsx` modules — use a local server.

## Before opening a pull request

- Keep the existing code style (the `.jsx` files are plain Babel-in-browser JSX,
  no bundler).
- For anything larger than a small fix, please **open an issue first** so we can
  agree on the approach.
- Describe what you changed and how you tested it.

## Code of conduct

Be respectful and constructive. This is a small community project built to help
students and creators.
