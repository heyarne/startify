# 🚀

My minimalistic starter skeleton for frontend development. Comes with ES2015 via
`babel`, `browserify` and a live-reloading dev server thanks to `beefy`. Easily
extendible for use with React or other more fully-fledged solutions, no big
`gulp` config files. Also configures `standard` to use `babel-eslint` as the
parser, which is useful for linting some syntax extensions (e.g. async / await).

## Preconfigured commands

```
# Start a live-reload server that compiles scripts/index.js and and provides it temporarily as bundle.js
$ npm run dev
# Compile and mangle scripts/index.js, spit out bundle.js
$ npm run bundle
```
