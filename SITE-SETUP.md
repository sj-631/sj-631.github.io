# 网站资料与发布说明

这个目录是基于 Academic Pages 模板的草稿，目标 GitHub 账号为 `sj-631`。
网站预计地址是 `https://sj-631.github.io/`；只有仓库创建并成功发布后才能访问。

## 需要补充的资料

- 姓名、机构、简介、邮箱以及头像，在 `_config.yml` 的 `author` 中填写。
- 首页文字：`_pages/about.md`。
- 研究方向及论文：`_pages/research.md`。
- 头像可放入 `images/`，并在 `_config.yml` 的 `author.avatar` 填写文件名。

当前页面的身份和学术信息采用了不作事实断言的临时文字。模板自带的示例论文、博客、课程等已在 `_config.yml` 中排除；需要启用时，先删除对应示例并移除相应的排除项，再添加真实内容。

## 发布

在 GitHub 账户 `sj-631` 下创建 `sj-631.github.io` 仓库，将该项目内容推送到仓库，然后在 GitHub 仓库 Settings → Pages 中选择 GitHub Actions。公开发布前请先核对网站内容。

本项目来自 Academic Pages，保留原始 LICENSE 和模板文档。
