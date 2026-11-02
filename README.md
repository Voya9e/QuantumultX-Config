<div align="center">

# Quantumult X 配置

基于墨鱼配置整理的个人版 Quantumult X 配置文件

[配置文件](https://raw.githubusercontent.com/Voya9e/QuantumultX-Config/main/QuantumultX.conf) · [上游项目](https://github.com/ddgksf2013/ddgksf2013) · [墨鱼原始配置](https://ddgksf2013.top/Profile/QuantumultX.conf)

</div>

---

## 配置简介

本仓库以 [@ddgksf2013（墨鱼）](https://github.com/ddgksf2013/ddgksf2013) 的配置为基础，结合个人使用习惯整理策略组与分流规则。

- 保留并调整常用代理策略组与区域测速组
- 将国际媒体策略组命名为 `Stream`，将 Twitter 策略组命名为 `X`
- X 视频流量单独使用 `Stream` 策略组
- 自动选择与地区测速组的检测周期为 900 秒
- 自动选择正则排除名称包含“网易”或“墨鱼”的节点
- 更新 DNS、远程重写和本地分流配置

## 使用方式

在 Quantumult X 中添加配置文件时，使用以下订阅地址：

```text
https://raw.githubusercontent.com/Voya9e/QuantumultX-Config/main/QuantumultX.conf
```

也可以直接打开 [QuantumultX.conf](https://github.com/Voya9e/QuantumultX-Config/blob/main/QuantumultX.conf) 查看配置内容。

## 说明

- 远程规则和重写资源由各自上游维护，具体功能及可用性以资源作者发布内容为准。
- 节点来自用户自己的订阅；请按实际节点名称检查策略组匹配情况。
- 修改前建议备份现有配置，并根据自己的节点与使用需求调整策略。

## 致谢

感谢 [@ddgksf2013（墨鱼）](https://github.com/ddgksf2013)、[@blackmatrix7](https://github.com/blackmatrix7)、[@KOP-XIAO](https://github.com/KOP-XIAO)、[@Orz-3](https://github.com/Orz-3) 及所有规则和脚本维护者。
