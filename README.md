# nuxt-express-vuetify-boilerplate

> Nuxt.js + Express boilerplate with Vuetify component framework

<p align="center"><img src="https://github.com/danijelmartinek/nuxt.js-express-vuetify/blob/master/assets/img/nuxtexpressvuetify.png"></p>

## Modified Files
- gritty.patch    # to patch gritty frontend.js, make it can be required via webpack
- nuxt.config.js  # add gritty vender
- pages/index.vue # main page (where gritty vender is included)
  - Reference:
    - [gritty client api](https://www.npmjs.com/package/gritty#client-api)
- server/index.js     # socket.io with gritter server side configuration
  - Reference:
    - [gritty usage as middleware](https://www.npmjs.com/package/gritty#usage-as-middleware)
- package.json    # add postinstall command and gritty module

## Build Setup

``` bash
# clone repository
$ git clone https://github.com/danijelmartinek/nuxt.js-express-vuetify.git

# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm start
```

## Documentation

Nuxt.js --> https://nuxtjs.org/guide </br>
Express --> http://expressjs.com/ </br>
Vuetify --> https://vuetifyjs.com/ </br>

Nuxt.js + Express --> https://github.com/nuxt-community/express-template
