# Build Tools Template :sunglasses:

This build tools template has a Gulp-powered build system with the following features:

- Sass compilation and prefixing
- JavaScript concatenation
- Built-in BrowserSync server
- Handlebars HTML templates with Panini
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## System Requirements

  * [Node.js](http://nodejs.org/) (8.x recommended)
  * [bower](http://bower.io/): `npm install bower -g`
  * [gulp-cli](http://gulpjs.com/): `npm install gulp-cli -g`

## Project Set-Up

### Start

To install project dependencies & start the server, run:

```
$ npm start
```

### Build

To compress CSS, JS and images for deployment, run:

```
$ npm run build
```
