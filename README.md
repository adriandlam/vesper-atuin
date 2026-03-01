# Vesper for atuin

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Peppermint and orange flavored dark theme for [atuin](https://atuin.sh) (shell history). Port of the [Vesper](https://github.com/raunofreiberg/vesper) VS Code theme by [Rauno Freiberg](https://github.com/raunofreiberg).

## Colors

| Role | Color | Hex |
|------|-------|-----|
| Base | White | `#ffffff` |
| AlertInfo | Aqua | `#99ffe4` |
| AlertWarn | Orange | `#ffc799` |
| Important | Orange | `#ffc799` |
| AlertError | Red | `#ff8080` |
| Guidance | Gray | `#a0a0a0` |
| Annotation | Dim gray | `#505050` |

## Installation

1. Copy `vesper.toml` to your atuin themes directory:

```sh
mkdir -p ~/.config/atuin/themes
cp vesper.toml ~/.config/atuin/themes/vesper.toml
```

2. Add to your `~/.config/atuin/config.toml`:

```toml
[theme]
name = "vesper"
```

## Credits

Based on the original [Vesper](https://github.com/raunofreiberg/vesper) VS Code theme by [Rauno Freiberg](https://github.com/raunofreiberg).

## License

[MIT](LICENSE)
