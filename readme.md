# is-azure-function [![Build Status](https://travis-ci.org/SamVerschueren/is-azure-function.svg?branch=master)](https://travis-ci.org/SamVerschueren/is-azure-function)

> Detect if your code is running in an [Azure Function](https://azure.microsoft.com/en-us/services/functions/)


## Install

```
$ npm install --save is-azure-function
```


## Usage

```js
const isAzureFunction = require('is-azure-function');

if (isAzureFunction) {
	console.log('Running in an Azure Function');
}
```


## Related
- [is-lambda-function](https://github.com/SamVerschueren/is-lambda-function) - Detect if your code is running in [AWS Lambda](https://aws.amazon.com/lambda/)


## License

MIT © [Sam Verschueren](https://github.com/SamVerschueren)
