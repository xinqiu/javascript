# 高级运算符

一些高级的运算符可以这样用，比如：

* **求余 (除法的余数)**: ```x = y % 2```
* **累加**: 让 a = 5
    * ```c = a++```, 结果: c = 5 和 a = 6
    * ```c = ++a```, 结果: c = 6 和 a = 6
* **递减**: 让 a = 5
    * ```c = a--```, 结果: c = 5 和 a = 4
    * ```c = --a```, 结果: c = 4 和 a = 4

    
{% exercise %}
定义一个变量 `c` 作为自减变量 `x` 对3的模。
{% initial %}
var x = 10;

var c =
{% solution %}
var x = 10;

var c = (--x) % 3;
{% validation %}
assert(c === 0);
{% endexercise %}
