<h1 align="center"><img src="/logo/logotype-vertical.png" width="50%"></h1>

[![Maintainability](https://api.codeclimate.com/v1/badges/dd17b74cb4a19b100fdb/maintainability)](https://codeclimate.com/github/bertdida/DeclareThatColor/maintainability)
[![codebeat badge](https://codebeat.co/badges/cf67c947-b827-4301-9605-7c3b275b090a)](https://codebeat.co/projects/github-com-bertdida-declarethatcolor-master)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/bertdida/DeclareThatColor.svg)](https://github.com/bertdida/DeclareThatColor/releases)
[![MIT License](https://img.shields.io/github/license/bertdida/DeclareThatColor.svg)](https://github.com/bertdida/DeclareThatColor/blob/master/LICENSE)

DeclareThatColor is a Sublime Text 3 plugin that aims to help developers declare CSS hex codes to their human-readable color names. It does this by using the ported JavaScript library from Chirag Mehta's [name that color](http://chir.ag/projects/name-that-color/) tool.

![usage](img/usage.gif)

## Installation

Download [Package Control](https://packagecontrol.io/) and use the _Package Control: Install Package_ command from the command palette. Using Package Control ensures DeclareThatColor will stay up to date automatically.

## Usage

From the Sublime Text's main menu click on:
- **Edit** → **Declare That Color** to declare hex codes
- **Edit** → **Undeclare That Color** to revert declarations

### Key bindings

DeclareThatColor doesn't ship with default key bindings, use the template below to set up your own.

```json
[
  { "keys": ["Your shortcut"], "command": "declare_that_color" },
  { "keys": ["Your shortcut"], "command": "undeclare_that_color" }
]
```

## Settings

For a comprehensive list of settings navigate to **Preferences** → **Package Settings** → **DeclareThatColor** → **Settings - Default** or go to [DeclareThatColor/declare_that_color.sublime-settings](https://github.com/bertdida/DeclareThatColor/blob/master/declare_that_color.sublime-settings). To avoid your changes from being overwritten by updates, make sure all of your edits are saved to **Settings – User**.

## Contribute

If you have any problem, idea or suggestion, feel free to create issues and pull requests on [GitHub](https://github.com/bertdida/DeclareThatColor).

## License

Distributed under the MIT license. See [LICENSE](https://github.com/bertdida/DeclareThatColor/blob/master/LICENSE) for more information.

## Author

Herbert Verdida / [@bertdida](https://twitter.com/bertdida)

## Credits

1. Chirag Mehta - for creating the [name that color](http://chir.ag/projects/name-that-color/) tool and for open sourcing its [JavaScript code](http://chir.ag/projects/ntc/ntc.js)
2. [@Tobaloidee](https://github.com/Tobaloidee) - for contributing his logo design