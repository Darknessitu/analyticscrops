# Analytic Crop App #
Version: 0.0.1

### How do I get set up? ###

Open [package.json](./package.json/) to see all modules you need for developer and production.
To download and setup all necessary modules and run the app:

```sh
$ npm install
$ npm start
```
Note: If you want to run a test mode you should do this
```sh
$ npm test
```
Note: If you haven't install a webpack or/and stylus you should do this
```sh
$ npm install -g webpack
$ npm install -g stylus
```
Note: If you have a permission problems go to [fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions) 
Do this to run webpack and compiled the react code:
```sh
$ cd dev/
$ webpack --watch
```
Do this ti run stylus and complied the css to public:
```sh
$ cd dev/src/css/
$ stylus -w -c style.styl -o ../../../public/css/
```
License
----

MIT
