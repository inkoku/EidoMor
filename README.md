# EidoMor — AI 驱动的产品设计引擎<br><sub>AI-Powered Product Design Engine</sub>


<p align="center">
  <strong>从一句话、一句故事、一份市场分析、从需求到高保真产品设计，一键直达</strong><br>
  <em>From a single sentence, a story, or a market analysis, straight from requirements to high-fidelity product design — all with one click</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-4.0-blue" alt="Version">
  <img src="https://img.shields.io/badge/python-3.13-blue" alt="Python">
  <img src="https://img.shields.io/badge/electron-latest-brightgreen" alt="Electron">
  <img src="https://img.shields.io/badge/react-18-61dafb" alt="React">
  <img src="https://img.shields.io/badge/license-Apache2.0-green" alt="License">
</p>

---

## 🎯 项目简介 · Overview

**EidoMor** 是一个 AI 驱动的产品设计系统，覆盖从需求分析到 PRD 交付的完整生命周期。只需输入一句话、一张截图、或一份 Excel，系统自动调度 30+ 个专业 AI Agent 协作完成工作。
多 Agent 产品设计系统 —— 从市场分析、需求、原型、PRD，到交付，Multi-Agent Serial Product Design System — From Requirements to Prototype, From PRD to Delivery

**核心理念**：让产品经理和设计师把精力放在创意和决策上，把繁重的文档、原型、校验工作交给 AI。

---

**EidoMor** is an AI-driven product design system that covers the full lifecycle from requirements analysis to PRD delivery. Just input a sentence, a screenshot, or an Excel file — the system automatically orchestrates 30+ specialized AI Agents to collaborate and deliver results.

**Core Philosophy**: Let PMs and designers focus on creativity and decisions. Leave the tedious documentation, prototyping, and validation to AI.
<img width="1920" height="1020" alt="en-01" src="https://github.com/user-attachments/assets/1b30bbe9-3edf-466c-b488-56e5728ec7ef" />
<img width="1920" height="1020" alt="home" src="https://github.com/user-attachments/assets/16cf57d9-c128-4e6f-9aa6-7216d49307ab" />
<img width="1920" height="1020" alt="en-1" src="https://github.com/user-attachments/assets/4f499904-d646-45c2-a98f-cfd6bdf55c03" />
<img width="1920" height="1020" alt="yitu" src="https://github.com/user-attachments/assets/38351370-6ff6-4bf5-9543-88afe89b3075" />
<img width="1920" height="1020" alt="html" src="https://github.com/user-attachments/assets/951de099-c547-402b-9c79-783624d318a1" />

---

## ✨ 核心亮点 · Highlights

### 🚀 极速启动 · Lightning Fast
| 中文 | English |
|------|---------|
| 上传 Excel 功能清单 → 自动生成功能文档 | Upload Excel → auto-generate feature specs |
| 粘贴产品截图 → 自动转换为交互原型 | Paste screenshot → auto-convert to interactive prototype |
| 一句话模糊描述 → AI 自动补全流程节点 | Vague description → AI auto-completes workflow nodes |

### 🧠 智能调度 · Intelligent Orchestration
| 中文 | English |
|------|---------|
| 30+ Agent 按 DAG 依赖图并行/串行调度 | 30+ Agents scheduled by DAG — parallel & serial |
| 意图识别自动路由到最佳工作流 | Intent recognition auto-routes to optimal workflow |
| 基因进化引擎持续优化模型选择 | Genetic evolution engine continuously optimizes model selection |

### 🎨 所见即所得 · WYSIWYG
| 中文 | English |
|------|---------|
| 内置 GrapesJS 可视化原型编辑器 | Built-in GrapesJS visual prototype editor |
| 实时预览 + 一键校验 + 自动修复 | Live preview + one-click validation + auto-fix |
| 9 维度 58 项自动 UI 校验 | 9-category 58-rule automated UI validation |

### 🔌 多模态输入 · Multimodal Input
| 中文 | English |
|------|---------|
| 文字 / 图片 / Excel / Word / PDF / 语音 | Text / Images / Excel / Word / PDF / Voice |
| 文件夹批量扫描自动分类路由 | Batch folder scanning with auto-classification |

### 🌐 双语支持 · Bilingual
| 中文 | English |
|------|---------|
| 中文 / English 无缝切换 | Seamless 中文 ↔ English switching |
| ~600 条翻译全覆盖 | ~600 translation entries across all components |

