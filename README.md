# MFRP MZY7灵活无线协议（非商用）
本协议针对nRF24L01及其兼容芯片设计，保留了对其它芯片的兼容开发空间。  
当前版本为`v0.1`。  

## 目录
- [1 概述](characters/1)
  - [1.1 协议设计的原理](characters/1#1_1_协议设计的原理)
  - [1.2 协议的术语](characters/1#1_2_协议的术语)
  - [1.3 协议的特性](characters/1#1_3_协议的特性)
  - [1.4 协议的局限性](characters/1#1_4_协议的局限性)
- [2 协议结构](characters/2)
  - [2.1 物理层](characters/2#2_1_物理层)
  - [2.2 数据链路层](characters/2#2_2_数据链路层)
  - [2.3 网络层](characters/2#2_3_网络层)
  - [2.4 用户层](characters/2#2_4_用户层)
- [3 协议依赖的HAL函数](characters/3)
- [4 物理层及原理实现](characters/4)
  - [4.1 无线外设的驱动](characters/4#4_1_无线外设的驱动)
- [5 数据链路层及原理实现](characters/5)
  - [5.1 低层帧](characters/5#5_1_低层帧)
  - [5.2 低层逻辑](characters/5#5_2_低层逻辑)
- [6 网络层及原理实现](characters/6)
- [7 用户层](characters/7)
  - [7.1 集成协议](characters/7#7_1_集成协议)
- [8 需要注意的问题](characters/8)
