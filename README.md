# Why randn?

- Clean and focused
- [CLI](#cli) included
- Actively maintained
- Fast and reliable
- Easy to get numbers

# Install

```
$ npm install randn
```

# Usage

```js
const randn = require('randn');

console.log(randn());
//=> 315764787997033782716506419531

console.log(randn(5));
//=> 86773
```

# API

**rand()**

> Return a number with default value of 30

Return Type: `string`

**rand(number)**

> Return an string with custom number

Return Type: `string`

# CLI

```
Examples
	$ randn
	315764787997033782716506419531

	$ randn --number 5
	86773

	$ randn -n 23
	46379458263283978267360

	Options
	 -n, --number  Generate a number with certain length
```
