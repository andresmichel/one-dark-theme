# Sublime Text - One Dark theme
A dark Sublime Text theme based on [Atom One Dark UI theme](https://github.com/atom/one-dark-ui).

![Sublime One dark theme](http://i.imgur.com/sJB4gjm.png)
> Color scheme by [IceTimux](https://github.com/IceTimux/one-dark-sublime-text-3-color-scheme)

## Installation

### Easy
You can install this awesome theme through the [Package Control](https://packagecontrol.io/installation).

1. Press <kbd>cmd/ctrl</kbd> + <kbd>shift</kbd> + <kbd>p</kbd> to open the command palette.
2. Type `Install Package` and press enter. Then search for `Theme - One Dark`.

### Manual
1. Download the [latest release](https://github.com/andresmichel/one-dark-theme/releases/latest), extract and rename the directory to `Theme - One Dark`.
2. Move the directory inside your packages directory, `Preferences` > `Browse packages`.

## Activation
Open your preferences `Preferences` > `Setting - User` and add this lines:

```json
"theme": "One Dark.sublime-theme",
"color_scheme": "Packages/Theme - One Dark/One Dark.tmTheme",
```

## Recommended settings
```json
"line_padding_bottom": 1,
"line_padding_top": 1,
"tree_animation_enabled": false,
"indent_guide_options" : [ "draw_normal", "draw_active" ],
"margin": 0,
```

## Optional settings
```json
"show_scroll_tabs": true,
"show_tabs_dropdown": true,
```
