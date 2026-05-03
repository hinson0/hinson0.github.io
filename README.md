## 个人简历

<table>
  <tr>
    <td>
      <b>姓名：</b> 杨志兵 <b> 性别：</b> 男 
      <b>学历：</b> 本科 <br />
      <b>Phone：</b> 13907941239 <b>E-mail：</b> 356745844@qq.com <br>
      <b>github: </b> https://github.com/hinson0 <br>
      <b>github.io: </b> https://hinson0.github.io 
    </td>
    <td width="120">
      <img src="yzb.jpeg" width="100" />
    </td>
  </tr>
</table>

---

## 个人评价

- Agent相关技能扎实:Prompt Engineering/Context Engineering/Harness Engineering,以及熟练使用LangGraph Agent开发框架.
- 15 年软件开发经验，历经 PHP 后端、全栈开发到 AI 应用的技术演进，先后在完美世界、小米、阿里等公司参与大型项目开发。具备独立从 0 到 1构建产品的能力，擅长将 AI 能力融入产品设计，熟练运用 AI 辅助(cursor/trae/claude code/open code)开发工具提升工程效率。有创业经历，对产品运营和商业闭环有实际认知。

---

## 专业技能

**Agent 开发**

- **Prompt Engineering**：熟练运用 CoT / Persona / Few-shot / ReAct 等提示工程技巧，解决 问什么 / 怎么问的工程问题；熟悉结构化输出（JSON Schema / Structured Output）在 Agent 决策链路中的落地
- **Context Engineering**：熟悉 RAG、Function Calling (Tool Use)、Semantic Compression、History Pruning、Memory（短期 + 长期）等上下文工程技巧，针对性解决 LLM 会忘记 与 知识滞后 的工程问题；熟悉 Prompt Cache 提升缓存命中率、降低 Token 成本
- **Harness Engineering**：理解 Agent 工程的三大核心约束——稳健性、成本、安全性；持续迭代关键能力建设：Automated Eval（含 LLM-as-Judge）、Guardrails（输入 / 输出过滤）、Tracing 与实验跟踪
- **Agent 架构范式**：熟悉 Single-Agent ReAct 循环、Plan-and-Execute、Multi-Agent 协同（Supervisor / Hierarchical）等典型架构
- **开发框架**：熟练使用 LangGraph 构建有状态 Agent（StateGraph / Checkpointer / Human-in-the-Loop），落地多轮对话意图识别、状态记忆、对话管理等场景；了解 DeepAgents、Claude Agent SDK；熟悉 MCP（Model Context Protocol）将外部工具与数据源接入 Agent 系统

**AI Coding 驱动开发（Claude Code CLI）**

- 自研 smart-claude-code-plugins 插件
  - 实现自动化 commit/push/PR 与版本管理、statusline 部署、会话日志、特殊文件保护；
- Claude Code 深度使用者（Max 订阅，当前主力）
  - 平均一周token的使用量在5.3亿~6.6亿token
  - 最高5个worktree并行开发,通过pr merge+code-review(官方skill)快速迭代.
- 熟悉 claude-code-official 官方大部分 skill，熟练运用 Superpowers、Everything Claude Code (ECC)、GSD 等主流社区工作流插件
- 熟练掌握 Agent 模式完整开发流程：
  - 持续迭代 CLAUDE.md（AGENTS.md），熟练编写 skill / subagent / hook / command 及插件开发与分发
  - 全链路工作流：brainstorming → writing-plans → executing-plans，编码前完成需求澄清、方案设计与 spec 评审
  - TDD 驱动 + 质量闭环：先写测试再写实现，code-review 与 verification-before-completion 验证后提交
  - 并行开发：tmux + git worktree 隔离分支 + dispatching-parallel-agents 推进独立任务.

**后端开发**

