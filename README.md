<div align="center">

<img src="assets/banner.png" width="1280" alt="ErisPulse" />

# ErisPulse

**Write once, run on 15+ chat platforms. · 一份代码，跑遍 15+ 聊天平台。**

<p>
  <a href="https://github.com/ErisPulse/ErisPulse"><img src="https://img.shields.io/github/stars/ErisPulse/ErisPulse?style=flat-square&logo=github&color=brightgreen" alt="Stars"></a>
  <a href="https://pypi.org/project/ErisPulse/"><img src="https://img.shields.io/pypi/v/ErisPulse?style=flat-square&logo=pypi&logoColor=white" alt="PyPI"></a>
  <a href="https://hub.docker.com/r/erispulse/erispulse"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"></a>
  <img src="https://raw.githubusercontent.com/ErisPulse/.github/main/assets/badges/powered-by.svg" alt="Powered by ErisPulse">
</p>

[Website](https://www.erisdev.com) · [Dashboard Demo](https://dashdemo.erisdev.com) · [Module Market](https://www.erisdev.com/#market) · [Discussions](https://github.com/ErisPulse/ErisPulse/discussions)

</div>

---

## English

You know Python and want a bot for your group chat or community. The annoying part: every platform has its own API, auth flow and message types, so the same logic ends up maintained three or four times.

ErisPulse hides platform differences behind adapters. Business code is written once against the OneBot12 event model and deploys to QQ, Telegram, Kook, Yunhu, WeChat, Discord, Matrix, Email and more — platform-specific features stay reachable when you actually need them. Hot reload, permissions and declarative config come with the framework.

```bash
pip install ErisPulse
epsdk init
```

| Repo | What it is |
|------|------------|
| [ErisPulse](https://github.com/ErisPulse/ErisPulse) | The framework |
| [ErisPulse-Dashboard](https://github.com/ErisPulse/ErisPulse-Dashboard) | Web admin panel |
| [ErisPulse-ModuleRepo](https://github.com/ErisPulse/ErisPulse-ModuleRepo) | Module marketplace source |
| [erisdev.com](https://www.erisdev.com) | Website & docs |

Modules get published through [ModuleRepo](https://github.com/ErisPulse/ErisPulse-ModuleRepo). For framework contributions, read the [contributing guide](https://github.com/ErisPulse/ErisPulse/blob/main/CONTRIBUTING.md). MIT licensed.

## 简体中文

会 Python，想给群聊或社区做个机器人。麻烦在于：每个平台的 API、鉴权、消息类型都不一样，同一套逻辑往往要维护好几份。

ErisPulse 把平台差异挡在适配器层：业务代码基于 OneBot12 统一事件模型只写一遍，就能部署到 QQ、Telegram、Kook、云湖、微信公众号、Discord、Matrix、邮件等 15+ 平台，平台专有能力照样直达。热重载、权限管控、声明式配置都是框架自带的。

安装与初始化命令见上方代码块。

| 仓库 | 干什么用 |
|------|----------|
| [ErisPulse](https://github.com/ErisPulse/ErisPulse) | 主框架 |
| [ErisPulse-Dashboard](https://github.com/ErisPulse/ErisPulse-Dashboard) | Web 管理面板 |
| [ErisPulse-ModuleRepo](https://github.com/ErisPulse/ErisPulse-ModuleRepo) | 模块市场源仓库 |
| [erisdev.com](https://www.erisdev.com) | 官网与文档 |

模块发布走 [ModuleRepo](https://github.com/ErisPulse/ErisPulse-ModuleRepo)，参与框架开发先看[贡献指南](https://github.com/ErisPulse/ErisPulse/blob/main/CONTRIBUTING.md)。基于 MIT 协议开源。
