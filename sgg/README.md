## 介绍

> 来源Bilibili尚硅谷宋红康老师JVM教程：[硅谷2020最新版宋红康JVM教程](https://www.bilibili.com/video/BV1PJ411n7xZ)

## 目录

### 内存与垃圾回收篇

- [JVM与Java体系结构](./1_内存与垃圾回收篇/1_JVM与Java体系结构)
- [类加载子系统](./1_内存与垃圾回收篇/2_类加载子系统)
- [运行时数据区概述及线程](./1_内存与垃圾回收篇/3_运行时数据区概述及线程)
- [程序计数器](./1_内存与垃圾回收篇/4_程序计数器)
- [虚拟机栈](./1_内存与垃圾回收篇/5_虚拟机栈)
- [本地方法接口](./1_内存与垃圾回收篇/6_本地方法接口)
- [本地方法栈](./1_内存与垃圾回收篇/7_本地方法栈)
- [堆](./1_内存与垃圾回收篇/8_堆)
- [方法区](./1_内存与垃圾回收篇/9_方法区)
- [对象实例化内存布局与访问定位](./1_内存与垃圾回收篇/10_对象实例化内存布局与访问定位)
- [直接内存](./1_内存与垃圾回收篇/11_直接内存)
- [执行引擎](./1_内存与垃圾回收篇/12_执行引擎)
- [StringTable](./1_内存与垃圾回收篇/13_StringTable)
- [垃圾回收概述](./1_内存与垃圾回收篇/14_垃圾回收概述)
- [垃圾回收相关算法](./1_内存与垃圾回收篇/15_垃圾回收相关算法)
- [垃圾回收相关概念](./1_内存与垃圾回收篇/16_垃圾回收相关概念)
- [垃圾回收器](./1_内存与垃圾回收篇/17_垃圾回收器)

## 字节码与类的加载篇

## 性能监控与调优篇

## 大厂面试篇

[
JVM与Java体系结构](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#jvm与java体系结构)

- [前言](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#前言)

- [架构师每天都在思考什么？](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#架构师每天都在思考什么？)

- [为什么要学习JVM](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#为什么要学习jvm)

- [Java vs C++](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#java-vs-c)

- [推荐书籍](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#推荐书籍)

- [Java生态圈](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#java生态圈)

- [字节码](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#字节码)

- [多语言混合编程](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#多语言混合编程)

- [Java发展的重大事件](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#java发展的重大事件)

- [虚拟机与Java虚拟机](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#虚拟机与java虚拟机)

- - [虚拟机](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#虚拟机)
  - [Java虚拟机](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#java虚拟机)

- [JVM的位置](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#jvm的位置)

- [JVM整体结构](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#jvm整体结构)

- [Java代码执行流程](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#java代码执行流程)

- [JVM的架构模型](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#jvm的架构模型)

- - [举例](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#举例)
  - [字节码反编译](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#字节码反编译)

- [总结](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#总结)

- - [栈](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#栈)

- [JVM生命周期](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#jvm生命周期)

- - [虚拟机的启动](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#虚拟机的启动)
  - [虚拟机的执行](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#虚拟机的执行)
  - [虚拟机的退出](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#虚拟机的退出)

- [JVM发展历程](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#jvm发展历程)

- - [Sun Classic VM](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#sun-classic-vm)
  - [Exact VM](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#exact-vm)
  - [HotSpot VM](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#hotspot-vm)
  - [JRockit](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#jrockit)
  - [IBM的J9](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#ibm的j9)
  - [KVM和CDC / CLDC Hotspot](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#kvm和cdc--cldc--hotspot)
  - [Azul VM](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#azul-vm)
  - [Liquid VM](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#liquid-vm)
  - [Apache Marmony](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#apache-marmony)
  - [Micorsoft JVM](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#micorsoft-jvm)
  - [Taobao JVM](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#taobao-jvm)
  - [Dalvik VM](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#dalvik-vm)
  - [Graal VM](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#graal-vm)
  - [总结](http://localhost:4000/1_内存与垃圾回收篇/1_JVM与Java体系结构/#总结_1)