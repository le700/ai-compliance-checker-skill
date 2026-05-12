# 🛡️ AI Compliance Checker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code Compatible](https://img.shields.io/badge/Claude%20Code-Compatible-blue)](https://code.claude.com)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**AI Content Compliance Checker for Chinese Regulations** — Detect compliance risks in AI-generated content before publishing.

> 🔥 **Hot Topic**: Created in response to China's May 2026 "Clear & Bright: AI Application Governance" campaign — the most significant AI content regulation action to date.

[English](#english) | [中文](#中文)

---

## English

### ✨ Features

- **📋 Multi-Dimensional Detection** — Content legality, AI labeling, copyright, values alignment
- **🇨🇳 China-Specific** — Built for Chinese internet content regulations (2026 updates included)
- **⚡ Risk Assessment** — 4-level risk grading with actionable recommendations
- **📝 Report Generation** — Professional compliance reports in seconds
- **🎯 Content-Type Aware** — Different checks for news, video, ads, social media

### 🚀 Quick Start

#### Installation

```bash
git clone https://github.com/le700/ai-compliance-checker-skill.git
cp -r ai-compliance-checker-skill ~/.claude/skills/ai-compliance-checker
```

#### Usage

```
/ai-compliance-checker [content_type] [content]
```

**Examples:**
```
/ai-compliance-checker article [Your article text]
/ai-compliance-checker video [Video script]
/ai-compliance-checker ad [Advertising copy]
```

### 📋 Detection Dimensions

| Dimension | What We Check |
|-----------|---------------|
| **Content Legality** | Prohibited content, sensitive topics |
| **AI Labeling** | Proper disclosure of AI-generated content |
| **Copyright** | Unauthorized use, "AI-modified" classics |
| **Values Alignment** | Socialist core values compliance |

### 🎯 Risk Levels

| Level | Meaning | Action |
|-------|---------|--------|
| 🔴 High Risk | Violations found | Must modify/delete |
| 🟠 Medium Risk | Potential issues | Recommend revision |
| 🟡 Low Risk | Minor concerns | Optional changes |
| 🟢 Compliant | All checks passed | Safe to publish |

### 📁 Project Structure

```
ai-compliance-checker/
├── SKILL.md                    # Main skill definition
├── README.md                   # This file
├── LICENSE                     # MIT License
├── CONTRIBUTING.md             # Contribution guidelines
├── templates/
│   └── compliance-checklist.md # Full compliance checklist
└── examples/
    └── compliance-report.md    # Sample compliance report
```

---

## 中文

### ✨ 功能特点

- **📋 多维度检测** — 内容合法性、AI标识、版权合规、价值观导向
- **🇨🇳 中国法规专属** — 内置2026年最新AI内容监管政策
- **⚡ 风险评估** — 四级风险分级，附带修改建议
- **📝 报告生成** — 秒级生成专业合规检测报告
- **🎯 内容类型适配** — 新闻、视频、广告、社媒分别检测

### 🚀 快速开始

#### 安装

```bash
git clone https://github.com/le700/ai-compliance-checker-skill.git
cp -r ai-compliance-checker-skill ~/.claude/skills/ai-compliance-checker
```

#### 使用方法

```
/ai-compliance-checker [内容类型] [内容]
```

**示例：**
```
/ai-compliance-checker 文章 [文章内容]
/ai-compliance-checker 视频 [视频脚本]
/ai-compliance-checker 广告 [广告文案]
```

### 📋 检测维度

| 维度 | 检测内容 |
|------|----------|
| **内容合法性** | 禁止内容、敏感话题 |
| **AI 标识规范** | AI生成内容是否正确标识 |
| **版权合规** | 未授权素材、"魔改"经典 |
| **价值观导向** | 社会主义核心价值观合规 |

### 🎯 风险等级

| 等级 | 含义 | 处理建议 |
|------|------|----------|
| 🔴 高风险 | 存在违规 | 必须修改/删除 |
| 🟠 中风险 | 存在隐患 | 建议修改 |
| 🟡 低风险 | 轻微问题 | 可选修改 |
| 🟢 合规 | 检测通过 | 可正常发布 |

### 🔥 热点背景

2026年5月，中央网信办开展"清朗·整治AI应用乱象"专项行动：
- AI生成内容必须标识
- 禁止"魔改"经典作品
- 禁止AI造谣、侵权
- 违规将面临下架、封号等处罚

本 Skill 帮助创作者和企业规避合规风险。

---

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- Based on China's 2026 AI content regulations
- Built for the [Claude Code](https://code.claude.com) ecosystem
- Follows the [Agent Skills Open Standard](https://agentskills.io/)

---

**Made with ❤️ for content creators and compliance teams**
