# Rosé Pine Moon for tut

A [Rosé Pine Moon](https://rosepinetheme.com/palette/ingredients/) theme for
[tut](https://github.com/RasmusLindroth/tut), the TUI Mastodon client.

> Rosé Pine Moon is the dimmed, slightly warmer variant of Rosé Pine — soft
> contrast, easy on the eyes for long timeline sessions.

## Install

1. Drop the theme into tut's themes directory:

   ```sh
   mkdir -p ~/.config/tut/themes
   curl -o ~/.config/tut/themes/rose-pine-moon.toml \
     https://raw.githubusercontent.com/Derrekito/tut-rose-pine-moon/main/rose-pine-moon.toml
   ```

   Or clone and copy:

   ```sh
   git clone https://github.com/Derrekito/tut-rose-pine-moon.git
   cp tut-rose-pine-moon/rose-pine-moon.toml ~/.config/tut/themes/
   ```

2. Point tut at it in `~/.config/tut/config.toml`:

   ```toml
   theme="rose-pine-moon"
   ```

3. Restart tut.

## Palette mapping

This is a **complete** port: every one of tut's 28 theme slots is set
explicitly to a Rosé Pine Moon role — nothing falls back to tut's built-in
(Monokai-ish) defaults.

| tut slot                            | Rosé Pine Moon role | Hex       |
|-------------------------------------|---------------------|-----------|
| `background`                        | Base                | `#232136` |
| `text`                              | Text                | `#e0def4` |
| `subtle`                            | Muted               | `#6e6a86` |
| `warning-text`                      | Love                | `#eb6f92` |
| `text-special-one`                  | Foam                | `#9ccfd8` |
| `text-special-two`                  | Iris                | `#c4a7e7` |
| `top-bar-background`                | Overlay             | `#393552` |
| `top-bar-text`                      | Text                | `#e0def4` |
| `status-bar-background`             | Surface             | `#2a273f` |
| `status-bar-text`                   | Subtle              | `#908caa` |
| `status-bar-view-background`        | Pine                | `#3e8fb0` |
| `status-bar-view-text`              | Text                | `#e0def4` |
| `list-selected-background`          | Highlight Med       | `#44415a` |
| `list-selected-text`                | Text                | `#e0def4` |
| `list-selected-inactive-background` | Highlight Low       | `#2a283e` |
| `list-selected-inactive-text`       | Subtle              | `#908caa` |
| `controls-text`                     | Subtle              | `#908caa` |
| `controls-highlight`                | Iris                | `#c4a7e7` |
| `autocomplete-background`           | Surface             | `#2a273f` |
| `autocomplete-text`                 | Text                | `#e0def4` |
| `autocomplete-selected-background`  | Highlight Med       | `#44415a` |
| `autocomplete-selected-text`        | Text                | `#e0def4` |
| `button-color-one`                  | Iris                | `#c4a7e7` |
| `button-color-two`                  | Base                | `#232136` |
| `timeline-name-background`          | Overlay             | `#393552` |
| `timeline-name-text`                | Rose                | `#ea9a97` |
| `icon-color`                        | Foam                | `#9ccfd8` |
| `command-text`                      | Gold                | `#f6c177` |

## Credits

- Palette: [Rosé Pine](https://rosepinetheme.com/) by the Rosé Pine team.
- Client: [tut](https://github.com/RasmusLindroth/tut) by Rasmus Lindroth.

## License

MIT — see [LICENSE](LICENSE).
