[English](README.md) | 简体中文

# Awesome RK3588 | [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://www.rock-chips.com/templets/new_2014_9/images//logo.png" align="right" width="100">](https://www.rock-chips.com/)

RK3588是瑞芯微旗舰级8K SoC芯片，配备四核Cortex-A76、四核Cortex-A55及6 TOPS NPU。本列表整理了开发必备资源。:rocket:

## 目录
- [官方资源](#官方资源)
- [RKNN与AI工具](#rknn与ai工具)
- [大语言模型](#大语言模型)
- [操作系统](#操作系统)
- [项目](#项目)
- [开发板](#开发板)
- [文档](#文档)
- [开发工具](#开发工具)
- [示例代码](#示例代码)
- [社区](#社区)

## 官方资源
1. [Rockchip Linux ↗](https://github.com/rockchip-linux) - 官方内核、u-boot、MPP
2. [RKNN SDK文档 ↗](https://github.com/airockchip/rknn-toolkit2/tree/master/doc) - 最新SDK指南
3. [RKNPU2教程 ↗](https://www.bilibili.com/video/BV1Kj411D78q) - RKNPU2从入门到实践
4. [瑞芯微资源门户 ↗](https://console.zbox.filez.com/l/I00fc3) - SDK下载（提取码：rknn）

## RKNN与AI工具
### 核心SDK
1. **[RKNN-Toolkit2 ↗](https://github.com/airockchip/rknn-toolkit2)** - 模型转换与评估（v2.3.2+）
2. **[RKNPU2 Runtime ↗](https://github.com/rockchip-linux/rknpu2)** - NPU运行时库
3. **[RKNN-Toolkit-Lite2 ↗](https://github.com/airockchip/rknn-toolkit2/tree/master/rknn-toolkit-lite2)** - 设备端Python API
4. **[librga ↗](https://github.com/airockchip/librga)** - 2D图形加速库

### 模型库
1. **[RKNN Model Zoo ↗](https://github.com/airockchip/rknn_model_zoo)** - 30+预训练模型（YOLO11、SAM、Whisper、CLIP）
2. **[RKLLM ↗](https://github.com/airockchip/rknn-llm)** - 大语言模型部署栈

## 大语言模型
*RK3588支持边缘LLM部署，需使用RKLLM栈*
1. **支持模型**：TinyLlama 1.1B（约10-15 token/秒）、Qwen2 0.5B、Whisper
2. **[RKLLM Toolkit ↗](https://github.com/airockchip/rknn-llm)** - LLM转换与部署工具

## 操作系统
1. **[Ubuntu Rockchip ↗](https://github.com/Joshua-Riek/ubuntu-rockchip)** - Ubuntu 22.04/24.04 LTS（推荐）
2. **[Armbian ↗](https://www.armbian.com/)** - 官方RK3588支持
3. **[Buildroot RK3588 ↗](https://github.com/Military-Vehicle-Detection/buildroot-rk3588)** - 极简Buildroot
4. **[NixOS RK3588 ↗](https://github.com/ryan4yin/nixos-rk3588)** - 适用于香橙派/ROCK 5A的NixOS

## 项目
1. **[YOLOv8 C++ ↗](https://github.com/cqu20160901/yolov8_rknn_Cplusplus)** - 生产级YOLOv8推理
2. **[rknn-multi-threaded ↗](https://github.com/leafqycc/rknn-multi-threaded)** - 多线程NPU（性能+40%）
3. **[YOLOv5+DeepSORT ↗](https://github.com/Zhou-sx/yolov5_Deepsort_rknn)** - 实时目标跟踪
4. **[GStreamer MPP ↗](https://github.com/rockchip-linux/gstreamer-rockchip)** - 硬件加速视频管线
5. **[FFmpeg RKMPP ↗](https://github.com/rockchip-linux/ffmpeg-rockchip)** - 8K视频编解码

## 开发板
### 消费级/创客
1. **[香橙派5系列 ↗](http://www.orangepi.org/)** - 性价比最高（4-16GB，PCIe 3.0）
2. **[Radxa ROCK 5 ↗](https://radxa.com/products/rock5)** - 工业级，双网口
3. **[野火LubanCat RK3588 ↗](https://doc.embedfire.com/products/link/zh/latest/linux/ebf_lubancat.html)** - 接口丰富，中文文档完善

### 工业级
1. **ITOP-3588 ↗** - 北京迅为，完整技术支持
2. **FireFly ITX-3588J ↗** - Mini-ITX嵌入式版型

## 文档
### 技术文档
1. **[RK3588数据手册 ↗](https://www.rock-chips.com/uploads/pdf/2022.8.26/191/RK3588%20Brief%20Datasheet.pdf)** - 官方规格（6 TOPS，8K@60fps）
2. **[RKNN用户指南 ↗](https://github.com/airockchip/rknn-toolkit2/tree/master/doc)** - 转换与部署指南
3. **[RKNPU2 API参考 ↗](https://github.com/rockchip-linux/rknpu2/blob/master/doc/Rockchip_RKNPU_User_Guide_RKNN_API_V2.0.0.pdf)** - C/C++ API文档

### 开发板专用
1. **[Radxa ROCK 5文档 ↗](https://docs.radxa.com/rock5)** - 优质英文文档
2. **[野火LubanCat手册 ↗](https://doc.embedfire.com/linux/rk3588/quick_start/zh/latest/)** - 最佳中文文档

## 开发工具
1. **[RKDevTool ↗](https://github.com/rockchip-linux/rkdeveloptool)** - 固件烧录工具
2. **[RKNN-Toolkit2 Docker ↗](https://github.com/airockchip/rknn-toolkit2/tree/master/docker)** - 预配置环境
3. **NPU监控**: `cat /sys/kernel/debug/rknpu/load`

## 示例代码
1. **[RKNN Model Zoo ↗](https://github.com/airockchip/rknn_model_zoo)** - 30+官方模型示例
2. **[rknn_api_demo ↗](https://github.com/rockchip-linux/rknpu2/tree/master/rknn_api_demo)** - 极简C API示例
3. **[RKLLM Examples ↗](https://github.com/airockchip/rknn-llm/tree/main/examples)** - LLM聊天机器人示例

## 社区
### 国际社区
1. **[Radxa论坛 ↗](https://forum.radxa.com/)** - ROCK系列社区
2. **[Armbian论坛 ↗](https://forum.armbian.com/forum/29-rockchip-3588-3566-3568-3399/)** - 操作系统级支持
3. **[香橙派论坛 ↗](http://www.orangepi.org/orangepibbsen/)** - 官方香橙派论坛

### 中文社区
1. **[iTOP-RK3588论坛 ↗](http://bbs.topeetboard.com/forum.php?mod=forumdisplay&fid=55)** - 北京迅为技术支持
2. **[野火LubanCat社区 ↗](https://forums.embedfire.com/c/lubancat/21)** - 野火电子

---

## 贡献 🤝

有提交请求吗？打开它，我们将尽快审查。如果您有任何建议或发现任何错误，请随时提出您的新想法！[贡献指南](contributing.md)

- [Open Issues](https://github.com/choushunn/awesome-RK3588/issues)
- [Open Pull Requests](https://github.com/choushunn/awesome-RK3588/pulls)
- [Open Discussions](https://github.com/choushunn/awesome-RK3588/discussions)

感谢所有代码贡献者。 [[Contribute](contributing.md)].

<a href="https://github.com/choushunn/awesome-RK3588/graphs/contributors"><img src="https://contrib.rocks/image?repo=choushunn/awesome-RK3588&max=200&columns=24" width=850px /></a>