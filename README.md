# @libtommy2024/non-delectus-modi-maiores

## Install

Do not use it if you can use maps.

```sh
yarn add @libtommy2024/non-delectus-modi-maiores
```

or if npm is package manager of your choice

```sh
npm install @libtommy2024/non-delectus-modi-maiores --save
```

## Usage

### I want to create a new object

```js
import box from '@libtommy2024/non-delectus-modi-maiores';

const trackedObj = box({});
```

### I have an existing object

```js
import box from '@libtommy2024/non-delectus-modi-maiores';

const myObj = { 
  a: true,
  b: void 0,
};

const trackedObj = box(myObj);
// alternatively if you want to provide a custom orer
const trackedReversedObj = box(myObj, ['b', 'a']);
```

## LICENSE

[Apache License 2.0](https://github.com/libtommy2024/non-delectus-modi-maiores/blob/master/LICENSE)
