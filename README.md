# ECANET 公司网站

ECANET International Company Limited 的官方单页网站（合规咨询 · 公司秘书）。

## 文件说明

- `index.html` — 网站主文件（自包含，所有样式与脚本已内嵌，无需额外依赖）
- `.nojekyll` — 告诉 GitHub Pages 跳过 Jekyll 处理，确保静态文件正常发布
- `README.md` — 本说明文件

## 部署到 GitHub Pages

1. 将本文件夹内的 `index.html`、`.nojekyll`、`README.md` 上载到仓库 `simonchchan/ecanet-site` 的根目录（`main` 分支）。
2. 打开仓库 **Settings → Pages**。
3. 在 **Build and deployment** 下，将 **Source** 设为 **Deploy from a branch**。
4. **Branch** 选 `main`，文件夹选 `/ (root)`，按 **Save**。
5. 等待约 1–2 分钟，网站会发布于 `https://simonchchan.github.io/ecanet-site/`。

## 自定义

- 联络资讯（电邮、电话、微信）位于 `index.html` 的 `#contact` 区块。
- 配色变量集中在 `<style>` 顶部的 `:root` 中，可统一调整深蓝与金色。
- 网站内容以简体中文呈现，配色沿用公司介绍的深蓝＋金色。
