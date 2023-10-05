## 数字类型
- 数字资料类型
- 二进位和十进位
- 定点数和浮点数
- 为什么要同类型才能相加？


![](https://img.surgee.me/file/ad5a74f6f214f8c741ab0.png)


**Int(整数)  定点数**


![](https://img.surgee.me/file/25c0adea233cd8b62d127.png)


**Double(双精度浮点数) 64 bits**
**Float(单精度浮点数)  32 bits**


![](https:img.surgee.me/file/6499372754c64494483ad.png)


```
let int: Int =1
let float: Float =2
let double: Double =3


let number = Double(1.0)
```

**The maximum value of a floating-point number does not mean that all numbers smaller than it can be stored with precision**

**Int can be queried through the max and min ranges**

**Double is safe for 15 consecutive digits, Float is safe for 6 consecutive digits**


### Why does it have to be the same type to add up?


let x = 1 / 2## 数字类型
- 数字资料类型
- 二进位和十进位
- 定点数和浮点数
- 为什么要同类型才能相加？


![](https://img.surgee.me/file/ad5a74f6f214f8c741ab0.png)


**Int(整数)  定点数**


![](https://img.surgee.me/file/25c0adea233cd8b62d127.png)


**Double(双精度浮点数) 64 bits**
**Float(单精度浮点数)  32 bits**


![](https:img.surgee.me/file/6499372754c64494483ad.png)


```
let int: Int =1
let float: Float =2
let double: Double =3


let number = Double(1.0)
```

**The maximum value of a floating-point number does not mean that all numbers smaller than it can be stored with precision**

**Int can be queried through the max and min ranges**

**Double is safe for 15 consecutive digits, Float is safe for 6 consecutive digits**


### Why does it have to be the same type to add up? 


let x = 1 / 2   ## 0.5
print(x)  ##0

let x1 = 1 / 2.0 
print(x1)
let x2: Double = 1 / 2
print(x2)



