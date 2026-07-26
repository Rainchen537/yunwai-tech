# 云外科技企业官网

云外科技的中文企业展示站。项目基于 Astro 官方 GitHub Pages 模板构建，使用 GitHub Actions 自动完成静态构建与发布。

## 技术方案

- Astro 7 静态站点生成
- `@lucide/astro` 图标组件
- Astro Assets 图片优化
- 原生 CSS 设计系统与少量渐进增强脚本
- GitHub Actions + GitHub Pages 自动部署

## 本地开发

```bash
npm ci
npm run dev
```

生产构建：

```bash
npm run build
npm run preview
```

## 部署

推送到 `main` 分支后，`.github/workflows/deploy.yml` 会自动构建并发布到 GitHub Pages。

当前 Pages 地址：

`https://rainchen537.github.io/yunwai-tech/`

## 内容说明

当前企业介绍、服务范围与联系邮箱均为展示内容。正式使用前，请替换为企业真实资料、备案信息、隐私条款与有效联系方式。

## 素材与授权

- 项目骨架来自 `withastro/github-pages`
- 图标来自 Lucide，采用 ISC License
- 页面视觉素材为本项目专门生成
