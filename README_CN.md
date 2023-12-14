[English](README.md) | 简体中文

# Awesome RK3588 | [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## 简介
[<img src="https://www.rock-chips.com/templets/new_2014_9/images//logo.png" align="right" width="100">](https://www.rock-chips.com/)

RK3588 是由 [Rockchip ↗](https://www.rock-chips.com/a/en/)发布的旗舰 8K SoC 芯片，采用 ARM 架构，主要用于 PC、边缘计算设备、个人移动互联网设备和其他数字多媒体应用。RK3588 集成了四个 Cortex-A76 核心和四个 Cortex-A55 核心，以及一个独立的 NEON 协处理器，支持 8K 视频编解码和解码。

> 本仓库包含了一个为使用 RK3588 开发提供有用资源的列表。:rocket:

## 目录

- [官方资源](#官方资源)
- [RKNN](#rknn)
- [项目](#项目)
- [开发板](#开发板)
- [文档](#文档)
- [工具](#工具)
- [示例代码](#示例代码)

## 官方资源

- [Rockchip-Linux ↗](https://github.com/rockchip-linux) - GitHub 上的 Rockchip Linux 官方仓库。
- [RKNPU2 ↗](https://github.com/rockchip-linux/rknpu2) - Rockchip NPU 接口的官方仓库。
- [RKNN-Toolkit2 ↗](https://github.com/rockchip-linux/rknn-toolkit2) - 在 Rockchip NPU 上执行模型转换、推理和性能评估的官方软件开发工具包。
- [RK3588 Linux SDK 开发及产品应用介绍↗](https://www.bilibili.com/video/BV1kV4y1W7X5) - RK3588 Linux SDK 开发及产品应用介绍
- [RKNPU2 从入门到实践↗](https://www.bilibili.com/video/BV1Kj411D78q) - RKNPU2 从入门到实践（基于 RK3588 和 RK3568）
- [RK3588 Linux SDK开发及产品应用介绍↗](https://www.bilibili.com/video/BV1kV4y1W7X5) - RK3588 Linux SDK开发及产品应用介绍
- [RKNPU2从入门到实践（基于RK3588和RK3568）↗](https://www.bilibili.com/video/BV1Kj411D78q) - RKNPU2从入门到实践（基于RK3588和RK3568）

## RKNN

- [RKNN模型库 ↗](https://github.com/airockchip/rknn_model_zoo/tree/main) - 一个包含了预训练模型的收藏夹，用于 Rockchip NPU，包括图像分类、目标检测、语义分割等。
- [RKNPU2模型部署 ↗](https://github.com/PaddlePaddle/FastDeploy/blob/develop/docs/en/faq/rknpu2/rknpu2.md) - 使用 RKNPU2 接口在 Rockchip NPU 上部署模型的指南。

## 项目

- [Yolov5 DeepSORT ↗](https://github.com/Zhou-sx/yolov5_Deepsort_rknn) - 使用YoloV5和DeepSORT在RK3588/RK3399pro上跟踪车辆和人的项目。
- [Yolov5 RK3588 Python ↗](https://github.com/cluangar/YOLOv5-RK3588-Python) - 使用rknn-toolkit2修改代码在RK3588上运行YoloV5的项目。
- [RKNN多线程 ↗](https://github.com/leafqycc/rknn-multi-threaded) - 一个在多线程上运行RKNN模型以提高性能的项目。
- [ubuntu-rockchip ↗](https://github.com/Joshua-Riek/ubuntu-rockchip/tree/main) - 适用于Rockchip RK3588设备的Ubuntu 22.04。
- [buildroot-rk3588 ↗](https://github.com/Military-Vehicle-Detection/buildroot-rk3588) - 基于RK3588 CPU的ROCK 5B的Buildroot构建。
- [NixOS running on RK3588/RK3588s ↗](https://github.com/ryan4yin/nixos-rk3588) - 在基于 RK3588/RK3588s 的 SBC（Orange Pi 5 Plus、Orange Pi 5、Rock 5A）上运行的Minimal  NixOS.

## 开发板

- [ITOP ↗](http://www.topeetboard.com/sydymfl/Product/iTOP-3588.html) - 基于 RK3588 芯片的开发板，提供完整的硬件接口和软件支持。
- [Fire-Fly ↗](https://www.t-firefly.com/doc/download/164.html) - 基于 RK3588 芯片的开发板，提供完整的硬件接口和软件支持。
- [Orange Pi ↗](http://www.orangepi.cn/) - Orange Pi。
- [YourLand Laptop ↗](https://nanocode.cn/#/yl/) - 基于RK3588和Linux的笔记本电脑，专为软件开发人员设计，具有丰富的开发工具和JTAG调试支持。

## 文档

- [RK3588数据手册 ↗](https://www.rock-chips.com/uploads/pdf/2022.8.26/191/RK3588%20Brief%20Datasheet.pdf) - RK3588 的官方数据手册。
- [RKNN用户指南 ↗](https://github.com/rockchip-linux/rknn-toolkit2/tree/master/doc) - Rockchip NPU 接口的官方用户指南。
- [iTOP-RK3588开发板规格书↗](http://topeetboard.com/sydymfl/dwon/iTOP3588%E5%BC%80%E5%8F%91%E6%9D%BF%E8%A7%84%E6%A0%BC%E4%B9%A6.pdf) - 此款开发板的各项详细参数

## 工具

- [RKNN-Toolkit2 ↗](https://github.com/rockchip-linux/rknn-toolkit2) - 在 Rockchip NPU 上执行模型转换、推理和性能评估的官方软件开发工具包。
- [librga ↗](https://github.com/airockchip/librga) - RGA (Raster Graphic Acceleration Unit)是一个独立的2D硬件加速器，可用于加速点/线绘制，执行图像缩放、旋转、bitBlt、alpha混合等常见的2D图形操作。

## 示例代码

- [RKNN示例 ↗](https://github.com/rockchip-linux/rknn-toolkit2/tree/master/examples) - 使用 RKNN-Toolkit2 执行模型转换、推理和评估的官方示例。

## 论坛

- [iTOP-RK3588↗](http://bbs.topeetboard.com/forum.php?mod=forumdisplay&fid=55) - 北京迅为 iTOP-RK3588 开发板技术讨论专区

---

## 贡献 🤝

有提交请求吗？打开它，我们将尽快审查。如果您有任何建议或发现任何错误，请随时提出您的新想法！[贡献指南](contributing.md)

- [Open Issues](https://github.com/choushunn/awesome-RK3588/issues)
- [Open Pull Requests](https://github.com/choushunn/awesome-RK3588/pulls)
- [Open Discussions](https://github.com/choushunn/awesome-RK3588/discussions)
