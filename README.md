# just-dev-landing

Static "coming soon" landing page for just-dev.org, built with Gulp, SCSS, and vanilla JavaScript.

## Features

- Single-page static site
- SCSS compiled and minified to CSS bundle
- JavaScript concatenated and minified
- BrowserSync live reload for local development

## Stack

- Gulp 4 for build automation
- node-sass / gulp-sass for SCSS compilation
- BrowserSync for development server

## Project structure

```
client/
  index.html      # page markup
  scss/           # stylesheets (style.scss, variables.scss, reset.scss)
  js/             # JavaScript sources
build/            # compiled output (CSS bundle, JS bundle, HTML)
```

## Run locally

```bash
npm install
gulp
```

Starts BrowserSync dev server at http://localhost:3000 with file watching.

## Build

```bash
npm install
gulp html
gulp css
gulp js
```
