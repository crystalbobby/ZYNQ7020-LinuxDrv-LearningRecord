# 基于ALINX-AX7020开发板的Linux驱动学习。
--------------------------------------------
### ZYNQ上的Linux资料很少，毕竟本身也不是专门跑Linux的平台。不过借助Xilinx的一套开发工具，搭建板端的Linux系统还是很方便的。
### 主要涉及到工具有：PC端vivado、ubuntu端vivado、ubuntu端petalinux，vivado用来配置PL端(fpga)硬件资源，petalinux工具则用来快速搭建系统。具体操作，建议参考ALINX的教程，都是开源的资料，里面有详细的讲解。

### ubuntu系统是使用VM搭建的虚拟机，版本是16.04.6，Xilinx的工具。

### 关于用到的Linux指令，就不专门做介绍了。就算不熟悉也没必要刻意花时间去记忆，四个字熟能生巧。
### 哪怕每次要用到的时候都要去搜索一下，也总会有烂熟于心的一天。
------------------------------
### 会按项目持续更新，每个项目形式为：驱动程序(+设备树)+测试程序+实验教程。
### 若内容错误请务必不吝指正！
--------------------------------------
<---------------已更新---------------->
=======================================
||==== 1.字符设备
=======================================
||==== 2.字符设备的新写法
=======================================
||==== 3.设备树与of函数
=======================================
||==== 4.pinctrl和gpio子系统
=======================================
||==== 5.并发
=======================================
||==== 6.gpio输入
=======================================
||==== 7.定时器
=======================================
