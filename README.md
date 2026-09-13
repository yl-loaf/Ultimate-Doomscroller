# Ultimate Doomscroller 🔥

A completely unserious joke website that lets you run **up to 10 YouTube Shorts players** at once in a 2×5 grid.

## Features

- 2 rows × 5 columns layout (choose 1–10 windows)
- Custom global playback speed (0.25× – 2×)
- **Spacebar** → advance to the next Short in **every** window
- **Ctrl / ⌘ + 1–9 / 0** → advance only that specific window
- Paste any Shorts URL, watch URL, or 11-character video ID into a window and hit Load
- Play / Pause / Mute / Unmute all
- Pure static HTML + CSS + JS — perfect for **GitHub Pages**

## How “Next Short” works

YouTube does not expose the algorithmic Shorts feed to embeds, so each window simply cycles through a built-in list of public short-form video IDs.  
You can override any window with your own Shorts at any time.

## Deploy to GitHub Pages

1. Create a new repository (or use an existing one).
2. Upload the contents of this folder (`index.html` is the only required file).
3. Go to **Settings → Pages**.
4. Under **Source**, choose the branch (usually `main`) and `/ (root)`.
5. Save. Your site will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`.

That’s it. No build step, no backend, no API keys.

## Keyboard cheatsheet

| Shortcut              | Action                          |
|-----------------------|---------------------------------|
| `Space`               | Next Short — all windows        |
| `Ctrl/⌘ + 1` … `9`    | Next Short — window 1–9         |
| `Ctrl/⌘ + 0`          | Next Short — window 10          |

## Disclaimer

This is a joke / chaos toy.  
Not affiliated with YouTube or Google.  
Please be nice to the algorithm (and your CPU/GPU).
