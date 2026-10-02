<h1 align="center">尘世凡间 · chenshifanjian</h1>

<p align="center">
  <b>王文龙</b> · 信息安全技术 · Linux 桌面折腾 · 自托管 · 硬件创客<br>
  墨刃工坊 Ink Blade Studio 创始人
</p>

<p align="center">
  <i>「能力愈大　责任愈大」</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Arch-Linux-F5C06F?style=flat-square&logo=archlinux&logoColor=white" alt="Arch">
  <img src="https://img.shields.io/badge/niri-Wayland-8A2BE2?style=flat-square" alt="niri">
  <img src="https://img.shields.io/badge/DankMaterialShell-plugin-FF69B4?style=flat-square" alt="DMS">
  <img src="https://img.shields.io/badge/CTF-取证%20%2F%20Web%20%2F%20Pwn-2E8B57?style=flat-square" alt="CTF">
  <img src="https://img.shields.io/badge/Linux-运维%20%2F%20自托管-333333?style=flat-square&logo=linux&logoColor=white" alt="Linux">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
</p>

<p align="center">
  <a href="#-关于我">🙋 关于我</a> ·
  <a href="#-关注方向">🔍 关注方向</a> ·
  <a href="#-环境与装备">🧰 环境与装备</a> ·
  <a href="#-项目">📦 项目</a> ·
  <a href="#-现在在做">🚧 现在在做</a> ·
  <a href="#-联系">📮 联系</a>
</p>

---

## 🙋 关于我

**王文龙**，网名**尘世凡间**，**石家庄职业技术学院 · 信息工程系 · 信息安全技术应用**专业在读；**墨刃工坊 Ink Blade Studio** 创始人 —— 一支 **9 人的在校团队**，做数字创意与智能硬件的融合服务（3D 打印、激光雕刻、软硬件定制），从谈需求、采购、建模、装配到交付，整条链路自己走一遍。

技术上我更偏"把系统跑起来，并且跑得住"的那一侧：

