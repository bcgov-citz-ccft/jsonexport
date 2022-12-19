# jsonexport {} → 📄

[![Travis](https://travis-ci.org/kauegimenes/jsonexport.svg)](https://travis-ci.org/kauegimenes/jsonexport)
[![Known Vulnerabilities](https://snyk.io/test/npm/jsonexport/badge.svg)](https://snyk.io/test/npm/jsonexport)
[![NPM Version](http://img.shields.io/npm/v/jsonexport.svg?style=flat)](https://www.npmjs.org/package/jsonexport)
[![NPM Downloads](https://img.shields.io/npm/dm/jsonexport.svg?style=flat)](https://www.npmjs.org/package/jsonexport)
[![NPM Downloads](https://img.shields.io/npm/dt/jsonexport.svg?style=flat)](https://www.npmjs.org/package/jsonexport)
[![NPM License](https://img.shields.io/npm/l/jsonexport.svg?style=flat)](https://www.npmjs.org/package/jsonexport)
[![GitHub stars](https://img.shields.io/github/stars/kauegimenes/jsonexport.svg)](https://github.com/kaue/jsonexport/stargazers)
[![Try jsonexport on RunKit](https://badge.runkitcdn.com/jsonexport.svg)](https://npm.runkit.com/jsonexport)
![npm bundle size](https://img.shields.io/bundlephobia/minzip/jsonexport)

✔ **easy to use** 👌 (should work as expected without much customization)️

✔ **extendable** 🕺 (many options to customize the output)

✔️ **tiny** 🐜 (0 dependencies)

✔ **scalable** 💪 (works with big files using Streams)

✔ **fast** ⚡

[Project Page](https://kaue.github.io/jsonexport/)

[Online Demo Page](https://kaue.github.io/jsonexport/demo/)

<details>
  <summary><b>Table of Contents</b></summary>

- [Usage](#usage)
- [CLI](#cli)
- [Browser](#browser)
  - [Browser Import Examples](#browser-import-examples)
- [Stream](#stream)
- [Promise](#promise)
- [JSON Array Example](#json-array-example)
  - [Simple Array](#simple-array)
  - [JSON Object Example](#json-object-example)
- [Options](#options)
  - [typeHandlers](#typehandlers)
- [Contributors](#contributors)

</details>


# Usage

Installation command is `npm install jsonexport`.

Run tests with `npm test`.

```javascript
const jsonexport = require('jsonexport');

jsonexport({lang: 'Node.js', module: 'jsonexport'}, {rowDelimiter: '|'}, function(err, csv){
    if (err) return console.error(err);
    console.log(csv);
});
```

## CLI

Global installation command is `npm install -g jsonexport`.

Convert JSON to CSV using `cat data.json | jsonexport` or `jsonexport data.json`

Usage: `jsonexport <JSON filename> <CSV filename>`

## Browser
Use the code in the folder named **dist** to run jsonexport in the browser

### Browser Import Examples

This a forked repository from kaue/jsonexport. For more information on how to use this [link](https://github.com/kaue/jsonexporthttps://github.com/kaue/jsonexport)
