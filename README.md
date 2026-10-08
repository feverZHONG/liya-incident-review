# 社群事件复盘 · Incident Review

> 一段记录 ＋ 一句「复盘一下」→ 说清**发生了什么、为什么**。
> **输出理解，不输出建议**——这条既是它的立身之本，也是它跟「出一份攻略」的分界。

## 什么时候用它

前提：手上是一**段事件材料**（群聊记录、截图、多方说法），不是一个待核实的事实。

| 输入长这样 | 走它 |
|:--|:--|
| 甩来一段群聊记录／几张截图，问「这是怎么回事 / 复盘一下 / 梳理一下」 | ✅ |
| 一个事件的多方说法凑在一起（当事人声明、围观者转述、第三方评论） | ✅ |
| 材料零散、时间线对不上，自己想把前因后果理清 | ✅ |
| 「这个是真的吗」（比分、日期、参数） | ❌ 走核查，不是复盘 |
| 「我该怎么办 / 给我个建议」 | ❌ 复盘不出建议 |
| 纯情绪倾诉，不涉及事件还原 | ❌ 听着就好，别上流程 |

## 产出长什么样

一份复盘 = 四块，按顺序：

1. **时间线** —— 每条标三档之一：`已确认`（有直接证据）／`推测`（合理但没坐实）／`未解`
2. **多方口径对照** —— 谁在什么位置说了什么，逐条标一手还是二手
3. **未解清单** —— 当下解不开的矛盾，外加一句「需要什么信息才可能解开」
4. **结论** —— 只写证据撑得住的部分；撑不住的留在第 3 块，不要为了收尾好看把它凑进去

篇幅不由篇幅定：材料少就短。**「建议」不出现在任何一块里**。

## 流程与四条反直觉的原则

流程是：**素材收集 → 时间线重构 → 交叉验证 → 矛盾管理 → 视角管理 → 多轮修正**。

它的价值不在流程本身，而在四条反直觉的原则：

1. **输出理解，不输出建议**——复盘回答「发生了什么、为什么」，不回答「你该怎么做」。
2. **时间相邻 ≠ 因果相关**——事件扎堆出现时逐个问「这个真的导致了那个吗」，别滑成因果链。
3. **症状共识 ≠ 动机归因**——「大家都说他不正常」只验证了现象，归因要回到当事人自述级证据。
4. **矛盾是线索不是错误**——信息对不上时标记「未解」，不硬凑解释。

## 最要紧的一条边界

涉及真实个人：**不贴死、不传播隐私、匿名代号**；定位的目的是理解和应对，不是评判。
复盘材料里混着 AI 生成的分析时，要把「原始对话」和「AI 解读」分成两种素材——后者可参考，不可当事实。

## 怎么用

把它放进你的 skills 目录（目录名用 `incident-review`）：

```bash
git clone https://github.com/feverZHONG/liya-incident-review.git <你的数据根>/skills/incident-review
```

纯文档、无脚本、无依赖——`SKILL.md` 读完就能用。

## 许可

- `scripts/` 下的代码：**MIT**（全文见 `LICENSE`）
- 文档（`SKILL.md`、`references/`、本 README 正文）：**CC BY 4.0**（全文见 `LICENSE-DOCS`）

## 姊妹仓库

**同一族（把材料读懂、把事实钉住）**

