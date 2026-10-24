# 个人作品集

一个无需构建工具的响应式静态作品集网站，使用原生 HTML、CSS 和 JavaScript。

## 本地预览

直接用浏览器打开 `index.html` 即可。网站没有安装依赖或构建步骤。

## 个性化内容

在 `index.html` 中搜索并替换以下占位内容：

- `你的名字`：姓名和浏览器页面标题
- `YN`：导航和页脚中的姓名缩写
- 项目名称、项目描述、标签和年份
- 个人介绍、关注方向、所在地
- `hello@example.com`：联系邮箱
- 项目卡片链接：替换为项目详情页或真实项目地址

页面的颜色、间距和排版集中在 `styles.css` 顶部的 CSS 变量中。移动端导航和页脚年份由 `script.js` 处理。

## 发布到 GitHub Pages

仓库包含 `.github/workflows/pages.yml` 部署工作流。将仓库的 Pages 发布来源设置为 **GitHub Actions** 后，每次推送到 `main` 都会自动部署；也可在 Actions 页面手动运行工作流。网站无需构建步骤。
