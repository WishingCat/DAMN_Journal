<div align="center">

# DAMN

### Discovery and Advancement of Modern Nature

**《彻诞》— 彻底探索，诞生新知**

[![Deploy](https://img.shields.io/badge/Cloudflare%20Pages-deployed-orange?logo=cloudflare)](https://damn-journal.pages.dev)
[![License](https://img.shields.io/badge/license-CC%20BY%204.0-blue)](https://creativecommons.org/licenses/by/4.0/)

*Truth fades, but DAMN lasts forever.*

**[访问期刊官网 / Visit Journal Website →](https://damn-journal.pages.dev)**

</div>

---

## 关于 / About

**《DAMN》** 是一本致力于收录**严肃荒诞研究**的开放获取学术期刊，创办于 2026 年。

> 课题可以荒诞，但思维必须严谨；
> 表达可以有趣，但逻辑必须自洽；
> 形式可以解构，但绝不允许造假。

我们相信：世界上最伟大的发现，往往诞生于最荒诞的提问。

## 网站结构 / Site Structure

| 页面 / Page | 路由 / Route | 说明 / Description |
|---|---|---|
| 首页 / Home | `/` | 期刊身份、最新文章、投稿入口 |
| 文章 / Articles | `/articles` | 全部已发表文章列表 |
| 文章详情 / Article Detail | `/articles/:slug` | 单篇论文完整展示 + 评论区 |
| 投稿指南 / Submit | `/submit` | 征稿范围、格式规范、投稿方式 |
| 关于 / About | `/about` | 期刊介绍、编委会、联系方式 |

## 技术栈 / Tech Stack

- **框架**: [Astro](https://astro.build/) — 零 JS 静态站点生成
- **样式**: [Tailwind CSS v4](https://tailwindcss.com/) — 暗色学术主题
- **内容**: Astro Content Collections — Markdown + YAML frontmatter
- **部署**: [Cloudflare Pages](https://pages.cloudflare.com/) — 自动构建部署
- **字体**: Noto Serif SC + Inter — 中英文学术排版

## 本地开发 / Development

```bash
# 安装依赖 / Install dependencies
npm install

# 启动开发服务器 / Start dev server
npm run dev

# 构建静态站点 / Build for production
npm run build
```

## 添加新文章 / Add New Article

在 `src/content/articles/` 目录下新建 `.md` 文件：

```markdown
---
id: "DAMN-2026-XXX"
title: "你的论文标题"
authors:
  - name: "作者姓名"
    affiliation: "所属单位"
date: 2026-01-01
abstract: "摘要内容..."
keywords: ["关键词1", "关键词2"]
---

## 摘要 / Abstract
...

## 引言 / Introduction
...
```

提交并推送后，Cloudflare Pages 会自动构建部署。无需修改任何代码。

## 投稿 / Submit

欢迎来自一切学科领域的投稿！

- **投稿邮箱**: 470045806@qq.com
- **邮件标题**: 请注明"《DAMN》投稿"
- **详细指南**: [damn-journal.pages.dev/submit](https://damn-journal.pages.dev/submit/)

## 联系我们 / Contact

- **主编**: 祈愿的猫
- **QQ**: 470045806
- **邮箱**: 470045806@qq.com

---

<div align="center">

**彻古今之变，诞闻所未闻**

*鸣谢《SHIT》期刊的开创性贡献*

</div>
