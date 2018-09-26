# Goose JsDOM Environment

[![Build Status](https://img.shields.io/circleci/project/github/redco/goose-jsdom-environment.svg?style=flat)](https://circleci.com/gh/redco/goose-jsdom-environment)
[![Latest Stable Version](https://img.shields.io/npm/v/goose-jsdom-environment.svg?style=flat)](https://www.npmjs.com/package/goose-jsdom-environment)
[![Total Downloads](https://img.shields.io/npm/dt/goose-jsdom-environment.svg?style=flat)](https://www.npmjs.com/package/goose-jsdom-environment)

Environment for [Goose Parser](https://github.com/redco/goose-parser) which allows to run it using [JsDom](https://github.com/jsdom/jsdom)

## JsDOMEnvironment
This environment is used for running Parser with jsdom.
```JS
const env = new JsDOMEnvironment({
    url: 'http://google.com',
});
```
The main and only required parameter is `url`. It contains an url address of the site, where Parser will start.

This environment allows:
- execute dynamic JavaScript on the page
- use single proxy
- and more sweet features
