# 一个STM32项目
## 主要实现了通过UART发送指令控制灯光

有四种模式：常亮、闪烁、呼吸、熄灭；其中呼吸和闪烁模式可以实现调频，常亮模式可以实现亮度调节

命令示例：

set_mode on

set_mode blink

set_mode breathe

set_mode off

set_frequency 5

set_lightness 128
