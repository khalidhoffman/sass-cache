# sass-cache
selector-specifc cache functionality for node-sass

## How to install
`npm i sass-cache`

## How to use
```
const sass = require('node-sass'),
    sassCache = require('sass-cache');

sass.render({
        file: scss_filename,
        functions: sassCache.functions
    },
    function (err, result) {
        /*...*/
    });
```
