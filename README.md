# NCU Three-Year Board Presentation

An 11-slide HTML companion presentation for the North Central University Executive Committee Report.

## Privacy

This repository is intended to remain private until the owner deliberately changes its visibility. The presentation contains enrollment, financial, partnership, and Board-planning information.

## Viewing locally

Serve the repository directory with any static web server, then open `index.html`. For example:

```powershell
python -m http.server 8765 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8765/`.

## Publishing with GitHub Pages

The included GitHub Actions workflow deploys the presentation from `main`. When the repository is made public, confirm **Settings → Pages → Build and deployment → Source: GitHub Actions**, then run the workflow if GitHub does not start it automatically.

Expected address after publication:

`https://<github-username>.github.io/ncu-three-year-board-presentation/`

