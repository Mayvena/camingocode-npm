# camingocode-npm

[![npm (scoped)](https://img.shields.io/npm/v/@mayvena/camingocode-npm.svg)](https://www.npmjs.com/package/@mayvena/camingocode-npm)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@mayvena/camingocode-npm.svg)](https://www.npmjs.com/package/@mayvena/camingocode-npm)

An npm module containing the CamingoCode font

The font itself is freely distributed at https://www.myfonts.com/fonts/jan-fromm/camingo-code/

Designer and publisher of the font: Jan Fromm

## Install

```
npm i @mayvena/camingocode-npm
```

## Use

Typefaces assume you’re using webpack to process CSS and files. Each typeface
package includes all necessary font files (woff2, woff) and a CSS file with
font-face declarations pointing at these files.

You will need to have webpack setup to load css and font files. Many tools built
with Webpack will work out of the box with Typefaces such as [Gatsby](https://github.com/gatsbyjs/gatsby)
and [Create React App](https://github.com/facebookincubator/create-react-app).

To use, simply require the package in your project’s entry file e.g.

```javascript
// Load CamingoCode typeface
require('@mayvena/camingocode-npm')
```

Usage in SCSS:
```scss
@import "~@mayvena/camingocode-npm/index.css";
```
