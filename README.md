# Engineering Wiki

Our team wiki, stored as Markdown in this repo and published with GitHub Pages.

- **Browse on GitHub:** open the [`docs/`](docs/index.md) folder. Every page renders directly in the GitHub UI.
- **Browse the site:** `https://ORG.github.io/engineering-wiki/` (or your GHE Pages URL).

## Quick start

```bash
pip install -r requirements.txt
mkdocs serve          # live preview at http://127.0.0.1:8000
```

## Layout

```
engineering-wiki/
├── docs/                      # all wiki pages (Markdown)
│   ├── index.md               # home page
│   ├── getting-started/
│   ├── migration/
│   ├── publishing/
│   └── assets/                # images and attachments
├── mkdocs.yml                 # site config + navigation
├── requirements.txt           # build dependencies
└── .github/
    ├── CODEOWNERS             # who reviews wiki changes
    ├── pull_request_template.md
    └── workflows/publish-wiki.yml   # builds and deploys to Pages
```

## Contributing

See [How to contribute](docs/getting-started/contributing.md).
