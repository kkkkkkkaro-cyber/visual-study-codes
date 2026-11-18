---
name: "visual-study-codes"
description: "Turn any topic into a study visual, or tasks into a planner, when the user types one of 16 slash codes (/blueprint, /roadmap, /handwritten, /decision-matrix, /flowchart, /infographic, /canvas, /layers, /cycle, /diagram, /sketchnotes, /exploded-view, /tree, /timeline, /weekly-plan, /project-planner) followed by a topic."
---

# Visual Study Codes

When the user types `/code topic` (e.g. `/roadmap coffee from bean to cup`), draw the topic as a study visual in the matching layout.

用户输入 `/代码 主题`（例如 `/roadmap 咖啡从豆到杯`）时，用对应版式把主题画成一张用于学习的图。

## General rules / 通用规则

1. **Research first, then draw.** List 4–8 key facts or steps and make sure they are accurate; search to verify numbers, dates or anything that may have changed.
   **先查内容，再画图**：先列出主题的 4–8 个关键事实或步骤，确保准确；涉及具体数字、日期等会变化或不确定的信息时先搜索核实。
2. **How to render.** Prefer the in-chat visualizer (SVG/HTML); if it is not available, deliver a self-contained HTML file. Never just describe the layout in words.
   **出图方式**：优先用对话内可视化工具（SVG/HTML）直接画出；如果没有该工具，就写成一个独立 HTML 文件交付。不要只用文字描述版式。
3. **No photos.** Realistic photos can't be generated; use icons, emoji and simple geometric illustrations instead.
   **没有照片**：无法生成写实照片，用图标、emoji、简单几何插画代替。
4. **Language.** Text in the visual follows the user's language; keep titles short and each node's body ≤ 25 characters (Chinese) or ≤ 12 words (English).
   **语言**：图中文字跟随用户的语言；标题简短，每个节点正文 ≤ 25 字（中文）或 ≤ 12 词（英文）。
5. **Structure.** Every visual has a title, a one-line subtitle, the main layout, and an optional one-line footer summary.
   **结构**：每张图包含标题、副标题（一句话概括）、主体版式，必要时一行页脚小结。
6. **Planner codes** (/weekly-plan, /project-planner) hold the user's own schedule, not study facts: fill them with the user's tasks, dates and habits; leave blank cells for anything missing and never invent tasks. With no date given, /weekly-plan uses the current week.
   **计划类代码**（/weekly-plan、/project-planner）填的是用户自己的安排，不是知识点：用用户给的任务、日期、习惯填表；缺的内容留空白格供填写，不要编造任务。没给日期时 /weekly-plan 默认用本周。
7. If no topic is given, ask for one; if a topic is given without a code, suggest the 2–3 best-fitting codes.
   用户没给主题时，问一句主题是什么；只给主题没给代码时，推荐最合适的 2–3 个代码让用户选。

## The 16 codes / 16 个代码

