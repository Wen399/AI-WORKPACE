---
name: "ui-color-palette"
description: "Classifies UI visuals into color systems and generates palette names, tokens, and section guidance. Invoke when designing or reviewing UI color schemes."
---

# UI Color Palette

## 目标

当用户提供 UI 参考图、设计截图、页面风格描述，或要求“按配色命名、颜色分类、生成 UI 视觉规范”时，使用本 Skill 输出统一的配色体系、语义命名、使用场景和板块建议。

## 适用场景

- 用户上传 UI 页面截图，希望整理颜色分类。
- 用户要求根据现有视觉创建配色命名。
- 用户正在设计 App、网页、后台、课程平台、健康数据看板、卡片式页面。
- 用户希望生成 CSS 变量、设计 Token、主题变量或视觉规范。
- 用户要求评审某个页面的配色是否统一。

## 输出结构

优先按以下结构输出：

1. 视觉风格归类
2. 主色、背景色、卡片色、强调色、文字色分类
3. 每个颜色的语义名称、HEX 值、用途
4. 页面板块建议
5. CSS / Design Token 命名
6. 使用限制和搭配建议

## 命名原则

使用语义化命名，不只使用机械编号。

推荐格式：

`质感/情绪 + 功能角色`

## 默认配色体系

### 柔光新拟物

- 背景：`#F4F3EF`，Soft Porcelain
- 卡片：`#FFFFFF`，Cloud White
- 强调：`#FFC83D`，Honey Glow
- 光晕：`#FFE6A3`，Warm Halo
- 辅助文字：`#8E8E88`，Mist Gray
- 主文字：`#3E3E3C`，Soft Charcoal

适合天气、智能家居、轻工具、情绪化产品。

### 健康暖动感

- 背景：`#D6D0C6`，Warm Stone
- 卡片：`#F7F5F0`，Ivory Panel
- 深色面板：`#20232B`，Graphite Night
- 完成/高亮：`#FFD93B`，Active Lemon
- 热量/警示：`#FF6F61`，Coral Burn
- 分割线：`#E5DED3`，Pale Taupe

适合健身、健康、运动、习惯追踪和数据看板。

### 教育粉彩卡片

- 背景：`#B7EAD8`，Mint Breeze
- 画布：`#F8F4EF`，Warm Canvas
- 粉色分类：`#F4B8C0`，Blush Course
- 橙色分类：`#F8D7A8`，Cream Apricot
- 紫色分类：`#C9C2F6`，Lavender Study
- 绿色分类：`#B7EEDC`，Aqua Skill
- 主文字：`#111116`，Ink Black

适合在线教育、课程平台、内容分类页。

### 学习深色对比

- 背景：`#B9C3DA`，Powder Blue Gray
- 画布：`#F8F8F7`，Clean White
- 主卡：`#262445`，Deep Indigo
- 高亮：`#EDFF33`，Neon Lime
- 次级卡：`#B895FF`，Soft Violet
- 温和卡片：`#F9DDA7`，Butter Cream
- 图表辅助：`#D8C9FF`，Pale Violet

适合学习后台、课程进度、任务管理和统计面板。

## 板块生成规则

- 顶部导航：使用浅底、黑色文字、轻边界。
- 侧边栏：使用圆角图标和清晰选中态。
- 核心总览卡：可使用深色面板承载关键指标。
- 数据图表区：使用白色或米色卡片，配合浅色图表。
- 分类卡片区：使用粉彩色承载课程、分类、标签。
- 进度状态区：使用黄色、黄绿或珊瑚红表达状态。
- 搜索筛选区：使用胶囊形浅色控件和弱阴影。

## 约束

- 每个页面最多使用 1 个背景色、1 个主强调色、2 到 4 个分类色。
- 强调色面积控制在 5% 到 10%。
- 粉彩色不用于长正文文字。
- 深色面板只用于核心区域，不要堆满页面。
- 新拟物风格必须搭配阴影、圆角和高光。

