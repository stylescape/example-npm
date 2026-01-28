<div align="right">

[![GitHub License](https://img.shields.io/github/license/stylescape/example-npm?style=flat-square&logo=readthedocs&logoColor=FFFFFF&label=&labelColor=%23041B26&color=%23041B26&link=LICENSE)](https://github.com/stylescape/example-npm/blob/main/LICENSE)
[![devContainer](https://img.shields.io/badge/devContainer-23041B26?style=flat-square&logo=Docker&logoColor=%23FFFFFF&labelColor=%23041B26&color=%23041B26)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/stylescape/example-npm)
[![StackBlitz](https://img.shields.io/badge/StackBlitz-23041B26?style=flat-square&logo=StackBlitz&logoColor=%23FFFFFF&labelColor=%23041B26&color=%23041B26)](https://stackblitz.com/github/stylescape/example-npm/tree/main?file=src%2Findex.html)

</div>

<p align="center">
    <img src="https://raw.githubusercontent.com/stylescape/brand/master/src/logo/logo-transparant.png" width="20%" alt="Stylescape Logo">
</p>
<h1 align="center" style='border-bottom: none;'>Stylescape + NPM</h1>
<h3 align="center">Example Project</h3>

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/stylescape/example-npm)

---

This example demonstrates how to use [Stylescape](https://scape.style) with npm and Sass compilation.

## Features

- **Sass Compilation**: Import Stylescape's source Sass files for customization
- **Auto-initialization**: Components with `data-ss` attributes initialize automatically
- **Live Reload**: Development server with automatic CSS recompilation

## Installation

```sh
git clone https://github.com/stylescape/example-npm.git
cd example-npm
npm install
```

## Usage

### Development

Start the development server with live reload:

```sh
npm start
```

This runs the server at `http://localhost:3000` and watches for Sass changes.

### Build

Compile Sass to CSS:

```sh
npm run build
```

## Project Structure

```
├── src/
│   ├── index.html      # Main HTML file
│   ├── js/
│   │   └── main.js     # JavaScript entry point
│   └── scss/
│       └── main.scss   # Sass entry point (imports Stylescape)
├── css/                # Compiled CSS output
└── package.json
```

## Stylescape Components

Use `data-ss` attributes for auto-initialization:

```html
<!-- Sidebar -->
<aside data-ss="aside">...</aside>

<!-- Accordion -->
<div data-ss="accordion">...</div>

<!-- Theme Toggle -->
<button data-ss="theme-toggle">...</button>
```

---

## Colophon

Made with ❤️ by **[Scape Agency](https://www.scape.agency)**

### Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

### License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for details.

---
