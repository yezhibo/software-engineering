# 一、Java 基本程序设计结构
## 1.8种基本数据类型
整型：byte(1字节 8bit)、short(2字节 16bit)、int(4字节 32bit)、long(8字节 64bit)<br>
浮点型：float(4字节)、double(8字节)<br>
字符型：char(2字节)<br>
布尔型：boolean
c和c++的整型大小与平台相关。

## 2.运算符和变量

### 变量
变量的声明要尽量靠近变量第一次使用的地方。<br>
double x = 9.997;<br>
int n = (int)x;<br>
强制转换为截掉小数部分后的整数。<br>
### 常量
常量：利用关键字final修饰的变量为常量。<br>
### 运算符
数学运算符：+ - * / % <br>
结合赋值：+= -=  <br>
自增自减运算符：++ --<br>
关系运算符：&& || x<y?x:y <br>
位运算符：& | ^ ~ <br>

## 3.字符串（String）
### 子串
substring(startIndex, length)<br>
### 拼接
1.直接相加<br>
2.join(分割符,str1,str2,...)<br>
### 检测字符串是否相等
equals()
### 空串与null串
空串""是长度为0的字符串<br>
null是一个特殊值，表示目前没有任何对象与该变量关联。
## 4.输入输出
### 输入
通过创建Scanner对象来获取控制台输入流;<br>
常用方法： nextLine()读取下一行、next()读取下一个单词以空格为分隔符、nextDouble()读取下一个浮点数、nextInt()读取下一个整数、hasNext()判断是否还有其他单词<br>
### 输出
System.out.printf("",x);<br>
## 5.控制流程
switch case语句，case标签可以是：<br>
类型为char、byte、short或者int表达式
枚举常量
从javase7开始支持字符串字面量
## 6.大数值
BigInteger
BigDecimal
## 7.数组
int[] a = new int[100]; 数组在定义时需要给出数组的长度。<br>
int[] a = {1,2,3,4,5,6,7,8}; 初始化数组。<br>
a = new int[]{1,2,3,4,5,6,7,8};<br>
Arrays类是对数组进行操作的类<br>
for(variable : colection) statement;
# 二、对象与类

# 三、继承

# 四、接口、lambda表达式与内部类

# 五、异常、断言和日志

# 六、泛型程序设计

# 七、集合

# 八、并发
