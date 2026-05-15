# Feng Codex MVP 学习计划：10 天闭环 + 4 周路线

## 0. 计划定位

这个计划不是“系统学习前端开发”的课程大纲，而是一个面向业务交付的训练计划。

目标不是让 Feng 先掌握完整工程体系，而是让他在 Codex 辅助下，逐步跑通一个最小交付闭环：

> 业务想法 → 拆成小网页工具 → Codex 生成/修改代码 → 本地运行 → GitHub commit → push → 部署上线 → 汇报 demo → 根据反馈修改

第一阶段只验证一件事：

> Feng 能不能借助 Codex 独立交付一个轻量前端 MVP。

先不进 WUI.AI 主仓库、先从轻量前端工具页开始。真实项目的难点不只是页面，还包括本地环境、路由、样式、依赖、构建和部署流程。更稳妥的顺序是：

1. 先从零做小站。
2. 再做独立 SEO 工具页。
3. 最后进入 WUI.AI 现有仓库做真实落地页。

---

## 1. 当前阶段能力目标

现阶段要从单点产品运营，转向借助 Codex 端到端完成小型 MVP：

- 能把业务想法拆成一个简单前端 MVP。
- 能用 Codex 搭 HTML / CSS / JavaScript 页面。
- 能本地运行、修改页面、部署上线。
- 能读懂基础目录结构和页面入口。
- 能修改文案、样式、表单、按钮、交互逻辑。
- 能做 prompt generator 这类轻量前端工具。
- 能使用 mock 数据或固定模板生成结果。
- 能接入简单第三方工具，例如 Tally / Typeform / Google Form / analytics。
- 能看懂基础 diff，并做简单 review。

---

## 2. SMART 总目标

### Specific：具体目标

在 4 周内，Feng 需要用 Codex 交付一组轻量前端网页工具，核心方向是 WUI.AI 相关的 AI 视频 prompt / workflow 工具页。

第一阶段只做前端，不接真实 API，不接数据库，不接登录，不进入 WUI.AI 主仓库。

### Measurable：可衡量标准

4 周结束时，必须交付：

1. 至少 1 个 GitHub repo
2. 至少 12 次有效 commit
3. 至少 2 个可访问的线上 URL
4. 至少 1 个完整可用的 Prompt Generator 工具页
5. 至少 1 个可复用的新模型热点页模板
6. 每个项目都有 README
7. 每个页面都包含输入区、输出区、复制按钮、CTA、基础 SEO 信息
8. 每天有进度汇报

### Achievable：可实现范围

第一阶段只使用：

- HTML
- CSS
- JavaScript
- Codex
- GitHub
- Vercel / Netlify / GitHub Pages 任意一个

暂时不强制使用：

- React
- Next.js
- API
- LLM 调用
- 数据库
- 登录系统
- WUI.AI 现有仓库

React / Next.js 只作为第 4 周之后的进阶选项，不作为第一阶段成功标准。

### Relevant：业务相关性

所有练习都围绕 WUI.AI 的潜在增长方向：

- AI 视频 prompt generator
- AI story video workflow
- AI children’s book video workflow
- AI science explainer video workflow
- 新模型发布后的 prompt generator / waitlist 页面

不做和业务无关的长期练习项目。Todo List 只允许作为 1 天内的技术热身，不作为主要交付。

### Time-bound：时间限制

计划周期为 4 周。每周一个主目标，每天至少一次 commit。

如果 7 天内无法完成第一个可部署页面，则暂停后续计划，先复盘最小闭环卡在哪里。

---

## 3. 第一阶段范围锁定

### 允许做

- 静态 landing page
- 前端 prompt generator
- 表单输入
- 下拉选择
- 模板化文本生成
- Copy 按钮
- CTA
- Tally / Typeform / Google Form 嵌入
- 简单 analytics 埋点
- 基础 SEO title / description
- README
- 部署上线

### 暂时不做

- 不接 LLM API
- 不做真实视频生成
- 不做用户登录
- 不做数据库
- 不做复杂后端
- 不进入 WUI.AI 主仓库
- 不做完整 SaaS
- 不做 YouTube 矩阵号
- 不做纯模型 wrapper

---

## 4. 业务方向

### 方向 A：AI 视频工作流模板 + SEO 工具页

把已有的 AI 视频工作流、提示词、脚本、分镜、生图 prompt、视频 prompt 产品化成轻量网页工具。

可做页面包括：

