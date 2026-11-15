English | [简体中文](README_CN.md)

# Awesome RK3588 | [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://www.rock-chips.com/templets/new_2014_9/images//logo.png" align="right" width="100">](https://www.rock-chips.com/)

RK3588 is Rockchip's flagship 8K SoC with quad Cortex-A76, quad Cortex-A55, and 6 TOPS NPU. This list curates essential development resources. :rocket:

## Contents
- [Official Resources](#official-resources)
- [RKNN & AI Tools](#rknn--ai-tools)
- [Large Language Models](#large-language-models)
- [Operating Systems](#operating-systems)
- [Projects](#projects)
- [Development Boards](#development-boards)
- [Documentation](#documentation)
- [Development Tools](#development-tools)
- [Sample Code](#sample-code)
- [Community](#community)

## Official Resources
1. [Rockchip Linux ↗](https://github.com/rockchip-linux) - Official kernel, u-boot, MPP
2. [RKNN SDK Documentation ↗](https://github.com/airockchip/rknn-toolkit2/tree/master/doc) - Latest SDK guides
3. [RKNPU2 Tutorial ↗](https://www.bilibili.com/video/BV1Kj411D78q) - RKNPU2 from entry to practice
4. [Rockchip Resource Portal ↗](https://console.zbox.filez.com/l/I00fc3) - SDK downloads (code: rknn)

## RKNN & AI Tools
### Core SDK
1. **[RKNN-Toolkit2 ↗](https://github.com/airockchip/rknn-toolkit2)** - Model conversion & evaluation (v2.3.2+)
2. **[RKNPU2 Runtime ↗](https://github.com/rockchip-linux/rknpu2)** - NPU runtime libraries
3. **[RKNN-Toolkit-Lite2 ↗](https://github.com/airockchip/rknn-toolkit2/tree/master/rknn-toolkit-lite2)** - On-device Python API
4. **[librga ↗](https://github.com/airockchip/librga)** - 2D graphics acceleration

### Model Zoo
1. **[RKNN Model Zoo ↗](https://github.com/airockchip/rknn_model_zoo)** - 30+ pre-trained models (YOLO11, SAM, Whisper, CLIP)
2. **[RKLLM ↗](https://github.com/airockchip/rknn-llm)** - LLM deployment stack

## Large Language Models
*RK3588 supports edge LLM deployment with RKLLM*
1. **Supported Models**: TinyLlama 1.1B (~10-15 tokens/sec), Qwen2 0.5B, Whisper
2. **[RKLLM Toolkit ↗](https://github.com/airockchip/rknn-llm)** - Convert and deploy LLMs

## Operating Systems
1. **[Ubuntu Rockchip ↗](https://github.com/Joshua-Riek/ubuntu-rockchip)** - Ubuntu 22.04/24.04 LTS (recommended)
2. **[Armbian ↗](https://www.armbian.com/)** - Official RK3588 support
3. **[Buildroot RK3588 ↗](https://github.com/Military-Vehicle-Detection/buildroot-rk3588)** - Minimal Buildroot
4. **[NixOS RK3588 ↗](https://github.com/ryan4yin/nixos-rk3588)** - NixOS for Orange Pi/ROCK 5A

## Projects
1. **[YOLOv8 C++ ↗](https://github.com/cqu20160901/yolov8_rknn_Cplusplus)** - Production YOLOv8 inference
2. **[rknn-multi-threaded ↗](https://github.com/leafqycc/rknn-multi-threaded)** - Multi-threaded NPU (+40% perf)
3. **[YOLOv5+DeepSORT ↗](https://github.com/Zhou-sx/yolov5_Deepsort_rknn)** - Real-time tracking
4. **[GStreamer MPP ↗](https://github.com/rockchip-linux/gstreamer-rockchip)** - Hardware-accelerated video
5. **[FFmpeg RKMPP ↗](https://github.com/rockchip-linux/ffmpeg-rockchip)** - 8K video codec

## Development Boards
### Consumer/Maker
1. **[Orange Pi 5 Series ↗](http://www.orangepi.org/)** - Best value (4-16GB, PCIe 3.0)
2. **[Radxa ROCK 5 ↗](https://radxa.com/products/rock5)** - Industrial grade, dual Ethernet
3. **[LubanCat RK3588 ↗](https://doc.embedfire.com/products/link/zh/latest/linux/ebf_lubancat.html)** - Rich IO, Chinese docs

### Industrial
1. **ITOP-3588 ↗** - Beijing Xunwei, full support
2. **FireFly ITX-3588J ↗** - Mini-ITX embedded form factor

## Documentation
### Technical
1. **[RK3588 Datasheet ↗](https://www.rock-chips.com/uploads/pdf/2022.8.26/191/RK3588%20Brief%20Datasheet.pdf)** - Official specs (6 TOPS, 8K@60fps)
2. **[RKNN User Guide ↗](https://github.com/airockchip/rknn-toolkit2/tree/master/doc)** - Conversion & deployment
3. **[RKNPU2 API Reference ↗](https://github.com/rockchip-linux/rknpu2/blob/master/doc/Rockchip_RKNPU_User_Guide_RKNN_API_V2.0.0.pdf)** - C/C++ API

### Board-Specific
1. **[Radxa ROCK 5 Docs ↗](https://docs.radxa.com/rock5)** - Excellent English docs
2. **[LubanCat Manual ↗](https://doc.embedfire.com/linux/rk3588/quick_start/zh/latest/)** - Best Chinese docs

## Development Tools
1. **[RKDevTool ↗](https://github.com/rockchip-linux/rkdeveloptool)** - Firmware flashing
2. **[RKNN-Toolkit2 Docker ↗](https://github.com/airockchip/rknn-toolkit2/tree/master/docker)** - Pre-configured environment
3. **NPU Monitor**: `cat /sys/kernel/debug/rknpu/load`

## Sample Code
1. **[RKNN Model Zoo ↗](https://github.com/airockchip/rknn_model_zoo)** - 30+ official model demos
2. **[rknn_api_demo ↗](https://github.com/rockchip-linux/rknpu2/tree/master/rknn_api_demo)** - Minimal C API examples
3. **[RKLLM Examples ↗](https://github.com/airockchip/rknn-llm/tree/main/examples)** - LLM chatbot demos

## Community
### International
1. **[Radxa Forum ↗](https://forum.radxa.com/)** - ROCK series community
2. **[Armbian Forum ↗](https://forum.armbian.com/forum/29-rockchip-3588-3566-3568-3399/)** - OS-level support
3. **[Orange Pi Forum ↗](http://www.orangepi.org/orangepibbsen/)** - Official Orange Pi forum

### Chinese
1. **[iTOP-RK3588 Forum ↗](http://bbs.topeetboard.com/forum.php?mod=forumdisplay&fid=55)** - Beijing Xunwei support
2. **[LubanCat Community ↗](https://forums.embedfire.com/c/lubancat/21)** - Wildfire Electronics

---

## Contribute 🤝

Got a pull request? Open it, and we'll review it as soon as possible. If you have any suggestions or find any bugs and feel free to bring your fresh ideas to the table! [Contribution Guidelines](contributing.md)

- [Open Issues](https://github.com/choushunn/awesome-RK3588/issues)
- [Open Pull Requests](https://github.com/choushunn/awesome-RK3588/pulls)
- [Open Discussions](https://github.com/choushunn/awesome-RK3588/discussions)

This project exists thanks to all the people who contribute. [[Contribute](contributing.md)].

<a href="https://github.com/choushunn/awesome-RK3588/graphs/contributors"><img src="https://contrib.rocks/image?repo=choushunn/awesome-RK3588&max=200&columns=24" width=850px /></a>