# Ghostty configuration

Personal [Ghostty](https://ghostty.org/) terminal configuration.

## Restore on macOS

```sh
git clone git@github.com:dincorvaia-nc/ghostty.git /tmp/ghostty-config
mkdir -p "$HOME/Library/Application Support/com.mitchellh.ghostty"
cp /tmp/ghostty-config/config.ghostty "$HOME/Library/Application Support/com.mitchellh.ghostty/config.ghostty"
```

Restart Ghostty after restoring the file. Application caches, preferences,
logs, and binaries are intentionally not tracked.
