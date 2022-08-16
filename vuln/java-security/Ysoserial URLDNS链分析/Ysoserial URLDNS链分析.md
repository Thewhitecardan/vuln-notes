# ysoserial学习 URLDNS链

## 0x01 关于ysoserial

**ysoserial**是java反序列化中常用的工具，内部集成了很多利用链。堪称为“java反序列利用神器”。

项目地址：https://github.com/frohoff/ysoserial

## 0x02 ysoseial 项目启动&初步分析

通过github获取ysoserial的项目源码，拖入idea中，发现pom.xml，是Maven项目，刷新拉取依赖

![1](./img\1.png)

发现拉去依赖后仍有一部分缺少依赖报错的情况，但是不会影响程序运行，通过对pom.xml文件的简单分析，可以找到图中的"mainClass"即主执行类或者可以理解为程序入口点。

