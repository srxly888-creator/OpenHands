<a name="readme-top"></a>

<div align="center">
  <img src="https://raw.githubusercontent.com/OpenHands/docs/main/openhands/static/img/logo.png" alt="Logo" width="200">
  <h1 align="center" style="border-bottom: none">OpenHands: AI 驱动开发</h1>
</div>


<div align="center">
  <a href="https://github.com/OpenHands/OpenHands/blob/main/LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-20B2AA?style=for-the-badge" alt="MIT License"></a>
  <a href="https://docs.google.com/spreadsheets/d/1wOUdFCMyY6Nt0AIqF705KN4JKOWgeI4wUGUP60krXXs/edit?gid=811504672#gid=811504672"><img src="https://img.shields.io/badge/SWEBench-77.6-00cc00?logoColor=FFE165&style=for-the-badge" alt="Benchmark Score"></a>
  <br/>
  <a href="https://docs.openhands.dev/sdk"><img src="https://img.shields.io/badge/文档-000?logo=googledocs&logoColor=FFE165&style=for-the-badge" alt="Check out the documentation"></a>
  <a href="https://arxiv.org/abs/2511.03690"><img src="https://img.shields.io/badge/论文-000?logoColor=FFE165&logo=arxiv&style=for-the-badge" alt="Tech Report"></a>

  <p><strong>🇨🇳 中文版</strong> | <a href="README_EN.md">English</a></p>

  <!-- Keep these links. Translations will automatically update with the README. -->
  <a href="https://www.readme-i18n.com/OpenHands/OpenHands?lang=de">Deutsch</a> |
  <a href="https://www.readme-i18n.com/OpenHands/OpenHands?lang=es">Español</a> |
  <a href="https://www.readme-i18n.com/OpenHands/OpenHands?lang=fr">français</a> |
  <a href="https://www.readme-i18n.com/OpenHands/OpenHands?lang=ja">日本語</a> |
  <a href="https://www.readme-i18n.com/OpenHands/OpenHands?lang=ko">한국어</a> |
  <a href="https://www.readme-i18n.com/OpenHands/OpenHands?lang=pt">Português</a> |
  <a href="https://www.readme-i18n.com/OpenHands/OpenHands?lang=ru">Русский</a> |
  <a href="https://www.readme-i18n.com/OpenHands/OpenHands?lang=zh">中文</a>

</div>

<hr>

🙌 欢迎来到 OpenHands，一个专注于 AI 驱动开发的[社区](COMMUNITY.md)。我们很希望你能[加入我们的 Slack](https://dub.sh/openhands)。

有以下几种方式可以使用 OpenHands：

### OpenHands Software Agent SDK
SDK 是一个可组合的 Python 库，包含我们所有的智能体技术。它是驱动下面所有其他内容的核心引擎。

在代码中定义智能体，然后在本地运行，或者在云端扩展到数千个智能体。

[查看文档](https://docs.openhands.dev/sdk) 或 [查看源码](https://github.com/OpenHands/software-agent-sdk/)

### OpenHands CLI
CLI 是开始使用 OpenHands 最简单的方式。体验将类似于使用 Claude Code 或 Codex 的用户。你可以使用 Claude、GPT 或任何其他 LLM 来驱动它。

[查看文档](https://docs.openhands.dev/openhands/usage/run-openhands/cli-mode) 或 [查看源码](https://github.com/OpenHands/OpenHands-CLI)

### OpenHands Local GUI
使用 Local GUI 在你的笔记本电脑上运行智能体。它附带 REST API 和单页 React 应用程序。体验将类似于使用 Devin 或 Jules 的用户。

[查看文档](https://docs.openhands.dev/openhands/usage/run-openhands/local-setup) 或在这个仓库中查看源码。

### OpenHands Cloud
这是在托管基础设施上运行的 OpenHands GUI 部署。

你可以通过[使用 GitHub 或 GitLab 账户登录](https://app.all-hands.dev)免费试用 Minimax 模型。

OpenHands Cloud 附带源代码可用的功能 and 集成：
- 与 Slack、Jira 和 Linear 的集成
- 多用户支持
- RBAC 和权限
- 协作功能（例如，对话共享）

### OpenHands Enterprise
大型企业可以与我们合作，通过 Kubernetes 在自己的 VPC 中自托管 OpenHands Cloud。
OpenHands Enterprise 也可以使用上面的 CLI 和 SDK。

OpenHands Enterprise 是源代码可用的——你可以在这里的 enterprise/ 目录中看到所有源代码，但如果你想运行超过一个月，你需要购买许可证。

企业合同还附带扩展支持和访问我们研究团队的机会。

在 [openhands.dev/enterprise](https://openhands.dev/enterprise) 了解更多

### 其他

查看我们的[产品路线图](https://github.com/orgs/openhands/projects/1)，如果你有想看到的东西，请随时[提出问题](https://github.com/OpenHands/OpenHands/issues)！

你可能还会对我们的[评估基础设施](https://github.com/OpenHands/benchmarks)、[Chrome 扩展](https://github.com/OpenHands/openhands-chrome-extension/)或[心智理论模块](https://github.com/OpenHands/ToM-SWE)感兴趣。

我们所有的工作都在 MIT 许可下可用，除了本仓库中的 `enterprise/` 目录（详情请参见[企业许可证](enterprise/LICENSE)）。
核心的 `openhands` 和 `agent-server` Docker 镜像也是完全 MIT 许可的。

如果你需要任何帮助，或者只是想聊天，[来 Slack 找我们](https://dub.sh/openhands)。