### 📊 全链路监控 · End-to-End Monitoring
| 中文 | English |
|------|---------|
| Token 用量、耗时、成功率实时仪表板 | Real-time dashboard: tokens, latency, success rate |
| 每次交互完整记录，Markdown 人类可读 | Every interaction logged in human-readable Markdown |

---

## 🧬 基因进化引擎 · Genetic Evolution Engine

EidoMor 内置遗传算法引擎，持续从执行历史中学习。随使用次数增加，系统自动变得更准确、更快速、更省 Token。

EidoMor features a built-in genetic algorithm engine that continuously learns from execution history. The more you use it, the more accurate, faster, 和 more token-efficient it becomes.

```
每轮任务 → 采集性能基因 → 综合评分 → 选择最优模型 → 交叉变异 → 自动调优
Each task → collect performance genes → fitness scoring → selection → crossover → auto-tuning
```

---

## 📦 技术栈 · Tech Stack

| 层 Layer | 技术 Technology |
|----------|----------------|
| **桌面壳 Desktop Shell** | Electron |
| **前端 Frontend** | React 18 + TypeScript + Ant Design + GrapesJS + ReactFlow |
| **后端 Backend** | Python 3.13 + FastAPI + WebSocket + SSE |
| **AI 引擎 AI Engine** | OpenAI 兼容 API + 遗传算法 + 意图路由 |
| **国际化 i18n** | i18next + react-i18next |
| **打包 Packaging** | PyInstaller + Electron Builder |

---

## 🚀 快速开始 · Quick Start

### 环境要求 · Prerequisites

- Python 3.11+（推荐 3.13）
- Node.js 22+
- OpenAI 兼容 API Key（DeepSeek / OpenAI / 任意兼容服务）
- OpenAI-compatible API Key (DeepSeek / OpenAI / any compatible provider)

### 安装 · Installation

```bash
# 1. 克隆项目 · Clone
git clone https://github.com/your-org/eidomor.git
cd eidomor

# 2. 安装 Python 依赖 · Install Python deps
pip install -r requirements.txt

# 3. 安装前端依赖 · Install frontend deps
cd desktop && npm install

# 4. 配置 LLM · Configure LLM
# 编辑 config/llm_config.json，填入 API Key 和模型信息
# Edit config/llm_config.json with your API Key and model info
```

### 启动桌面应用 · Launch Desktop App

```bash
cd desktop
npm run dev
```

### CLI 命令行 · CLI Mode

```bash
# 全流程设计 · Full-flow design
python tools/cli.py start --project-dir ./data/my_project --type 1 --name "My Product"

# Excel → 功能清单 · Excel → Feature list
python tools/cli.py start --project-dir ./data/features --type 7 --name "Features"

# 截图 → 原型 · Screenshot → Prototype
python tools/cli.py start --project-dir ./data/proto --type 1 --name "Prototype"
```

---

## 🎬 典型工作流 · Typical Workflows

### 场景 1 · Scenario 1：截图 → 原型 · Screenshot → Prototype
```
粘贴产品截图 → AI 识别布局 → 自动生成 HTML 原型 → 可视化编辑器微调
Paste screenshot → AI recognizes layout → auto-generate HTML → tweak in visual editor
```

### 场景 2 · Scenario 2：Excel → 功能文档 · Excel → Feature Specs
```
上传功能清单 Excel → 解析表格数据 → 生成结构化功能说明 → 自动校验通过
Upload Excel → parse table data → generate structured specs → auto-validation passed
```

### 场景 3 · Scenario 3：全流程设计 · Full-flow Design
```
输入"做一个 B2C 电商后台" → 全流程执行 → 需求分析 → 业务建模 → 功能设计 → 原型 → PRD
Input "build a B2C e-commerce admin" → full pipeline → analysis → modeling → design → prototype → PRD
```

---

## 🌍 国际化 · Internationalization

EidoMor 支持中英文双语界面，通过设置页面一键切换。所有 22 个前端组件均已完成国际化覆盖。

EidoMor supports 中文 / English bilingual UI — switch with one click in Settings. All 22 frontend components are fully internationalized.

---

## 🤝 贡献指南 · Contributing

欢迎提交 Issue 和 PR！  |  Issues and PRs welcome!

- 代码通过 TypeScript 编译（`npx tsc --noEmit`）
- Python 语法正确（`python -m py_compile`）
- 新功能需要适配中英文双语 · New features must support both languages
- 遵循项目现有的代码风格 · Follow existing code style

---

## 📄 License

Apache2.0  License © 2026 EidoMor Team

```


