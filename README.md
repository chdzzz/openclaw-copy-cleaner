# copy-cleaner

中文名：清洗稿件工具

一个面向 OpenClaw 的中文稿件二轮优化 skill。

## 解决什么问题

当你已经有一段文案/稿件，但它：
- 有 AI 味
- 太光滑
- 标题弱
- 开头弱
- 平台不适配
- 像“差不多能发”，但还不够稳

这个 skill 负责做第二轮清洗，而不是从 0 到 1 硬写整篇。

## 能力范围

- 内容诊断
- AI 味检测
- 标题优化
- 开头钩子优化
- 平台内容调性清洗

适合：小红书 / 抖音 / 公众号 / X / 朋友圈 / 销售表达  
不适合：技术文档 / 法律文本 / 正式报告

## 目录

- `SKILL.md`：主入口
- `references/content-diagnosis.md`
- `references/ai-fingerprint.md`
- `references/title-patterns.md`
- `references/hook-patterns.md`

## 来源说明

本项目改造自 `dontbesilent2025/dbskill` 的写作相关模块，但不照搬整套商业诊断框架，只保留最适合日常写作增强的部分。