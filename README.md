# Alinex Control

[![GitHub watchers](
  https://img.shields.io/github/watchers/alinex/node-control.svg?style=social&label=Watch&maxAge=86400)](
  https://github.com/alinex/node-control/subscription)<!-- {.hidden-small} -->
[![GitHub stars](
  https://img.shields.io/github/stars/alinex/node-control.svg?style=social&label=Star&maxAge=86400)](
  https://github.com/alinex/node-control)
[![GitHub forks](
  https://img.shields.io/github/forks/alinex/node-control.svg?style=social&label=Fork&maxAge=86400)](
  https://github.com/alinex/node-control)<!-- {.hidden-small} -->
<!-- {p:.right} -->

[![npm package](
  https://img.shields.io/npm/v/alinex-control.svg?maxAge=86400&label=latest%20version)](
  https://www.npmjs.com/package/alinex-control)
[![latest version](
  https://img.shields.io/npm/l/alinex-control.svg?maxAge=86400)](
  #license)<!-- {.hidden-small} -->
[![Travis status](
  https://img.shields.io/travis/alinex/node-control.svg?maxAge=86400&label=develop)](
  https://travis-ci.org/alinex/node-control)
[![Gemnasium status](
  https://img.shields.io/gemnasium/alinex/node-control.svg?maxAge=86400)](
  https://gemnasium.com/alinex/node-control)
[![GitHub issues](
  https://img.shields.io/github/issues/alinex/node-control.svg?maxAge=86400)](
  https://github.com/alinex/node-control/issues)<!-- {.hidden-small} -->

The control application is part of the [IT Operator](https://github.com/alinex/node-operator)
application and serves as the data source for the front-end applications.

## Technologies

- Base Framework [Quasar](http://quasar-framework.org/)
- Scripting Language [ES6](http://es6-features.org/#Constants) Javascript
- Client Framework [Vue](https://vuejs.org/)
- [Vue Router]
- [Vuex] if building large scale Apps.
- [Webpack] for tweaking the build system to your specific needs
- [Cordova] for building native mobile phone Apps out of your Quasar App

## Usage

**In the moment this is in heavy development and not really ready for productive use.**

The Operator contains both, the Control and REST server, so you may start one or
the other and maybe also both on one server.

### Installation

For production use the best way is to install the webserver through
[IT Operator](https://github.com/alinex/node-operator).

The applications are downloadable under...

### Development

For easy and fast handling use yarn:

``` bash
# Install yarn package manager
$ sudo npm install -g yarn
# Clone from github
$ git clone https://github.com/alinex/node-control
# Install the modules
$ yarn
```

Now you may run the development version with hot reloading or in the production
version:

``` bash

$ yarn dev      # serve with hot reload at localhost:8080
$ yarn lint     # lint code

$ yarn build    # build for production with minification
```

## License

(C) Copyright 2017 Alexander Schilling

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

>  <https://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
