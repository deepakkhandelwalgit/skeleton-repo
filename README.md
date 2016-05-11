## react-npm-skeleton

[![Build Status](https://travis-ci.org/lobdev/react-npm-skeleton.svg?branch=master)](https://travis-ci.org/lobdev/react-npm-skeleton)

An ES6 skeleton project for creating react components packaged with npm
Based on [this project](https://github.com/danvk/mocha-react)

### Technology Stack:

* react
* mocha

### Usage:

Clone the repo as a new project:

```
git clone https://github.com/lobdev/react-npm-skeleton.git <shiny-new-project>
```
Start Server:

```
cd shiny-new-project
npm i
npm start
```
Run App:

```
npm start command automatically initiate browser at 3000 port
http:://localhost:3000
```

Run tests:

```
cd shiny-new-project
npm i
npm test
```

Find Code Coverage:

```

### Developer Notes:

Make sure you configure your editor/IDE to use:

```
.editorconfig
.eslintrc
```
### TODO:
1. Add a 'hello world' component (Daffodil)
1. Add a 'hello world' component test (Daffodil)
1. Add `webpack` or `gulp` with `browserSync` (Daffodil)
1. Add an entry point index.html (Daffodil)
1. Configure `npm start` to launch web server and serve hello world component (Daffodil)
1. Create Jenkins build pipeline to run tests and build npm package (Cam)


Note: [this repo](https://github.com/tinkertrain/jspm-react) looks like it has most of what we need
