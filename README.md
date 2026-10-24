<img src="docs/banner.png" width="100%" alt="Caoran · NAS / Docker / 影视自动化" />

## Hi, I'm Caoran 👋

**自建折腾党 · NAS / Docker / 影视自动化 · 让家里的服务器替我干活**

<img align="right" src="https://komarev.com/ghpvc/?username=Caoran1314&label=VISITORS&color=6878ff&style=flat-square" alt="visitors" />

> 「把重复的事交给脚本，把选择留给自己。」

---

## 🧭 关于我

- 🏠 家里跑着一台 **fnOS NAS**，70+ 容器、几十个服务，能自建的绝不用第三方
- 🎬 沉迷 **媒体自动化**：订阅 → 搜资源 → 挑画质 → 入库 → 刮削 → 播放，全程不想手点
- 🤖 喜欢把**真实流程**做成工具：多智能体编排、订阅管理、抢购、签到这些重复动作
- 🐳 交付习惯：**一条 `docker run` 能起来的**，才算做完

---

## 🧰 正在折腾

> 家里这台 NAS 上长期跑着的服务（全部 Docker 自建、仅内网/自用反代访问）

| 类别 | 服务 | 在干什么 |
|---|---|---|
| 🎬 媒体中枢 | **media-suite** | 本仓库：搜资源 → 推送 → 回序号 → 入库调度 |
| | **Cloud Media Sync** | 115 转存 → 自动整理命名 → strm → 302 直链 |
| | **Emby** | 播放端，读 strm 直接 302 拉到 115 CDN |
| | **MoviePilot** | 订阅中心（只读给 media-suite 用） |
| | **MTW / MoonTV** | 影视聚合、片源检索 |
| 🎵 音乐 | **Navidrome / 道理鱼音乐** | 音乐库与播放 |
| | **Musicn / Coco / RoMusic** | 音源与下载 |
| 📚 阅读 | **Komga / Audiobookshelf** | 漫画与有声书 |
| 🖼 照片 | **Immich** | 自建相册与备份 |
| 🌐 入口与网络 | **Lucky** | 反代、端口转发、证书自动化 |
| | **mihomo** | 代理与规则分流 |
| | **Homepage / Sun-Panel** | 两个导航面板（一个看状态、一个纯快捷） |
| | **Home Assistant** | 智能家居中枢 |
| 🛠 运维 | **Halo** | 自建博客 |
| | **pansou / qBittorrent** | 资源搜索与下载 |
| | **fnOS / GlassDock** | 底层系统与容器监控 |

---

## 🚀 项目

### 🎬 影音与订阅

<table>
<tr>
<td width="50%" valign="top">

**[media-suite](https://github.com/Caoran1314/media-suite)**
影视订阅自动化中枢：pansou 搜 115 → 画质优选 → TG/飞书推送 → 回序号转存 → 自动整理 → Emby 302 直连

`Docker` `Telegram Bot` `飞书长连接` `管理面板`

</td>
<td width="50%" valign="top">

**[subs](https://github.com/Caoran1314/subs)** ⭐
把订阅理清，把选择留给自己 —— 本地优先的订阅管理与续费决策：会员/AI 套餐、每月花费、分类构成

`TypeScript` `Local-first`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[douyin-auto-fire](https://github.com/Caoran1314/douyin-auto-fire)** ⭐
抖音自动续火花 Docker 版：自带配置网页 + 每日晨报（热点/天气/名言）+ 热门视频转发

`Python` `Docker` `Cron`

</td>
<td width="50%" valign="top">

**[browser-skill-headless-ops](https://github.com/Caoran1314/browser-skill-headless-ops)**
用无头 Chromium 跑 Tencent BrowserSkill（bsk）做页面操作与验证

`Shell` `Headless Chrome`

</td>
</tr>
</table>

### 🏛 多智能体 / DeepSeek Harness 插件

<table>
<tr>
<td width="50%" valign="top">

**[dsh-edict](https://github.com/Caoran1314/dsh-edict)** ⭐
三省六部制多智能体审核流程，移植为 DSH 插件：12 状态状态机、门下省封驳、高风险确认、越权矩阵、委派防环

`Multi-Agent` `DSH Plugin`

</td>
<td width="50%" valign="top">

**[sansheng-liubu](https://github.com/Caoran1314/sansheng-liubu)** ⭐
三省六部制多智能体任务编排：状态机、封驳退回、越权矩阵、委派防环与审计

`JavaScript` `Claude Code Plugin`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[dsh-envkit](https://github.com/Caoran1314/dsh-envkit)** ⭐
DeepSeek Harness 环境工具插件：env_probe 探明网络/代理/可写性/子进程管道；safe_json_edit 安全改 JSON

`DSH Plugin` `Node.js`

</td>
<td width="50%" valign="top">

**（持续新增中…）**
把日常踩过的坑做成插件，比写笔记有用

`…`

</td>
</tr>
</table>

### 🖥 折腾与自动化脚本

<table>
<tr>
<td width="50%" valign="top">

**[apple-cn-checkout](https://github.com/Caoran1314/apple-cn-checkout)** ⭐
苹果中国官网 iPhone 全自动选购与结账：稳定选择器、分级门控、静默失败坑位记录

`Browser Automation` `Shell`

</td>
<td width="50%" valign="top">

**[YankeeBBR](https://github.com/Caoran1314/YankeeBBR)** ⭐
来自 Loc 大佬 Yankee 魔改的 BBR 内核，Debian 一键安装包

`Shell` `Linux Kernel`

</td>
</tr>
</table>

---

## 🛠 技术栈

<div align="center">

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?logo=gnubash&logoColor=white)
![飞书](https://img.shields.io/badge/飞书-3370FF?logo=feishu&logoColor=white)

</div>

---

## 📊 数据

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Caoran1314&show_icons=true&hide_border=true&theme=tokyonight&locale=cn" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Caoran1314&layout=compact&hide_border=true&theme=tokyonight&locale=cn" />

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Caoran1314&theme=tokyonight" width="100%" />

<img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Caoran1314&theme=tokyonight" />
<img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Caoran1314&theme=tokyonight" />
<img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Caoran1314&theme=tokyonight&utcOffset=8" />

</div>

## 📈 贡献与动态

<div align="center">

<img src="https://ghchart.rshah.org/6878ff/Caoran1314" width="100%" alt="Caoran1314 的贡献图" />

</div>

---

<div align="center">

<sub>⭐ 如果哪个项目帮到了你，点个 star 就是最大的鼓励</sub>

</div>
