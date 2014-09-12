free：显示内存的使用情况，包括实体内存，虚拟的交换文件内存，共享内存区段，以及系统核心使用的缓冲区等。

语法： free [-bkmotV][-s <间隔秒数>]
参数：

- -b 　以Byte为单位显示内存使用情况。
- -k 　以KB为单位显示内存使用情况。
- -m 　以MB为单位显示内存使用情况。
- -o 　不显示缓冲区调节列。
- -s  <间隔秒数> 持续观察内存使用状况。
- -t 　显示内存总和列。
- -V 　显示版本信息。

![](https://raw.githubusercontent.com/melin/LinuxPerformanceTools/master/images/free.jpg)

参考资料：

1.[Linux上的free命令详解 ](http://www.cnblogs.com/coldplayerest/archive/2010/02/20/1669949.html)

2.[Linux内存管理及Free命令详解](http://www.askoracle.org/linux/base/528.html)