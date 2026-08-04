VS开户测速【Q-——333307——】VS开户测速【 辋芷《888yx●vip》 】
VS开户测速【Q-——333307——】VS开户测速【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hugo 详细指南

你是否想过拥有一个完全属于自己的技术博客？无需购买服务器，不需要复杂的运维知识，GitHub Pages + Hugo 的组合能让你在半小时内上线一个高性能的静态博客。今天我们就来手把手拆解全流程。

 为什么选择 Hugo 而非 Hexo？
相比 Hexo，Hugo 的构建速度极快（数百篇文章秒级生成），且单二进制文件部署无依赖。更关键的是，它原生支持 GitHub Actions 自动部署，你只需专注写作，推送代码即可完成发布。

 三步完成博客搭建

 1. 创建 GitHub 仓库
登录 GitHub 新建仓库，命名为 `你的用户名.github.io`。务必勾选 Add a README file，方便后续初始化。

 2. 本地环境初始化
- 安装 Hugo（macOS 用 `brew install hugo`，Windows 用 Chocolatey）
- 执行 `hugo new site myblog` 创建项目骨架
- 下载喜欢的主题（推荐 PaperMod 或 Even），放入 `themes` 目录

 3. 自动化部署配置
在项目根目录创建 `.github/workflows/deploy.yml`，写入以下关键代码：
```yaml
- name: deploy
  run: hugo --minify
- name: push
  uses: peaceiris/actions-gh-pages@v3
```

 你可能会遇到的 3 个坑
1. 路径配置问题：如样式丢失，检查 `config.toml` 中的 `baseURL` 是否为 `https://用户名.github.io`  
2. Git 子模块错误：删除主题的 `.git` 文件夹后再提交  
3. Actions 权限不足：在仓库 Settings → Actions → General 中勾选 Read and write permissions

 进阶玩法
- 绑定自定义域名：在仓库设置中添加 CNAME 文件  
- 接入 Giscus 评论系统：引用 GitHub Discussions 实现动态交互  
- 使用 GitHub API 自动更新文章更新时间

遇到报错时，优先查看 Actions 构建日志——80% 的问题都能通过红字提示定位。如果这篇文章对你有帮助，欢迎在评论区留下你的搭建链接，我会去参观并反向链接你的博客。记得点击右上角关注，获取更多效率工具干货！

相关推荐：

https://github.com/parkergloria9526/anwwee/blob/main/2026%E7%A7%91%E6%8A%80%E7%83%AD%E7%82%B9%EF%BC%9AVS%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E9%97%AE%E7%94%B7%E9%97%AE%E5%B1%B1%E4%BB%95MZTBD.md

<img src="https://i.postimg.cc/c4YqSXdK/V8-00012.png" />

相关推荐：

https://github.com/parkergloria9526/anwwee/commit/d8955eda64364835cd3910450990a4a967f5128f

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/blob/main/%E6%B7%B1%E5%BA%A6%E5%AE%9E%E6%93%8D%E6%95%99%E7%A8%8B%EF%BC%9AVS%E5%A8%B1%E4%B9%90%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E5%90%88%E5%BE%84%E7%96%A4%E5%96%84PYLLN.md

<img src="https://i.postimg.cc/tJZ5FSB6/V8-00007.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/commit/4cc9a07b6226b63bf021ef57296e89b702ad1503

<img src="https://i.postimg.cc/5tbnDmt0/V8-00001.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