| Code 代码 | Layout 版式 | Best for 适合 |
|---|---|---|
| /blueprint | Navy background, thin white lines; numbered parts, leader-line labels, dimension grid<br>深蓝底、白色细线的工程蓝图；部件编号 + 引线标注 + 尺寸感网格 | Systems, machines, structures<br>系统、机器、结构 |
| /roadmap | A winding road with 5–8 numbered stops, each with icon + title + one line<br>一条蜿蜒道路，沿途 5–8 个编号站点，每站图标 + 标题 + 一句说明 | Staged processes, learning paths<br>阶段性过程、学习路径 |
| /handwritten | Cream paper, handwriting font, underlines and arrows, yellow sticky notes with fun facts<br>米色纸底、手写体字体、带下划线和箭头、旁边贴黄色便签补充趣味知识 | Notes, revision outlines<br>笔记、复习提纲 |
| /decision-matrix | Table: columns = options, rows = criteria (1–10), cells colored green/yellow/orange/red, totals and a "winner" card<br>表格：列 = 选项，行 = 评价指标（1–10 分），按分数着色（绿/黄/橙/红），底部合计与“赢家”卡片 | Comparing options<br>多选项比较 |
| /flowchart | Top-down rounded nodes with diamond decision branches that can merge again<br>自上而下的圆角节点 + 菱形判断分支，分支后可再汇合 | Conditional processes<br>带条件的流程 |
| /infographic | Magazine-style long page: title banner, icon-left/text-right sections, a side stat per section<br>杂志式长图：大标题横幅，左图标/右文字的分段，每段配一个侧边小数据 | Topic overviews<br>主题概览 |
| /canvas | Business Model Canvas, nine blocks (partners, activities, value proposition, relationships, segments, resources, channels, costs, revenue) with colored sticky notes<br>商业模式画布九宫格（关键伙伴、关键活动、价值主张、客户关系、客户细分、关键资源、渠道、成本结构、收入来源），格内用彩色便利贴 | Business / project analysis<br>商业/项目分析 |
| /layers | Vertical cross-section, layers top to bottom, each labeled on the right with name + one line<br>物体纵向剖面，自上而下分层，每层右侧引线标注名称 + 一句说明 | Composition, layered systems<br>组成结构、分层系统 |
| /cycle | 4–8 stages in a ring, arrows end to end, topic in the center<br>环形排列的 4–8 个阶段，箭头首尾相连，中心写主题 | Cyclical processes<br>循环过程 |
| /diagram | Central concept with surrounding parts joined by labeled links<br>中心概念 + 周围组件，用带标签的连线表示关系 | Concept relations, system parts<br>概念关系、系统组成 |
| /sketchnotes | Visual notes: hand-drawn icons, speech bubbles, arrows, mixed font sizes, free layout<br>视觉笔记：手绘风小图标、气泡框、箭头、大小不一的字体，自由排布 | Lecture / book summaries<br>讲座/书籍总结 |
| /exploded-view | Parts spread along one axis, dashed assembly guides, numbered labels<br>部件沿一条轴线分开排列，虚线指示装配位置，每个部件有编号标注 | Taking apart products or structures<br>拆解产品或结构 |
| /tree | Root at top (or left), branching level by level, siblings aligned, optional leaf notes<br>根节点在上（或左），逐级分支，同级节点对齐，叶子节点可加小注释 | Classification, lineage, hierarchy<br>分类、谱系、层级 |
| /timeline | One horizontal or vertical axis; events in order with year + event + significance<br>一条横向或纵向时间轴，按时间顺序排列事件节点，节点写年份 + 事件 + 一句意义 | History, evolution<br>历史、演进 |
| /weekly-plan | Journal-style weekly page (portrait A4): left column Mon–Sun with date + items; right column Goals, Priorities, To do, Notes with checkboxes; habit tracker at the bottom (habits × 7 dots). Soft colors (cream, light pink, light green), sticker icons, highlighter accents<br>手帐风周计划页（竖版 A4 比例）：左栏周一至周日每天一格，写日期 + 当天事项；右栏依次是本周目标（Goals）、优先事项（Priorities）、待办清单（To do）、备忘（Notes），全部带勾选框；底部习惯打卡表（习惯 × 一至日七个圆点）。配色柔和（奶油、浅粉、浅绿），可加小贴纸式图标和荧光笔高亮 | Weekly schedule, habits<br>一周安排、习惯养成 |
| /project-planner | Project sheet (portrait, clean tables): project name, goal, deadline; ① milestones (no., milestone, progress bar, due, ✓); ② Gantt timeline (tasks × dates, done cells ticked, dependency arrows, diamond milestones); ③ task table (no., task, start, end, priority, ✓); ④ notes. Mostly grey-blue, handwriting font allowed for entries<br>项目规划表（竖版，简洁表格风）：顶部项目名、目标、截止日期；① 里程碑表（序号、里程碑、进度条、截止日、✓）；② 甘特图时间线（任务 × 日期格，已完成格打勾，依赖用折线箭头，里程碑用菱形）；③ 任务表（序号、任务、开始、结束、优先级、✓）；④ 备注。灰蓝单色为主，可用手写体填内容 | Project scheduling, tracking<br>项目排期、进度跟踪 |

## After drawing / 画完之后

In one or two sentences, point out the single most memorable takeaway, and suggest trying another code for a different angle on the same topic.

用一两句话点出这张图里最值得记住的一点，并提示用户可以换另一个代码看同一主题的其他角度。
