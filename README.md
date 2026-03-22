# IBM1970 theme for Visual Studio Code

An IBM and 1970s inspired dark color theme for [Visual Studio Code](https://code.visualstudio.com).

Download and install from the [Extension Marketplace](https://marketplace.visualstudio.com/items?itemName=Andornaut.ibm1970), or launch VS Code *Quick Open* (Ctrl+P), paste the following command, and press enter: `ext install Andornaut.ibm1970`

![screenshot](./screenshots/ibm1970.png)

This color theme uses [Solarized Dark](https://ethanschoonover.com/solarized/) [`tokenColors`](https://github.com/microsoft/vscode/blob/main/extensions/theme-solarized-dark/themes/solarized-dark-color-theme.json).

This color theme is part of the [IBM1970 desktop theme](https://github.com/andornaut/ibm1970-desktop-theme).

## Primary Colors

### UI

| Color | Hex | Usage |
| ----- | --- | ----- |
| ![#33A999](swatches/33a999.svg) Teal | `#33A999` | Accent — links, badges, peek view border |
| ![#006B6B](swatches/006b6b.svg) Dark Teal | `#006B6B` | Editor selection |
| ![#dddccc](swatches/dddccc.svg) Cream | `#dddccc` | Primary foreground |
| ![#d2bb84](swatches/d2bb84.svg) Tan | `#d2bb84` | Modified files |
| ![#9c9977](swatches/9c9977.svg) Khaki | `#9c9977` | Tab backgrounds, scrollbar, gutter headers |
| ![#7c7755](swatches/7c7755.svg) Olive | `#7c7755` | UI borders, status bar, activity bar |
| ![#545040](swatches/545040.svg) Dark Olive | `#545040` | Toolbar active |
| ![#423f2e](swatches/423f2e.svg) Brown | `#423f2e` | Editor background |
| ![#373424](swatches/373424.svg) Dark Brown | `#373424` | Panel backgrounds, inputs |
| ![#24201A](swatches/24201a.svg) Near Black | `#24201A` | Drop backgrounds, shadows |

### Syntax (Solarized Dark)

| Color | Hex | Usage |
| ----- | --- | ----- |
| ![#859900](swatches/859900.svg) Green | `#859900` | Keywords, variable start, library class/type, diff inserted |
| ![#2AA198](swatches/2aa198.svg) Cyan | `#2AA198` | Strings, markup inline |
| ![#268BD2](swatches/268bd2.svg) Blue | `#268BD2` | Variables, functions, tags, headings, diff header |
| ![#6C71C4](swatches/6c71c4.svg) Violet | `#6C71C4` | Inherited class |
| ![#D33682](swatches/d33682.svg) Magenta | `#D33682` | Numbers, markup styling |
| ![#CB4B16](swatches/cb4b16.svg) Orange | `#CB4B16` | Class names, constants, exceptions, diff changed |
| ![#B58900](swatches/b58900.svg) Yellow | `#B58900` | Built-in constants, markup lists |
| ![#DC322F](swatches/dc322f.svg) Red | `#DC322F` | Errors, regexp, invalid, diff deleted |
| ![#93A1A1](swatches/93a1a1.svg) Light Gray | `#93A1A1` | Storage, tag attributes |
| ![#839496](swatches/839496.svg) Base0 | `#839496` | Default foreground |
| ![#586E75](swatches/586e75.svg) Dark Gray | `#586E75` | Comments, tag delimiters |

## Developing

### Testing

1. Press F5 to launch an Extension Development Host window.
1. Select: File > Preferences > Color Theme > IBM 1970

### Publishing

* [Publishing extensions](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)
* [Get a Personal Access Token](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#get-a-personal-access-token)

```bash
nvm use
npm install @vscode/vsce
npx vsce login Andornaut

npx vsce package
npx vsce publish
npx vsce publish patch
npx vsce publish minor
npx vsce publish major
```

### Guides

* [Extension guide: color theme](https://code.visualstudio.com/api/extension-guides/color-theme)
* [Theme color documentation](https://code.visualstudio.com/api/references/theme-color)
