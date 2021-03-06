# Electron.js Quickstart
> Boilerplate for a simple Electron app

[![Known Vulnerabilities](https://snyk.io/test/github/MichaelCurrin/electron-quickstart/badge.svg?targetFile=package.json)](https://snyk.io/test/github/MichaelCurrin/electron-quickstart?targetFile=package.json)
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/electron-quickstart?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/electron-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node.js](https://img.shields.io/badge/Node.js->=12-blue?logo=node.js&logoColor=white)](https://nodejs.org "Node.js homepage")
[![Package - electron](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/electron-quickstart/dev/electron?logo=electron&logoColor=white)](https://www.npmjs.com/package/electron)


## Preview

<div align=center>
    <img src="sample.png" alt="sample screenshot" title="sample screenshot" width="400" />
</div>


## About

Electron is a JavaScript framework which lets you write desktop applications. Such as Facebook Messenger, Slack and Visual Studio Code. This project is a template to help you learn the basics and get a Hello World project running with minimal effort.

<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/electron-quickstart/generate)

</div>


## Resources

See [Electron](https://michaelcurrin.github.io/dev-resources/resources/javascript/packages/electron/) in Dev Resources site.


## Create your own app from scratch

This project's contents and the steps this section are based on the intro tutorial in the docs.

- [Writing Your First Electron App](https://www.electronjs.org/docs/tutorial/first-app)

```sh
$ mkdir my-app
$ npm init
$ npm install --save-dev electron
```

Setup these files at minimum:

- `index.html`
- `main.js`

Copy the content from the tutorial or from the scripts in this repo.

Add this to the `scripts` section of `package.json` - `"start": "electron ."`. 

Note that using `node main.js` will not work - the `require('electron')` import will just return a string (a path like `'.../node_modules/electron/dist/electron'`) and `app` will cause errors as it is undefined.

Run your app with:

```sh
$ npm start
```


## Installation

Install Node.js - see [instructions](https://gist.github.com/aa1fc56419a355972b96bce23f3bccba).

Clone the repo.

Install dependencies.

```sh
$ npm install
```


## Usage

```sh
$ npm start
```


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
