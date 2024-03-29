# AngularJS sample app

*A sample app for AngularJS 1.x and 2.x by [@franciov](//twitter.com/franciov)*

## Styleguide

This sample app is following this styleguide:

https://github.com/franciov/angularjs-sample-app/labels/styleguide

based on this project:

https://github.com/johnpapa/angular-styleguide

## How to run the sample app

### Angular 1

Run a local HTTP server:

```sh
$ npm install -g http-server
$ http-server
```

Open your favourite browser and go to http://0.0.0.0:8080/angular1/

### Angular 2

Please note that Angular 2 is based on Typescript, so make sure you install tsd:

```sh
$ npm install -g tsd@^0.6.0
$ tsd install angular2 es6-promise rx rx-lite
```

This will generate the folder `typings`, to be moved into the `angular2` folder.

Make sure you run tsc to create js source files:

```sh
$ npm install -g typescript@^1.5.0
$ tsc --watch -m commonjs -t es5 --emitDecoratorMetadata --experimentalDecorators app/angular2/app/*.ts
```

Finally, run a local HTTP server:

```sh
$ npm install -g http-server
$ http-server
```

Open your favourite browser and go to http://0.0.0.0:8080/angular2/

## How to contribute

Please check the list of issues/features and feel free to leave a comment / start working on one of them / open a new one:

https://github.com/franciov/angular2-sample-app/issues

Make sure you:

- work on your own branch
- write specs before writing code
- ask questions ;)
- send a pull request when tests pass
- expect a review :)
