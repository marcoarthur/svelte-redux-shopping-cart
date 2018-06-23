
[![Greenkeeper badge](https://badges.greenkeeper.io/khtdr/svelte-redux-shopping-cart.svg)](https://greenkeeper.io/)
[![Build Status](https://travis-ci.org/khtdr/svelte-redux-shopping-cart.svg?branch=master)](https://travis-ci.org/khtdr/svelte-redux-shopping-cart)
[![Dependency Status](https://david-dm.org/khtdr/svelte-redux-shopping-cart/master.svg)](https://david-dm.org/khtdr/svelte-redux-shopping-cart/master)
[![devDependency Status](https://david-dm.org/khtdr/svelte-redux-shopping-cart/master/dev-status.svg)](https://david-dm.org/khtdr/svelte-redux-shopping-cart/master#type=dev)

This is a port of the [Redux Shopping Cart](https://github.com/reactjs/redux/tree/master/examples/shopping-cart/) example to [Svelte](https://svelte.technology/)

The bindings between Svelte and Redux are provided by the [svelte-redux](https://github.com/UnwrittenFun/svelte-redux) package.

The bundle is build with [Webpack](https://webpack.js.org/) and is configured with hot-reloading.

To get started:
  1. Clone the repo
  2. Install dependencies
  3. Start the server

```bash
git clone git@github.com:khtdr/svelte-redux-shopping-cart.git
cd ./svelte-redux-shopping-cart && yarn
yarn start
```

Open: `http://localhost:8080`

:question: __Already using port 8080?__

Find and change the port number in `package.json`:

  "start": "http-server public -p 8080 -o"


**ScreenShot**
![App Screenshot](https://raw.githubusercontent.com/khtdr/svelte-redux-shopping-cart/master/sreenshot.png)
