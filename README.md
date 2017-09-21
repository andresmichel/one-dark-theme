# One Dark theme
A dark Sublime Text theme based on [Atom One Dark UI theme](https://github.com/atom/one-dark-ui).

![Sublime Text - One Dark theme](http://i.imgur.com/DyTXxc5.png)
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
"color_scheme": "Packages/Theme - One Dark/One Dark.tmTheme",
"theme": "One Dark.sublime-theme",
"one_dark_sublime_text_2": true // Only for Sublime Text 2
```

### Recommended settings
```json
"animation_enabled": false,
"caret_extra_bottom": 1,
"caret_extra_top": 2,
"caret_extra_width": 1,
"caret_style": "blink",
"draw_white_space": "none",
"ensure_newline_at_eof_on_save": true,
"highlight_line": true,
"line_padding_bottom": 1,
"line_padding_top": 2,
"margin": 0,
"match_selection": false,
"tree_animation_enabled": false,
"scroll_past_end": false,
"show_definitions": false
```

### Optional settings
```json
"one_dark_native_title_bar": true, // Only for Mac & Sublime Text 3 >= build 3127
"one_dark_show_scroll_tabs": true, // Only for Sublime Text 3
"one_dark_show_tabs_dropdown": true // Only for Sublime Text 3
```
