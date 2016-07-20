# is-valid-json
----

A small tool to check if a Javscript literal/object is JSON or not

### Installation (as node package)
```sh
npm install is-valid-json --save
```
### Version
1.0.0

### License
MIT

### Usage

```sh
var isJSON = require('is-valid-json');

if( isJSON(obj) ){
  // Valid JSON, do something
}
else{
  // not a valid JSON, show friendly error message
}
```
