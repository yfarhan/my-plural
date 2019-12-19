# mytspkg
A Node.js module that returns the plural form of any noun
## Installation 
```sh
npm install mytspkg --save
yarn add mytspkg
```
## Usage
### Javascript
```javascript
var pluralise = require('mytspkg');
var boys = pluralise.getPlural('Boy');
```
```sh
Output should be 'Boys'
```
### TypeScript
```typescript
import { getPlural } from 'mytspkg';
console.log(getPlural('Goose'))
```
```sh
Output should be 'Geese'
```
### AMD
```javascript
define(function(require,exports,module){
  var pluralise = require('mytspkg');
});
```
## Test 
```sh
npm run test
```
