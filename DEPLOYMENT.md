# GitHub Pages

- Website: https://z-702.github.io/
- Repository: `Z-702/z-702.github.io`
- Branch: `main`
- Settings → Pages → Source: GitHub Actions

修改后提交到 `main`，网站会自动构建和部署。在仓库 **Actions → Build and deploy personal homepage** 查看状态，build 和 deploy 均显示绿色后刷新网站。

## 常见修改

- 姓名、学校、公开链接：`_config.yml`。
- 英文简介：`_pages/about.md`。
- 中文简介：`_pages/about-zh.md`。
- 研究方向：`_pages/research.md`。
- 论文：`_publications/`，每篇论文一个 Markdown 文件。
- 照片：上传到 `images/`，设置 `_config.yml` 的 `author.avatar`。

主页和论文页沿用 Academic Pages 的原版布局，无需同步修改 JavaScript。
