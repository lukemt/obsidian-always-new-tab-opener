# Obsidian Opener: New Tab by Default

**Obsidian Opener** ensures every document opens in its own tab. Much like an IDE.

## Features

- Always opens markdown notes in new tabs; switches to an existing tab if already open.
- When cmd/ctrl is pressed, it will open the Link in a new tab, even if the file is already open in another tab.
- If desired: Open PDFs or other supported formats with your default system app.
- Battle-tested with other plugins — patches Obsidian’s built‑in `openFile()` function under the hood.
- If you do find an issue, please open an issue on GitHub [here](https://github.com/lukemt/obsidian-opener/issues).

## Installation

### Recommended
1. Install [BRAT](https://github.com/TfTHacker/obsidian42-brat).
2. Use BRAT to install from this link: [lukemt/obsidian-opener](https://github.com/lukemt/obsidian-opener).
3. Enable the plugin under **Settings → Community Plugins**.

### From Source
```sh
cd {your vault}/.obsidian/plugins
git clone https://github.com/lukemt/obsidian-opener
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