- AI Story Video Prompt Generator
- AI Children’s Book Video Generator
- AI Science Explainer Video Generator
- AI Historical Story Video Generator
- AI Faceless YouTube Script Generator

第一版只做小工具页：用户输入主题、时长、风格、平台，页面输出脚本、分镜、生图提示词、视频提示词。

目标是验证：是否有人访问、输入、复制结果、留下联系方式，或进一步试用 WUI.AI。

### 方向 B：新模型 Prompt Workflow 抢热点页

现阶段更合适的方式是提前准备一套“新模型发布后第一时间上线”的前端页面模板和 prompt generator 模板。

目标是：当某个热门 AI 视频模型发布新版本时，能在 24 小时内上线对应的 landing page / prompt generator / waitlist 页面，第一时间吃到搜索、社媒和开发者讨论的流量红利。

第一阶段先不接真实 API，而是准备：

1. 通用 landing page 模板：hero、模型介绍、使用步骤、prompt examples、FAQ、comparison、CTA、waitlist 表单
2. 通用 prompt generator 前端模板：主题输入、视频类型、比例、时长、风格、模板生成、复制结果
3. SEO 关键词模板：`{Model Name} API`、`{Model Name} prompt generator`、`{Model Name} video generator`、`{Model Name} examples`、`{Model Name} tutorial`、`{Model Name} alternatives`、`{Model Name} vs Veo / Kling / Runway`
4. 发布后 24 小时 SOP：快速替换模型名称、能力描述、示例 prompt、FAQ 和 SEO 信息；API 未开放时先上线 prompt generator + waitlist

这一阶段抢的是页面上线速度和流量入口，不是完整产品能力。

### 方向 C：WUI.AI 增长落地页

可做页面包括：

- AI Story Video Generator Landing Page
- Seedance Prompt Generator Landing Page
- AI Children’s Story Video Landing Page
- AI Faceless Video Workflow Landing Page

---

## 5. 第一个最小项目

## AI Story Video Prompt Generator

第一版不用 React，不用 Next.js，不接后端，不接 LLM API，不接数据库。只用最简单的 HTML / CSS / JavaScript。

页面需要有：

- 标题和一句介绍
- 输入框：用户输入视频主题
- 下拉选择：平台、时长、风格
- 一个 Generate 按钮
- 一个输出区：生成脚本结构、分镜、生图 prompt、视频 prompt
- 一个 Copy 按钮
- 一个 CTA，比如“Contact us / Join waitlist / Try WUI.AI”
- 一个 README，写清楚怎么本地运行、怎么部署、每个文件大概做什么

---

## 6. 10 天最小闭环计划

## 第 1 天：建项目和跑起来

- 创建 GitHub repo
- 让 Codex 生成最简单的 HTML / CSS / JS 三个文件
- 本地能打开页面
- commit 一次
- 发 repo 链接和截图

## 第 2 天：做基础交互

- 加输入框、下拉框、Generate 按钮
- 点击按钮后能生成固定模板结果
- commit 一次
- 发页面截图或本地 demo 说明

## 第 3 天：完善输出内容

- 输出分成几个模块：Script / Storyboard / Image Prompt / Video Prompt
- 加 Copy 按钮
- commit 一次
- 发 commit 链接和功能截图

## 第 4 天：做样式和移动端适配

- 页面看起来干净一点
- 手机上也能正常看
- 调整标题、按钮、卡片、间距
- commit 一次

## 第 5 天：部署上线

- 部署到 Vercel / Netlify / GitHub Pages 任意一个
- 发线上 URL
- README 写清楚如何运行和部署
- commit 一次

## 第 6 天：收集反馈并做第一轮修改

- 整理 2–3 个最重要的修改点
- 先改最影响使用的问题
- 再 commit
- 再发线上 URL

## 第 7 天：优化生成结果质量

- 调整生成模板，让 Script / Storyboard / Image Prompt / Video Prompt 更具体
- 根据不同平台、时长、风格输出不同内容
- 检查空输入、短输入、特殊主题时页面是否还能正常使用
- commit 一次
- 发功能截图和线上 URL

## 第 8 天：完善 README 和项目说明

- README 补充项目目标、功能列表、本地运行方式、部署方式
- 写清楚每个文件大概做什么
- 加一段未来可以接入 LLM API 的计划，但不用现在实现
- commit 一次
- 发 README 链接和线上 URL

## 第 9 天：做一次完整自测

