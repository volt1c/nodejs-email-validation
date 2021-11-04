# email-validation

Email-validation is a zero-dependency module that validate emils.

## Install

```bash
npm install email-validation
yarn add email-validation
```

## Usage

#### Javascript

```js
const emailValidation = require('email-validation')

emailValidation.validate('example@gmail.com') // true
```

#### Typescript

```ts
import * as emailValidation from 'email-validation'

emailValidation.validate('example@gmail.com') // true
```

## Development

### Testing

#### Install required packages

```
$ npm install
```

#### Run tests

```
$ npm test
```
