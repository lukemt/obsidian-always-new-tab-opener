# Obsidian Opener: New Tab by Default

**Obsidian Opener** ensures every markdown note opens in its own tab and routes PDFs (or other supported file types) to your OS’s default application.

## Features

- Opens markdown notes in new tabs; switches to an existing tab if already open.
- Opens PDFs or other supported formats with your default system app.
- Fully compatible with all plugins—patches Obsidian’s built‑in `openFile()` function under the hood.

## Installation

### Recommended
1. Install [BRAT](https://github.com/TfTHacker/obsidian42-brat).
2. Use BRAT to install from this link: [aidan-gibson/obsidian-opener](https://github.com/aidan-gibson/obsidian-opener).
3. Enable the plugin under **Settings → Community Plugins**.

### From Source
```sh
cd {your vault}/.obsidian/plugins
git clone https://github.com/aidan-gibson/obsidian-opener
npm install
npm run build
```

## Usage

- Click internal links or search results to open notes in new tabs.
- Use the **Open Graph View in new tab** command (reassignable under **Settings → Hotkeys**) to open graph views.

## Known Limitations

- If a note is open in another Obsidian window (minimized), the plugin cannot unminimize that window.
- Graph view via context menu still uses a different API; use the dedicated command above.

## Contributing & License

Contributions welcome! Please open issues or pull requests on GitHub. Licensed under the [MIT License](LICENSE).