- 从头测试一次：打开页面 → 输入主题 → 选择选项 → Generate → Copy
- 在手机尺寸或浏览器窄屏下检查布局
- 修复发现的小问题，比如按钮文案、间距、输出换行、复制失败提示
- commit 一次
- 发测试结果和线上 URL

## 第 10 天：总结和交付

- 整理这 10 天完成了什么
- 列出所有重要 commit 或最终 repo 链接
- 写清楚当前版本还缺什么、下一版可以做什么
- 发最终线上 URL、repo 链接和一张截图
- 准备进入第二个轻量 SEO 工具页

---

## 7. 4 周路线

## Week 1：跑通最小前端交付闭环

目标：完成一个最简单的前端项目，并部署上线。

项目：AI Story Video Generator Landing Page 静态版

页面必须包含：

1. Hero 标题
2. 一句话介绍
3. 3 个功能卖点
4. 一个 CTA 按钮
5. 一个 FAQ 区域
6. 基础 SEO title / description
7. README
8. 线上 URL

验收标准：

1. GitHub repo 链接
2. 线上 URL
3. 至少 4 次 commit
4. README
5. Feng 能说明页面入口文件、样式文件、文案位置、本地打开方式、部署方式

## Week 2：完成第一个业务相关 Prompt Generator

目标：完成一个可交互的 AI Story Video Prompt Generator。

用户可以输入或选择：

1. 视频主题
2. 视频类型
3. 视频时长
4. 视频风格
5. 发布平台

点击 Generate 后，页面输出：

1. Script outline
2. Storyboard outline
3. Image prompts
4. Video prompts

页面支持：

1. Copy 全部结果
2. Clear / Reset
3. CTA 表单或联系方式入口

验收标准：

1. 可访问线上 URL
2. 至少 4 次新增 commit
3. 用户输入后能生成结果
4. Copy 按钮可用
5. 页面移动端可用
6. README 更新
7. Feng 能说明输入读取、Generate 逻辑、输出模板、Copy 功能分别在哪里

## Week 3：复制成 3 个 SEO 工具页

目标：把 Week 2 的工具页复制为多个业务场景页面，验证模板化能力。

至少 3 个页面：

1. AI Story Video Prompt Generator
2. AI Children’s Book Video Generator
3. AI Science Explainer Video Generator

每个页面必须包含：

1. 独立标题
2. 独立 SEO description
3. 独立使用场景说明
4. 输入区
5. 输出区
6. Copy 按钮
7. CTA
8. 表单或联系方式收集入口

验收标准：

1. 至少 3 个可访问页面
2. 至少 3 个页面主题不同
3. 至少 4 次新增 commit
4. 每个页面的 prompt 模板不同
5. 每个页面都有基础 SEO 信息
6. Feng 能说明如何新增第 4 个页面

## Week 4：新模型热点页模板

目标：完成一个可快速替换内容的新模型发布热点页模板。

项目：New Model Prompt Generator Template

模板需要支持替换：

1. Model Name
2. Model capability description
3. Prompt examples
4. FAQ
5. SEO title
6. SEO description
7. Comparison section
8. Waitlist form

页面结构必须包含：

1. Hero
2. 模型能力介绍
3. 使用步骤
4. Prompt examples
5. Prompt generator
6. Comparison
7. FAQ
8. Waitlist CTA

验收标准：

1. 一个可访问的新模型热点页模板 URL
2. 至少 4 次新增 commit
3. 页面内容可以在 1 小时内替换成另一个模型主题
4. README 说明如何替换模型名称、FAQ、prompt examples、SEO 信息
5. Feng 能完成一次模拟替换，例如从 `{Model Name}` 替换成 `Seedance 2.0`

---

## 8. 工程学习切片

### 切片 1：静态页面

目标：能做出一个结构完整、视觉可接受的网页。

需要掌握：

- HTML 基础结构
- CSS 基础样式
- 页面布局
- 响应式适配
- 基础 SEO 标题和描述
- 部署到 Vercel / Netlify / GitHub Pages

验收标准：

- 页面能本地打开。
- 页面能部署上线。
- 能修改标题、文案、图片、按钮、版块顺序和样式。

### 切片 2：交互页面

目标：能做输入框、按钮、下拉选择、复制结果等基础交互。

需要掌握：

- JavaScript 基础
- DOM
- state
- event
- 表单输入
- 复制按钮
- 简单 loading 状态

验收标准：

- 用户输入内容后，页面能生成结果。
- 用户能复制结果。
- 能知道按钮逻辑在哪里。
- 能让 Codex 修改交互并自己验证。

