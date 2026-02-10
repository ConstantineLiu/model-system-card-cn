# AI 模型系统卡 中文翻译

Claude Opus 4.6 和 GPT-5-3 Codex 的 System Card 中文全文翻译。

原文都是英文 PDF，目前网上没找到中文版，就自己翻了。

> **Disclaimer:** Translated by AI (Claude Opus 4.6). Not human-reviewed.

## 内容

| 模型 | 原文页数 | 翻译字数 | 图片 |
| ---- | ------- | ------- | ---- |
| [Claude Opus 4.6](./claude-opus-4.6/) | 212 页 | ~2800 行 | 90 张 |
| [GPT-5-3 Codex](./gpt-5-3-codex/) | 31 页 | ~600 行 | 9 张 |

每个文件夹里有：中文翻译（Markdown）、原版 PDF、文中图片。

懒得看全文的可以先看 **[速览：两篇报告的核心看点](./highlights.md)**，附原文行号引用。

## 翻译说明

用 Claude Opus 4.6（通过 Claude Code CLI 调用子 Agent）翻的。顺便测试了一下这个模型的长程工作能力，结果还不错。两篇同时开跑：

- Claude 那篇 212 页，跑了大概 **56 分钟**，全程一个 Agent 没断
- GPT 那篇 31 页，大概 **10 分钟**搞定

流程：分批读 PDF（每次 20 页）→ 翻译 → 写入 Markdown，图片用 PyMuPDF 提取后插入对应位置。

翻译质量还行，专业术语保留英文，上下文连贯。不过机翻终究是机翻，肯定有不完美的地方。发现问题欢迎提 issue。

## 原文来源

- Claude Opus 4.6 System Card - Anthropic（2026 年 2 月）
- GPT-5-3 Codex System Card - OpenAI（2026 年 2 月）
