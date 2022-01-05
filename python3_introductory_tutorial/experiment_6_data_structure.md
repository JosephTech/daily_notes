## list基本语法

注意:  和c++的区别  
c++明确  
python优雅易用  

## 栈, 队列,  双端队列,  从中间操作的队列
栈就像杯子  
python的list可以当栈,   
可以  **.pop(),  返回最后一个**  
**.pop(0), 返回第一个**  
(这tnnd的,  就是个双端队列啊)  

最马叉虫的是,  **还能 .pop(中间的idx)**,   能操作中间位置的队列,   牛到家了,  这空间复杂度多少?  时间复杂度多少?  夸张  

## 列表推倒式
可以lambda,  (太秀了)  

![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640913114005)

可以list = [x*x for x in range(10)],  太美了,  还可以跟if,  **反正就是写逻辑**  
**注意:**  python的平方,  可以x**2

![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641257413834)

![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640912962321)


![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640912974460)

**相当于**
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641257577774)


列表推倒式, 可以嵌套,  **注意: 先算最内层的**
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640913367939)
**相当于**

![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641257756072)




## 元组
逗号就能 定义元组, (太秀了)  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640914050702)

for()能遍历元组
**注意: print(,  end = ' ') 可定义分隔符,  改换行符为空格**
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640914065261)


divmod()返回元组    
(整数部分, 余数部分)  = divmod(被除数, 除数)  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640914291784)

元组可括号定义,  
元组中元素不可改变(即不可赋值assignment),   亦不可删除
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640914452317)
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640914513579)

**逗号才是元组的灵魂**  
括号只是让人看的  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640914616278)

len()可以查看长度  
len()是**内置函数或方法**  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20211231-1640914735548)

## 集合set
{}创建有元素的集合,  自动去重  
创建空集合,  必须用set(),  
{}是创建空字典的  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641258450419)

**set()传入一个字符串, 只会是一堆char**  
(不知道python搞这么奇葩,  干啥)
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641258407014)

.pop()随机弹元素  
.add()添加元素
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641258908865)

## 字典dict()
(为啥不直接叫map?)  
键值对 唯一  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641259209232)
创建键值对  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641259313925)
关键字 del 删除  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641259379518)
关键字 in 判断  
(c++要map.find(key)!=map.end() 或者 map.count(key))   
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641259429520)  

dict()太丑了,  要两层括号  
就是传入一个元组(),     套元组(k, v)
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641259627221)
.items() 能遍历每个(k, v)  
**注意:  返回的是元组**  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641259897884)
## 考试成绩


![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641261744735)

测试:  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220104-1641261632989)

## 矩阵Hadamard乘积(阿达马, 马大哈)
(还是我的代码好看)  
**注意: 每次输入一行, 按空格分割**  
所以是   [这行.splict(' ')]  
![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220105-1641392610810)  

str()把int转换为字符串, 相当于c++的to_string()  
string.rjust(5)能往右调 5格  

![图片描述](https://dn-simplecloud.shiyanlou.com/courses/uid1784844-20220105-1641392511707)