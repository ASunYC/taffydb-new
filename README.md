# taffydb-new
taffydb-new is clone library from TaffyDB.

## Introduction
Please see the [official website](http://www.taffydb.com) for more 
complete documentation.

taffydb-new lib just update to node v18.x and above. Please read LICENSE , the copyrigh is from TaffyDB.

Some usefull links: git://github.com/typicaljoe/taffydb.git.

## Usage
### (1) Use it in Node.JS
TaffyDB is easy to use in Node.JS.  Simply install using `npm` and `require` the
package:

```js
$ npm install --production taffy

# and then in your code
TAFFY = require( 'taffy' ).taffy;
```

The automated regression test file `nodeunit_suite.js` is an excellent
example.

### (2) Use it in ES Module
TaffyDB is easy to use in Node.JS.  Simply install using `npm` and `require` the
package:

```ts or js
$ import Taffy from './taffy-es'

# and then in your code
const friends = Taffy([
	{"id":1,"gender":"M","first":"John","last":"Smith","city":"Seattle, WA","status":"Active"},
	{"id":2,"gender":"F","first":"Kelly","last":"Ruth","city":"Dallas, TX","status":"Active"},
	{"id":3,"gender":"M","first":"Jeff","last":"Stevenson","city":"Washington, D.C.","status":"Active"},
	{"id":4,"gender":"F","first":"Jennifer","last":"Gill","city":"Seattle, WA","status":"Active"}	
])
```