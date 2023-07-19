# [CM32M433](https://github.com/SoCXin/CM32M433)

* [cmiot](https://www.xinshengcmiot.cn)：[RISC-V N308(RV32IMACFP)](https://github.com/SoCXin/RISC-V)
* [L2R2](https://github.com/SoCXin/Level)：144 MHz (211 DMIPS)

## [简介](https://github.com/SoCXin/CM32M433/wiki)

[CM32M433](https://www.xinshengcmiot.cn/production/detail/2) 系列采用32bit RISC-V Nuclei N308内核，最高工作主频144MHz，集成FPU，支持DSP指令，集成高达512KB嵌入式加密Flash，144KB SRAM，集成丰富的高性能模拟功能模块及通信接口，内置4个12bit 5Msps ADC、4路独立轨到轨运算放大器，7个高速比较器，2个1Msps 12bit DAC，支持多达24通道电容式触摸按键，集成多路U(S)ART、I2C、SPI、QSPI、CAN等数字通信接口，内置密码算法硬件加速引擎。

### 关键特性

* 144 MHz RISC-V Core (RV32IMAC)
* 144KB SRAM + 512KB Flash
* 4x12bit 5Msps ADC
* 12bit 1Msps DAC
* 7x CMP + 4x OPA


## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin)

[CM32M433](https://github.com/SoCXin/CM32M433) 集成4个5Msps ADC，具有数量和速率优势。

[CM32M10xA](https://www.xinshengcmiot.cn/production/detail/1) 配备1个5Msps ADC，外设数量减少，成本更低。