### 切片 3：前端工具页 / SEO 页面组

目标：能把一个业务方向复制成多个前端工具页，用于 SEO 和用户验证。

需要掌握：

- 组件复用
- 页面模板化
- SEO metadata
- CTA
- 第三方表单嵌入
- analytics 基础埋点

验收标准：

- 至少上线 3 个前端工具页。
- 每个页面都有输入区、输出区、复制按钮、CTA 和基础 SEO。
- 能用同一套模板快速替换成不同主题页面。

---

## 9. 每日最小交付要求

Feng 每天至少完成一次以下闭环：

1. 修改代码或文案
2. 本地运行并检查页面
3. 查看改动文件
4. commit
5. push 到 GitHub
6. 向 Dennis 汇报

每日汇报格式：

```text
今天完成：
今天的 GitHub repo：
今天的 commit：
当前页面截图 / 线上 URL：
卡点：
明天计划：
```

如果当天卡住，也要汇报：

- 卡在哪一步
- 错误截图
- Codex 的报错信息
- 已经尝试了什么

卡住可以接受，不同步不可接受。

---

## 10. 每周 Review 标准

每周 Review 不看“学了多少”，只看交付证据。

### 必须提交

1. GitHub repo
2. 本周 commit 列表
3. 线上 URL
4. README
5. 页面截图
6. 本周卡点总结
7. 下周计划

### Review 问题

Dennis 可以只问以下问题：

1. 这个页面在哪里打开？
2. GitHub repo 在哪里？
3. 这一周有哪些 commit？
4. 你今天改了哪些文件？
5. 页面入口文件在哪里？
6. 样式在哪里改？
7. 按钮逻辑在哪里？
8. 如果我要改标题，你会改哪里？
9. 如果我要新增一个输入项，你会怎么让 Codex 改？
10. 如果部署失败，你怎么看日志？

---

## 11. 通过标准

4 周结束时，如果 Feng 达到以下标准，则进入第二阶段：

1. 能稳定每天 commit
2. 能独立创建 repo
3. 能用 Codex 修改页面
4. 能本地运行页面
5. 能部署上线
6. 能看懂基础文件结构
7. 能根据反馈修改页面
8. 能说明基础 diff
9. 能完成一个 prompt generator
10. 能复制出相似工具页

### 第二阶段可以学习

- React / Next.js
- API
- LLM 调用
- `.env`
- 数据库
- CRUD
- 登录
- 用户历史记录
- 后端错误处理
- 部署环境变量

---

## 12. 暂停 / 降级标准

如果出现以下情况，需要暂停大计划，只复盘最小闭环：

1. 连续 2 天没有 commit，也没有说明卡点
2. 7 天后没有任何可访问页面
3. 7 天后 GitHub 上没有有效代码
4. 只写文档，不交付页面
5. 无法说明自己改了哪些文件
6. 无法根据反馈完成小修改

暂停后，不继续 Week 2 / Week 3 / Week 4，而是回到最小任务：

> 48 小时内完成一个 HTML / CSS / JS 静态页面，commit 并部署。

---

## 13. 推荐给 Codex 的任务提示词

### 创建项目

```text
Create a simple static website project for an AI Story Video Prompt Generator. Use only HTML, CSS, and JavaScript. Create index.html, styles.css, app.js, and README.md. Keep the code beginner-friendly and explain the file structure in README.
```

### 增加交互

```text
Add a form where users can input a video topic and select platform, duration, and style. When users click Generate, create a structured output with script outline, storyboard outline, image prompts, and video prompts. Use only frontend JavaScript templates. Do not call any API.
```

### 增加复制按钮

```text
Add a Copy Result button that copies the generated output to the clipboard. Show a simple success message after copying.
```

### 检查改动

```text
Show me what files changed and summarize the diff in beginner-friendly language before committing.
```

### 提交代码

```text
Commit the current changes with a clear commit message and then push to GitHub.
```

### 部署说明

```text
Update README with step-by-step instructions for running this project locally and deploying it to GitHub Pages or Vercel.
```

---

## 14. 一句话版本

Feng 第一阶段不是要系统学习前端，而是要证明自己能用 Codex 完成这个闭环：

> 小需求 → 写出页面 → 本地跑通 → commit → push → 部署 → demo → 根据反馈修改

只要这个闭环能稳定跑起来，后面再学 React、Next.js、API、数据库和 WUI.AI 主项目。
