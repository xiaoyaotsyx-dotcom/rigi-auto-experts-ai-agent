
<p align="center">
  <img src="https://placehold.co/600x150/ffffff/5b5fe7?text=AI+Automation+Expert+Builder&font=Montserrat" width="500">
</p>

<p align="center">
  <strong>You define the persona. We handle the browser. 3 minutes to an AI expert that actually works.</strong><br>
  <strong>你定人设，我们搞定浏览器。3 分钟造一个真的能干活的 AI 专家。</strong>
</p>

<p align="center">
  <a href="https://github.com/xiaoyaotsyx-dotcom/expert-panel/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPLv3-blue"></a>
  <a href="#"><img src="https://img.shields.io/github/stars/xiaoyaotsyx-dotcom/expert-panel"></a>
</p>

---

## The Problem · 痛点

AI 助手很聪明，但**只能聊不能干**。你想让它帮你查房价、分析股票、审合同、筛简历——它说"我无法访问互联网"或者给你一段通用建议。

**That's because your AI has a brain but no hands. We give it hands.**
**因为你的 AI 有脑没手。我们给它装上手脚。**

---

## The Solution · 解决方案

**Expert Builder = 人设模板 + 浏览器操控引擎**

你只需要定义：
- 👤 **身份**：它是谁？（房产评估师 / 投研分析师 / HR 猎头...）
- 🧠 **知识**：它懂什么？（行业规则、专业术语、判断标准...）
- 🛡️ **边界**：它不能做什么？（安全边界声明）

**剩下的我们搞定：**
- ✅ 开浏览器查数据
- ✅ 填表单、传文件
- ✅ 抓取网页、提取结构化数据
- ✅ 在 X / 微博 / 知乎 / 头条 / 小红书发帖
- ✅ 截图、下载、整理

---

## Who Is This For? · 谁适合用？

| 你是什么角色 | 你可以造什么专家 | 典型场景 |
|------|------|------|
| 👔 投资人 | 投研分析师 | "这三只股票，拉数据→交叉验证→出对比研报" |
| ⚖️ 法务/律师 | 合同审查专家 | "审这份合同，标出所有风险条款" |
| 💼 HR/猎头 | 简历筛选专家 | "筛这 50 份简历，匹配 JD，打分排序" |
| 🌍 跨境卖家 | 选品顾问 | "查 Amazon 榜单 + 1688 供应链 → 选品建议" |
| 🏠 房产从业者 | 房产评估师 | "查这个小区挂牌价+成交价→估值报告" |
| 🎓 教师/培训师 | 学习教练 | "根据知识点出题→自动批改→个性化辅导" |
| 🔍 分析师 | 数据猎手 | "全网搜索 XX 行业→结构化提取→趋势报告" |
| 🕵️ 产品经理 | 竞品侦探 | "逆向分析 XX 产品的 AI 提示词架构" |

> **一句话：只要你的工作涉及"查信息→整理→出结论"，就能造一个专家替你干。**
> **If your work involves "search → organize → conclude" — you can build an expert for it.**

---

## How It Works · 原理

```
  👤 你定义的                             🤖 造出来的
  You define                             You get

  ┌────────────────┐                 ┌─────────────────────┐
  │ 身份：投研分析师  │                 │ "分析特斯拉"           │
  │ 性格：理性、数据驱动│    ───▶        │ → 自动开浏览器         │
  │ 擅长：三源交叉验证  │                 │ → 拉取财报+新闻+行情    │
  │ 边界：不推荐买卖   │                 │ → 交叉验证             │
  └────────────────┘                 │ → 输出 4 份研报        │
        ×                             └─────────────────────┘
  ┌────────────────┐
  │ 🔧 自动化引擎    │
  │ CDP 浏览器操控   │
  │ 搜索·填表·抓取   │
  │ 社媒发布·截图    │
  └────────────────┘
```

---

## What's Inside? · 包含什么？

### 🎁 Pre-built Experts · 预置专家（开箱即用）

| Expert · 专家 | Capability · 核心能力 | Folder · 目录 |
|------|------|------|
| 📈 **Investment Research · 投研分析师** | 三源数据→交叉验证→四份研报 / Multi-source → cross-validate → 4 reports | `investment-research/` |
| 🔒 **Security Audit · 安全审计师** | 扒前端源码→扫敏感信息→出审计报告 / Scrape source → scan secrets → audit report | `security-audit/` |
| 🕵️ **Competitive Analysis · 竞品分析师** | 逆向 AI 产品→提取提示词架构→分析工作流 / Reverse-engineer AI → extract prompts → analyze workflow | `competitive-analysis/` |

### 🎨 Build Your Own · 自己造专家

```bash
# 1. 复制模板
cp -r template/ my-expert/

# 2. 改四个文件：
#    SKILL.md      → 人设 + 专业能力
#    README.md     → 介绍 + 安全边界
#    命令模板.md    → 6-9 条用户可直接粘贴的命令
#    examples/     → 两个真实对话示例

# 3. 完成。你的专家自动获得：
#    ✅ 浏览器操控   ✅ 网页搜索   ✅ 表单填写   ✅ 社媒发布
```

> 💡 所有自动化能力从 `shared/` 继承——零额外配置。跟预置专家完全一样的底层引擎。
> 💡 All automation inherited from `shared/` — zero config. Same engine as pre-built experts.

---

## Quick Start · 快速开始

```bash
# 用预置专家
"加载 investment-research skill。分析特斯拉。"

# 造你自己的
"用专家模板创建一个房产评估专家，能查北京各小区房价。"
```

> 支持 Hermes Agent / Claude Code / Cursor。任何能跑 Python + CDP 的 AI 助手。

---

## Requirements · 环境要求

- AI assistant with Python execution + CDP browser control · 支持 Python + CDP 的 AI 助手
- Google Chrome (your own login) · Chrome 浏览器（你自己的登录态）

---

## License · 许可

| Use Case · 使用场景 | License · 许可 |
|------|---------|
| Personal, non-commercial · 个人非商业 | AGPLv3 ✅ Free · 免费 |
| Any company or commercial use · 任何企业/商用 | [Contact us · 联系我们](mailto:Walter.x@qq.com) |

---

## Contact · 联系

- 📕 RedNote · 小红书: [@瑞吉AI人民公社](https://www.xiaohongshu.com/user/profile/42084313799)
- 📧 Walter.x@qq.com

---

*Rigi AI Commons — Reject AI echo chambers. Democratize practical AI for everyone.*
*Rigi AI Commons — 拒绝 AI 小圈子自嗨，推动实用 AI 全面普惠。*
