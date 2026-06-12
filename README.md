# Issue 的博客

[![Hugo](https://img.shields.io/badge/Hugo-0.163-blue?logo=hugo)](https://gohugo.io/)
[![Theme](https://img.shields.io/badge/Theme-PaperMod-8e44ad)](https://github.com/adityatelange/hugo-PaperMod)
[![Deploy](https://img.shields.io/badge/Deploy-Cloudflare%20Pages-f38020?logo=cloudflare)](https://pages.cloudflare.com/)

个人博客 📝 — 记录奇思妙想，分享有趣的东西。

🔗 **[myblog.whatisissue.dpdns.org](https://myblog.whatisissue.dpdns.org/)**

## 功能

- ✍️ Markdown 写作，push 即发布
- 💬 匿名评论（Twikoo · Cloudflare Workers + D1）
- ❤️ 匿名点赞（localStorage 持久化）
- 📤 一键分享（Web Share API + 复制链接）
- 🌓 亮/暗主题切换
- 🔍 全文搜索
- 📅 按时间归档

## 本地运行

```bash
hugo server -D
# 浏览器打开 http://localhost:1313
```

## 写文章

```bash
hugo new posts/标题.md
# 编辑 content/posts/标题.md
git add . && git commit -m "新文章" && git push
# Cloudflare Pages 30 秒自动上线
```

## 技术栈

| 层级 | 技术 |
|------|------|
| 静态生成 | Hugo |
| 主题 | PaperMod |
| 托管 | Cloudflare Pages |
| 评论 | Twikoo（Cloudflare Workers + D1） |
| 字体 | 系统默认 |

## 许可证

MIT
