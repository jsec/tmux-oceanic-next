# tmux-oceanic-next

A tmux color scheme based on the [oceanic-next](https://github.com/mhartington/oceanic-next) color palette.

Currently this is only tested on systems with 24-bit color support. Making the theme degrade gracefully for 8-bit palettes is in the works.

## Screenshot

![tmux_oceanic_next](https://github.com/jsec/tmux-oceanic-next/raw/master/screenshots/oceanic_tmux.png)

## Installation

Install with TPM:

```bash
set -g @plugin 'jsec/tmux-oceanic-next'
```

or add to your `tmux.conf` file:

```bash
source-file "/path/to/repository/tmux-oceanic-next.conf"
```

## Roadmap

- Clean up theme
- Add support for 256 color palettes.

## License

MIT
