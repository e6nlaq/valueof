# valueof-type

[![npm version](https://badge.fury.io/js/valueof.svg)](https://badge.fury.io/js/valueof)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![NPM Downloads](https://img.shields.io/npm/dw/valueof)

## Install
```bash
npm i valueof-type
```

## Usage
```typescript
import valueof from 'valueof-type';

interface foo{
    a: number;
    b: string;
}

// number | string
let bar: valueof<foo>;

```
