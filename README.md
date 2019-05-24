
# 编程语言 对比学习/速查

- [0.概览](./src/0.%E6%A6%82%E8%A7%88.md)
  - [hello](./src/0.%E6%A6%82%E8%A7%88.md#hello)
  - [helloword](./src/0.%E6%A6%82%E8%A7%88.md#helloword)
  - [Keywords（关键字/保留字）](./src/0.%E6%A6%82%E8%A7%88.md#Keywords%EF%BC%88%E5%85%B3%E9%94%AE%E5%AD%97%2F%E4%BF%9D%E7%95%99%E5%AD%97%EF%BC%89)
  - [Built-in types(内置的类型)](./src/0.%E6%A6%82%E8%A7%88.md#Built-in%20types(%E5%86%85%E7%BD%AE%E7%9A%84%E7%B1%BB%E5%9E%8B))
  - [重要概念](./src/0.%E6%A6%82%E8%A7%88.md#%E9%87%8D%E8%A6%81%E6%A6%82%E5%BF%B5)
  - [库/包/模块](./src/0.%E6%A6%82%E8%A7%88.md#%E5%BA%93%2F%E5%8C%85%2F%E6%A8%A1%E5%9D%97)
  - [目录结构](./src/0.%E6%A6%82%E8%A7%88.md#%E7%9B%AE%E5%BD%95%E7%BB%93%E6%9E%84)
  - [安装](./src/0.%E6%A6%82%E8%A7%88.md#%E5%AE%89%E8%A3%85)
  - [包管理](./src/0.%E6%A6%82%E8%A7%88.md#%E5%8C%85%E7%AE%A1%E7%90%86)
  - [格式化](./src/0.%E6%A6%82%E8%A7%88.md#%E6%A0%BC%E5%BC%8F%E5%8C%96)
  - [命令行](./src/0.%E6%A6%82%E8%A7%88.md#%E5%91%BD%E4%BB%A4%E8%A1%8C)
- [1.基础知识](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md)
  - [标识符](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#%E6%A0%87%E8%AF%86%E7%AC%A6)
  - [命名风格](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#%E5%91%BD%E5%90%8D%E9%A3%8E%E6%A0%BC)
    - [要使用 UpperCamelCase 风格来命名类型名称](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#%E8%A6%81%E4%BD%BF%E7%94%A8%20UpperCamelCase%20%E9%A3%8E%E6%A0%BC%E6%9D%A5%E5%91%BD%E5%90%8D%E7%B1%BB%E5%9E%8B%E5%90%8D%E7%A7%B0)
    - [要使用 lowercase_with_underscores 风格来命名库和文件名名字](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#%E8%A6%81%E4%BD%BF%E7%94%A8%20lowercase_with_underscores%20%E9%A3%8E%E6%A0%BC%E6%9D%A5%E5%91%BD%E5%90%8D%E5%BA%93%E5%92%8C%E6%96%87%E4%BB%B6%E5%90%8D%E5%90%8D%E5%AD%97)
    - [要使用 lowerCamelCase 风格来命名其他的标识符](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#%E8%A6%81%E4%BD%BF%E7%94%A8%20lowerCamelCase%20%E9%A3%8E%E6%A0%BC%E6%9D%A5%E5%91%BD%E5%90%8D%E5%85%B6%E4%BB%96%E7%9A%84%E6%A0%87%E8%AF%86%E7%AC%A6)
  - [Variables（变量）](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#Variables%EF%BC%88%E5%8F%98%E9%87%8F%EF%BC%89)
  - [私有变量](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#%E7%A7%81%E6%9C%89%E5%8F%98%E9%87%8F)
  - [常量](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#%E5%B8%B8%E9%87%8F)
  - [Default value（默认值）](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#Default%20value%EF%BC%88%E9%BB%98%E8%AE%A4%E5%80%BC%EF%BC%89)
  - [Comments（注释）](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#Comments%EF%BC%88%E6%B3%A8%E9%87%8A%EF%BC%89)
  - [打印](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#%E6%89%93%E5%8D%B0)
  - [Assert（断言）](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#Assert%EF%BC%88%E6%96%AD%E8%A8%80%EF%BC%89)
  - [Exceptions（异常）](./src/1.%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#Exceptions%EF%BC%88%E5%BC%82%E5%B8%B8%EF%BC%89)
- [2.数据类型](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md)
  - [Type test operators（类型判定/类型判断操作符）](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Type%20test%20operators%EF%BC%88%E7%B1%BB%E5%9E%8B%E5%88%A4%E5%AE%9A%2F%E7%B1%BB%E5%9E%8B%E5%88%A4%E6%96%AD%E6%93%8D%E4%BD%9C%E7%AC%A6%EF%BC%89)
  - [数字转换/整数转换/类型转换](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E6%95%B0%E5%AD%97%E8%BD%AC%E6%8D%A2%2F%E6%95%B4%E6%95%B0%E8%BD%AC%E6%8D%A2%2F%E7%B1%BB%E5%9E%8B%E8%BD%AC%E6%8D%A2)
  - [计算最大值和最小值](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E8%AE%A1%E7%AE%97%E6%9C%80%E5%A4%A7%E5%80%BC%E5%92%8C%E6%9C%80%E5%B0%8F%E5%80%BC)
  - [数学常量](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E6%95%B0%E5%AD%A6%E5%B8%B8%E9%87%8F)
  - [生成随机数](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E7%94%9F%E6%88%90%E9%9A%8F%E6%9C%BA%E6%95%B0)
  - [三角函数](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E4%B8%89%E8%A7%92%E5%87%BD%E6%95%B0)
  - [十进制浮点运算](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E5%8D%81%E8%BF%9B%E5%88%B6%E6%B5%AE%E7%82%B9%E8%BF%90%E7%AE%97)
  - [进制转换](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E8%BF%9B%E5%88%B6%E8%BD%AC%E6%8D%A2)
  - [Strings（字符串）](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Strings%EF%BC%88%E5%AD%97%E7%AC%A6%E4%B8%B2%EF%BC%89)
  - [多行字符串](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E5%A4%9A%E8%A1%8C%E5%AD%97%E7%AC%A6%E4%B8%B2)
  - [“原始 raw” 字符串](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E2%80%9C%E5%8E%9F%E5%A7%8B%20raw%E2%80%9D%20%E5%AD%97%E7%AC%A6%E4%B8%B2)
  - [Searching inside a string（在字符串内搜索）](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Searching%20inside%20a%20string%EF%BC%88%E5%9C%A8%E5%AD%97%E7%AC%A6%E4%B8%B2%E5%86%85%E6%90%9C%E7%B4%A2%EF%BC%89)
  - [Extracting data from a string（从字符串中提取数据/字符串截取）](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Extracting%20data%20from%20a%20string%EF%BC%88%E4%BB%8E%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E6%8F%90%E5%8F%96%E6%95%B0%E6%8D%AE%2F%E5%AD%97%E7%AC%A6%E4%B8%B2%E6%88%AA%E5%8F%96%EF%BC%89)
  - [Converting to uppercase or lowercase（大小写转换）](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Converting%20to%20uppercase%20or%20lowercase%EF%BC%88%E5%A4%A7%E5%B0%8F%E5%86%99%E8%BD%AC%E6%8D%A2%EF%BC%89)
  - [Trimming and empty strings（裁剪和判断空字符串）](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Trimming%20and%20empty%20strings%EF%BC%88%E8%A3%81%E5%89%AA%E5%92%8C%E5%88%A4%E6%96%AD%E7%A9%BA%E5%AD%97%E7%AC%A6%E4%B8%B2%EF%BC%89)
  - [Replacing part of a string（替换部分字符）](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Replacing%20part%20of%20a%20string%EF%BC%88%E6%9B%BF%E6%8D%A2%E9%83%A8%E5%88%86%E5%AD%97%E7%AC%A6%EF%BC%89)
  - [格式化输出](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E6%A0%BC%E5%BC%8F%E5%8C%96%E8%BE%93%E5%87%BA)
  - [list/array列表/数组定义及操作](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#list%2Farray%E5%88%97%E8%A1%A8%2F%E6%95%B0%E7%BB%84%E5%AE%9A%E4%B9%89%E5%8F%8A%E6%93%8D%E4%BD%9C)
  - [列表推导式](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E5%88%97%E8%A1%A8%E6%8E%A8%E5%AF%BC%E5%BC%8F)
  - [列表/数组的高阶函数](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E5%88%97%E8%A1%A8%2F%E6%95%B0%E7%BB%84%E7%9A%84%E9%AB%98%E9%98%B6%E5%87%BD%E6%95%B0)
  - [tuple 元组定义及操作](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#tuple%20%E5%85%83%E7%BB%84%E5%AE%9A%E4%B9%89%E5%8F%8A%E6%93%8D%E4%BD%9C)
  - [Maps/dict(字典)](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Maps%2Fdict(%E5%AD%97%E5%85%B8))
  - [从 map 中删除 key 和 value](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E4%BB%8E%20map%20%E4%B8%AD%E5%88%A0%E9%99%A4%20key%20%E5%92%8C%20value)
  - [Maps(字典)遍历，获取 map 的所有 key 和 value](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Maps(%E5%AD%97%E5%85%B8)%E9%81%8D%E5%8E%86%EF%BC%8C%E8%8E%B7%E5%8F%96%20map%20%E7%9A%84%E6%89%80%E6%9C%89%20key%20%E5%92%8C%20value)
  - [判断 map 是否包含一个 key](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E5%88%A4%E6%96%AD%20map%20%E6%98%AF%E5%90%A6%E5%8C%85%E5%90%AB%E4%B8%80%E4%B8%AA%20key)
  - [Set 集合定义及操作](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Set%20%E9%9B%86%E5%90%88%E5%AE%9A%E4%B9%89%E5%8F%8A%E6%93%8D%E4%BD%9C)
  - [判断Iterable集合（List, Set, 和 Map）是否为空的](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E5%88%A4%E6%96%ADIterable%E9%9B%86%E5%90%88%EF%BC%88List%2C%20Set%2C%20%E5%92%8C%20Map%EF%BC%89%E6%98%AF%E5%90%A6%E4%B8%BA%E7%A9%BA%E7%9A%84)
  - [（List, Set, 和 Map）常用的集合函数](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%EF%BC%88List%2C%20Set%2C%20%E5%92%8C%20Map%EF%BC%89%E5%B8%B8%E7%94%A8%E7%9A%84%E9%9B%86%E5%90%88%E5%87%BD%E6%95%B0)
  - [序列和其它类型的比较](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E5%BA%8F%E5%88%97%E5%92%8C%E5%85%B6%E5%AE%83%E7%B1%BB%E5%9E%8B%E7%9A%84%E6%AF%94%E8%BE%83)
  - [检查两个引用是否指向同一个对象(内存地址)](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#%E6%A3%80%E6%9F%A5%E4%B8%A4%E4%B8%AA%E5%BC%95%E7%94%A8%E6%98%AF%E5%90%A6%E6%8C%87%E5%90%91%E5%90%8C%E4%B8%80%E4%B8%AA%E5%AF%B9%E8%B1%A1(%E5%86%85%E5%AD%98%E5%9C%B0%E5%9D%80))
  - [Symbols](./src/2.%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.md#Symbols)
- [3.操作符及流程控制](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md)
  - [Arithmetic operators（算术操作符）](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#Arithmetic%20operators%EF%BC%88%E7%AE%97%E6%9C%AF%E6%93%8D%E4%BD%9C%E7%AC%A6%EF%BC%89)
  - [Equality and relational operators（相等相关的操作符）](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#Equality%20and%20relational%20operators%EF%BC%88%E7%9B%B8%E7%AD%89%E7%9B%B8%E5%85%B3%E7%9A%84%E6%93%8D%E4%BD%9C%E7%AC%A6%EF%BC%89)
  - [Type test operators（类型判定操作符）](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#Type%20test%20operators%EF%BC%88%E7%B1%BB%E5%9E%8B%E5%88%A4%E5%AE%9A%E6%93%8D%E4%BD%9C%E7%AC%A6%EF%BC%89)
  - [Assignment operators（赋值操作符）](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#Assignment%20operators%EF%BC%88%E8%B5%8B%E5%80%BC%E6%93%8D%E4%BD%9C%E7%AC%A6%EF%BC%89)
  - [Logical operators（逻辑操作符）](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#Logical%20operators%EF%BC%88%E9%80%BB%E8%BE%91%E6%93%8D%E4%BD%9C%E7%AC%A6%EF%BC%89)
  - [Bitwise and shift operators（位和移位操作符）](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#Bitwise%20and%20shift%20operators%EF%BC%88%E4%BD%8D%E5%92%8C%E7%A7%BB%E4%BD%8D%E6%93%8D%E4%BD%9C%E7%AC%A6%EF%BC%89)
  - [Conditional expressions（条件表达式）/三元操作符](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#Conditional%20expressions%EF%BC%88%E6%9D%A1%E4%BB%B6%E8%A1%A8%E8%BE%BE%E5%BC%8F%EF%BC%89%2F%E4%B8%89%E5%85%83%E6%93%8D%E4%BD%9C%E7%AC%A6)
  - [Cascade notation (..)（级联操作符）](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#Cascade%20notation%20(..)%EF%BC%88%E7%BA%A7%E8%81%94%E6%93%8D%E4%BD%9C%E7%AC%A6%EF%BC%89)
  - [条件成员访问](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#%E6%9D%A1%E4%BB%B6%E6%88%90%E5%91%98%E8%AE%BF%E9%97%AE)
  - [If and else](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#If%20and%20else)
  - [For loops](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#For%20loops)
  - [range() 函数](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#range()%20%E5%87%BD%E6%95%B0)
  - [While and do-while](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#While%20and%20do-while)
  - [Break and continue](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#Break%20and%20continue)
  - [pass 语句](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#pass%20%E8%AF%AD%E5%8F%A5)
  - [Switch and case](./src/3.%E6%93%8D%E4%BD%9C%E7%AC%A6%E5%8F%8A%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6.md#Switch%20and%20case)
- [4.函数和方法](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md)
  - [Functions（方法）函数定义](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#Functions%EF%BC%88%E6%96%B9%E6%B3%95%EF%BC%89%E5%87%BD%E6%95%B0%E5%AE%9A%E4%B9%89)
  - [Optional named parameters（可选命名参数）](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#Optional%20named%20parameters%EF%BC%88%E5%8F%AF%E9%80%89%E5%91%BD%E5%90%8D%E5%8F%82%E6%95%B0%EF%BC%89)
  - [Optional positional parameters（可选位置参数）](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#Optional%20positional%20parameters%EF%BC%88%E5%8F%AF%E9%80%89%E4%BD%8D%E7%BD%AE%E5%8F%82%E6%95%B0%EF%BC%89)
  - [Default parameter values（默认参数值）](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#Default%20parameter%20values%EF%BC%88%E9%BB%98%E8%AE%A4%E5%8F%82%E6%95%B0%E5%80%BC%EF%BC%89)
  - [解包参数列表](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#%E8%A7%A3%E5%8C%85%E5%8F%82%E6%95%B0%E5%88%97%E8%A1%A8)
  - [The main() function（入口函数）](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#The%20main()%20function%EF%BC%88%E5%85%A5%E5%8F%A3%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Functions as first-class objects（一等方法对象）](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#Functions%20as%20first-class%20objects%EF%BC%88%E4%B8%80%E7%AD%89%E6%96%B9%E6%B3%95%E5%AF%B9%E8%B1%A1%EF%BC%89)
  - [Anonymous functions（匿名方法）匿名函数](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#Anonymous%20functions%EF%BC%88%E5%8C%BF%E5%90%8D%E6%96%B9%E6%B3%95%EF%BC%89%E5%8C%BF%E5%90%8D%E5%87%BD%E6%95%B0)
  - [函数标注](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#%E5%87%BD%E6%95%B0%E6%A0%87%E6%B3%A8)
  - [Lexical scope（静态作用域）](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#Lexical%20scope%EF%BC%88%E9%9D%99%E6%80%81%E4%BD%9C%E7%94%A8%E5%9F%9F%EF%BC%89)
  - [Lexical closures（词法闭包）](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#Lexical%20closures%EF%BC%88%E8%AF%8D%E6%B3%95%E9%97%AD%E5%8C%85%EF%BC%89)
  - [Testing functions for equality（测试函数是否相等）](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#Testing%20functions%20for%20equality%EF%BC%88%E6%B5%8B%E8%AF%95%E5%87%BD%E6%95%B0%E6%98%AF%E5%90%A6%E7%9B%B8%E7%AD%89%EF%BC%89)
  - [Return values（默认返回值）](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#Return%20values%EF%BC%88%E9%BB%98%E8%AE%A4%E8%BF%94%E5%9B%9E%E5%80%BC%EF%BC%89)
  - [立即调用的函数表达式（IIFE）](./src/4.%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%B9%E6%B3%95.md#%E7%AB%8B%E5%8D%B3%E8%B0%83%E7%94%A8%E7%9A%84%E5%87%BD%E6%95%B0%E8%A1%A8%E8%BE%BE%E5%BC%8F%EF%BC%88IIFE%EF%BC%89)
- [5.类](./src/5.%E7%B1%BB.md)
  - [Classes 类定义及用法](./src/5.%E7%B1%BB.md#Classes%20%E7%B1%BB%E5%AE%9A%E4%B9%89%E5%8F%8A%E7%94%A8%E6%B3%95)
  - [Instance variables 实例变量](./src/5.%E7%B1%BB.md#Instance%20variables%20%E5%AE%9E%E4%BE%8B%E5%8F%98%E9%87%8F)
  - [私有变量](./src/5.%E7%B1%BB.md#%E7%A7%81%E6%9C%89%E5%8F%98%E9%87%8F)
  - [Constructors 构造函数](./src/5.%E7%B1%BB.md#Constructors%20%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0)
  - [Default constructors（默认构造函数）](./src/5.%E7%B1%BB.md#Default%20constructors%EF%BC%88%E9%BB%98%E8%AE%A4%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Named constructors（命名构造函数）](./src/5.%E7%B1%BB.md#Named%20constructors%EF%BC%88%E5%91%BD%E5%90%8D%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Invoking a non-default superclass constructor（调用超类构造函数）](./src/5.%E7%B1%BB.md#Invoking%20a%20non-default%20superclass%20constructor%EF%BC%88%E8%B0%83%E7%94%A8%E8%B6%85%E7%B1%BB%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Initializer list（初始化列表）](./src/5.%E7%B1%BB.md#Initializer%20list%EF%BC%88%E5%88%9D%E5%A7%8B%E5%8C%96%E5%88%97%E8%A1%A8%EF%BC%89)
  - [Redirecting constructors（重定向构造函数）](./src/5.%E7%B1%BB.md#Redirecting%20constructors%EF%BC%88%E9%87%8D%E5%AE%9A%E5%90%91%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Constant constructors（常量构造函数）](./src/5.%E7%B1%BB.md#Constant%20constructors%EF%BC%88%E5%B8%B8%E9%87%8F%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Factory constructors（工厂方法构造函数）](./src/5.%E7%B1%BB.md#Factory%20constructors%EF%BC%88%E5%B7%A5%E5%8E%82%E6%96%B9%E6%B3%95%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Instance methods（实例函数）](./src/5.%E7%B1%BB.md#Instance%20methods%EF%BC%88%E5%AE%9E%E4%BE%8B%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Getters and setters](./src/5.%E7%B1%BB.md#Getters%20and%20setters)
  - [Abstract methods（抽象函数）](./src/5.%E7%B1%BB.md#Abstract%20methods%EF%BC%88%E6%8A%BD%E8%B1%A1%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Overridable operators（可覆写的操作符）](./src/5.%E7%B1%BB.md#Overridable%20operators%EF%BC%88%E5%8F%AF%E8%A6%86%E5%86%99%E7%9A%84%E6%93%8D%E4%BD%9C%E7%AC%A6%EF%BC%89)
  - [Abstract classes（抽象类）](./src/5.%E7%B1%BB.md#Abstract%20classes%EF%BC%88%E6%8A%BD%E8%B1%A1%E7%B1%BB%EF%BC%89)
  - [Implicit interfaces（隐式接口）](./src/5.%E7%B1%BB.md#Implicit%20interfaces%EF%BC%88%E9%9A%90%E5%BC%8F%E6%8E%A5%E5%8F%A3%EF%BC%89)
  - [Extending a class（扩展类）继承](./src/5.%E7%B1%BB.md#Extending%20a%20class%EF%BC%88%E6%89%A9%E5%B1%95%E7%B1%BB%EF%BC%89%E7%BB%A7%E6%89%BF)
  - [Enumerated types（枚举类型）](./src/5.%E7%B1%BB.md#Enumerated%20types%EF%BC%88%E6%9E%9A%E4%B8%BE%E7%B1%BB%E5%9E%8B%EF%BC%89)
  - [Adding features to a class: mixins（为类添加新的功能）多重继承](./src/5.%E7%B1%BB.md#Adding%20features%20to%20a%20class%3A%20mixins%EF%BC%88%E4%B8%BA%E7%B1%BB%E6%B7%BB%E5%8A%A0%E6%96%B0%E7%9A%84%E5%8A%9F%E8%83%BD%EF%BC%89%E5%A4%9A%E9%87%8D%E7%BB%A7%E6%89%BF)
  - [Static variables（静态变量）](./src/5.%E7%B1%BB.md#Static%20variables%EF%BC%88%E9%9D%99%E6%80%81%E5%8F%98%E9%87%8F%EF%BC%89)
  - [Static methods（静态函数）](./src/5.%E7%B1%BB.md#Static%20methods%EF%BC%88%E9%9D%99%E6%80%81%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Callable classes（可调用的类）](./src/5.%E7%B1%BB.md#Callable%20classes%EF%BC%88%E5%8F%AF%E8%B0%83%E7%94%A8%E7%9A%84%E7%B1%BB%EF%BC%89)
  - [Implementing map keys 自定义 hash 码](./src/5.%E7%B1%BB.md#Implementing%20map%20keys%20%E8%87%AA%E5%AE%9A%E4%B9%89%20hash%20%E7%A0%81)
  - [Iteration 可迭代对象](./src/5.%E7%B1%BB.md#Iteration%20%E5%8F%AF%E8%BF%AD%E4%BB%A3%E5%AF%B9%E8%B1%A1)
  - [Typedefs](./src/5.%E7%B1%BB.md#Typedefs)
- [6.语法专题](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md)
  - [Generics（泛型）](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Generics%EF%BC%88%E6%B3%9B%E5%9E%8B%EF%BC%89)
  - [Using collection literals（使用集合字面量）](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Using%20collection%20literals%EF%BC%88%E4%BD%BF%E7%94%A8%E9%9B%86%E5%90%88%E5%AD%97%E9%9D%A2%E9%87%8F%EF%BC%89)
  - [Using parameterized types with constructors（在构造函数中使用泛型）](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Using%20parameterized%20types%20with%20constructors%EF%BC%88%E5%9C%A8%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0%E4%B8%AD%E4%BD%BF%E7%94%A8%E6%B3%9B%E5%9E%8B%EF%BC%89)
  - [泛型判断](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#%E6%B3%9B%E5%9E%8B%E5%88%A4%E6%96%AD)
  - [Restricting the parameterized type（限制泛型类型）](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Restricting%20the%20parameterized%20type%EF%BC%88%E9%99%90%E5%88%B6%E6%B3%9B%E5%9E%8B%E7%B1%BB%E5%9E%8B%EF%BC%89)
  - [Using generic methods（使用泛型函数）](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Using%20generic%20methods%EF%BC%88%E4%BD%BF%E7%94%A8%E6%B3%9B%E5%9E%8B%E5%87%BD%E6%95%B0%EF%BC%89)
  - [Asynchrony support（异步支持）](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Asynchrony%20support%EF%BC%88%E5%BC%82%E6%AD%A5%E6%94%AF%E6%8C%81%EF%BC%89)
  - [Declaring async functions（声明异步方法）](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Declaring%20async%20functions%EF%BC%88%E5%A3%B0%E6%98%8E%E5%BC%82%E6%AD%A5%E6%96%B9%E6%B3%95%EF%BC%89)
  - [Using await expressions with Futures（使用 await 表达式）](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Using%20await%20expressions%20with%20Futures%EF%BC%88%E4%BD%BF%E7%94%A8%20await%20%E8%A1%A8%E8%BE%BE%E5%BC%8F%EF%BC%89)
  - [Using asynchronous for loops with Streams（在循环中使用异步）](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Using%20asynchronous%20for%20loops%20with%20Streams%EF%BC%88%E5%9C%A8%E5%BE%AA%E7%8E%AF%E4%B8%AD%E4%BD%BF%E7%94%A8%E5%BC%82%E6%AD%A5%EF%BC%89)
  - [并发/同时触发/竞争触发](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#%E5%B9%B6%E5%8F%91%2F%E5%90%8C%E6%97%B6%E8%A7%A6%E5%8F%91%2F%E7%AB%9E%E4%BA%89%E8%A7%A6%E5%8F%91)
  - [异步的错误捕获](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#%E5%BC%82%E6%AD%A5%E7%9A%84%E9%94%99%E8%AF%AF%E6%8D%95%E8%8E%B7)
  - [生成器](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#%E7%94%9F%E6%88%90%E5%99%A8)
  - [Metadata（元数据）注解/装饰器](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Metadata%EF%BC%88%E5%85%83%E6%95%B0%E6%8D%AE%EF%BC%89%E6%B3%A8%E8%A7%A3%2F%E8%A3%85%E9%A5%B0%E5%99%A8)
  - [Regular expressions（正则表达式）](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#Regular%20expressions%EF%BC%88%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F%EF%BC%89)
  - [new 命令](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#new%20%E5%91%BD%E4%BB%A4)
  - [this关键字](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#this%E5%85%B3%E9%94%AE%E5%AD%97)
  - [原型链](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#%E5%8E%9F%E5%9E%8B%E9%93%BE)
  - [获取对象的所有属性](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#%E8%8E%B7%E5%8F%96%E5%AF%B9%E8%B1%A1%E7%9A%84%E6%89%80%E6%9C%89%E5%B1%9E%E6%80%A7)
  - [对象的拷贝](./src/6.%E8%AF%AD%E6%B3%95%E4%B8%93%E9%A2%98.md#%E5%AF%B9%E8%B1%A1%E7%9A%84%E6%8B%B7%E8%B4%9D)
- [7.常用对象或方法](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md)
  - [内置函数](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#%E5%86%85%E7%BD%AE%E5%87%BD%E6%95%B0)
  - [Encoding and decoding fully qualified URIs（编码解码URI）](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Encoding%20and%20decoding%20fully%20qualified%20URIs%EF%BC%88%E7%BC%96%E7%A0%81%E8%A7%A3%E7%A0%81URI%EF%BC%89)
  - [Encoding and decoding URI components（编码解码URI组件）](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Encoding%20and%20decoding%20URI%20components%EF%BC%88%E7%BC%96%E7%A0%81%E8%A7%A3%E7%A0%81URI%E7%BB%84%E4%BB%B6%EF%BC%89)
  - [Parsing URIs](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Parsing%20URIs)
  - [Building URIs](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Building%20URIs)
  - [Dates and times 日期和时间](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Dates%20and%20times%20%E6%97%A5%E6%9C%9F%E5%92%8C%E6%97%B6%E9%97%B4)
  - [Comparing objects（比较对象）](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Comparing%20objects%EF%BC%88%E6%AF%94%E8%BE%83%E5%AF%B9%E8%B1%A1%EF%BC%89)
  - [Finding elements](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Finding%20elements)
  - [Manipulating elements](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Manipulating%20elements)
  - [Creating elements](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Creating%20elements)
  - [Adding, replacing, and removing nodes](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Adding%2C%20replacing%2C%20and%20removing%20nodes)
  - [Manipulating CSS styles](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Manipulating%20CSS%20styles)
  - [Handling events](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Handling%20events)
  - [Getting data from the server](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Getting%20data%20from%20the%20server)
  - [Sending data to the server](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Sending%20data%20to%20the%20server)
  - [Sending and receiving real-time data with WebSockets](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Sending%20and%20receiving%20real-time%20data%20with%20WebSockets)
  - [HTTP server](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#HTTP%20server)
  - [HTTP client](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#HTTP%20client)
  - [Reading a file as text 读取整个文本](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Reading%20a%20file%20as%20text%20%E8%AF%BB%E5%8F%96%E6%95%B4%E4%B8%AA%E6%96%87%E6%9C%AC)
  - [Reading a file as binary 把文件数据读取为字节流](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Reading%20a%20file%20as%20binary%20%E6%8A%8A%E6%96%87%E4%BB%B6%E6%95%B0%E6%8D%AE%E8%AF%BB%E5%8F%96%E4%B8%BA%E5%AD%97%E8%8A%82%E6%B5%81)
  - [Streaming file contents 一点点的/逐行读取](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Streaming%20file%20contents%20%E4%B8%80%E7%82%B9%E7%82%B9%E7%9A%84%2F%E9%80%90%E8%A1%8C%E8%AF%BB%E5%8F%96)
  - [Writing file contents 写入内容](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Writing%20file%20contents%20%E5%86%99%E5%85%A5%E5%86%85%E5%AE%B9)
  - [Listing files in a directory 查找目录中的所有文件和子目录](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Listing%20files%20in%20a%20directory%20%E6%9F%A5%E6%89%BE%E7%9B%AE%E5%BD%95%E4%B8%AD%E7%9A%84%E6%89%80%E6%9C%89%E6%96%87%E4%BB%B6%E5%92%8C%E5%AD%90%E7%9B%AE%E5%BD%95)
  - [Decoding and encoding JSON](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Decoding%20and%20encoding%20JSON)
  - [Decoding and encoding UTF-8 characters](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Decoding%20and%20encoding%20UTF-8%20characters)
  - [Base64](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#Base64)
  - [操作系统接口](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E6%8E%A5%E5%8F%A3)
  - [模板](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#%E6%A8%A1%E6%9D%BF)
  - [日志](./src/7.%E5%B8%B8%E7%94%A8%E5%AF%B9%E8%B1%A1%E6%88%96%E6%96%B9%E6%B3%95.md#%E6%97%A5%E5%BF%97)
- [8.算法](./src/8.%E7%AE%97%E6%B3%95.md)
  - [斐波那契数列](./src/8.%E7%AE%97%E6%B3%95.md#%E6%96%90%E6%B3%A2%E9%82%A3%E5%A5%91%E6%95%B0%E5%88%97)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)
  - [hello](./src/8.%E7%AE%97%E6%B3%95.md#hello)

![编程语言学习大纲](./src/images/language.png)
