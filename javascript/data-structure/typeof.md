# typeof 

> 检测一个**变量**或**数值字面量**的数据类型，格式：typeof targetValue，返回值为以下几种：
>
> * "undefined" => 变量未定义
> * "boolean"      =>布尔值
> * "string"          =>字符串
> * "number"      =>数值
> * "object"          =>对象或null
> * "function"      =>函数
> 注意：未初始化和未声明的变量执行typeof操作符都会返回undefined

#### Example

```javascript
var eg1;
var isBook = true;
var name = 'duke';
var age = 23;
var person = {
  name: 'duke',
  age: 23
};
var sayHello = function(name){
  console.log('hello', name);
}
var arr = [1, 2];
var date = new Date();

console.log(typeof eg1);  // undefined
console.log(typeof nodefined); // undefined ,未定义的变量也会返回undefined
console.log(typeof isBook);  // boolean
console.log(typeof name);  // string
console.log(typeof age);  // number
console.log(typeof person, typeof null);  // object object
console.log(typeof sayHello);  // function
console.log(typeof arr);  // object
console.log(typeof date);  // object
console.log(typeof 12);
```
