<div align="center">

<img src="https://getslatewave.com/brand/icon.png" alt="" height="64" align="middle">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://getslatewave.com/brand/wordmark-light.png">
  <img alt="Slatewave" src="https://getslatewave.com/brand/wordmark.png" height="64" align="middle">
</picture>

# Slatewave (Zed)

A dark [Zed](https://zed.dev) theme built around a slate foundation and a teal signature, with sky / rose / purple / amber accents. Part of the [Slatewave family](#slatewave-family) — one palette across editors, terminals, prompts, notes, and more.

> _Slate below, teal above._

![Slatewave preview](docs/preview.png)

</div>

---

## Palette

### Foundation — slate

The editor, sidebar, and panels all live in the slate scale.

| | Hex | Tailwind | Where |
|---|---|---|---|
| ![#0f172a](https://placehold.co/20x20/0f172a/0f172a.png) | `#0f172a` | slate-900 | ink on accent surfaces |
| ![#1e293b](https://placehold.co/20x20/1e293b/1e293b.png) | `#1e293b` | slate-800 | status bar, elevated surfaces, borders |
| ![#21252b](https://placehold.co/20x20/21252b/21252b.png) | slate-chrome | tab bar, panel, title bar (inactive) |
| ![#282c34](https://placehold.co/20x20/282c34/282c34.png) | slate-editor | editor, terminal, active tab |
| ![#334155](https://placehold.co/20x20/334155/334155.png) | `#334155` | slate-700 | selected element, border variant |
| ![#3a3f4c](https://placehold.co/20x20/3a3f4c/3a3f4c.png) | slate-guide | indent guide |
| ![#475569](https://placehold.co/20x20/475569/475569.png) | `#475569` | slate-600 | disabled text, predictive |

### Text — slate (inverse)

| | Hex | Tailwind | Where |
|---|---|---|---|
| ![#64748b](https://placehold.co/20x20/64748b/64748b.png) | `#64748b` | slate-500 | comments, line numbers, placeholders |
| ![#94a3b8](https://placehold.co/20x20/94a3b8/94a3b8.png) | `#94a3b8` | slate-400 | operators, punctuation, muted text |
| ![#cbd5e1](https://placehold.co/20x20/cbd5e1/cbd5e1.png) | `#cbd5e1` | slate-300 | parameters, properties, icons |
| ![#e2e8f0](https://placehold.co/20x20/e2e8f0/e2e8f0.png) | `#e2e8f0` | slate-200 | default foreground |
| ![#f1f5f9](https://placehold.co/20x20/f1f5f9/f1f5f9.png) | `#f1f5f9` | slate-100 | bright ANSI white |

### Signature — teal

The "wave" in Slatewave. Primary accent across the editor and the companion prompt.

| | Hex | Tailwind | Where |
|---|---|---|---|
| ![#0f766e](https://placehold.co/20x20/0f766e/0f766e.png) | `#0f766e` | teal-700 | terminal dim green |
| ![#5eead4](https://placehold.co/20x20/5eead4/5eead4.png) | `#5eead4` | teal-300 | **primary accent** — cursor, active line number, strings, focused border |
| ![#99f6e4](https://placehold.co/20x20/99f6e4/99f6e4.png) | `#99f6e4` | teal-200 | types, classes, interfaces, inline code |

### Accents

| | Hex | Role |
|---|---|---|
| ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) | `#38bdf8` | keywords, tags, info diagnostics, links, search match |
| ![#7dd3fc](https://placehold.co/20x20/7dd3fc/7dd3fc.png) | `#7dd3fc` | functions, JSON/YAML keys, CSS properties |
| ![#b388ff](https://placehold.co/20x20/b388ff/b388ff.png) | `#b388ff` | storage (`const`/`let`/`function`), `this`/`self`, attributes, constructors |
| ![#fb7185](https://placehold.co/20x20/fb7185/fb7185.png) | `#fb7185` | numbers, constants, errors, modified files |
| ![#fbbf24](https://placehold.co/20x20/fbbf24/fbbf24.png) | `#fbbf24` | decorators, escape chars, warnings, renamed files |
| ![#ef5350](https://placehold.co/20x20/ef5350/ef5350.png) | `#ef5350` | deleted files, bright ANSI red |
| ![#ff4500](https://placehold.co/20x20/ff4500/ff4500.png) | `#ff4500` | merge conflicts |

---

## Syntax mapping

| Token | | Color | Style |
|---|---|---|---|
| Comments | ![#64748b](https://placehold.co/20x20/64748b/64748b.png) | `#64748b` | italic |
| Keywords | ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) | `#38bdf8` | — |
| Storage (`const`, `let`, `class`) | ![#b388ff](https://placehold.co/20x20/b388ff/b388ff.png) | `#b388ff` | italic |
| Types | ![#99f6e4](https://placehold.co/20x20/99f6e4/99f6e4.png) | `#99f6e4` | — |
| Functions | ![#7dd3fc](https://placehold.co/20x20/7dd3fc/7dd3fc.png) | `#7dd3fc` | — |
| Strings | ![#5eead4](https://placehold.co/20x20/5eead4/5eead4.png) | `#5eead4` | — |
| Numbers, booleans, constants | ![#fb7185](https://placehold.co/20x20/fb7185/fb7185.png) | `#fb7185` | — |
| Escape sequences | ![#fbbf24](https://placehold.co/20x20/fbbf24/fbbf24.png) | `#fbbf24` | — |
| Variables / `self` / `this` | ![#b388ff](https://placehold.co/20x20/b388ff/b388ff.png) | `#b388ff` | italic |
| Parameters | ![#cbd5e1](https://placehold.co/20x20/cbd5e1/cbd5e1.png) | `#cbd5e1` | italic |
| Operators, punctuation | ![#94a3b8](https://placehold.co/20x20/94a3b8/94a3b8.png) | `#94a3b8` | — |
| Tags | ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) | `#38bdf8` | — |
| Attributes | ![#b388ff](https://placehold.co/20x20/b388ff/b388ff.png) | `#b388ff` | italic |
| Headings / titles | ![#5eead4](https://placehold.co/20x20/5eead4/5eead4.png) | `#5eead4` | bold |
| Links | ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) | `#38bdf8` | — |

---

## Installation

### From a local clone (dev extension)

```sh
git clone https://github.com/kevinlangleyjr/zed-slatewave.git
```

Then in Zed:

1. Open the command palette (`⌘⇧P` / `Ctrl+Shift+P`)
2. Run `zed: install dev extension`
3. Select the cloned `zed-slatewave` directory

Zed will load the extension immediately. Open the theme picker (`⌘K ⌘T` / `Ctrl+K Ctrl+T`) and pick **Slatewave**.

### From the extension registry

_(TBD — pending publish to the Zed extensions registry)_

Once published, open the command palette, run `zed: extensions`, search for **Slatewave**, and click **Install**.

---

## Customize

To override a specific color without forking, edit `~/.config/zed/settings.json` (or `⌘,` → Open settings file):

```jsonc
{
  "theme": "Slatewave",
  "experimental.theme_overrides": {
    "editor.background": "#0a0f1e",
    "syntax": {
      "comment": { "color": "#475569", "font_style": "italic" }
    }
  }
}
```

---

## Slatewave family

One palette. Every tool.

- **Editors** — [VSCode](https://github.com/kevinlangleyjr/vscode-slatewave) · [Neovim](https://github.com/kevinlangleyjr/neovim-slatewave) · [Helix](https://github.com/kevinlangleyjr/helix-slatewave) · [Sublime Text](https://github.com/kevinlangleyjr/sublime-text-slatewave) · [JetBrains](https://github.com/kevinlangleyjr/jetbrains-slatewave)
- **Terminals** — [Alacritty](https://github.com/kevinlangleyjr/alacritty-slatewave) · [Ghostty](https://github.com/kevinlangleyjr/ghostty-slatewave) · [iTerm2](https://github.com/kevinlangleyjr/iterm2-slatewave) · [WezTerm](https://github.com/kevinlangleyjr/wezterm-slatewave) · [Windows Terminal](https://github.com/kevinlangleyjr/windows-terminal-slatewave) · [Kitty](https://github.com/kevinlangleyjr/kitty-slatewave)
- **Prompts** — [Oh My Posh](https://github.com/kevinlangleyjr/slatewave-omp) · [Starship](https://github.com/kevinlangleyjr/starship-slatewave)
- **Multiplexer** — [tmux](https://github.com/kevinlangleyjr/tmux-slatewave)
- **CLI** — [LSD](https://github.com/kevinlangleyjr/lsd-slatewave)
- **Notes** — [Obsidian](https://github.com/kevinlangleyjr/obsidian-slatewave) · [Logseq](https://github.com/kevinlangleyjr/logseq-slatewave) · [MarkEdit](https://github.com/kevinlangleyjr/markedit-slatewave) · [Anytype](https://github.com/kevinlangleyjr/anytype-slatewave)
- **Launchers** — [Alfred](https://github.com/kevinlangleyjr/alfred-slatewave) · [Raycast](https://github.com/kevinlangleyjr/raycast-slatewave)
- **Chat** — [Slack](https://github.com/kevinlangleyjr/slack-slatewave)

See [getslatewave.com](https://getslatewave.com) for the full family.
---

## License

WTFPL — Do What The Fuck You Want To Public License. See [LICENSE](LICENSE).
