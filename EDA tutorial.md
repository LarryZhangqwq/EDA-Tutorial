# EDA Tutorial

## 1. 什么是EDA

EDA: Electronic Design Automation（电子设计自动化）

* 百度百科：EDA技术就是以计算机为工具，设计者在EDA软件平台上，用硬件描述语言VerilgHDL完成设计文件，然后由计算机自动地完成逻辑编译、化简、分割、综合、优化、布局、布线和仿真，直至对于特定目标芯片的适配编译、逻辑映射和编程下载等工作。DEA技术的出现，极大的提高了电路设计的效率和可操作性。

### EDA的目标：

* IC设计制造
* FPGA/CPLD应用
* PCB（印制电路板）设计

### EDA技术发展历程：

CAD(计算机辅助设计) ---> CAE(计算机辅助工程) ---> EDA(电子设计自动化) ---> ESDA？

CAD：图纸的绘制在计算机上完成，电路模拟在计算机上完成。

CAE（上个世纪七八十年代）：在现有的电路版图基础上，计算机帮助完成布局布线。

EDA（九十年代）：代替手工设计SOC芯片，由人写出HDL语言，电脑进行转换。

ESDA：S指的是系统。

### EDA技术实现目标

![截屏2022-09-10 下午3.20.15](Image/截屏2022-09-10 下午3.20.15.png)



### FPGA/CPLD/ASIC是什么

FPGA：Field Progrmmable Gate Array（现场可编程门阵列）

CPLD：Complex Programmable Logic Device（复杂可编程逻辑器件）

CPLD因为容量较小，逐渐退出市场。

ASIC：Application Specific Integrated Circuit（专用集成电路）

ASIC现在泛指所有集成电路，有时候集成电路设计也被称为ASIC设计

