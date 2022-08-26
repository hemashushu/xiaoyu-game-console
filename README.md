# XiaoXuan Console

XiaoXuan Console 是一个教学目的的 8 位风格游戏主机

XiaoXuan Console is an 8-bit style game console for education purposes.

## 规格

1. [自制的开源 RISC-V CPU](https://github.com/hemashushu/xiaoxuan-rv32-soc) 48MHz
2. 256KB 运行内存
3. 4MB 储存空间，可外接 SD Card
4. 自制的 8-bit 音效合成器
5. 支持 256 色的 320x240px 显示屏幕
6. 系统是自制的 [XiaoXuan RTOS](https://github.com/hemashushu/xiaoxuan-rtos)
7. 游戏程序采用自制的语言和编译器 [XiaoXuan Micro](https://github.com/hemashushu/xiaoxuan-micro) 制作。
8. 操作界面有 4 个方向键，以及 `A`、`B` 和 `Option` 3 个按键。

下图是硬件实物图：

![XiaoXuan Console](images/todo.png)

下图是拆解图：

![XiaoXuan Console](images/todo.png)

## 演示

下面是实际游戏 [XiaoXuan Adventure](https://github.com/hemashushu/xiaoxuan-adventure) 的演示视频：

![XiaoXuan Console](images/todo.png)

## 特点

1. 游戏主机从硬件芯片到实时操作系统，到编程语言全部自制开源，附带完整的从零开始搭建的教程，可作为学习数字电路、组成原理（RISC-V 指令和微体系结构）、编译原理、数据结构、游戏编程模式的生动教材。
2. 游戏主机的运行环境自带图形库、支持二次开发，环境自带游戏库管理界面，支持分享和下载自制的游戏。
3. CPU 可以替换为 RP2040（Raspberry Pi Pico）或者 ESP32-C3 或者 STM32F4，以获取更高的性能。
4. 储存空间由 SPI Flash 提供，可以替换更大容量的 Flash。

点击 [从零开始一步一步制作 XiaoXuan Console](docs/tutorial/README.md) 进入教程

