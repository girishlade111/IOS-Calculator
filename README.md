# iOS Style Calculator

A pixel-faithful recreation of the iPhone's stock calculator app, built as a lightweight web page. Dark iOS-style keypad, orange operator keys, and smooth button press feedback — all in a single HTML file.

Built by Girish Lade — https://ladestack.in

## Features

- Authentic iOS calculator look and feel — dark keys, orange operators, rounded layout
- Full basic arithmetic: add, subtract, multiply, divide, plus %, +/-, and decimal support
- AC (all-clear) and live display updates
- Button press animations mimicking the native iOS experience
- Single-file app — no dependencies, works offline

## Tech stack

- HTML5, CSS3, vanilla JavaScript
- Single `index.html` (~17 KB) — no bundler, no framework, no build step

## Quick start

No install needed — just open the file:

```bash
# open in browser
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows

# or serve locally
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Project structure

```
IOS-Calculator/
├── index.html    # the entire calculator: markup, iOS-style CSS, logic
├── LICENSE       # license terms
└── README.md     # this file
```

## Deploy notes

Static site — host on GitHub Pages, Cloudflare Pages, Netlify, or any static host with zero configuration. This repo is deployed via GitHub Pages.

## Customizing

Edit `index.html` directly to tweak the theme, add scientific functions, or restyle the keypad. Changes go live on the next push — no build step.

## License

See [LICENSE](LICENSE).
