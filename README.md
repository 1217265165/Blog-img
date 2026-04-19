# 🚀 My Blog Image Bed (个人博客图床)

这里是我的 Hexo 博客图片托管仓库。通过 **GitHub + PicGo + jsDelivr** 实现国内高速访问。

## 🛠 配置信息 (PicGo / Typora)

如果你需要在新设备上配置环境，请参考以下参数：

| 配置项 | 内容 |
| :--- | :--- |
| **仓库名 (Repo)** | `1217265165/Blog-img` |
| **分支 (Branch)** | `main` |
| **存储路径 (Path)** | `img/` |
| **自定义域名 (Custom Domain)** | `https://cdn.jsdelivr.net/gh/1217265165/Blog-img@main` |

---

## ⚡ CDN 加速原理

为了解决 GitHub 原始链接在国内访问缓慢的问题，本项目使用 **jsDelivr** 进行全站加速。

**转换规则：**
* 原始路径：`https://github.com/1217265165/Blog-img/blob/main/img/example.png`
* 加速路径：`https://cdn.jsdelivr.net/gh/1217265165/Blog-img@main/img/example.png`

---

## 📝 注意事项

1. **Token 安全**：切勿将你的 GitHub Personal Access Token 上传至此仓库或任何公开平台。
2. **重名覆盖**：建议在 PicGo 中开启“上传前重命名”或“时间戳命名”功能，防止图片因同名被覆盖。
3. **缓存刷新**：jsDelivr 有缓存机制。如果你覆盖了旧图片但链接内容未更新，可以在链接中的分支名后添加版本号或稍作等待。
4. **仓库容量**：GitHub 仓库建议保持在 1GB 以内。对于超大图片，建议先压缩再上传。

---

## 📂 目录结构

* `/img` - 存放所有博文配图
* `/assets` - 存放主题相关的静态资源（Logo, Banner 等）

---
Copyright © 2026 [搬砖分部]
