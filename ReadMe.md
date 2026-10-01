# STM32-Notes

用于记录 STM32 学习过程中的笔记、代码以及开发实践。

这里主要以 STM32CubeMX + HAL 库为基础，
记录从工程创建、外设配置到程序编写的完整学习过程。

~~其实也算是我在复习C8T6了（小声），用AI去写代码导致我都有点忘了一些东西了，所以来整理一下。~~

在学习 STM32 的过程中，逐渐发现现代 STM32 官方工具链与传统开发流程之间存在一些差异：

- STM32CubeMX 工程配置方式
- `.ioc` 文件与代码生成关系
- HAL 库结构
- 外设初始化流程
- 工程文件组织方式

因此建立这个仓库，用于整理 STM32 学习过程中的知识、实验记录以及相关代码。

---

## 开发流程

主要采用 STM32 官方推荐的开发方式：

```text
STM32CubeMX

        ↓

配置 MCU 与外设

        ↓

生成初始化代码

        ↓

STM32CubeIDE / Keil MDK

        ↓

编写应用程序

        ↓

编译、下载、调试
```

---

## 开发环境

主要使用：

* STM32CubeMX
* STM32CubeIDE
* Keil MDK
* STM32 HAL Library
* C Language

---

## 硬件平台

当前学习平台：

* 立创·地阔星 STM32F103C8T6 开发板
* ST-Link V2

后续会根据学习内容加入其他 STM32 系列芯片与外设。

---

## 内容

当前主要记录：

* STM32 基础概念
* STM32F103C8T6 硬件介绍
* Cortex-M3 基础
* STM32CubeMX 工程创建
* CubeMX 配置过程
* HAL 库开发方式
* 工程结构分析
* GPIO
* RCC 时钟系统
* 中断
* 定时器
* PWM
* USART
* SPI
* I2C
* ADC
* DMA
* Flash 存储
* 常用模块驱动

---

## 目录结构

```text
STM32-Notes

│
├── 01-Introduction
│
├── 02-STM32CubeMX
│
├── 03-HAL-Basics
│
├── 04-GPIO
│
├── 05-RCC
│
├── 06-Interrupt
│
├── 07-Timer
│
├── 08-PWM
│
├── 09-USART
│
├── 10-SPI
│
├── 11-I2C
│
├── 12-ADC
│
└── Projects
```

---

## 说明

内容会随着学习过程持续更新。

记录以实际实验和代码验证为基础，
整理 STM32 开发过程中遇到的知识、配置方法以及相关问题。

---

## License

本项目采用双协议授权：

* 文档、笔记、图片以及流程图等内容采用

  Creative Commons Attribution 4.0 International (CC BY 4.0)

* 源代码、示例工程以及软件组件采用

  Apache License 2.0

---

## Third-party Content

本项目部分内容参考其他开源项目。

相关内容版权归原作者所有，并遵循对应项目的许可证。

### 立创·地阔星 STM32F103C8T6 开发板

部分开发板资料、图片以及相关内容参考：

* 来源：立创开源硬件平台
* 项目地址：

[https://oshwhub.com/li-chuang-kai-fa-ban/lichuang-gekuo-star-stm32f103c8t6-development-board](https://oshwhub.com/li-chuang-kai-fa-ban/lichuang-gekuo-star-stm32f103c8t6-development-board)

该项目页面声明采用 GNU General Public License v3.0 (GPL-3.0)。

相关参考内容遵循原项目许可证。
