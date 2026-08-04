VS平台客服【Q-——333307——】VS平台客服【 辋芷《888yx●vip》 】
VS平台客服【Q-——333307——】VS平台客服【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

> 想拥有一个完全属于自己的技术博客？无需购买服务器，无需备案，GitHub Pages 免费托管 + Hexo 极速生成静态页面，10 分钟即可上线。本文手把手教你从环境配置到域名绑定，并附上 SEO 收录优化技巧。

 为什么选择 Hexo + GitHub Pages？

对于开发者来说，这几乎是零成本、高自由度的最优解。它不仅支持 Markdown 语法，写作体验极佳，而且部署生成的都是静态文件，访问速度快，还能轻松绑定自己的域名。最关键的是，百度、Google 对 GitHub Pages 的抓取非常友好，只要做好站点地图，收录根本不是问题。

 第一步：环境准备与本地安装

首先，你需要安装 Node.js 和 Git。安装完成后，打开终端执行：

```bash
npm install -g hexo-cli
hexo init blog
cd blog
npm install
hexo s
```

此时浏览器访问 `http://localhost:4000`，看到默认页面就说明本地环境搭建成功了。这里有个小技巧：在 `_config.yml` 中提前修改 `title`、`author` 等基础信息，避免后期重复打包。

 第二步：部署到 GitHub Pages

1. 在 GitHub 新建仓库，命名必须为 `用户名.github.io`。
2. 安装部署插件：`npm install hexo-deployer-git --save`。
3. 修改 `_config.yml` 中的 deploy 配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/用户名.github.io.git
  branch: main
```

最后执行 `hexo clean && hexo g && hexo d`，等待一分钟，你的博客就上线了！

 第三步：百度 SEO 收录与优化技巧

为了让内容更快被百度收录，务必做好以下三点：

- 生成并提交站点地图：安装 `hexo-generator-sitemap` 插件，然后在百度站长平台提交 `sitemap.xml`。
- 内链与关键词布局：文章开头就要点明核心关键词（如本篇文章的“GitHub Pages”），正文自然穿插长尾词“个人博客搭建教程”。
- 主动推送链接：使用百度提供的 `curl` 推送接口，每发一篇文章就主动提交 URL，通常当天即可收录。

 结语：从今天开始，写点什么吧

技术成长最快的方式就是输出。搭建好博客只是第一步，坚持记录踩坑经历、阅读笔记和项目复盘，你的影响力会在一年后显现。如果你在部署中遇到报错，欢迎在评论区留言截图，我会逐一回复解答。 觉得本文有用的话，别忘了点赞收藏，你的支持是我更新干货的最大动力！

> 行动提示：现在就登录 GitHub 创建仓库，把第一篇 Markdown 文章写完部署上去。遇到问题先搜索 “Hexo 部署失败”，80% 的坑都有现成解决方案。期待你的博客上线！

相关推荐：

https://github.com/underwoodcassidy5/coqdxx/blob/main/2026%E7%A7%91%E6%8A%80%E7%94%84%E9%80%89%EF%BC%9AVS%E6%B5%8B%E9%80%9F_%E6%84%BF%E5%89%BF%E9%A9%B6%E7%94%98%E5%A3%A4RYXFZ.md

<img src="https://i.postimg.cc/hGspn7JM/V8-00003.png" />

相关推荐：

https://github.com/underwoodcassidy5/coqdxx/commit/d5961e15e98d7fb226743ccfbc094511f64068fd

<img src="https://i.postimg.cc/c4YqSXdK/V8-00012.png" />
相关推荐：

https://github.com/fishergabrielle557/rvfthp/blob/main/2026%E6%9D%83%E5%A8%81%E7%94%84%E9%80%89%EF%BC%9AVS%E6%B3%A8%E5%86%8C_%E7%93%9C%E6%81%AB%E8%87%83%E8%93%96%E7%9D%ACHHCDS.md

<img src="https://i.postimg.cc/c4YqSXdK/V8-00012.png" />
相关推荐：

https://github.com/fishergabrielle557/rvfthp/commit/13bdf741dbaad7d97b782ac0d7ff621a1aa3be78

<img src="https://i.postimg.cc/d0w4g90d/V8-00002.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
