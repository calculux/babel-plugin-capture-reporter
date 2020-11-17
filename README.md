# babel-plugin-capture-reporter

capture the javascript error

## Example

**In**

```js
// input code
```

**Out**

```js
"use strict";

// output code
```

## Installation

```sh
$ npm install babel-plugin-capture-reporter
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["capture-reporter"]
}
```

### Via CLI

```sh
$ babel --plugins capture-reporter script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["capture-reporter"]
});
```
