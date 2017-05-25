# Quasar Framework

Quasar Framework allows to build hybrid mobile apps with near-native like user-interface
and uses VueJS 2 at its core. It has a good set of documentation available on its website
and provides an extensive set of Vue based UI components such as sliders, spinners, tooltip,
popover, model dialogs, context menu, video embedding and many more.

It is aimed for
- Web application
- Mobile apps (Android + IOS)
- Desktop application

## Feratures

While developing the server has:

- Webbpack + vue-loader for single file Vue components
- State preserving hot-reload
- State preserving compilation error overlay
- Lint-on-save with ESLint
- Source maps

Building the productive app:

 - Javascript minified with UglifyJS
 - HTML minified with html-minifier
 - CSS across all components extracted into a single file and minified with cssnano
 - All static assets compiled with version hashes for efficient long-term caching, and a production index.html is auto-generated with proper URLs to these generated assets


## Information

The best source are their websites:
- [Guide](http://quasar-framework.org/guide/) -
  Information about CLI, starter kits, how to get you started working on a project folder
- [Components](http://quasar-framework.org/components/) -
  List of Quasar components
- [API](http://quasar-framework.org/api/) -
  Global Javascript and CSS (framework) API

You may also discuss with the community under:
- [Forum](http://forum.quasar-framework.org/)
- [Chat](https://gitter.im/quasarframework/Lobby)


## Installation

Getting started with Quasar is easy and it offers its own set of CLI which should
be installed first:

```bash
# using yarn
$ yarn global add quasar-cli
# alternatively using npm
$ npm install -g quasar-cli
```

To test on Android the free "Quasar Play" app have to be installed to test your
app silently without releasing itself.
