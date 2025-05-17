English | [简体中文](README_CN.md)


# Awesome RK3588 | [![Awesome ↗](https://awesome.re/badge.svg)](https://awesome.re)


## Introduction

[<img src="https://www.rock-chips.com/templets/new_2014_9/images//logo.png" align="right" width="100">](https://www.rock-chips.com/)

RK3588 is the flagship 8K SoC chip released by [Rockchip ↗](https://www.rock-chips.com/a/en/), which adopts ARM architecture and is mainly used for PCs, edge computing devices, personal mobile Internet devices, and other digital multimedia applications. RK3588 integrates four Cortex-A76 cores and four Cortex-A55 cores, as well as a separate NEON coprocessor, supporting 8K video codec and decoding.

> This repository contains a curated list of useful resources for developing with the RK3588.:rocket:

## Contents

- [Official Resources](#official-resources)
- [RKNN](#rknn)
- [Projects](#projects)
- [Development Boards](#development-boards)
- [Documentation](#documentation)
- [Tools](#tools)
- [Sample Code](#sample-code)

## Official Resources

1. [Rockchip-Linux ↗](https://github.com/rockchip-linux) - The official Rockchip Linux repository on GitHub.
2. [RK3588 Linux SDK Development and Product Application↗](https://www.bilibili.com/video/BV1kV4y1W7X5) - RK3588 Linux SDK development and product application introduction
3. [RKNPU2: From Introduction to Practice↗](https://www.bilibili.com/video/BV1kV4y1W7X5) - RKNPU2 from entry to practice (based on RK3588 and RK3568)
4. [RK3588 Linux SDK Development and Product Application Introduction↗](https://www.bilibili.com/video/BV1kV4y1W7X5) - RK3588 Linux SDK Development and Product Application Introduction
5. [RKNPU2 From Beginner to Practice↗](https://www.bilibili.com/video/BV1Kj411D78q) - RKNPU2 From Beginner to Practice (Based on RK3588 and RK3568)

## RKNN

1. [RKNN Model Zoo ↗](https://github.com/airockchip/rknn_model_zoo/tree/main) - A collection of pre-trained models for the Rockchip NPU, including image classification, object detection, semantic segmentation, and more.
2. [RKNPU2 Model Deployment ↗](https://github.com/PaddlePaddle/FastDeploy/blob/develop/docs/en/faq/rknpu2/rknpu2.md) - A guide to deploying models on the Rockchip NPU using the RKNPU2 interface.
3. [RKNPU2 ↗](https://github.com/rockchip-linux/rknpu2) - The official repository for the Rockchip NPU interface.
4. [RKNN-Toolkit2 ↗](https://github.com/rockchip-linux/rknn-toolkit2) - The official software development kit for performing model conversion, inference, and performance evaluation on the Rockchip NPU.
5. [librga ↗](https://github.com/airockchip/librga) - RGA (Raster Graphic Acceleration Unit) is a standalone 2D hardware accelerator designed to accelerate point/line drawing, perform image scaling, rotation, bitBlt, alpha blending, and other common 2D graphic operations. 
6. [RKLLM ↗](https://github.com/airockchip/rknn-llm ) - RKLLM software stack can help users to quickly deploy AI models to Rockchip chips. 

## Projects

1. [Yolov5 DeepSORT ↗](https://github.com/Zhou-sx/yolov5_Deepsort_rknn) - A project for tracking vehicles and persons on RK3588 / RK3399pro using YOLOv5 and DeepSORT.
2. [Yolov5 RK3588 Python ↗](https://github.com/cluangar/YOLOv5-RK3588-Python) - Modified code from rknn-toolkit2 for running YOLOv5 on the RK3588.
3. [RKNN multi threaded ↗](https://github.com/leafqycc/rknn-multi-threaded) - A project for running RKNN models on multiple threads for improved performance.
4. [ubuntu-rockchip ↗](https://github.com/Joshua-Riek/ubuntu-rockchip/tree/main) - Ubuntu 22.04 for Rockchip RK3588 devices.
5. [buildroot-rk3588 ↗](https://github.com/Military-Vehicle-Detection/buildroot-rk3588)- Buildroot build for ROCK 5B based on RK3588 CPU.
6. [NixOS running on RK3588/RK3588s ↗](https://github.com/ryan4yin/nixos-rk3588)- Minimal NixOS running on RK3588/RK3588s based SBC(Orange Pi 5 Plus, Orange Pi 5, Rock 5A)
7. [Rockchip-Windows-Drivers ↗](https://github.com/worproject/Rockchip-Windows-Drivers)- Windows on Arm drivers for RK35xx platforms.)
8. [yolov8_rknn_Cplusplus ↗](https://github.com/cqu20160901/yolov8_rknn_Cplusplus)- YoloV8 rknn C++.


## Development Boards

1. [ITOP ↗](http://www.topeetboard.com/sydymfl/Product/iTOP-3588.html) - A development board based on the RK3588 chip, providing complete hardware interfaces and software support.
2. [Fire-Fly ↗](https://www.t-firefly.com/doc/download/164.html) - A development board based on the RK3588 chip, providing complete hardware interfaces and software support.
3. [Orange Pi ↗](http://www.orangepi.org/) - Orange Pi 5 series development board has relatively high cost performance among RK3588 development boards.
4. [YourLand Laptop ↗](https://nanocode.cn/#/yl/) - A laptop based on RK3588 and Linux, designed for sw-developers with rich dev-tools and JTAG debugging support.
5. [https://radxa.com/products/rock5 ↗] - Radxa - RK3588 SBC solutions.
6. [LubanCat](https://doc.embedfire.com/products/link/zh/latest/linux/ebf_lubancat.html) From EmbedFire, providing complete hardware interfaces and software support (Chinese).

## Documentation

1. [RK3588 Datasheet ↗](https://www.rock-chips.com/uploads/pdf/2022.8.26/191/RK3588%20Brief%20Datasheet.pdf) - The official datasheet for the RK3588.
2. [RKNN User Guide ↗](https://github.com/rockchip-linux/rknn-toolkit2/tree/master/doc) - The official user guide for the Rockchip NPU interface.
3. [iTOP-RK3588 Development Board Specification↗](http://topeetboard.com/sydymfl/dwon/iTOP3588%E5%BC%80%E5%8F%91%E6%9D%BF%E8%A7%84%E6%A0%BC%E4%B9%A6.pdf) - Detailed parameters of this development board.
4. [Radxa ROCK 5 Docs ↗](https://docs.radxa.com/rock5) - Provide web documents with excellent browsing experience.
5. [LubanCat ↗](https://doc.embedfire.com/products/link/zh/latest/linux/ebf_lubancat.html) - Detailed documentation, in addition to the information of the board card itself, also integrates the usage methods of common toolchains such as RK3588 (Chinese).


## Tools

-

## Sample Code

1. [RKNN Examples ↗](https://github.com/airockchip/rknn-toolkit2/) - Official examples of how to use the RKNN-Toolkit2 to perform model conversion, inference, and evaluation on the Rockchip NPU.

## Forum

1. [iTOP-RK3588↗](http://bbs.topeetboard.com/forum.php?mod=forumdisplay&fid=55) - Beijing Xunwei iTOP-RK3588 Development Board Technical Discussion Zone.

---

## Contribute 🤝

Got a pull request? Open it, and we'll review it as soon as possible. If you have any suggestions or find any bugs and feel free to bring your fresh ideas to the table! [Contribution Guidelines](contributing.md)

- [Open Issues](https://github.com/choushunn/awesome-RK3588/issues)
- [Open Pull Requests](https://github.com/choushunn/awesome-RK3588/pulls)
- [Open Discussions](https://github.com/choushunn/awesome-RK3588/discussions)

This project exists thanks to all the people who contribute. [[Contribute](contributing.md)].

<a href="https://github.com/choushunn/awesome-RK3588/graphs/contributors"><img src="https://contrib.rocks/image?repo=choushunn/awesome-RK3588&max=200&columns=24" width=850px /></a>
