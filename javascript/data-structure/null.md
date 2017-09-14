# Null

> null表示一个空对象指针

### Example

```javascript
var nullObj = null;
console.log(nullObj); // "object"

// undefined 派生自null,所以ECMA-262规定对它们的相等性测试返回true
console.log(null == undefined); // true 但是==会转换操作数的类型

```

### Practice
1. 若定义一个变量意在保存一个对象，最好初始化为null，否则，则没必要初始化为undefined
2. 有助于区分变量为null或undefined