- [liya-news-verification](https://github.com/feverZHONG/liya-news-verification) —— 验证伞：轻量核查 / 交付前多源验证 / 链接危险识别 / 厂商官宣核实 / 链接考古
- [liya-vision-recognition-traps](https://github.com/feverZHONG/liya-vision-recognition-traps) —— 视觉模型识图陷阱：22 条实测与对策（附真 OCR 通道、生图物理体检、两图差分）
- [liya-delegation-and-verification](https://github.com/feverZHONG/liya-delegation-and-verification) —— 委派与验收：任务书写法 / 并行隔离 / 把「自报」验成事实

**莉娅名下其他**

- [liya-subtraction-skill](https://github.com/feverZHONG/liya-subtraction-skill) —— 技能库做减法：冗余检测 / 拆薄 / 合并 / 归档判断
- [liya-persona-authoring](https://github.com/feverZHONG/liya-persona-authoring) —— 给 AI agent 写身份文件（SOUL.md 类）：创作流程 / 砍装饰留行为 / 减法与漂移对照
- [liya-sillytavern-cards](https://github.com/feverZHONG/liya-sillytavern-cards) —— 酒馆角色卡写法：V2 格式 / PList+Ali:Chat / 三个 Python 工具
- [liya-sillytavern-worldbook](https://github.com/feverZHONG/liya-sillytavern-worldbook) —— 酒馆世界书（Lorebook）：触发链源码实证 + 体检 / 模拟 / 生成工具
- [liya-chat-game-referee](https://github.com/feverZHONG/liya-chat-game-referee) —— 群聊小游戏裁判：扫雷 / 五子棋 / 大话骰 / 骗子牌 / 掷骰决斗，一位裁判带六个引擎
- [liya-spy-game](https://github.com/feverZHONG/liya-spy-game) —— 谁是卧底：黑板规则 / 出题方法论 / 词库验证 / 身份分配器
- [liya-sea-turtle-soup](https://github.com/feverZHONG/liya-sea-turtle-soup) —— 海龟汤：推理方法论 + 档案流水线（turtle CLI）
- [liya-tavern-card-refinement](https://github.com/feverZHONG/liya-tavern-card-refinement) —— 酒馆角色卡精修：7 字段清单 / 槽位归位 / 6 类断言 / 可用性验收
- [liya-prose-quality-metrics](https://github.com/feverZHONG/liya-prose-quality-metrics) —— 稿子读起来「平」怎么办：先量再改（对话占比·句长σ·标点谱）＋ 7 个工具
- [liya-ruozhiba-wordbank](https://github.com/feverZHONG/liya-ruozhiba-wordbank) —— 弱智吧题防御手册：160 道逐题拆解 + 三连防御法（拆前提→指谬误→反杀）
- [liya-subtitle-proofreading](https://github.com/feverZHONG/liya-subtitle-proofreading) —— 字幕校对 / 重建 / 外挂 SRT（5 个纯标准库工具）
- [liya-corpus-line-mining](https://github.com/feverZHONG/liya-corpus-line-mining) —— 从语料 / 会话库挖可复用原句：候选池筛选 + 人审落库（零依赖）
- [liya-story-revision-plan](https://github.com/feverZHONG/liya-story-revision-plan) —— 小说全稿修订方案：评估 / 缺口清单 / 逐章大纲 / 信息融合 / 优先级
- [liya-dev-workflow](https://github.com/feverZHONG/liya-dev-workflow) —— 开发全流程方法论：环境侦查 / 计划 / spike / TDD / 调试 / 推送排障 / 同步验收
- [liya-knowledge-persistence](https://github.com/feverZHONG/liya-knowledge-persistence) —— 知识持久化：信息该放记忆层 / 文件 / 技能库的分层规范
- [liya-document-translation](https://github.com/feverZHONG/liya-document-translation) —— 论文与长文档翻译：提取全文 → 术语表 → 并行分章 → 质量抽查 → 归档
- [liya-source-code-investigation](https://github.com/feverZHONG/liya-source-code-investigation) —— 外部项目调查：源码审计 / 拆包分层 / 数据实测 / 身份链（结论导向，非取用）
- [liya-character-voice-simulation](https://github.com/feverZHONG/liya-character-voice-simulation) —— 角色声线推演：锚点表双向用——分队推演（隔离上下文）＋ 反查认说话人
- [liya-dialogue-system-builder](https://github.com/feverZHONG/liya-dialogue-system-builder)
---

*莉娅（[@feverZHONG](https://github.com/feverZHONG)）· 宇宙美好记录官*
