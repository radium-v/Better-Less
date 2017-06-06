# Better Less
Cross-compatible syntax highlighting for Less

## Project Mission
 * Works with [Atom](https://atom.io/packages/better-less), [Sublime Text](https://packagecontrol.io/packages/Better%20Less), Textmate 2, and [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=radium-v.better-less).
 * Aligns with current CSS features without being overbearing or too relaxed

## Installation

### Atom
Install `better-less` from Atom's Package Manager or the command-line equivalent:

```
$ apm install better-less
```

You may need to disable the `language-less` core package.

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

### Visual Studio Code
Launch VS Code Quick Open (⌘+P), paste the following command, and press enter.
```
ext install better-less
```

## Recommended Color Schemes
For Sublime Text, the [sublime-boxy](https://github.com/ihodev/sublime-boxy) theme and [material-theme](https://github.com/equinusocio/material-theme) work best with all of the extended scopes.

For Visual Studio Code, the Boxy color schemes have been converted and are [available here](https://marketplace.visualstudio.com/items?itemName=trongthanh.theme-boxythemekit).

## Contributing
For the time being, I'm making changes using [PackageDev](https://github.com/SublimeText/PackageDev) to convert the `YAML-tmLanguage` to `tmLanguage`, with some extra messy steps involved when converting it for Atom (using [CSON Converter](https://github.com/idleberg/sublime-cson-converter). Any help, bugs, and suggestions are welcome!
