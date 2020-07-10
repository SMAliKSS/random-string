# Generate random string

![npm](https://img.shields.io/npm/v/@smakss/random-string) ![Snyk Vulnerabilities for npm package](https://img.shields.io/snyk/vulnerabilities/npm/@smakss/random-string) ![NPM](https://img.shields.io/npm/l/@smakss/random-string) ![npm](https://img.shields.io/npm/dt/@smakss/random-string) ![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@smakss/random-string)

This package will generate a random dummy string based on the available set of characters and given the length of the desired string. In case you don't care about uniqueness and don't want to use UUID this one will help you to achieve what you want.

## How it works?

To install it you can simply do the following command:

```
npm i @smakss/random-string
or
yarn add @smakss/random-string
```

to include it with common js module you should do this:

```
var randomString = require('@smakss/random-string');
```

and to include it with ECMAscript module you can simply do this one:

```
import randomString from '@smakss/random-string'
```

then to use it within your application you can do it just like this:

```
randomString(10) // This will generate a random string with a length of 10. The output should be something like this: BD@Z8dKf2%
```
