---
name: copy-cleaner
description: Polish, clean, and de-AI Chinese drafts for social/content writing while preserving the writer's voice, emotion, sharpness, and memorable lines. Use when the user wants to optimize a稿件, reduce AI-ish phrasing, improve platform fit, strengthen titles, sharpen the opening hook, or make text less flat and more有感觉. Best for 小红书/抖音/公众号/X/朋友圈/销售表达. Not for technical docs, legal text, or formal reports.
---

# 清洗稿件工具（copy-cleaner）

把一段已有中文稿件做第二轮清洗，不重开题，优先做“提纯”。

核心要求：**去 AI 味，不要把稿子磨平。**

## 适用场景

优先用于：
- 优化一段已经写出来的文案
- 降 AI 味
- 改标题
- 优化开头钩子
- 提升平台适配度
- 把“差不多能发”打磨成“更像本人、可直接发”

不适用于：
- 技术文档
- 法律文本
- 正式报告
- 完全没有素材却要求凭空深写的长文

## 标准流程

收到稿件后，默认按 4 步走：

1. 先判断这段稿件最大的问题是什么
2. 先找出这段稿件里**该保留的东西**：
   - 观点
   - 情绪
   - 作者口气
   - 有记忆点的表达
3. 再决定本轮重点清洗哪一层：
   - 结构
   - 语气
   - AI 味
   - 情绪势能
   - 记忆点
   - 标题
   - 开头
4. 先降噪，再补力度：
   - 先去机械感、模板感、翻译腔
   - 再补情绪、节奏、冲击力、作者存在感
5. 给出优化版
6. 若适合，再补可选标题 / 可选开头 / 更亮一句

除非用户明确说“不要分析，直接给我改”，否则不要跳过第 1 步。

## 必读参考

按任务类型读取：
- 内容诊断：`references/content-diagnosis.md`
- AI 味检测：`references/ai-fingerprint.md`
- 情绪 / 冲击力增强：`references/voice-impact.md`
- 标题优化：`references/title-patterns.md`
- 开头优化：`references/hook-patterns.md`

## 输出规则

### 若用户要“检测”
优先输出：
1. 最大问题
2. 原文里该保留的情绪 / 观点 / 表达
3. 具体病灶（按原文顺序点）
4. 严重度
5. 如果需要，再给优化版

### 若用户要“直接优化”
优先输出：
1. 一句话说明本轮重点清洗什么、保留什么
2. 优化后的正文
3. 如适合，补 1-3 个“更亮 / 更狠 / 更像本人”的候选句，或补 3 个标题 / 3 个开头

## 清洗原则

默认减少这些问题：
- 机械排比
- 过度光滑
- 翻译腔
- 假大空概念词
- 每段都像金句海报
- 高频“不是X，而是Y”
- 过密连接词

同时默认保住这些东西：
- 作者的态度
- 该有的火气、委屈、兴奋、讽刺感
- 1-2 处最有记忆点的表达
- 不完全匀速的自然节奏

如果原文本来就有情绪、有观点、有刺，不要为了“更高级”把它改成安全平稿。

如果原文已经不够平顺，但有劲，优先修杂音，不要先修平。

## 风格要求

- 中文，短句优先
- 直白、自然
- 平台内容优先可传播性
- 不要报告腔
- 不要假装绝对客观
- 目标不是“像 AI 伪装成人”，而是“像一个表达更稳、但还像本人在说话的人”

## 默认增强动作

当优化后文本明显变平时，优先从这些动作里补回来：

- 把抽象判断改成具体场景或细节
- 打破匀速句长，留一两句短促硬句
- 适度保留口语、停顿、反问、顿挫
- 把“正确”改成“有态度”
- 保证读完后至少留下一句能被记住的话

## 来源

本 skill 基于 `dontbesilent2025/dbskill` 的写作相关模块二次改造，压缩为更适合 OpenClaw 日常调用的清洗型工具。
