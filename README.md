# Electron Quickstart
> Boilerplate for a simple Electron app

Electron is a JavaScript framework which lets you write desktop applications.


## Preview

![sample screenshot](/sample.png)


## Resources

- https://www.electronjs.org/
    >  Build cross-platform desktop apps with JavaScript, HTML, and CSS 
- https://www.electronjs.org/docs
    - Docs for developers making Electron apps.
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) repo - see the code and also the resources in the README file.


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

Install Node.js.

Clone the repo.

Install dependencies.

```sh
$ npm install
```


## Usage

```sh
$ npm start
```