- **安全** —— 专业本行，CTF 按 Misc → Web → PWN → Reverse → Crypto 的路线系统学。第六届**「长城杯」网络安全大赛**初赛以**取证 + 综合防御**方向**个人解出 8 题 / 400 分**，赛后写了完整 WriteUp 与复盘
- **基础设施 / 运维** —— 为学校部署并持续维护一套**人脸采集与比对系统**（服务万级生源，含安全加固、异地备份与定期巡检）；自己搭了「服务器 + 边缘机 + frp 内网穿透 + 雷池 WAF + 面板」的整套链路，两条链路都在承载线上业务
- **桌面与自动化** —— **Arch Linux + niri**（Wayland），[DankMaterialShell](https://github.com/AvengeMedia/DankMaterialShell) 深度用户兼插件开发者；日常用 Hermes Agent 做自动化，Obsidian「外置大脑」里上百页的配置登记、踩坑复盘、项目台账都是它跑出来的
- **硬件** —— Quectel **EG25-G** 4G 模块接入 Linux 跑通短信 / 彩信 / GPS；激光雕刻机与 3D 打印机的装机、拆机与调优；ESP32 小玩意

处事信条：**稳重求进 · 守正出奇 · 保持热爱 · 坚守初心**。
座右铭：**「能力愈大　责任愈大」** —— 能力涨一分，就多担一分事；团队里最难的活默认归我，翻车了也我来复盘。

## 🔍 关注方向

| 方向 | 说明 |
| --- | --- |
| 🖥️ **桌面与系统** | **Arch Linux** + [niri](https://github.com/YaLTeR/niri)（Wayland），DankMaterialShell 深度使用与**插件开发** |
| 🔐 **安全** | 信息安全管理与评估、应急响应；**CTF** 取证 / Web / Pwn 方向的练习与复盘 |
| 🏗️ **基础设施** | 服务器部署与运维、内网穿透、反向代理与 **WAF**、异地备份 |
| 🛠️ **智能制造** | 3D 打印、激光雕刻、FreeCAD 参数化建模、硬件维修与自制 |
| 📡 **通信硬件** | Quectel **EG25-G** 4G 模块接入 Linux —— 短信、彩信、流量、定位全链路自建 |
| 🏠 **自托管** | NAS / 网盘 / 面板 / 自动化，能自己修的绝不将就 |

## 🧰 环境与装备

| 类别 | 现在用的 |
| --- | --- |
| 🖥️ **系统** | Arch Linux + niri（Wayland）+ DankMaterialShell，核显渲染 / N 卡直通热切换 |
| ⌨️ **主力语言** | Python · Shell · QML（写 DMS 插件） |
| 🔧 **硬件** | Quectel EG25-G 4G 模块、激光雕刻机、3D 打印机（含 0.4mm 热端自修）、ESP32 |
| 🧠 **本地 AI** | 笔记本跑 LM Studio 的小模型（≈3B 全 GPU，7–8B offload），够用就好 |
| ☁️ **自托管** | 一台便宜云服务器撑起博客、内网穿透与面板 |
| 🧩 **工作方式** | Obsidian「外置大脑」+ Hermes Agent 做配置登记、留痕与自动化 |

## 📦 项目

| 项目 | 说明 | 语言 |
| --- | --- | --- |
| [**dms-sim-network**](https://github.com/chenshifanjian/dms-sim-network) | DMS 插件 **SIM Network**：4G 模块的流量统计、短信/彩信收发、桌面通知、GPS 与 Obsidian 归档（正申请进入[官方插件市场](https://github.com/AvengeMedia/dms-plugin-registry/pull/995)） | ![language](https://img.shields.io/github/languages/top/chenshifanjian/dms-sim-network?style=flat-square) |
| [**voice-to-text**](https://github.com/chenshifanjian/voice-to-text) | 语贴：基于 faster-whisper 的 Linux 桌面语音输入工具，录音 → 转写 → 通知 → 复制四环打通，长期自用 | ![language](https://img.shields.io/github/languages/top/chenshifanjian/voice-to-text?style=flat-square) |
| [**engrave-svg**](https://github.com/chenshifanjian/engrave-svg) | 图片转激光雕刻 SVG 矢量工具，图形界面 + 命令行双模式，兼容 EzCad | ![language](https://img.shields.io/github/languages/top/chenshifanjian/engrave-svg?style=flat-square) |
| [**NCSE-Grade-3-Shield-Trainer**](https://github.com/chenshifanjian/NCSE-Grade-3-Shield-Trainer) | 全国计算机等级考试（NCRE）三级信息安全技术 · 选择题练习程序 | ![language](https://img.shields.io/github/languages/top/chenshifanjian/NCSE-Grade-3-Shield-Trainer?style=flat-square) |
| [**dms-plugin-registry**](https://github.com/chenshifanjian/dms-plugin-registry) | 我 fork 的 DMS 官方插件注册表（提交插件用） | ![language](https://img.shields.io/github/languages/top/chenshifanjian/dms-plugin-registry?style=flat-square) |

> 向 [NaClwww](https://github.com/NaClwww/dms-modem-plugin) 的 Mobile Network 插件致敬 —— SIM Network 是在它基础上扩展的，上游署名见仓库 README。

## 🚧 现在在做

- [ ] 把 **SIM Network** 推进 DMS 官方插件市场（PR 审核中，逐条整改）
- [ ] EG25-G 的 GPS 天线接触与 AGPS 冷启动问题排查（还在和商家拉锯）
- [ ] 墨刃工坊的技术标准化与业务搭建：让 3D 打印 / 激光雕刻的交付流程可复用
- [ ] CTF 继续练 —— 取证与防御已上手，下一步补 Web 与 PWN

## 📮 联系

| 方式 | 账号 | 备注 |
| --- | --- | --- |
| 📧 邮箱 | [wangwenlong1006@qq.com](mailto:wangwenlong1006@qq.com) | **首选**，邮件回复最稳 |
| 💬 微信 | `ChenShiFanJian_Long` | 一般，回得慢些 |
| 👤 QQ | 1349586536 | 也可发 [1349586536@qq.com](mailto:1349586536@qq.com) |

项目 / 合作 / 技术交流都欢迎 —— 开 [Issue](https://github.com/chenshifanjian/dms-sim-network/issues) 或直接发邮件。

---

<p align="center"><i>稳重求进 · 守正出奇 · 保持热爱 · 坚守初心</i></p>
<p align="center">如果这里的项目对你有帮助，欢迎点个 ⭐ Star 支持一下</p>
