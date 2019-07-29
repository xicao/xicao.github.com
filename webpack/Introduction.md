---
date: 2019-07-29
tags: webpack
---

# Introduction

## Why we need a bundler

- transfer ES6/ES Next syntax
- transform JSX
- CSS auto prefix/pre-processor
- compress source code and image

## First try of Webpack

- default config file: `webpack.config.js`
- can use `webpack --config` to set the custom config file path

```javascript
    module.exports = {
      entry: './src/index.js', // default entry file
      output: './dist/main.js', // default output file
      mode: 'production',
      modules: [
        // rules: [{ test, use }]
      ]
      plugins: [
      ]
    }
```

- [My First Webpack Bundle](./first/dist/index.html)
