# Undefined

> Undefined类型只有一个值，即undefined.
>
> 变量声明但未初始化时，其值为undefined.
>
> 注：为初始化和未定义的变量是不同的，使用为初始化变量返回undefined，而未定义的变量会报错
>
> ​	但是使用typeof检测两者，都会返回undefined，这个结果在逻辑上有一定的合理性，但在技术角度有本					   质的区别，但无论那种情况，都不能对变量进行实际的操作

### Example

```javascript
var msg;

console.log(msg == undefined); // true
console.log(msg === undefined); // true
console.log(age); // 产生错误
```

### Best practise

变量未初始化会被自动赋予undefined，但是显式地初始化变量依然是最佳选择，如果这样，当typeof返回undefined时，我们就知道变量未定义，而不是尚未初始化