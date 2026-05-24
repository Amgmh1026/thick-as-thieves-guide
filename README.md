# Thick As Thieves — Static Guide

简单静态网站，使用 HTML/CSS，可直接部署到 Vercel。

部署步骤（命令行）：

1. 安装并登录 Vercel CLI（可选）：

```bash
npm i -g vercel
vercel login
```

2. 在本站点目录运行部署（或将仓库连接到 Vercel）：

```bash
cd site
vercel --prod
```

说明：此项目为静态文件，Vercel 会自动识别并部署。若希望使用自定义域或添加评论/分析，请参照 Vercel 控制台配置。
