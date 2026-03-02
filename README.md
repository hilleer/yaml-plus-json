# yaml-plus-json

Website for the **YAML Plus JSON** editor extension — hosted on [GitHub Pages](https://hilleer.github.io/yaml-plus-json).

## About

This repository contains the source for the static website that introduces the YAML Plus JSON extension and links users to install it from the VS Code Marketplace.

The extension lets you effortlessly convert files and selections back and forth between YAML and JSON, directly inside your editor.

## Extension

| Editor | Link |
|--------|------|
| Visual Studio Code | [Install from Marketplace](https://marketplace.visualstudio.com/items?itemName=hilleer.yaml-plus-json) |

Source code for the VS Code extension lives at [hilleer/vscode-yaml-plus-json](https://github.com/hilleer/vscode-yaml-plus-json).

## Development

The site is a single self-contained `index.html` file with inline CSS — no build step, no dependencies.

To preview it locally, serve the repository root with any static file server, for example:

```bash
npx serve .
# or
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

## GitHub Pages

The site is served from the `main` branch root directory via [GitHub Pages](https://docs.github.com/en/pages/quickstart).

To enable GitHub Pages for this repository:

1. Go to **Settings → Pages** in the repository.
2. Under **Branch**, select `main` and the `/ (root)` folder.
3. Click **Save**.

The site will be available at `https://hilleer.github.io/yaml-plus-json`.
