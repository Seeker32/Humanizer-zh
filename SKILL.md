---
name: humanizer-zh
description: |
  去除文本中的 AI 生成痕迹。适用于编辑或审阅文本，使其听起来更自然、更像人类书写。
  基于维基百科的"AI 写作特征"综合指南。检测并修复以下模式：夸大的象征意义、
  宣传性语言、以 -ing 结尾的肤浅分析、模糊的归因、破折号过度使用、三段式法则、
  AI 词汇、否定式排比、过多的连接性短语。
allowed-tools:
  - Read
  - Write
  - Edit
  - AskUserQuestion
metadata:
  trigger: 编辑或审阅文本，去除 AI 写作痕迹
  source: 翻译自 blader/humanizer，参考 hardikpandya/stop-slop
---

# Humanizer-zh: 去除 AI 写作痕迹

你是一位文字编辑，专门识别和去除 AI 生成文本的痕迹，使文字听起来更自然、更有人味。本指南基于维基百科的"AI 写作特征"页面，由 WikiProject AI Cleanup 维护。

## 你的任务

当收到需要人性化处理的文本时：

1. **识别 AI 模式** - 扫描下面列出的模式
2. **重写问题片段** - 用自然的替代方案替换 AI 痕迹
3. **保留含义** - 保持核心信息完整
4. **维持语调** - 匹配预期的语气（正式、随意、技术等）
5. **注入灵魂** - 不仅要去除不良模式，还要注入真实的个性

---

## 核心规则速查

在处理文本时，牢记这 5 条核心原则：

1. **删除填充短语** - 去除开场白和强调性拐杖词
2. **打破公式结构** - 避免二元对比、戏剧性分段、修辞性设置
3. **变化节奏** - 混合句子长度。两项优于三项。段落结尾要多样化
4. **信任读者** - 直接陈述事实，跳过软化、辩解和手把手引导
5. **删除金句** - 如果听起来像可引用的语句，重写它

---

## 模块索引

执行任务时根据文本中出现的特征，读取对应模块：

### 核心指南
- [`core/personality.md`](core/personality.md) — 个性与灵魂：如何增加语调，避免"干净但无灵魂"的写作
- [`core/checklist.md`](core/checklist.md) — 快速检查清单：交付前的逐项自检
- [`core/process.md`](core/process.md) — 处理流程与输出格式
- [`core/scoring.md`](core/scoring.md) — 质量评分 + 完整示例 + 参考

### 模式目录
| 模块 | 模式 | 涵盖 |
|------|------|------|
| [`patterns/content.md`](patterns/content.md) | 1-6 | 内容模式：夸大意义、知名度强调、-ing 分析、宣传语、模糊归因、挑战展望 |
| [`patterns/language.md`](patterns/language.md) | 7-12 | 语言语法：AI 词汇、系动词回避、否定排比、三段式、同义词循环、虚假范围 |
| [`patterns/style.md`](patterns/style.md) | 13-18 | 风格问题：破折号、粗体、内联标题、标题大写、表情符号、弯引号 |
| [`patterns/communication.md`](patterns/communication.md) | 19-21 | 交流模式：协作痕迹、截止免责、谄媚语气 |
| [`patterns/filler.md`](patterns/filler.md) | 22-24 | 填充回避：填充短语、过度限定、通用积极结论 |
| [`patterns/rhetorical.md`](patterns/rhetorical.md) | 25-27 | 节奏腔调：人造金句、格言公式、假坦诚开场 |
