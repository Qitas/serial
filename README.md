﻿[![sites](docs/Qi.png)](http://www.qitas.cn)

# USB设备

### 描述
主要是针对window下的USB通信，可用于制作上位机控制软件

USB通信相关，包括驱动和示例代码

## 组成

####  VCP

虚拟串口，通过将USB设备模拟成相应的CDC设备，在上位机上安装相关的驱动，通过通用的串口工具进行通信

####  HID

通过将USB外设生成HID设备，适配上位机软件进行通信，也可以生成对应的标准外设

## 说明

2018-10-12: 新增HID源码，可用于定制相关USB外设

[![sites](docs/qitas.jpg)](http://www.qitas.cn)
