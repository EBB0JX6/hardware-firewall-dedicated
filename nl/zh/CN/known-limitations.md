---

copyright:
  years: 2017
lastupdated: "2017-10-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}

# 已知限制
硬件防火墙（专用）具有以下已知限制：

* 处理 ARP 的方式导致与 Windows 网络负载均衡 (NLB) 不兼容。

* 高可用性故障转移功能对用户不可用。如果主要防火墙发生故障，但未自动故障转移，那么需要提交支持凭单。建议对关键服务进行设备监控，以确保防火墙可正确传递流量。

* 硬件防火墙（专用）无法部署在当前与网关、硬件防火墙或 FortiGate Security Appliance 关联的 VLAN 上。
