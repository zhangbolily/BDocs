---
id: BUtils-intro
title: BUtils
---
所有 Ball Chang 專案的基礎設施。

## 主要特點

* 生成 UUID (基於隨機值)。
* 跨平臺的計時器系統（精度 1 微秒）。
* 跨平臺的定時器系統（精度 1 毫秒）。

## 開始

這些說明將為您提供在本地計算機上啟動和運行的項目副本，以進行開發和測試。

### 先決條件

如果要在您的平台中使用 BUtils，則應滿足這些要求。

    C++ 標準: c++11
    構建工具: cmake make autoconf automake gcc
    

### 安裝

    $ git clone https://gitlab.com/zhangbolily/BUtils.git BUtils
    $ cd BUtils
    $ git submodule update --init --recursive
    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ make install
    

##### 構建演示視頻（點擊觀看）

[![Build](https://asciinema.org/a/pxITpcCQsCXepW80eHSjB5byF.svg)](https://asciinema.org/a/pxITpcCQsCXepW80eHSjB5byF)

## 運行測試

    $ cd build
    $ rm -rf ./*
    $ cmake -DBUILD_TESTING=ON -DCODE_COVERAGE=ON -DCMAKE_BUILD_TYPE=Debug ..
    $ make tests
    $ bin/tests
    

## 版本信息

有關可用版本，請參閱此存儲庫上的 [ 標記 ](https://gitlab.com/zhangbolily/BUtils/tags)。

## 路線圖

* 下一個版本中進行性能提升。
* 更多例子。
* 將參數傳遞到定時器動作函數中。

## 作者

* **Ball Chang** - *構建整個專案*

## 許可證

該專案是根據麻省理工學院許可證許可 - 有關詳細資訊，請參閱 <LICENSE.md> 。

## 致謝

* GitLab
* Travis-CI