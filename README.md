# bootstrap4-custom-theme-seed
A seed for creating custom bootstrap themes


## Getting started

Install all dependencies via npm or yarn:

```sh
$ npm install
# or
$ yarn install
```

Build the `dist/theme.css` file and start an http server to serve the demo page at `localhost:8000`:

```
$ npm start
# or
$ yarn start
```

## Creating a theme

The directory `themes/variables.scss` contains all the default Sass variables for Bootstrap.

With the `start` command above running, change any variables listed there (you may also remove `!default`),
and watch as the demo page automatically updates to show your changes.


## Building

When you are satisfied with your theme, you can build a minified and unminified version in `dist/` via:

```sh
$ npm run css
# or
$ yarn run css
```
