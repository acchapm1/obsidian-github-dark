# GitHub Dark Default — Obsidian Theme

GitHub Dark Default color theme for [Obsidian](https://obsidian.md). Colors sourced from [github-vscode-theme](https://github.com/primer/github-vscode-theme) using Primer semantic tokens.

## Installation

### Community theme store (recommended)

1. Open Obsidian → Settings → Appearance → Themes
2. Click **Manage** → search for **GitHub Dark Default**
3. Click **Install and use**

### Manual

1. Download `theme.css` from this repository
2. Copy it to `<your-vault>/.obsidian/themes/GitHub Dark Default/theme.css`
3. Open Settings → Appearance → Themes → select **GitHub Dark Default**

## What's themed

- **App shell** — sidebar, ribbon, tab bar with coral (`#f78166`) active tab border matching VS Code's `tab.activeBorderTop`
- **Editor** — background, gutters, cursor, line highlight, selection, search matches
- **Live Preview & Source mode** — headings, bold, italic, code, links, blockquotes, tags, list markers
- **Reading view** — all markdown elements including tables, blockquotes, code blocks, task checkboxes
- **Callouts** — note, tip, warning, danger, success, quote with GitHub semantic colors
- **Command palette & modals** — overlay background, prompt input, suggestion highlights
- **Graph view** — node and line colors
- **Syntax highlighting** — code blocks styled with GitHub Dark token colors

## Color palette

| Token | Hex | Primer name |
|---|---|---|
| `#0d1117` | editor background | `canvas.default` |
| `#010409` | sidebar / inset bg | `canvas.inset` |
| `#161b22` | overlays / modals | `canvas.overlay` |
| `#21262d` | panel bg | `scale.gray[7]` |
| `#30363d` | borders | `border.default` |
| `#e6edf3` | primary text | `fg.default` |
| `#7d8590` | muted text | `fg.muted` |
| `#1f6feb` | accent / links | `accent.emphasis` |
| `#2f81f7` | cursor / interactive | `accent.fg` |
| `#f78166` | active tab coral | `primer.border.active` |
| `#3fb950` | success | `success.fg` |
| `#d29922` | warning | `attention.fg` |
| `#f85149` | danger | `danger.fg` |

## Contributing

Color values should always be cross-referenced against [`github-vscode-theme/themes/dark-default.json`](https://github.com/primer/github-vscode-theme) as the canonical source.
