# VTEX Checkout Payment UI

A mocked boilerplate to develop payment options to VTEX Smart Checkout based on [Pink](https://github.com/augustocb/pink).

## Features

The main features of Pink:

*   Local server
*   Less autocompile
*   Livereload for any files changes
*   Mocked VTEX Smart Checkout HTML and CSS

## How it works

When you run `grunt`, it starts a server at [http://localhost:8080/](http://localhost:8080/), compiles `style.less` file and begin watching changes in all files inside `assets` folder. Any change will reload the page or just reload css files, in case of style changes.

You can test your payment layout creating/modifying:

*   `src/partials/payment.html`: HTML file
*   `src/assets/css/less/style.less`: style file
*   `src/assets/img/`: images folder

## Dependencies

1.  [Node.js](http://nodejs.org/download)
2.  Grunt: run `sudo npm i -g grunt-cli`
3.  [Sass](http://sass-lang.com/install)

## Installation

1.  Download or clone this repo
2.  Install NPM dependencies: run `npm i`

## Hands on!

### Running

1.  Run `grunt`
2.  Go to [http://localhost:8080/](http://localhost:8080/)

## Thank you! :)
