# Script: easteregg-e621

Opens a random e621 post, when clicked... I'm so sorry

Modified version of [easteregg-pornhub][https://github.com/polybar/polybar-scripts/tree/master/polybar-scripts/easteregg-pornhub] but for e621

WARNING: e621 is NASTY, usually you'd have a blacklist to avoid seeing the worst things the internet offers

## Configuration

Set your browser at the `click-left` option in your module.

## Module

```ini
[module/e621]
type = custom/script
exec = echo "621"
interval = 3600
click-left = "firefox --private-window 'https://e621.net/posts/random'"

format = <label>
format-prefix = "  e"
format-prefix-foreground = #FFFFFF
format-prefix-background = #1F3C67

format-foreground = #fdba31
format-background = #012e56
```

