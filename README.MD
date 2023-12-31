# Introduction

A minimal theme for WordPress using [TailPress](https://tailpress.io) and [Tailwind CSS](https://tailwindcss.com/).

## Getting started

### General

You will find the editable CSS and Javascript files within the `/resources` folder.

Before you use your theme in production, make sure you run `npm run production`.

## NPM Scripts

There are several NPM scripts available. You'll find the full list in the `package.json` file under "scripts". A script is executed through the terminal by running `npm run script-name`.

| Script     | Description                                                                    |
| ---------- | ------------------------------------------------------------------------------ |
| production | Creates a production (minified) build of app.js, app.css and editor-style.css. |
| dev        | Creates a development build of app.js, app.css and editor-style.css.           |
| watch      | Runs several watch scripts concurrently.                                       |

## Block editor support

TailPress comes with support for the [block editor](https://wordpress.org/support/article/wordpress-editor/).

A basic setup for `theme.json` is included. This also means that you need to at least use WordPress 5.8. If you wan't to support earlier WordPress versions, you can use an [older version](https://github.com/jeffreyvr/tailpress/tree/0.1.1) of TailPress instead.

CSS-classes for alignment (full, wide etc.) are generated automatically. You can opt-out on this by removing the plugin from the `tailwind.config.js` file.

To make the editing experience within the block editor more in line with the front end styling, a `editor-style.css` is generated.

### Define theme colors and font sizes

Several colors and font sizes are defined from the beginning. You can modify them in `theme.json`.

## Links

- [TailPress website](https://tailpress.io)
- [Screencasts](https://www.youtube.com/playlist?list=PL6GBdOp044SHIOSCZejodwr1HcYsC43wG)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Laravel Mix Documentation](https://laravel-mix.com)
- [Esbuild Documentation](https://esbuild.github.io)
