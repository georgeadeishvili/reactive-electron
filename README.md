# Electron React Redux

A minimal boilerplate to get started with [Electron](http://electron.atom.io/), [React](https://facebook.github.io/react/) and [Redux](http://redux.js.org/).

Including:

* [React Router](https://reacttraining.com/react-router/)
* [Redux Thunk](https://github.com/gaearon/redux-thunk/)
* [Redux Actions](https://github.com/acdlite/redux-actions/)
* [Redux Local Storage](https://github.com/elgerlambert/redux-localstorage/)
* [Electron Packager](https://github.com/electron-userland/electron-packager)
* [Electron DevTools Installer](https://github.com/MarshallOfSound/electron-devtools-installer)
* [Electron Mocha](https://github.com/jprichardson/electron-mocha)
* [Browsersync](https://browsersync.io/)

## Quick start

Install dependencies
```bash
yarn install
```

Development
```bash
yarn develop
```

## Packaging

Modify [electron-builder.yml](./electron-builder.yml) to edit package info.

Create a package for OSX, Windows and Linux
```
npm run pack
```

Or target a specific platform
```
npm run pack:mac
npm run pack:win
npm run pack:linux
```

## Tests

```
npm run test
```
