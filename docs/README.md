<h1 align="center">Avaota A1 Documents</h1>
<p align="center">A Powerful SBC with Allwinner T527 Octa-Core A55 SoC</p>

Avaota A1是一款基于全志T527/A527 8核A55平台设计的单板计算机（SBC）。它搭载了T527处理器（Avaota A1）或A527处理器（Avaota A1C），并配备eMMC5.1和LPDDR4内存。此外，它支持HDMI、DP、RGB、MIPI DSI、LVDS、MIPI DBI等视频输出接口，以及4通道MIPI CSI视频输入。

Avaota A1还内置了双千兆网络，提供USB2.0 x 2和USB 3.1 Gen1 x 1接口，以及音频和麦克风复合接口。此外，它还配备了WS2812 RGB LED灯和1.14英寸IPS屏幕。此外，该设备还集成了WIFI&BT模组，支持2.4G和5.8G WIFI6网络，并兼容蓝牙5.4协议。



# 芯片简介

T527 系列芯片是针对电子商务、工业和汽车领域的高性能八核 Cortex-A55 平台 SoCs。该芯片系列集成了八核 Cortex-A55 CPU、一个 HiFi4 DSP、2 Tops NPU、G57 MC1 GPU、32 位 DDR3/DDR3L/DDR4/LPDDR3/LPDDR4/LPDDR4X DRAM、高速接口（PCIe2.1 和 USB3.1）、汽车接口（CAN）、多路视频输出接口（2xRGB/2x双路LVDS/2xMIPI-DSI/HDMI/eDP）以及视频输入接口（MIPI CSI）。该芯片系列支持 4K@60fps H.265 解码器、4K@30fps H.264 解码器、1080p@60fps H.264 编码器、DI 和 SmartColor 系统，为用户提供流畅的体验和专业的AI视觉效果。T527 系列可用于内容共享和自助互动终端、智能制造等电子商务和工业设备中。

## 芯片框图

![IMG_1032](assets/post/README/IMG_1032.PNG)


## 处理器（Processor）：

- 八核 ARM Cortex-A55 架构，主频最高可达 2.0 GHz
- RISC-V CPU，主频可达 200 MHz
- HiFi4 音频 DSP
- ARM G57 MC01 GPU
- 最高可达 2 Tops 的 NPU（神经网络处理单元）

## 内存（Memory）：

- 32位 LPDDR4/LPDDR4X 接口
- 支持 SD3.0/eMMC5.1 接口

## 视频引擎（Video Engine）：

- H.265 MP 和 VP9 解码器，支持最高 4K@60fps 分辨率
- H.264 BL/MP/HP 解码器，支持最高 4K@30fps 分辨率
- H.264 BP/MP/HP 编码器，支持最高 4K@25fps 分辨率
- MJPEG 编码器，支持最高 4K@15fps 分辨率；JPEG 编码器，支持最高 8K x 8K 分辨率

## 视频输出接口（Video Output）：

- 两个双链路 LVDS 接口，支持最高 1080p@60fps 分辨率
- 两个带有 DE/SYNC 模式的 RGB 接口，支持最高 1080p@60fps 分辨率
- DP 1.3 接口，支持最高 2.5K@60fps 和 4K@30fps 分辨率
- 4+4通道 MIPI-DSI 输出接口，支持最高 2.5K@60fps 和 4K@45fps 分辨率
- HDMI2.0 TX 接口，支持 HDCP1.4 加密协议

## 视频输入接口（Video Input）：
- 支持8/10/12/16位并行CSI接口，最高可达4*720P@30fps（BT.656）和4*1080P@30fps（BT.1120）
- 支持4+4通道、4+2+2通道或2+2+2+2通道MIPI CSI接口，每通道最高传输速率为2.0 Gbit/s，在HS传输模式下，符合MIPI-CSI2 V1.1和MIPI DPHY V1.1标准
- MIPI CSI最大视频采集分辨率为8M@30fps

## 音频（Audio）：
- 2个DAC和3个ADC
- 3个音频输出：LINEOUTLP/N、LINEOUTRP/N、HPOUTL/R
- 3个音频输入：MICIN1P/N、MICIN2P/N、MICIN3P/N
- 4个I2S/PCM外部接口：I2S0、I2S1、I2S2和I2S/PCM3
- 最多支持8个数字PDM麦克风（DMIC）
- 一个OWA RX和一个OWA TX，符合S/PDIF接口标准

## 外部外设（External Peripherals）：
- 1个USB2.0主机端口，1个USB2.0 DRD端口，1个USB3.1 DRD&PCIe2.1组合接口
- 2个GMAC（10/100/1000 Mbps端口，带有RGMII和RMII接口）
- 2个CIR RX，1个CIR TX，9个TWI，4个SPI，10个UART，2个CAN
- 30通道PWM，24通道GPADC，2通道LRADC
- SDIO 3.0，LEDC，SPIF（八路I/O）

## 安全系统（Security System）：
- 支持AES、DES、3DES和SM4加密解密算法
- 支持MD5、SHA和HMAC防篡改算法
- 支持RSA、ECC签名和验证算法

## 封装（Package）：
- HS-FCBGA 664balls封装，尺寸为17 mm x 17 mm，球距为0.5 mm，球径为0.3 mm

## 渲染图

![IMG_1443](assets/post/README/IMG_1443.PNG)

![IMG_1441](assets/post/README/IMG_1441.PNG)
