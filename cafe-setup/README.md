# Cafe Coding setup

Dark graphite ground, one mint accent, Geist / Geist Mono. Matches the
"Cafe Coding Screen" design.

| Role | Hex |
| --- | --- |
| Background | `#0B0D10` |
| Terminal / panel | `#090B0E` |
| Border | `#1B1F26` |
| Accent (cursor, `$`, active tab) | `#6EE7B7` |
| Keywords | `#B4A7FF` |
| Strings / numbers | `#F2C078` |
| Comments | `#5B6270` |

## VS Code

1. Install the Geist and Geist Mono fonts.
2. Merge `vscode-settings.jsonc` into your user `settings.json`.

## Terminal prompt

1. Install [Starship](https://starship.rs).
2. Copy `starship.toml` to `~/.config/starship.toml`.
3. Add `eval "$(starship init zsh)"` to your shell rc (bash/fish: swap the name).
4. Set your terminal app's font to Geist Mono and its background to `#090B0E`.
