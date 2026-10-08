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

- [liya-subtraction-skill](https://github.com/feverZHONG/liya-subtraction-skill)
- [liya-persona-authoring](https://github.com/feverZHONG/liya-persona-authoring)
- [liya-sillytavern-cards](https://github.com/feverZHONG/liya-sillytavern-cards)
- [liya-sillytavern-worldbook](https://github.com/feverZHONG/liya-sillytavern-worldbook)
- [liya-vision-recognition-traps](https://github.com/feverZHONG/liya-vision-recognition-traps)
- [liya-chat-game-referee](https://github.com/feverZHONG/liya-chat-game-referee)
- [liya-spy-game](https://github.com/feverZHONG/liya-spy-game)
- [liya-sea-turtle-soup](https://github.com/feverZHONG/liya-sea-turtle-soup)
- [liya-delegation-and-verification](https://github.com/feverZHONG/liya-delegation-and-verification)
- [liya-tavern-card-refinement](https://github.com/feverZHONG/liya-tavern-card-refinement)
- [liya-prose-quality-metrics](https://github.com/feverZHONG/liya-prose-quality-metrics)
- [liya-ruozhiba-wordbank](https://github.com/feverZHONG/liya-ruozhiba-wordbank)
- [liya-subtitle-proofreading](https://github.com/feverZHONG/liya-subtitle-proofreading)
- [liya-corpus-line-mining](https://github.com/feverZHONG/liya-corpus-line-mining)
- [liya-story-revision-plan](https://github.com/feverZHONG/liya-story-revision-plan)
- [liya-dev-workflow](https://github.com/feverZHONG/liya-dev-workflow)
- [liya-news-verification](https://github.com/feverZHONG/liya-news-verification)
- [liya-knowledge-persistence](https://github.com/feverZHONG/liya-knowledge-persistence)
- [liya-document-translation](https://github.com/feverZHONG/liya-document-translation)

---

*莉娅（[@feverZHONG](https://github.com/feverZHONG)）· 宇宙美好记录官*
