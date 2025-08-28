# Cyberdyne

A dark VS Code theme adapted from the **Cyberdyne** palette in the Ghostty terminal emulator. High-contrast neon accents on a deep indigo background, with full semantic token coverage and tuned highlights.

---

## Install

- **From VS Code:** Open **Extensions** → search **Cyberdyne** → Install.
- **From VSIX:** `Extensions` → `…` menu → **Install from VSIX…**

---

## Palette (highlights)

| Role        | Color    |
|-------------|----------|
| Background  | `#151144` |
| Foreground  | `#00ff92` |
| Selection   | `#454d96` |
| Cursor      | `#00ff9c` |

**Terminal ANSI** (0–15)

`#080808`, `#ff8373`, `#00c172`, `#d2a700`, `#0071cf`, `#ff90fe`, `#6bffdd`, `#f1f1f1`, `#2e2e2e`, `#ffc4be`, `#d6fcba`, `#fffed5`, `#c2e3ff`, `#ffb2fe`, `#e6e7fe`, `#ffffff`

---

## Recommended settings

```jsonc
"editor.bracketPairColorization.enabled": true,
"editor.guides.bracketPairs": true,
"editor.cursorSmoothCaretAnimation": "on",
"workbench.list.smoothScrolling": true
````

---

## Accessibility

Cyberdyne aims for readable contrast on normal text and UI, with translucent highlights to avoid obscuring content. If anything looks muddy on your display, please open an issue with a screenshot and your OS/VS Code version.

---

## Contributing

Issues and PRs welcome!

1. Clone the repo and open it in VS Code
2. Press **F5** to launch the Extension Development Host
3. Test across TS/JS, Python, HTML/CSS, Markdown, JSON
4. Use **Developer: Inspect Editor Tokens and Scopes** (and the Semantic variant) to propose improvements

---

## Attribution

Portions of the base color palette are adapted from the Ghostty terminal emulator, used under the MIT License.
Ghostty © Mitchell Hashimoto and contributors.

---

## License

* Theme code: MIT (see [LICENSE](./LICENSE))
* Third-party: Ghostty MIT (see [ATTRIBUTION.md](./ATTRIBUTION.md)
