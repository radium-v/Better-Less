# Better Less

Cross-compatible syntax highlighting for Less

## Project Mission

- Works with [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=radium-v.better-less), [Sublime Text](https://packagecontrol.io/packages/Better%20Less), and Textmate 2.
- Aligns with current CSS features without being overbearing or too relaxed

## Installation

### Visual Studio Code

Launch VS Code Quick Open (⌘+P), paste the following command, and press enter.

```
ext install better-less
```

### Sublime Text

Use `Package Control` and install `Better Less`. Alternatively, you can clone this project and put it in your Sublime Text packages directory.

### TextMate 2

Clone the repository to the Bundles directory and add the `.tmbundle` extension:

```
$ cd ~/Library/Application\ Support/TextMate/Bundles
$ git clone git@github.com:radium-v/Better-Less.git Better-Less.tmbundle
```

Alternatively, you can clone the repository and symlink to it in your Bundles directory:

```
$ git clone git@github.com:radium-v/Better-Less.git
$ ln -s Better-Less/ ~/Library/Application\ Support/Textmate/Bundles/better-less.tmbundle
```

## Recommended Color Schemes

Some themes are more suitable than others for the extended scopes provided by Better Less. Built-in themes tend to reuse the same colors for different scopes. For instance, many color schemes use the same color for variables and selectors, without taking the prefix into account (`.`, `#`, `@`, etc.). This can make it difficult to scan your code for specific tokens.

I've found that the [Oceanic Next Color Scheme](https://github.com/voronianski/oceanic-next-color-scheme) works well. I primarily use the [Boxy Theme Kit](https://marketplace.visualstudio.com/items?itemName=trongthanh.theme-boxythemekit) for Visual Studio Code, which is adapted from the original Boxy Theme for Sublime Text.

## Contributing

For the time being, I'm making changes using [PackageDev](https://github.com/SublimeText/PackageDev) and [Textmate Languages](https://marketplace.visualstudio.com/items?itemName=pedro-w.tmlanguage) to convert the `YAML-tmLanguage` to `tmLanguage`. Any help, bugs, and suggestions are welcome!
