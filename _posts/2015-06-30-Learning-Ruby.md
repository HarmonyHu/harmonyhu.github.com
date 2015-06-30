---
layout: post
title:  ruby学习整理
date:   2015-06-30
summary:
categories:
---
###执行方式  
1. 单行执行：`ruby -e 'print "hello,world"'`  
2. 交互方式：`irb`;使用`exit`退出  
3. 文件方式：`ruby test.rb`

###数据类型
1. **数字**  
1e3   => 1000  
1.0e3 => 1000.0  
012   => 10  
0x12  => 18  
0b11  => 3  

2. **数组**  
array = []; //定义空数组  
[2.4,99,"hello",[1,2]]; //包含各种类型的成员
array<<"f"<<2;  //加入元素，["f",2]
array+=["f"]+[2]； //数组相加，["f",2]
array<<["f"]<<[2]; //注意与+的差别，[["f],[2]]  

3. **字符**  
str = "hello,world"; //定义字符串  
"a"+"bc"; //"abc"  
"a"<<"bc"; //"abc"  
"ab"*3;  //"ababab"  
x=5;"x is #{x}"; //"x is 5"  
65.chr;  //"A"  
"A".ord;  //65  
"0x%x"%65;  //"0x41"  
"123".to_i; //123  
 
4. **区间**  
1..5 =>[1,5]
1...5 =>[1,5)

###控制语句
1. **条件判断语句**  
if ... elsif ... else ... end  
(...)if...  
case ... when ... when ... else ...end  
unless = if not  
