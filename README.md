# Sistine_blog

这是个人博客仓库（仓库描述：my blog）。

下面的 README 是一个通用模板；如果你的博客使用特定的框架（例如 Next.js、Hugo、Jekyll、Hexo 等），请根据实际项目修改“本地运行”和“部署”部分。

## 目录
- 简介
- 特性
- 快速开始
- 本地预览
- 更新与发布
- 贡献
- 许可证
- 联系方式

## 简介
Sistine_blog 是我的个人博客，存放博客源码、文章和配置。此仓库用于记录、发布和维护个人写作与项目笔记。

## 特性
- 文章与页面管理
- 静态/动态站点（视具体实现而定）
- 可自定义主题与样式

## 快速开始
1. 克隆仓库：

```bash
git clone https://github.com/angellsla/Sistine_blog.git
cd Sistine_blog
```

2. 查看仓库根目录，确认使用的框架或构建工具（例如 package.json、Gemfile、config.toml 等）。

## 本地预览（通用方法，按项目实际技术栈选择）

- 如果只是静态 HTML 文件：

```bash
# 使用 python3 提供临时静态服务器
python3 -m http.server 8000
# 或者
python -m http.server 8000
```
然后在浏览器打开 http://localhost:8000

- 如果使用 Node.js（例如 Next.js、Gatsby、Hexo 等）：

```bash
# 安装依赖
npm install
# 或者使用 pnpm/yarn
# 本地开发
npm run dev
# 或
npm start
```

- 如果使用 Jekyll：

```bash
bundle install
bundle exec jekyll serve
```

- 如果使用 Hugo：

```bash
hugo server -D
```

> 如果不确定使用哪个框架，请打开仓库查看是否存在 package.json、config.toml、Gemfile 等文件，以判断使用的技术栈。

## 更新与发布
- 编辑或新增文章/页面（通常在 posts/、content/ 或 _posts/ 目录）。
- 本地测试无误后提交并推送：

```bash
git add .
git commit -m "更新：写点内容的说明"
git push origin main
```

- 如果启用了 GitHub Pages、Netlify、Vercel 等持续部署服务，推送到指定分支后会自动构建并发布站点。

## 贡献
欢迎提交 PR 或 Issue：
- 提交新的文章或修复拼写/格式问题
- 提交主题/样式改进的建议

在提交 PR 前，请确保：
- 格式与现有文件风格一致
- 运行本地预览检查无错误

## 许可证
仓库当前未指定许可证。建议添加 LICENSE 文件，例如 MIT 许可证：

```
MIT License
```

（根据需要替换为你选择的许可证）

## 联系方式
如果你需要我协助修改 README 或添加更具体的使用说明，请告诉我你的博客框架或提供仓库中与框架相关的文件名（例如 package.json、config.toml、Gemfile 等），我会把 README 更新为更详细的版本。
