# 基于 STM32F407 的嵌入式灯光控制固件
## 主要实现 LED 灯光控制及相关外设驱动。

有四种模式：常亮、闪烁、呼吸、熄灭；其中呼吸和闪烁模式可以实现调频，常亮模式可以实现亮度调节

命令示例：

set_mode on

set_mode blink

set_mode breathe

set_mode off

set_frequency 5

set_lightness 128
