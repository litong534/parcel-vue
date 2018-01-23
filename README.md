# vue-example

> A Vue.js project

## Build Setup

``` bash
# install dependencies
# To try it out, install yarn globally (brew install yarn or npm install -g yarn), then run:
yarn global add vue-cli
vue init shawwn/parcel-simple vue-example
yarn add postcss-modules autoprefixer --dev
# Create .postcssrc:

{
  "plugins": {
    "autoprefixer": {...config}
  }
}

// or

{
  "plugins": ["autoprefixer"]
}

# serve with hot reload at localhost:1234
npm run dev

# build for production with minification
npm run build
```
