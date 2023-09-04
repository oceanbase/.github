# 贡献指南

[English](README.md) | 中文版

👍🎉 首先，感谢您愿意投入时间做出贡献！ 🎉👍

OceanBase 社区热情欢迎每一位开发者，无论是文档调整、文字修正，还是问题修复、增加新功能，都是对 OceanBase 社区做出贡献的方式之一。

如果您对 OceanBase 社区的贡献流程还不熟悉，请参考以下内容。如果您对本文档的内容有异议，欢迎直接在此仓库提出 Issue 或 Pull Request。

## 贡献流程

### 准备工作

在向 OceanBase 社区进行贡献前，您需要先完成以下准备工作。

#### 1. GitHub 账号

在开始贡献前，您需要先 [注册](http://github.com/signup) 一个 GitHub 账号。

#### 2. 行为准则

请仔细阅读并遵守 OceanBase 社区的 [行为准则](CODE_OF_CONDUCT.md)。

#### 3. CLA 协议

请仔细阅读 [CLA 协议](https://cla-assistant.io/oceanbase/oceanbase) 并使用 GitHub 账号签署该协议。

### 社区贡献流程

OceanBase 社区的工作流程基于 GitHub 平台，一般包含以下几个步骤。

#### 1. 关联或创建 Issue

OceanBase 社区在 GitHub 平台使用 [Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) 来对任务进行追踪， 社区内的项目大体上将 Issues 分为 `Bug Report`, `Documentation Related`, `Enhancement`, `Feature Request` and `Question`。除此之外，我们为一些适合新手开发者的 Issue 打上了 `help wanted` 或 `good first issue` 标签，您可以从这些 Issue 入手来进行您的第一次贡献。

在您开始进行贡献之前，我们建议您先提交一个 Issue 来与社区进行讨论，以避免做出与社区内其他开发者重复或冲突的修改。如果您对某个已有的 Issue 感兴趣，您可以直接在该 Issue 进行回复，让相关的维护者将该 Issue 分配给您。

#### 2. Fork 仓库

Fork 您想要修改的项目仓库，并将您的 fork 仓库拉去到本地，具体操作可以参考 [GitHub 文档](https://docs.github.com/en/get-started/quickstart/fork-a-repo)。

#### 3. 提交修改

对于想要向 OceanBase 内核仓库进行贡献的开发者，可以参阅内核仓库的[开发指南](https://github.com/oceanbase/oceanbase/blob/master/docs/README.md)。

对于想要向其他社区项目进行贡献的开发者，请参考对应项目仓库的相关文档进行修改。 

您也可以访问 OceanBase 的[文档网站](https://en.oceanbase.com/docs)来了解各个项目的更多信息。

在修改完成后，您需要使用 Git 进行提交，并将该提交推送到您的 fork 仓库。

#### 4. 提交 Pull Request

现在您的 fork 仓库的开发分支已经包含了您进行修改的提交，您需要使用该分支来提交一个 Pull Request。详细操作可以参考 [GitHub 文档](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)。

我们为社区内的仓库设置了 Pull Request 模板，您需要正确填写它，以便其他人可以更好地评审您的 Pull Request。 对于 Pull Request 的标题，我们推荐使用 [conventional commits](https://www.conventionalcommits.org) 格式。如果您的 Pull Request 解决了一个已有的 Issue，请使用 `close #xxx` 等关键字在 Pull Request 正文中关联该 Issue，详情可参考 [GitHub 文档](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)。

#### 5. 代码评审

Pull Request 发起完成后，社区内将会有相关的研发人员对修改内容进行评审。在此过程中，如果您需要更新该 Pull Request 对应的代码，请直接在对应的分支追加新的 Git 提交，并将该修改推送到您的 fork 仓库，关联的 Pull Request 将会自动更新。

评审完成后，代码将会被合并到主仓库中，至此您就完成了在 OceanBase 社区的一次贡献。

## 保持联系

欢迎您随时通过社区的[各种渠道](https://github.com/oceanbase/oceanbase#community)与我们进行交流。

我们也会定期举行开发者会议，您可以订阅此 [Issue](https://github.com/oceanbase/oceanbase/issues/1368) 来获取最新消息。
