<p align="center"><img src="../../icon.png" alt="AnchorMC 图标" width="128"></p>

# AnchorMC

以 Minecraft 1.8 为基础的现代 PvP 服务器，提供 PracticePvP、活动、PartyPvP 等玩法。

*由 Schema’Fox Labs 重建*

---

[English](../../README.md) · **中文** · [日本語](README.ja-JP.md) · [हिन्दी](README.hi-IN.md)

AnchorMC 是 NetherMC（现已关闭）的完整重构版，是一个不以盈利为目的的社区项目。

> 各语言版本存在差异或歧义时，服务器与社区规则的解释以英语版为准。

> 任何版本（包括英语版）的规则措辞、翻译差异或歧义，都可以通过 [Security and quality](https://github.com/SchemaFoxLabs/AnchorMC/security) 中的 **Report a vulnerability** 反馈，以便澄清和修正。

报告安全问题时，请在 Security 页面选择 **Report a vulnerability**。若入口不可用，请仅通过 Issue 询问私密联系方式，不要披露漏洞细节。

_本仓库是服务器的公开反馈与更新记录入口。_
_不包含可克隆的源代码或可部署的服务端，项目政策不接受 Pull Request。_
_反馈或 bug 报告请使用 Issues。_

## 常用文档与功能

- [服务器与社区规则](SERVER_RULES.zh.md)
- [玩家举报／申诉](https://github.com/Labs-mcdev/AnchorMC-PublicReport/)
- [报告安全问题](https://github.com/SchemaFoxLabs/AnchorMC/security)
- [功能建议／提交反馈](https://github.com/SchemaFoxLabs/AnchorMC/issues/new/choose)
- [开发日志](https://github.com/SchemaFoxLabs/AnchorMC/releases)
- [活动记录／存档](../../Events/)
- [客户端优化 Mod](https://github.com/Labs-mcdev/VanillaEnhance)
- [玩法特性与机制](GAMEPLAY_FEATURES.zh.md)
- 官方网站（soon）

---

## 目录

- [项目介绍](#项目介绍)
- [反馈与问题追踪](#反馈与问题追踪)
- [服务器与基础命令](#服务器与基础命令)
- [支持者奖励](#支持者奖励)
- [规则与运营](#规则与运营)
- [项目历史](#项目历史)
- [特别致谢](#特别致谢)

## 项目介绍

AnchorMC 是一个竞技 Minecraft 服务器项目，致力于为亚洲玩家提供现代 PvP 体验。

Schema’Fox Labs 重建并维护 AnchorMC，将经典 1.8 PvP 机制与新技术、优化的基础设施及创新玩法结合起来。

我们的目标是在引入新体验的同时保留经典 Minecraft。

## 反馈与问题追踪

提交 bug 报告、使用疑问或功能建议前，请阅读[反馈规则（英文）](../FeedbackRule_QA-SI.md)。

> [!IMPORTANT]
> 请清楚说明具体问题或需求。只有主观评价或没有实质信息的反馈可能无法处理。

> [!WARNING]
> 请确认反馈准确描述了你的观察。
>
> 公开 Issue 对其他人可见。请从文本、日志和截图中移除真实姓名、私人联系方式、可识别信息和现实位置；已发布信息可能无法完全撤回。

Staff 根据可用时间和证据处理提交，部分反馈可能长期处于待处理状态。

通常 1–7 天、繁忙时 8–30 天仅为初次处理或首次回复的参考，可能超出，特别是功能请求。这不是调查、解决或处罚期限。

功能请求需要评估必要性、可行性、开发排期和与现有架构的兼容性。

普通功能故障，包括不涉及安全的严重故障，请使用 Bug 报告表单。漏洞或可能被滥用的问题，请通过上方 Security 页面报告。

Staff 离线时的玩家举报，以及对 Join Block、Feature Block 或 SubServer Block 的误判申诉，请使用 [AnchorMC-PublicReport](https://github.com/Labs-mcdev/AnchorMC-PublicReport/)。

## 服务器与基础命令

切换服务器：

```minecraft-command
/server <identification>
```

| 服务器 | 内部标识 | 介绍 | Minecraft 版本 |
| :--- | :--- | :--- | :--- |
| Practice | `practice` | 提供 1v1 对战、活动和 PartyPvP 的现代 Practice PvP | 核心 1.8.x；客户端 1.7.10–1.20.x |
| Bridge | `bridge` | 搭路、战斗和方块放置练习 | 核心 1.8.x；客户端 1.7.10–1.20.x |
| Flat-PVP | `flatpvp/flat` | 在极高击退效果下击败对手 | 核心 1.8.x；客户端 1.7.10–1.20.x |
| Sky PVP | `skypvp` | 收集资源，购买具有不同效果的装备 | 核心 1.8.x；客户端 1.7.10–1.20.x |
| PracticeX | soon | 面向 1.20.x 的 Practice PvP | 核心 1.20.x；客户端 1.7.10–1.20.x |
| 1.9+ | soon | 剑术对战 | 核心 1.12.2；客户端 1.7.10–1.20.x |

受预算限制，部分服务器在没有玩家活跃时可能暂时下线。Practice 通常保持在线。

## 支持者奖励

经核实符合奖励条件的严重漏洞、bug 或安全问题报告将获得：

- 长期有效的 Support Rank。
- 贡献者公示（名单过长时可能移至独立文档）。

Rank 会根据报告的价值和数量升级：

**Support → SupportX → BugFinder → IssueExpert**

奖励资格由 Staff 核实。提交或受理本身不会自动产生奖励。奖励属于非购买型贡献奖励，与未来资金资助无关。

## 规则与运营

- [服务器与社区规则](SERVER_RULES.zh.md)
- [玩法特性与机制](GAMEPLAY_FEATURES.zh.md)
- [服务器使用与运营说明](SERVER_TERMS.zh.md)
- [版权与第三方内容说明](ASSET_RIGHTS.zh.md)

服务器目前不出售外观、权限或其他付费内容，也不接受赞助、捐赠或付款。未来可能考虑允许使用正版 Minecraft 在线账户的玩家直接资助实际服务器托管费用；任何安排都会在开放前另行公布。

## 项目历史

原始服务器由 NightCelest 与 Tiantang 建设。Schema’Fox Labs 重建了项目，Alice Tuna 和 nullindex 负责技术、系统设计与重建工作。AnchorMC 在保留经典 PvP 基础的同时持续发展新的体验。

---

## 特别致谢

### 原始服务器建设者

- [NightCelest](https://github.com/a3087814532)
- Tiantang（未找到公开社交媒体主页）

### 系统、玩法、UI/UX 设计与体验架构

- [Alice Tuna](https://github.com/LocalHost0080)

### 技术

- [nullindex](https://github.com/error-nullindex)

### 地图资源提供者

- [Alice Tuna](https://github.com/LocalHost0080)
- [rido](https://builtbybit.com/members/rido.331767/)
- [thegetawxy](https://www.planetminecraft.com/project/slime-arena-duel-pvp/)
- [Redstone Labs](https://builtbybit.com/members/redstone-labs.268653/)
- [betapaste](https://builtbybit.com/members/betapaste.512624/)
- [ColoN_](https://builtbybit.com/members/colon_.468523/)
- [PokyBuilds](https://builtbybit.com/members/pokybuilds.531551/)
- [zsomborr](https://builtbybit.com/members/zsomborr.335177/)
- [Solar Studios](https://builtbybit.com/members/solar-studios.500547/)

如需登记或更正地图资源、系统设计贡献，请联系 `mc-s-reg@schemafoxlabs.com`。

---

*该优先规则仅解释 AnchorMC 自己的规则，不改变第三方许可证、平台规则或不可排除的法定权利。*

*本项目不隶属于 Mojang 或 Microsoft，也未获其批准或与其关联。*

Regards,

@SchemaFoxLabs 2026
