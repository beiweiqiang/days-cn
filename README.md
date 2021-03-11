# days-cn [![NPM version](https://img.shields.io/npm/v/days-cn.svg?style=flat)](https://www.npmjs.com/package/days-cn)

> Days of the week in zh_cn. See https://github.com/datetime/days in EN.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save days-cn
```

## Usage

```js
var days = require('days-cn');

console.log(days);
//=> ['星期日', '星期一', '星期二', '星期三', '星期四', '星期五', '星期六']

console.log(days.abbr)
//=> ['周日', '周一', '周二', '周三', '周四', '周五', '周六']

console.log(days.short)
//=> ['周日', '周一', '周二', '周三', '周四', '周五', '周六']
```

## Other

[Is Sunday 星期天 or 星期日?](https://chinese.stackexchange.com/questions/16265/is-sunday-%E6%98%9F%E6%9C%9F%E5%A4%A9-or-%E6%98%9F%E6%9C%9F%E6%97%A5)
