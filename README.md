## React Native Redux Wix Navigation

#### Main Dependencies

* [React](https://github.com/facebook/react) 16.4.1
* [Redux](http://redux.js.org) 4.0.0
* [Styled Components](https://github.com/styled-components/styled-components) 3.3.3
* [Wix React Native Navigation](https://github.com/wix/react-native-navigation) 1.1.476
* [Recompose](https://github.com/acdlite/recompose) 0.27.1

#### Code Quality Tools

* [eslint](https://github.com/eslint/eslint) 5.1.0
* [stylelint](https://github.com/stylelint/stylelint) TODO
* [jest](https://github.com/facebook/jest) TODO
* [.editorconfig](http://editorconfig.org/)

#### Data Flow

I included only redux. Most projects will be fine with [redux-thunk](https://github.com/gaearon/redux-thunk) If you are more advanced developer then you will probably want to install either [redux-observables](https://github.com/redux-observable/redux-observable) or [redux-sagas](https://github.com/redux-saga/redux-saga). redux-observables are the cool thing to use but working with redux-sagas is much easier.

#### Testing

TODO

## Installation

Official installation guide is [here](https://facebook.github.io/react-native/docs/getting-started.html).

The rest of the process is not much different than for any other javascript project.

Install `node_modules`:

```
$ yarn install
```

Then link native libraries:

```bash
$ react-native link
```


## Development

Run react native server:

```bash
$ npm start
```

Compile mobile application for ios:

```bash
$ yarn ios
```

## Troubleshooting
If any problems occur, compilation is not working, etc, try some of these points:

* Project clean up: `Xcode -> Product -> Clean`
* Run `./repair.sh` in root folder
* Start development server yourself from command line using `yarn start`. (because of cache)
* Make sure that your device has access to internet.

## Preview

![1](https://github.com/developer239/react-native-redux-wix-navigation-boilerplate/blob/master/preview.gif?raw=true)
