# String Transform [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=String%20transform%20module%20from%20Glize%20library.&url=https://glize.js.org&via=GitHub&hashtags=Glize,JavaScript,ECMAScript,ES6)
[![Build Status](https://github.com/Datamart/string-transform/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/Datamart/string-transform/actions/workflows/npm-publish.yml) [![License](https://img.shields.io/:license-apache-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0.html) [![NPM version](https://img.shields.io/npm/v/string-transform.svg?style=flat)](https://npmjs.org/package/string-transform) [![Website](https://img.shields.io/website-up-down-green-red/https/glize.js.org.svg?style=flat)](https://glize.js.org) [![NPM downloads](https://img.shields.io/npm/dm/string-transform.svg?style=flat)](https://npmjs.org/package/string-transform)

String transform module from Glize library.

## Usage

```bash
npm install string-transform --save
```

```js
import { capitalize, hash } from 'string-transform';

/**
 * Transforms the first character of each word to uppercase; other
 * characters are unaffected.
 * @param {string} str The string to be transformed.
 * @return {string} Returns transformed string.
 */
console.log(capitalize('test string')); // Test String

/**
 * Converts <code>str</code> to hashed string.
 * @param {string} str The input string.
 * @return {string} Returns hashed string.
 * @method
 */
console.log(hash('https://glize.js.org/')); // 4Q69R
```

For more information please visit [Glize project page](https://glize.js.org).