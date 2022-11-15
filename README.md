[![Build Status](https://travis-ci.org/amindia/invoice-number.svg?branch=master)](https://travis-ci.org/amindia/invoice-number)
[![Coverage Status](https://coveralls.io/repos/github/amindia/invoice-number/badge.svg?branch=master)](https://coveralls.io/github/amindia/invoice-number?branch=master)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

# invoice-number
Node.js module to generate invoice number sequentially 

## Installation

```sh
$ npm install invoice-number
```
## Usage

```typescript
import { InvoiceNumber } from 'invoice-number'

InvoiceNumber.next('2017/08/ABC001')
// => 2017/08/ABC002

InvoiceNumber.next('xjsiwe234njshd6')
// => XJSIWE234NJSHD7

InvoiceNumber.next('899ZZZ9')
// => 900AAA0

```
