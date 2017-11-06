# Android-Android 复习提高
## Java SE
### 八种基本数据类型
八种基本数据类型 ：[http://www.cnblogs.com/1130136248wlxk/articles/5105524.html]  
整型六种  
byte  
    8位有符号 以2进制补码表示的整数 总共有256个数字 占位1字节  
    最小值 -128（-2^7）  最大值 127（2^7-1）  默认值 0   
    byte类型用在大型数组中节约空间，主要代替整数，因为byte变量占用的空间只有int类型的四分之一  
    例子：byte a = 13，byte b = -50。  
short
    16位有符号 以2进制补码表示的整数 占位2字节
    最小值是-9,223,372,036,854,775,808（-2^63）最大值是9,223,372,036,854,775,807（2^63 -1） 默认值 0
    Short数据类型也可以像byte那样节省空间。一个short变量是int型变量所占空间的二分之一
    例子：short a = 1000，short b = -2000
int
    64位有符号 以2进制补码表示的整数 占位4字节
    最小值是-2,147,483,648（-2^31） 最大值是2,147,485,647（2^31 - 1） 默认值 0
    一般默认整形是int型
    例子：int a = 100000，int b = -200000
long
    32位有符号 以2进制补码表示的整数 占位3字节
    最小值是-2,147,483,648（-2^31） 最大值是2,147,485,647（2^31 - 1） 默认值 0L
    这种类型主要使用在需要比较大整数的系统上
    例子：long a = 10000000L，short b = -200000000L
    long a=111111111111111111111111(错误，整数型变量默认是int型)
    long a=111111111111111111111111L(正确，强制转换)
