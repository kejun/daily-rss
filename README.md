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
- 🔥 **核心主题聚合**（6-8 个主题，每个主题 2-3 条相关新闻，相同主题合并）
- 🌐 **开源社区动态**
  - GitHub Trending Top 8 (AI/ML 相关)
  - Hacker News 热门讨论 Top 5
- 🤖 **LLM 动态速递**（10-15 条，增强版）
  - 模型更新 / 技术突破 / 工具生态 / 应用案例
- 💰 **投融资快报**
  - AI 初创公司融资消息 (3-5 条)
  - 大额并购/战略合作
- 🛠️ **开发者工具更新**
  - 框架版本发布 / 重要工具更新 (3-5 条)
- 📰 **行业深度**
  - 至少 3 篇值得细读的深度文章摘要
- 📊 **论文精选**
  - 2-3 篇重要论文摘要
- 📅 **今日活动预告**
  - 技术发布会/直播 / 重要财报/数据发布

### 总结与数据
- 📊 **今日数据概览**（多维度统计）
- 💡 **编者观察**（500-600 字深度总结）

**所有条目必须包含原文链接**

## 🔄 自动化

日报通过 OpenClaw Cron 自动生成，每日早上 6:30 更新。

## 📚 数据源

### 核心 RSS
- [Andrej Karpathy Curated RSS](https://youmind.com/rss/pack/andrej-karpathy-curated-rss)
- [TLDR AI](https://tldr.tech/api/rss/ai)
- [The Rundown AI](https://rss.beehiiv.com/feeds/2R3C6Bt5wj.xml)
- [Hacker News Front](https://hnrss.org/frontpage)
- [GitHub Trending](https://github-trends-atom.vercel.app/trending)

### 深度媒体
- [MIT Technology Review AI](https://www.technologyreview.com/topic/artificial-intelligence/feed/)
- [WIRED AI](https://www.wired.com/feed/tag/ai/latest/rss)
- [Ars Technica AI](https://arstechnica.com/ai/feed/)
- [TechCrunch AI](https://techcrunch.com/category/artificial-intelligence/feed/)
- [VentureBeat AI](https://venturebeat.com/category/ai/feed/)
- [MarkTechPost](https://www.marktechpost.com/feed/)

### 行业/研究
- [Hugging Face Blog](https://huggingface.co/blog/feed.xml)
- [AI Business](https://aibusiness.com/rss.xml)
- [SiliconANGLE AI](https://siliconangle.com/category/ai/feed)
- [Ahead of AI (Sebastian Raschka)](https://magazine.sebastianraschka.com/feed)
- [KDnuggets](https://www.kdnuggets.com/feed)
- [InfoQ AI/ML/Data Eng](https://feed.infoq.com/ai-ml-data-eng/)
- [LangChain Blog](https://blog.langchain.dev/rss/)
- [Interconnects](https://www.interconnects.ai/feed)
- [Last Week in AI](https://lastweekin.ai/feed)

### 论文/学术
- [arXiv cs.AI](https://arxiv.org/list/cs.AI/recent)
- [arXiv cs.CL](https://arxiv.org/list/cs.CL/recent)

### 更多候选源
- 完整来源列表：[foorilla/allainews_sources](https://github.com/foorilla/allainews_sources)
- 按需补充：Nature ML, ZDNET AI, The Guardian AI, IEEE Spectrum AI 等

---
*由 AI 自动生成 | 更新时间：每日 06:30 CST | 字数目标：5000-7000 字 | 数据源：20+ RSS*
