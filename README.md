# Ziliang Qiu — Academic homepage

无需安装依赖的英文静态学术主页。简介、五篇论文和教育信息来自作者提供的材料。

## 修改内容

- `dist/index.html`：姓名、简介、论文和教育经历。
- `dist/styles.css`：配色、字体和响应式排版。
- `dist/favicon.svg`：网页图标。
- `dist/portrait.jpg`：作者提供的照片。

直接用浏览器打开 `dist/index.html` 即可查看。没有外部字体、追踪脚本或构建依赖。

## GitHub Pages

源码推送到 `main` 后，在仓库 **Settings → Pages → Build and deployment → Source** 选择 **GitHub Actions**。仓库已包含发布 `dist/` 的工作流；需要时可在 Actions 中手动运行。

当前用户名 `ziliang6` 和仓库名 `ziliang.github.io` 不相同；按 GitHub 的默认项目页面规则，网址为 `https://ziliang6.github.io/ziliang.github.io/`。若希望使用根网址 `https://ziliang6.github.io/`，可将仓库改名为 `ziliang6.github.io`。本网站的资源使用相对路径，两种方式均可。

## 内容说明

保留提供的学位名称及出版信息。EMNLP 论文链接对应 ACL Anthology 正式记录，并附 PACE 代码链接；self-correction 论文附 arXiv 论文、Octopus 项目主页和代码；两篇 2024 年论文附作者提供的 CNKI 链接，古汉语典故论文另附资源数据库代码链接。2026 年数字人文工作坊综述暂未提供论文网址。联系邮箱为 `ziliang6@illinois.edu`。已添加作者提供的照片，保持原图色彩；页面模板为黑白单栏，所有内容按上下顺序阅读。暂未添加简历文件。

EMNLP 论文页码按 [ACL Anthology 正式记录](https://aclanthology.org/2025.emnlp-main.550/) 修正为 10859–10872（提供的截图为 10870–10883）。

`.openai/hosting.json` 仅用于 Sites 私人预览，与 GitHub Pages 工作流相互独立。