- 熟练掌握 Python，熟悉 async/await 底层机制、GIL 与异步 I/O、generator/coroutine、内存泄漏跟踪、type/metaclass等
- 熟练掌握 FastAPI，熟悉 RESTful API 设计、SQLAlchemy ORM、Alembic 数据库迁移
- 熟悉 PostgreSQL，掌握索引优化、数据建模；熟练编写 SQL
- 有 PHP（完美世界 / 小米 / 天猫）与 Node.js（天猫）后端开发经验，熟悉 MVC 架构与大规模服务设计

**DevOps & 工程化**

- 熟练使用 Docker / Docker Compose 容器化部署；熟悉 GitHub Actions CI/CD，有阿里云 ECS、AWS EC2 运维经验
- 熟练使用 Linux 与 Shell 编程，掌握 vim、pnpm Monorepo、justfile 等工程化工具

**前端开发**

- 了解 React Native (Expo) / TypeScript / React 19，具备从零构建跨平台移动应用的能力
- 熟悉 expo-router、Zustand、React Query、expo-sqlite 等 Expo 生态技术栈
- 熟悉 Web 前端（HTML / CSS / JavaScript），有 Next.js 项目开发经验

---

## 工作经历

**StoryverseAI（海外）| 2025/04 - 至今**

- StoryverseAI — 面向海外市场的 AI 多模态内容生产产品（从 0 到 1 构建 MVP，历时 19 天）
- CoCo AI 记账 — 多模态智能记账 App（从 0 到 1 构建 MVP，历时 15 天）

**赣玛公司 | 2020/05 - 2025/04**

- 独立负责赣玛公司企业客服机器人从 0 到 1 建设，基于LangGraph 接入 ERP，实现多轮对话意图识别、状态记忆、对话管理；
- 对接江西省级司法行政系统的 ERP 开发，覆盖全省 14 个下属机构部署落地。（Python + PostgreSQL）

**自主创业 | 2017/03 - 2020/05**

- 创办 PHP/Web 技术培训班，独立完成课程体系设计与教学
- 创办线下果吧，独立完成选址、装修、进货、运营全流程；运用微信公众号、社群等渠道进行线上推广运营

**阿里巴巴杭州天猫技术有限公司 | 2014/10 - 2016/12**

- 参与天猫活动平台「斑马」功能开发与活动联调（Nodejs）

**小米科技（北京）有限公司 | 2012/04 - 2014/09**

- 负责仓储物流模块开发（PHP+MySQL）

**完美世界（北京）网络技术有限公司 | 2011/02 - 2012/04**

- 参与纵横微博、178 微博、173-Webmail 玩家口袋等产品开发（PHP+MySQL）

**抚州市某市级机关信息通信部门 | 2008/07 - 2010/09**

- 基于 PHPCMS 进行政务网站二次开发与建设（PHP + MySQL）

---

## 项目经历（近期）

### CoCo AI 记账 — 多模态智能记账 App（个人项目，全程基于Claude Code进行AI Coding）

- 官网: https://cocoai.chat
- github: https://github.com/hinson0/coco

**阶段：** 从 0 到 1 构建，历时 15 天开发 MVP 版本

**技术栈：** React Native (Expo 55) · TypeScript · FastAPI · PostgreSQL · Qwen LLM · 腾讯云 ASR/OCR · pnpm Monorepo

**项目描述：** 以 AI 对话为核心交互的移动端记账应用，将语音、拍照、文字三种输入方式统一在聊天界面中，用户无需手动填写表单即可完成记账。

**前端（React Native / Expo 55）：**

- 基于 expo-router 构建聊天式记账界面，集成语音录制（expo-audio）、相机拍照（expo-camera）和文字输入三种交互方式，统一通过对话流完成记账
- 使用 expo-sqlite（WAL 模式）构建本地离线存储层，持久化交易、分类、预算、聊天记录等数据，离线时支持数据查看与编辑
- 采用 React Query 作为数据访问层封装本地 CRUD 操作，实现即时 UI 响应；使用 Zustand 管理全局状态
- 实现收支统计模块，包含月报/周报、分类饼图（react-native-gifted-charts）、趋势折线图，支持按时间范围导出 CSV
- 实现分类预算管理功能，支持按类别设置预算上限与超支提醒

