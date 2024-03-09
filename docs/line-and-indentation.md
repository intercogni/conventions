# Line and Indentation
This document outlines all the line and indentation conventions to be followed.

## Character Limit
A line code should not contain more than `80` characters.

> an exception is made for lines with url links, in which the developer is allowed to write **only the url** past 80 characters. Even then, they should minimize the character count on such line/s

### Examples
In the example below, devs should realize that **only the url** is allowed to past the `80` character limit
```json
"node_modules/@babel/runtime": {
    "version"      : "7.24.0",
    "resolved"     : "https://registry.npmjs.org/@babel/runtime/-/runtime-7.24.0.tgz",
    "integrity"    : "sha512-Chk32uHMg6TnQdvw2e9IlqPpFX/6NLuK0Ys2PqLb7/gL5uFn9mXvK715FGLlOLQrcO4qIkNHkvPGktzzXexsFw==",
    "dev"          : true,
    "dependencies" : {
        "regenerator-runtime" : "^0.14.0"
    },
    "engines": {
        "node" : ">=6.9.0"
    }
},
```