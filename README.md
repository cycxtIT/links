---
draft: true
---

# 想要和 [我](https://www.dejavu.moe) 交换 [友情链接](https://www.dejavu.moe/links/) 吗？

## 友链要求

- 网站应是 **生活类** 或 **技术类** 的个人博客
- 域名是应该是 **付费** 的 **独立域名** 或包含于 [**Public Suffix List**](https://publicsuffix.org/list/public_suffix_list.dat) 的 **子域名**
- 网站完全使用 HTTPS 连接和可信 SSL 证书
- 网站应有 **实质性内容**，尊重 **原创** 和 **版权**
- 网站保持 **长期稳定运行**
- 至少应该在中国大陆以外地区 **访问体验良好**
- 文章 **排版良好**，阅读舒适，参考 [中文文案排版指南](https://github.com/sparanoid/chinese-copywriting-guidelines)

## 开始交换

> 确保您的网站满足以上「友链要求」，现在可以尝试和 [我](https://www.dejavu.moe) 交换 [友链](https://www.dejavu.moe/links/) 啦~

- 将 [我](https://www.dejavu.moe) 的网站信息添加到您的「友链页面」

  ```yaml
    - 名称: "Dejavu's Blog"
      网址: "https://www.dejavu.moe"
      头像: "https://www.dejavu.moe/links/src/www.dejavu.moe.webp"
      描述: "与君初相见，犹如故人归"
  ```
  
- 在 GitHub 上 Fork [这个仓库](https://github.com/DejavuMoe/links)

- 在 `src` 下提交你的站点 `Logo/头像`

  - **图片形状** 为 **正方形** 或 **圆形**
  - **长**、**宽** 均不超过 512 像素（`px`）
  - **图片格式** 应为 `.webp`
  - **文件名称** 为 `[your-domain].webp`，比如 `www.dejavu.moe.webp`
  - **文件大小** 不超过 50 KB
  - **建议** 使用 [Squoosh](https://squoosh.app/) 对图片进行裁切或转换

- 在 `index.md` 添加您的站点信息

  ```html
  {{<friend name="名称" url="网址" logo="头像" word="描述" >}}
  ```
  
- 最后，向 [这个仓库](https://github.com/DejavuMoe/links) 发起一个 Pull Request 请求
- 当您的 Pull Request 被合并后，代表友链交换成功
- 至多 8 小时后，您的站点将出现在 [友链页面](https://www.dejavu.moe/links/)
