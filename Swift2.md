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

**浮点数的最大值不代表所有比它小的数字都可以精确存储**

**Int 可以通过 max 和 min 查询范围**

**Double 可以安全地放 15 个连续数字, Float 可以安全的放 6 个连续的数字**

### 为什么要同类型才能相加？

```
let x = 1 / 2   // 0.5
print(x)  ## 0

let x1 = 1 / 2.0  //0.5
print(x1)  ## 0.5

let x2: Double = 1 / 2
print(x2)


```
![](https://img.surgee.me/file/888ca6d22afe5032a959d.png)

```
let a = 1
let b = 2.0
print(Double(a) + b)

```

**十进位数字类型 Decimal**
```
import Foundation

let decimal: Decimal = 1
let decimal2 =  Decimal(1)


let decimal4 = Decimal(String:"3.24")!
print(decimal4)
```
![](https://img.surgee.me/file/6e7d2e84b96043364b6f2.png)
