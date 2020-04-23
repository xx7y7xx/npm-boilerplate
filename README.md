# npm-boilerplate

[![Build Status][travis-svg]][travis-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]

> An npm package boilerplate.

![npm-boilerplate in action](https://raw.githubusercontent.com/xxd3vin/airbnb-npm-boilerplate/master/airbnb-npm-boilerplate-demo.gif)

## Live Playground

For examples of the component in action, go to https://xxd3vin.github.io/npm-boilerplate.

OR

To run that demo on your own computer:
* Clone this repository
* `npm install`
* `npm run storybook`
* Visit http://localhost:9001/

## Getting Started
### Install dependencies
Ensure packages are installed with correct version numbers by running:
  ```sh
  (
    export PKG=npm-boilerplate;
    npm info "$PKG" peerDependencies --json | command sed 's/[\{\},]//g ; s/: /@/g; s/ *//g' | xargs npm install --save "$PKG"
  )
  ```

  Which produces and runs a command like:

  ```sh
  npm install --save npm-boilerplate react@>=#.## react-dom@>=#.## react-addons-shallow-compare@>=#.##
  ```

[travis-svg]: https://travis-ci.org/xxd3vin/npm-boilerplate.svg
[travis-url]: https://travis-ci.org/xxd3vin/npm-boilerplate
[deps-svg]: https://david-dm.org/xxd3vin/npm-boilerplate.svg
[deps-url]: https://david-dm.org/xxd3vin/npm-boilerplate
[dev-deps-svg]: https://david-dm.org/xxd3vin/npm-boilerplate/dev-status.svg
[dev-deps-url]: https://david-dm.org/xxd3vin/npm-boilerplate#info=devDependencies
[license-url]: LICENSE
