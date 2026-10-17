# 发布到 GitHub Pages

目标仓库：`Z-702/Z-702.github.io`

部署成功后，个人主页地址为：`https://z-702.github.io/`。这是目标地址，并不表示当前已经发布。

## 网页上传

1. 登录 GitHub，创建名为 **Z-702.github.io** 的公开仓库。
2. 将本项目文件上传到仓库根目录。确保 `_config.yml`、`Gemfile`、`_pages/`、`_layouts/`、`_includes/`、`_sass/`、`assets/`、`images/` 和 `.github/workflows/pages.yml` 都在仓库根目录对应位置。
3. 打开 **Settings → Pages**，将 **Source** 设为 **GitHub Actions**。
4. 打开 **Actions → Build and deploy personal homepage**。如果首次上传时尚未启用 Pages 导致工作流失败，启用后选择 **Re-run all jobs**，或通过 **Run workflow** 重新触发。
5. 等待 build 与 deploy 两个任务成功，再打开主页地址。

Windows 有时不显示 `.github` 等点开头目录，请务必确认工作流文件已上传。

## 使用 Git

在解压后的项目目录中打开终端，且仅在你创建的目标仓库为空时执行：

```sh
git init -b main
git add .
git commit -m "Create academic homepage based on Academic Pages"
git remote add origin https://github.com/Z-702/Z-702.github.io.git
git push -u origin main
```

随后按上方第 3–5 步启用 Pages。首次推送可能需要 GitHub 登录授权；不要把密码或访问令牌写进项目文件。

## 已配置

- 用户名与仓库：`Z-702/Z-702.github.io`
- 站点 URL：`https://z-702.github.io`
- `baseurl`：空字符串（用户主页仓库）
- GitHub Actions：推送到 `main` 或 `master` 后构建并部署
- 自动部署所需的 Pages 权限与 `github-pages` 环境
- 每篇论文的状态与作者顺序

## 后续常见修改

- 邮箱：在 `_config.yml` 的 `author` 下添加 `email`。
- 照片：上传到 `images/`，修改 `author.avatar`。
- 论文：修改 `_includes/selected-publications.html`；摘要、引用与中英文文本在 `assets/js/personal.js`。
- 文章发表状态发生变化时，同时修改列表标签与摘要弹窗的说明。

已发表 TractoMFormer 的 DOI 与 MR–US 工作的 arXiv 链接已保留。CT 稿件仅展示研究简介和方法图，不包含投稿文件全文及附信。
