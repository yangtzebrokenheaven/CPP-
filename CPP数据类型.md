# 数据类型

## 1.整型

CPP中有一下几种方式创建不同的整形吗，区别在于所占内存空间不同

| short短整形           | 2    |
| --------------------- | ---- |
| **int整形**           | 4    |
| **long长整型**        | 4    |
| **long long长长整型** | 8    |

## 2.sizeof关键字

利用sizeof关键字可以统计数据类型所占内存的大小

```cpp
sizeof()
```

括号内既可是数据类型，也可以是变量名

## 3.浮点型

单精度float        -----4字节

双精度double   ------8字节

```cpp
float a = 11.12f;
double b = 11.22;
```

默认情况下输出的小数为6位

## 4.字符型

表示单个字母的类型

```cpp
char ch = 'a'
```

CPP中字符型变量只占用一个字节

若输入多个字母，即会输出最后一个字母

## 5.转义字符

常用于一些不能显示出来的ASCII字符

```cpp
\n 换行符
\\ 反斜杠，输出一个\
\t 水平制表符  \\8个字符空间
```

## 6.字符串型

```cpp
char str1[] = "Hello World";
string str2 = "Hello World";
```

第一种为C，第二种为CPP风格

## 7.布尔类型 bool

·true

·false

bool类型占用一个字节大小

## 8.数据的输入

从键盘获取数据

关键词：cin

```cpp
int a = 0;
cin >> a;
float b = 0.0f;
cin >> b;
string str = "Hello";
cin >> str;
```

**注意，要使用string类型需加入#include <string>头文件**

