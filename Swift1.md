## 变数

![](https://img.surgee.me/file/ed0325de65e8e79c840a6.png)

```
var
#变量
let
#常量
```
```
//建立变数
//关键字 + 变数名称：类型 = 值

var number = 1
print(number)
print("Hello World")

//改变变数
 number =2
print(number)

//debug (除错)
let number2:Int = 2
print(number2)

//实作：打招呼

var name = "Steve"
let location = "China"
print("Hello", name,"from", location )
print("Hello \(name) from \(location) )

name = "Jane"
print("Hello \(name) from \(location) )
```
![](https://img.surgee.me/file/66813f8e1a76667fe80fe.png)

![](https://img.surgee.me/file/aeb09df2f69fd51993253.png)

![](https://img.surgee.me/file/821816863074345ae7e81.png)

## 运算子

![](https://img.surgee.me/file/b746cdfa188a1cb00ff3d.png)

![](https://img.surgee.me/file/2f066b672774b4907f3b3.png)

![](https://img.surgee.me/file/c426badfb979dda1b6fee.png)


### 等号用法
```
1 + 2 = 3

var a = 1 + 2

a = a + 2

a += 2   ## 先算 a + 2 再算 a = (a + 2)

```
**空白键分隔 & 数学运算必须是同类型**

```
var number = 0

number = number +5      ## 5

number += 5  ## 10

number += number  ##  20

number -= 5   ## 15
number *= 2   ## 30
number /= 3   ## 10
number %= 3   ##1
```
**除法注意事项**
**整数相除结果无条件舍去**
```
100 / 20   ## 5
100 / 30   ## 3
100 / 27   ## 3
```
**不能除 0**


 
