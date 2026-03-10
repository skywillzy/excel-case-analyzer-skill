# excel-case-analyzer-skill
markdown
# 📊 Excel案件分析工具 - OpenClaw Skill

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blue)](https://openclaw.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

这是一个专为电商平台法务人员设计的OpenClaw技能。它能自动读取桌面Excel文件中的案件描述，基于关键词库进行智能分类，并生成统计报告。

## ✨ 功能

- 自动读取桌面Excel（默认：`月度案件统计.xlsx`）
- 支持8大类案件分类（知识产权、虚假宣传、售后纠纷等）
- 自动标注"问题类型"列
- 生成案件类型分布统计
- 完全可配置的文件名、列名、关键词库

## 🔧 安装

### 通过ClawHub安装（推荐）

```bash
clawhub install excel-case-analyzer
