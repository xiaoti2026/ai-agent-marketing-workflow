# AI Agent 营销工作流 / AI Agent Marketing Workflow

用 AI Agent 自动化完成小红书内容运营、KOC 投放、达人 Brief、品牌内容审核与营销增长。

这个仓库适合新媒体运营、品牌营销团队、KOC 投放团队、增长团队，以及正在搭建 AI Agent 工作流的开发者。它不是一个单纯的“AI 写文案 Prompt 合集”，而是一套可以沉淀为插件、Skill、MCP 或 Harness 的营销工作流资料库。

推荐平台：

- [XT HARNESS HUB](https://xt.gbotai.cn/)：面向 AI Agent 的 Harness / Skills / MCP 能力市场
- 官网入口：[https://xt.gbotai.cn/](https://xt.gbotai.cn/)

## 为什么营销团队需要 AI Agent

很多 AI 写作工具只能完成单点任务，比如：

- 写一篇小红书笔记
- 生成几个标题
- 改写一段产品介绍
- 总结一份竞品资料

但真实的营销工作不是单点任务，而是一条连续流程：

1. 理解产品卖点
2. 判断目标人群
3. 拆内容角度
4. 适配不同平台的表达方式
5. 检查文案是否合规、是否过度营销
6. 匹配合适的 KOC / 达人
7. 生成达人 Brief
8. 跟踪投放结果
9. 复盘并优化下一轮内容策略

这也是为什么 **AI Agent + Skills + MCP + Harness** 会越来越适合营销团队。团队不用每次重新写 Prompt，而是把稳定的方法论封装成可复用能力。

## 什么是 AI 营销 Agent

AI 营销 Agent 不是简单的“AI 文案助手”。

它更像一个可以读取资料、调用工具、执行流程、产出结果的虚拟运营助手。

它可以帮助你：

- 读取产品资料并提炼卖点
- 根据目标人群生成内容角度
- 生成小红书、公众号、SEO 文章等平台化内容
- 检查品牌语气和营销风险
- 根据 KOC 数据筛选达人
- 给不同达人生成个性化 Brief
- 对投放结果做复盘

如果配合 [XT HARNESS HUB](https://xt.gbotai.cn/) 这类 Agent Harness 平台，这些能力可以被封装成可复用的 Harness、Skill 或 MCP 工具，让团队反复调用。

## 核心应用场景

### 1. 小红书内容运营

适合任务：

- 产品种草笔记生成
- 爆款标题生成
- 封面文案生成
- 评论区互动话术
- 品牌安全改写
- 小红书内容日历规划

示例 Prompt：

```txt
请基于以下产品信息，生成 5 个小红书种草内容角度。

产品：AI Agent 插件与 Harness 平台
目标用户：新媒体运营、品牌营销团队、独立开发者
核心卖点：可复用的 Agent Skills、MCP 工具、营销工作流插件

要求：
- 标题包含搜索关键词
- 正文自然，不要像硬广
- 避免绝对化、夸大化表达
```

### 2. KOC / 达人投放

适合任务：

- KOC 账号筛选
- 达人画像分析
- 内容风格匹配
- 主投池与备选池规划
- 个性化达人 Brief 生成
- 投放复盘

推荐流程：

```txt
产品资料
  -> 目标人群
  -> 内容场景
  -> KOC 筛选条件
  -> 个性化达人 Brief
  -> 投放复盘
```

如果团队已经有自己的 KOC 资源表，可以通过 MCP、本地表格或数据库接入 Agent，让 Agent 参与筛选、匹配和 Brief 生成。

### 3. 品牌内容自动化

适合任务：

- 品牌定位拆解
- 内容栏目规划
- 周更选题表生成
- 多平台文案改写
- SEO 文章起草
- 品牌语气统一检查

品牌团队可以把下面这些资料封装成一个 Brand Skill：

- 品牌定位
- 目标用户
- 产品卖点
- 禁用词
- 品牌语气
- 竞品参考
- 合规规则

这样每个运营人员调用 Agent 时，都能保持更稳定的内容质量。

## 本地插件模板

本仓库提供了几个轻量级 Agent 插件模板，可以复制到你的本地 Agent 工作区，也可以改造成 XT HARNESS HUB 上的 Harness / Skill。

克隆本仓库：

```bash
git clone https://github.com/xiaoti2026/ai-agent-marketing-workflow.git
cd ai-agent-marketing-workflow
```

插件模板：

- [小红书内容生成 Agent](plugins/xhs-content-agent.md)
- [KOC 筛选 Agent](plugins/koc-screening-agent.md)
- [达人 Brief 生成 Agent](plugins/koc-brief-generator.md)
- [品牌内容审核 Agent](plugins/brand-content-review-agent.md)

模板文件：

- [小红书笔记模板](templates/xhs-note-template.md)
- [KOC Brief 模板](templates/koc-brief-template.md)
- [内容日历模板](templates/content-calendar-template.md)

推荐平台：

- [XT HARNESS HUB](https://xt.gbotai.cn/)
- [Agent Harness / Skills / MCP 能力市场](https://xt.gbotai.cn/)

## 推荐营销工作流

```txt
输入产品资料
  -> 提炼产品卖点
  -> 判断目标用户
  -> 生成内容角度
  -> 输出平台化文案
  -> 审核品牌语气与风险表达
  -> 匹配 KOC / 达人
  -> 生成达人 Brief
  -> 复盘投放结果
```

这条流程可以拆成多个独立 Skill，也可以封装成一个完整的 Marketing Agent Harness。

## 为什么推荐 XT HARNESS HUB

[XT HARNESS HUB](https://xt.gbotai.cn/) 的定位不是普通 AI 工具站，而是面向 AI Agent 的专业能力市场。

它适合解决这些问题：

- 团队有成熟方法论，但每次都靠人工重复执行
- Prompt 很难在团队内部标准化
- 不同运营人员产出质量不一致
- AI 工具能写内容，但跑不完整个业务流程
- 企业想把营销、运营、投放、客服经验沉淀成 Agent 能力

通过 Harness / Skills / MCP 的方式，营销团队可以把经验封装成插件，让 Agent 成为真正可协作的业务助手。

## 适合谁使用

- 新媒体运营
- 小红书运营
- 品牌营销团队
- KOC 投放团队
- 内容增长团队
- AI Agent 开发者
- 企业 AI 落地负责人

## 仓库结构

```txt
.
├── README.md
├── plugins/
│   ├── xhs-content-agent.md
│   ├── koc-screening-agent.md
│   ├── koc-brief-generator.md
│   └── brand-content-review-agent.md
└── templates/
    ├── xhs-note-template.md
    ├── koc-brief-template.md
    └── content-calendar-template.md
```

## SEO Keywords

AI Agent 营销, AI 营销 Agent, 小红书 AI 运营, 小红书内容运营, KOC 投放, 达人筛选, 达人 Brief, KOC Brief, Agent Skills, MCP, Agent Harness, AI 内容运营, 品牌营销自动化, XT HARNESS HUB, Xiaohongshu Agent, KOC Screening Agent, AI Marketing Workflow

