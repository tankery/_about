---
layout: default
modal-id: 5
title: Zigbee Vote
date: 2012-06-23
img: Satellite.png
background: hsl(348, 70%, 70%)
alt: Zigbee Vote
meta-data:
  - name: Organization
    text: Dian Group
    url: http://dian.hust.edu.cn/
  - name: Date
    text: 2011 ~ 2012
  - name: Category
    text: Embedded Development
    url: /
language: zh
---

Zigbee vote 是一套利用Zigbee技术进行通讯的无线投票器系统。
是[Dian团队](http://dian.hust.edu.cn/)的一个项目。

系统使用一个USB基站，收集其他手持投票器的投票数据，并上传至PC客户端展示。
基站和投票器的通讯利用支持Zigbee协议栈的硬件完成，USB基站采用HID设备协议与PC客户端通讯，PC客户端代码继续QT框架编写。
