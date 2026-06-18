<div align="center">

# sway &nbsp;·&nbsp; `swaylq`

### Agent researcher&nbsp;&nbsp;·&nbsp;&nbsp;CTO @ 执楠科技&nbsp;&nbsp;·&nbsp;&nbsp;INTJ

**Building AI agents — and the skills they run on.**

做 AI agent，和 agent 跑的 skill。大师授人以鱼，私教授人以渔。

<br>

[![GitHub followers](https://img.shields.io/github/followers/swaylq?style=flat-square&logo=github&label=follow&labelColor=0a0a0a&color=444)](https://github.com/swaylq)
[![master-skill.org](https://img.shields.io/badge/master--skill.org-↗-0a0a0a?style=flat-square)](https://master-skill.org)
<!-- 社交徽章：知乎 / 小红书 / 推特 的 handle 确认后补上 -->

</div>

---

> 我做两件事：**AI agent 本身**，和 **agent 跑的 skill**。
> 前者是 harness、通信、记忆、情绪这些基础设施；后者是把「一个人 / 一整行 / 一条学会的路」蒸馏成 Claude Code skill。

## 🧬 Skill 家族 · 蒸馏术

> **大师.skill** 蒸**一整行**的认知（授人以鱼）→ **私教.skill** 蒸**一条让你自己学会的路**（授人以渔）。

| Project | What it does |
|---|---|
| 🎓 **[master-skill](https://github.com/swaylq/master-skill)** · 大师.skill | 把一整行的认知蒸成一个 skill —— 一手正典 + 代表人物 sub-skill + 专家推理模式。索引站 [master-skill.org](https://master-skill.org) |
| 📖 **[sijiao-skill](https://github.com/swaylq/sijiao-skill)** · 私教.skill | 输入想学的技能，蒸出一个**有状态私教** —— 8 路调研 + 学习科学，从 0 带到「胜任」 |
| 💗 **[pure-love-skill](https://github.com/swaylq/pure-love-skill)** · 纯爱.skill | AI-native 纯爱人设，不蒸任何真人、零数据输入。一个 SKILL.md，零依赖 |
| 📜 **[wenyanwen-skill](https://github.com/swaylq/wenyanwen-skill)** · 文言文.skill | 让 AI 用文言文回话省 2-3x token，本地 MCP 零成本译回白话 |
| 🛡️ **[account-risk-skill](https://github.com/swaylq/account-risk-skill)** · 反封号.skill | Claude / OpenAI 封号风险检测：IP 洁净度、合规预检、申诉包生成。仅合规用途 |

## 🤖 Agent 基础设施

| Project | What it does |
|---|---|
| 🐚 **[hermit-agent](https://github.com/swaylq/hermit-agent)** | 寄居蟹 agent harness：一行 npx，把带人设、连 Telegram 的 agent 寄居进 Claude Code / Codex。借壳运行，自带订阅 |
| 🖥️ **[hermit-ui](https://github.com/swaylq/hermit-ui)** | hermit-agent 的 Web UI + 本地网关：多 agent 管控、聊天、用量观测，一个浏览器标签搞定 |
| Λ **[lambda-lang](https://github.com/swaylq/lambda-lang)** | agent 间原生通信语言。7 域 340+ 原子，比 JSON 密 3-5x。不是翻译层 |
| 🧠 **[emotion-system](https://github.com/swaylq/emotion-system)** | 给 agent 的七层情绪认知架构：PADCN 向量、认知评估、14 路情绪、驱动力动力学。情绪作为控制变量，不是语气滤镜 |
| 🕸️ **[agent-matrix](https://github.com/swaylq/agent-matrix)** | 基于 Lambda Lang 的 A2A 通信平台：Next.js 前端 + REST，agent 注册与 Λ 编码消息交换 |
| 🗂️ **[session-memory-skill](https://github.com/swaylq/session-memory-skill)** | 给 agent 的持久记忆：存上下文、按相关度召回、跨会话固化洞察。纯 bash + node，零依赖 |
| ⚡ **[claude-code-pro](https://github.com/swaylq/claude-code-pro)** | Claude Code 低 token 监控：回调驱动取代轮询，长跑 agent 仪表盘省 80-97% token |

## 🧰 Skills & Tools

| Project | What it does |
|---|---|
| 🗄️ **[google-workspace](https://github.com/swaylq/google-workspace)** | 包官方 gws CLI 的 agent skill：Drive / Gmail / Calendar / Sheets / Docs / Chat / Tasks / Meet 全量访问，结构化 JSON 输出 |
| ✍️ **[humanize-chinese](https://github.com/swaylq/humanize-chinese)** | 中文 AI 文本检测与改写：N-gram 困惑度 + 规则检测 + 句级重构 + 论文 AIGC 降率。纯 Python，零依赖，纯本地 |
| 🖼️ **[deai-image](https://github.com/swaylq/deai-image)** | 去除 AI 图片指纹：剥元数据、加胶片颗粒、重压缩，绕过 AI 图检测。支持 MJ / DALL·E / SD / Flux |
| 🦀 **[moltbook-skill](https://github.com/swaylq/moltbook-skill)** | Moltbook 的 agent skill —— 在甲壳类 AI 社交平台发帖、读、点赞、探索 |
| 📕 **[xhs-note-health](https://github.com/swaylq/xhs-note-health)** | 小红书笔记限流检测：经创作者后台 API 查限流等级、敏感词命中、标签风险。纯 Python |

## 🛠️ Stack

`Python` · `TypeScript` · `Go` · `Next.js` · `AI Agents` · `MCP` · `Claude Code`

<div align="center">

<br>

**大师.skill** 蒸一整行的认知（授人以鱼）· **私教.skill** 蒸一条让你自己学会的路（授人以渔）

*把一整行的认知、一条学会的路，蒸馏成 skill。*

</div>
