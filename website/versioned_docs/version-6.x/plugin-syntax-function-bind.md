---
# Don't edit this file directly, it was copied using scripts/download-readmes.js: 
id: version-6.x-babel-plugin-syntax-function-bind
title: babel-plugin-syntax-function-bind
sidebar_label: syntax-function-bind
original_id: babel-plugin-syntax-function-bind
---

## Installation

```sh
npm install --save-dev babel-plugin-syntax-function-bind
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["syntax-function-bind"]
}
```

### Via CLI

```sh
babel --plugins syntax-function-bind script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["syntax-function-bind"]
});
```

