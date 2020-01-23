# webcomponent es5 lib

This repo has been written in order to show the minimum example of webcomponent lib authoring, using `lit-element` or `haunted`.
Build has been done through webpack/babel-loader.
It is possible to disable transpilation to es5 and let webcomponent work in modern browsers (I tested it in chrome latest).
When transpilation is enabled, lit-element component is not working.

## setup

```
$ npm ci
$ npm run build
$ npm run serve
```

## disable transpilation

In order to disable babel transpilation, just set `DISABLE_TRANSPILE = true` in `./webpack.config.js`.