# Daily RSS

每日技术 RSS 聚合日报，基于多源信息聚合的增强版技术快报。

## 📁 目录结构

```
daily-rss/
├── README.md
├── 2026/
│   ├── 02/
│   │   ├── 2026-02-13.md  # 每日日报
│   │   └── ...
│   └── ...
└── archive/               # 归档目录
```

## 📊 日报格式（增强版）

每份日报必须包含以下板块：

### 核心内容
- 🔥 **核心主题聚合**（4-6 个主题，相同主题合并）
- 🌐 **开源社区动态**（新增）
  - GitHub Trending Top 5 (AI/ML 相关)
  - Hacker News 热门讨论 Top 3
- 🤖 **LLM 动态速递**（8-10 条，增强版）
  - 模型更新 / 技术突破 / 工具生态 / 应用案例
- 💰 **投融资快报**（新增）
  - AI 初创公司融资消息 (2-3 条)
  - 大额并购/战略合作
- 🛠️ **开发者工具更新**（新增）
  - 框架版本发布 / 重要工具更新
- 📅 **今日活动预告**（新增）
  - 技术发布会/直播 / 重要财报/数据发布

### 总结与数据
- 📊 **今日数据概览**（多维度统计）
- 💡 **编者观察**（300-400 字深度总结）

**所有条目必须包含原文链接**

## 🔄 自动化

日报通过 OpenClaw Cron 自动生成，每日早上 6:30 更新。

## 📚 数据源

### 核心 RSS
- [Andrej Karpathy Curated RSS](https://youmind.com/rss/pack/andrej-karpathy-curated-rss)
- [MIT Tech Review](https://www.technologyreview.com/feed/)
- [Hacker News Top](https://hnrss.org/frontpage)
- [GitHub Trending](https://github-trends-atom.vercel.app/trending)

### 补充来源
- Hugging Face Blog
- arXiv cs.CL / cs.AI
- React Blog, Vercel Blog
- ClawNews, Moltbook 社区
- Web Search (实时搜索补充)

---
*由 AI 自动生成 | 更新时间：每日 06:30 CST | 字数目标：2500-3500 字*
