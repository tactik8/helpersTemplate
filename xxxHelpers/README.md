# templateHelpers

JS library template for developing helper functions



## Install

### From github
This command will install the helper functions under the directory helpers. 


```
git clone https://github.com/tactik8/jsonldHelpers ./helpers
```


## Test and publish

```
npm install --save-dev jest

npm install --save-dev babel-jest @babel/core @babel/preset-env
npm install --save-dev jest-environment-jsdom

node --experimental-vm-modules node_modules/.bin/jest

npx parcel build
npm adduser
npm publish

```

git clone https://github.com/tactik8/jsonldHelpers ./helpers




## How to use

```
import { jsonldHelpers as h } from 'https://tactik8.github.io/krakenJsSchema/kraken_schema/kraken_schema.js'

let k = KrakenSchemas.get(record_type)


```

## Examples

```
let k = KrakenSchemas.get('Person')

let p = k.getProperty('givenName')

p.getLocalizedPropertyID('en-US')) --> 'first name'




```

## Tests

Prompt:
```
please write unit tests for all functions in arrayHelpers.js. Please separate the tests one file by function. Please consider edge cases.
```


## Running tests
node --experimental-vm-modules node_modules/.bin/jest

## Attributes

- k.properties: list of properties objects
- l.propertiesLight: mvp list of properties object


