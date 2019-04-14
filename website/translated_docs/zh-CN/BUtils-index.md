---
id: BUtils-home
title: Overview
---
所有 Ball Chang 项目的基础设施。

## 主要特性

* 生成 UUID (基于随机值)。
* 跨平台计时系统（精度 1 微秒）。
* Cross-platform Timer system (Minimum precision 1 ms).

## 开始

这些指示将会获得本项目的所有文件，并在本地机器上运行，用于开发和测试。

### 先决条件

如果您想要在您的平台中使用 BUtils，这些要求应该得到满足。

    C++ 标准：c++ 11
    构建工具：cmake make autoconf automake gcc
    

### 安装

    $ git clone https://gitlab.com/zhangbolily/BUtils.git BUtils
    $ cd BUtils
    $ git submodule update --init --recursive
    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ make install
    

##### 演示构建视频（点击观看）

[![Build](https://asciinema.org/a/pxITpcCQsCXepW80eHSjB5byF.svg)](https://asciinema.org/a/pxITpcCQsCXepW80eHSjB5byF)

## 运行测试

    $ cd build
    $ rm -rf ./*
    $ cmake -DBUILD_TESTING=ON -DCODE_COVERAGE=ON -DCMAKE_BUILD_TYPE=Debug ..
    $ make tests
    $ bin/tests
    

## 版本

对于可用的版本，请参阅此版本库中 [标签](https://gitlab.com/zhangbolily/BUtils/tags)。

## 路线图

* 下一个版本进行性能提升。
* 更多的例子。
* 将参数传递到定时器事件。

## 作者

* **Ball Chang** - *构建整个项目*

## 许可证

这个项目在 MIT 许可证下获得许可 - 请参阅 [LISE.md](LICENSE.md) 文件的详细信息

## 致谢

* GitLab
* Travis-CI