**后端（FastAPI / Python）：**

- 基于 FastAPI 设计统一的 /chat 接口，接收文字/语音输入，通过 Qwen 大模型实现三级意图分类（记账 / 查询 / 闲聊），根据意图路由到不同处理链
- 集成腾讯云 ASR 实现语音转文字、腾讯云 OCR 实现票据识别，识别结果经 Qwen 提取结构化账单字段（金额、分类、备注、时间）
- 实现自然语言查账功能，通过 Qwen text-to-SQL 将用户问题转换为 SQL 查询，添加安全校验防止 SQL 注入，并将查询结果以自然语言摘要返回
- 使用 SQLAlchemy ORM + Alembic 管理数据模型与数据库迁移，实现 JWT 认证体系；通过 Docker Compose 编排 PostgreSQL 与后端服务

**DevOps：**

- **独立完成生产环境全链路落地**：域名注册 → ICP 备案 → 腾讯云 CVM 购置 → Docker 容器化部署 → SSL 证书签发与 HTTPS 配置 → OCR / ASR / SMS 云服务开通 → Qwen 大模型 API 接入，覆盖从 0 到 1 的云端部署与合规上线全流程

---

### StoryverseAI — 海外 AI 多模态内容生产产品

**阶段：** 从 0 到 1 构建 MVP，历时 19 天 | 主要负责前端页面 + 后端 API + DevOps

**技术栈：** Next.js · FastAPI · PostgreSQL · Redis · GPT · Google Nano-Banana · Sora · FFmpeg · Docker · GitHub Actions

**前端（Web）：**

- 开发 8 个核心页面，覆盖从故事文本到多媒体成片的完整链路：首页、Chatbot
  文本编写页、角色设定页、分集文本页、资产管理页、关键帧页、分镜片段页、最终合成成片页
- 各页面支持完整 CRUD 操作，Chatbot 页面支持基于对话或现有文本进行交互式编辑

**后端（FastAPI）：**

- 基于 FastAPI 搭建 RESTful API 服务，实现用户鉴权（OAuth 2.1）、项目管理、文件上传、图片存储等基础模块
- 设计并实现 AI 多模态内容生产核心流水线：文本编写（Chatbot）→ LLM 提炼角色设定与分集内容（GPT）→ 角色图像生成（Nano-Banana）→ 场景/道具/背景资产生成 →
  关键帧九宫格生成 → 分镜片段生成（Sora）→ FFmpeg 合成最终成片（含音频、字幕）
- 对接多个 AI 模型 API，协调异步任务流转，处理多阶段依赖关系

**DevOps：**

- **混合架构选型**：自建云服务器（阿里云国际站 ECS，后迁移至 AWS EC2）+ Supabase BaaS（PostgreSQL / Edge Functions / Auth / Storage），在基础设施可控性与开发交付效率之间取得平衡
- 基于 Docker Compose 容器化 PostgreSQL、Redis 等服务，通过 systemctl 托管 compose 进程实现开机自启与崩溃自恢复，落地结构化日志追踪
- 基于 GitHub Actions 搭建 CI/CD 流水线实现推送即部署，并主导从阿里云 ECS 到 AWS EC2 的跨云迁移

## 教育背景

- 北京康盛创想培训中心 | PHP 开发培训 | 2010/09 - 2010/12
- 桂林电子科技大学 | 信息与通信学院 · 电子信息工程 · 本科 · 学士 | 2004/09 - 2008/07
- 抚州一中 | 高中 | 2001/09 - 2004/07

---

## 兴趣爱好

- 王者荣耀，Dota，长跑，中国象棋，三阶魔方。
