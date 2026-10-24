<div align="center">

<img src="assets/banner.png" width="1280" alt="ErisPulse" />

# ErisPulse

**事件驱动的模块化 Python 机器人框架。一次编写，多平台部署。**

<p>
  <a href="https://github.com/ErisPulse/ErisPulse"><img src="https://img.shields.io/github/stars/ErisPulse/ErisPulse?style=flat-square&logo=github&color=brightgreen" alt="Stars"></a>
  <a href="https://pypi.org/project/ErisPulse/"><img src="https://img.shields.io/pypi/v/ErisPulse?style=flat-square&logo=pypi&logoColor=white" alt="PyPI"></a>
  <a href="https://hub.docker.com/r/erispulse/erispulse"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"></a>
  <a href="https://www.erisdev.com"><img src="https://img.shields.io/badge/文档-erisdev.com-FF6B9D?style=flat-square&logo=bookstack&logoColor=white" alt="文档"></a>
  <a href="https://www.erisdev.com/#market"><img src="https://img.shields.io/badge/模块市场-erisdev.com-C724B1?style=flat-square&logo=webpack&logoColor=white" alt="模块市场"></a>
</p>

[快速开始](https://www.erisdev.com) · [Dashboard 在线演示](https://dashdemo.erisdev.com) · [模块市场](https://www.erisdev.com/#market) · [讨论区](https://github.com/ErisPulse/ErisPulse/discussions)

</div>

---

你会写 Python，想给自己的群聊、社区或内部系统做个机器人。麻烦在于：每个平台的 API、鉴权、消息类型各不相同，同一套逻辑往往要维护好几份代码。

ErisPulse 把平台差异挡在适配器层。业务代码基于 OneBot12 统一事件模型只写一遍，就能部署到 QQ、Telegram、Kook、云湖、微信公众号、Discord、Matrix、邮件等 15+ 平台，平台专有能力也依然直达。插件热重载、多轮对话、权限管控、声明式配置开箱即用，从第一个「hello bot」到长期挂机的自动化系统，用同一套框架。

```bash
pip install ErisPulse
epsdk init    # 交互式向导，几分钟跑起第一个机器人
```

## 这个组织在维护什么

| 项目 | 解决什么问题 |
|------|--------------|
| [**ErisPulse**](https://github.com/ErisPulse/ErisPulse) 主框架 | 一份业务代码跑遍 15+ 平台：统一事件模型、链式发送、热重载、作用域权限管控 |
| [**ErisPulse-Dashboard**](https://github.com/ErisPulse/ErisPulse-Dashboard) 可视化面板 | 在浏览器里管机器人：系统监控、模块启停、配置编辑、事件流查看 |
| [**ErisPulse-ModuleRepo**](https://github.com/ErisPulse/ErisPulse-ModuleRepo) 模块市场 | 社区模块与适配器的源头仓库，`epsdk install` 即装即用 |
| [**官方网站 · erisdev.com**](https://www.erisdev.com) | 五语言文档与快速上手指南，你的第一个机器人从这里开始 |


## 加入社区

- 文档与教程：[erisdev.com](https://www.erisdev.com)
- 问题与想法：[GitHub Discussions](https://github.com/ErisPulse/ErisPulse/discussions)

ErisPulse 基于 MIT 协议开源。写第一个模块、为新的平台做适配器、改进文档，或者只是聊聊你想做什么，都欢迎：发布模块请到 [ModuleRepo 提交](https://github.com/ErisPulse/ErisPulse-ModuleRepo)，参与框架开发请看[主仓贡献指南](https://github.com/ErisPulse/ErisPulse/blob/main/CONTRIBUTING.md)。
