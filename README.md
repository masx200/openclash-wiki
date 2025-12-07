# OpenClash-wiki

OpenClash 是一个可运行在 OpenWrt 上的 Clash 客户端，提供强大的代理功能和灵活的规则配置。

![OpenClash](https://github.com/Dreamacro/clash/raw/master/docs/logo.png)

## 项目简介

OpenClash 是基于 [Clash](https://github.com/Dreamacro/clash) 内核开发的 OpenWrt 客户端插件，兼容 Shadowsocks、Vmess、Trojan、Socks5、HTTP(S)、Snell 等多种协议，通过灵活的规则配置实现流量策略代理。

**作者**: vernesong

## 主要特性

- 🔧 基于 Clash 内核，功能强大
- 🌐 兼容多种代理协议：Shadowsocks、Vmess、Trojan、Socks5、HTTP(S)、Snell
- 📋 灵活的规则配置系统
- 🎯 智能流量分流
- 🔄 实时规则更新
- 📊 连接状态监控
- 🛠️ 丰富的配置选项

## 适用平台

OpenClash 主要用于 OpenWrt 系统，同时也适用于其他使用 Clash 内核的平台：

- **OpenWrt** - 主要支持平台
- **Windows** - [Clash for Windows](https://github.com/Fndroid/clash_for_windows_pkg)
- **macOS** - [clashX](https://github.com/yichengchen/clashX)
- **Android** - [ClashA](https://github.com/ccg2018/ClashA)、[Clash for Android](https://github.com/Kr328/ClashForAndroid)
- **OpenWrt** - [Clash for OpenWrt](https://github.com/frainzy1477/clash)
- **Koolshare** - [KoolClash](https://github.com/SukkaW/Koolshare-Clash)

## 项目结构

```
openclash-wiki/
├── DNS设置.md                          # DNS配置指南
├── Home.md                             # 项目主页
├── SOCKS5、HTTP(S)认证信息.md           # 认证信息配置
├── Sponsor.md                          # 赞助信息
├── _Footer.md                          # 页脚
├── _Sidebar.md                         # 侧边栏导航
├── 外部控制.md                         # 外部控制设置
├── 安装.md                             # 安装指南
├── 常规设置.md                         # 常规配置
├── 服务器和策略组管理.md                # 服务器管理
├── 游戏规则与策略组管理.md              # 游戏规则配置
├── 版本更新.md                         # 版本更新说明
├── 编译.md                             # 编译指南
├── 网络连接异常时排查原因.md            # 故障排除
├── 自定义Hosts.md                      # 自定义Hosts设置
├── 规则设置（访问控制）.md             # 访问控制规则
├── 订阅设置.md                         # 订阅配置
├── 许可.md                             # 许可证信息
├── 运行状态.md                         # 运行状态监控
└── 配置文件.md                         # 配置文件说明
```

## 快速导航

### 🚀 安装和配置

- **[安装指南](安装.md)** - 详细的安装步骤
- **[常规设置](常规设置.md)** - 基本配置选项
- **[服务器和策略组管理](服务器和策略组管理.md)** - 管理代理服务器
- **[订阅设置](订阅设置.md)** - 配置订阅链接

### ⚙️ 高级配置

- **[规则设置（访问控制）](规则设置（访问控制）.md)** - 访问控制规则配置
- **[游戏规则与策略组管理](游戏规则与策略组管理.md)** - 游戏专用规则
- **[DNS设置](DNS设置.md)** - DNS配置优化
- **[自定义Hosts](自定义Hosts.md)** - Hosts文件自定义

### 🔧 开发和维护

- **[编译指南](编译.md)** - 从源码编译
- **[版本更新](版本更新.md)** - 更新说明
- **[外部控制](外部控制.md)** - 外部API控制
- **[配置文件](配置文件.md)** - 配置文件详解

### 🐛 故障排除

- **[网络连接异常时排查原因](网络连接异常时排查原因.md)** - 常见问题解决方案
- **[运行状态](运行状态.md)** - 状态监控和诊断

## 使用说明

本手册介绍的工作原理同样适用于目前使用Clash内核的其他平台类似软件。如果您在使用过程中遇到任何功能问题，请先查阅本Wiki，如仍没有得到满意答案，可以提交Issues咨询。

## 贡献

欢迎提交Pull Request和Issues来改进这个项目。

## 许可证

请查看 [许可.md](许可.md) 了解详细信息。

## 赞助

如果您觉得这个项目有帮助，可以通过 [Sponsor.md](Sponsor.md) 了解赞助方式。

---

*此README.md由MiniMax Agent自动生成*