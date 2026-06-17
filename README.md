# 黄小西与贵客荟融合汇报页

这是一个可直接部署到 GitHub Pages 的静态汇报页。

## 文件说明

- `index.html`: 汇报页首页
- `fusion-home-prototype.html`: 融合后首页原型
- `assets/`: 汇报页和原型使用的图片素材
- `qa/`: 汇报页引用的原型截图

## GitHub Pages 部署

仓库已包含 `.github/workflows/pages.yml`。推送到 `main` 分支后，GitHub Actions 会自动发布静态页面。

如果首次部署方式选择 GitHub Actions，需要在 GitHub 仓库中进入：

`Settings` -> `Pages` -> `Build and deployment` -> `Source`，选择 `GitHub Actions`。

也可以选择分支部署：

`Settings` -> `Pages` -> `Build and deployment` -> `Source`，选择 `Deploy from a branch`，分支选择 `gh-pages`，目录选择 `/ (root)`。

部署完成后访问：

`https://arifinfirman788-blip.github.io/guikehui/`
