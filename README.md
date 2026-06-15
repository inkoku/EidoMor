# EidoMor
多 Agent 产品设计系统 —— 从市场分析、需求、原型、PRD，到交付，Multi-Agent Serial Product Design System — From Requirements to Prototype, From PRD to Delivery

EidoMor 是一个**多 Agent 产品设计系统**，覆盖产品设计全生命周期（Phase 0–7），通过 8 大核心服务统筹调度，支持中英文双语界面。

### 核心能力

- **产品设计专业流程**：需求清洗 → 业务建模 → 功能设计 → 原型生成 → PRD 生成 → 总结 → PRD 标注
- **多模态动态工作流**：多模态输入（文本/图片/文档/语音）→ 智能路由推荐
- **基因进化引擎**：遗传算法自动优化模型选择和校验规则
- **实时工作日志**：每次交互完整记录，Markdown 人类可读
- **Electron 桌面应用**：内置原型编辑器、流程编排、监控面板

## 项目结构
EidoMor/
├── services/                    # ⑧ 大核心服务层（外观包装）
│   ├── intent/                  # ① 意图识别服务
│   ├── orchestration/           # ② 编排与流程引擎
│   ├── context_cache/           # ③ 上下文与缓存服务
│   ├── validation/              # ④ 校验服务
│   ├── evolution/               # ⑤ 基因进化引擎
│   ├── monitor/                 # ⑥ 异步监控服务
│   ├── capabilities/            # ⑦ 能力注册服务
│   └── tools/                   # ⑧ 工具插件管理
├── engine/                      # 引擎层（调度/状态/校验/缓存/版本）
├── config/                      # 配置层（阶段/规则/意图路由/Token）
├── agents/                      # Agent 实现层
├── desktop/                     # Electron 桌面应用
│   ├── src/                     # React 前端 (22 组件)
│   │   ├── components/          # 页面组件
│   │   └── i18n/                # 国际化 (~600 条/语言)
│   ├── backend/                 # FastAPI 后端
│   │   └── api/                 # API 路由
│   └── electron/                # Electron 主进程
├── tools/                       # CLI 工具箱
├── templates/                   # Agent Prompt 模板

<img width="1920" height="1020" alt="home" src="https://github.com/user-attachments/assets/16cf57d9-c128-4e6f-9aa6-7216d49307ab" />
<img width="1920" height="1020" alt="yitu" src="https://github.com/user-attachments/assets/38351370-6ff6-4bf5-9543-88afe89b3075" />
<img width="1920" height="1020" alt="pro-1" src="https://github.com/user-attachments/assets/7234f699-a07b-4e5f-8144-344fb6d4b65b" />
<img width="1920" height="1020" alt="html" src="https://github.com/user-attachments/assets/951de099-c547-402b-9c79-783624d318a1" />
<img width="1920" height="1020" alt="en-4" src="https://github.com/user-attachments/assets/1c6d7a1e-14db-4326-8a97-dbee21f893e0" />
<img width="1920" height="1020" alt="en-3" src="https://github.com/user-attachments/assets/9efa6fe3-f5db-46ba-98fb-146c29a37383" />
<img width="1920" height="1020" alt="en-2" src="https://github.com/user-attachments/assets/d9ea52f5-bc0b-42bd-8b8c-75e00f319dae" />
<img width="1920" height="1020" alt="en-1" src="https://github.com/user-attachments/assets/4f499904-d646-45c2-a98f-cfd6bdf55c03" />
