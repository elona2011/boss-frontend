# ES6

## 教程

http://es6.ruanyifeng.com/

## babel-root-import

CommonJS和ES6的模块引用只能采用相对路径或绝对路径，而不能采用相对项目根目录的路径引用

```
// Usually
import SomeExample from '../../../some/example.js';
const OtherExample = require('../../../other/example.js');

// With Babel-Root-Importer
import SomeExample from '~/some/example.js';
const OtherExample = require('~/other/example.js');
```

https://www.npmjs.com/package/babel-root-import
