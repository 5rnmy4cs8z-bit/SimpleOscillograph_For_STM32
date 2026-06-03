# STM32 Oscilloscope Study

基于开源项目进行学习与二次开发

原项目：
https://github.com/shuai132/SimpleOscillograph_For_STM32

## 技术栈

- STM32F103
- ADC
- Timer
- TFT LCD
- Keil

## 项目原理
- TIM2定时器产生固定周期中断
- ADC进行多通道连续采样
- DMA自动将采样结果搬运到内存
- USB虚拟串口将采样数据发送到PC端
- 上位机完成波形显示

## 学习内容

- ADC采样原理
- 定时器触发机制
- 波形显示流程

## 我的工作

- 阅读项目代码结构
- 分析ADC采样流程
- 调试显示模块
