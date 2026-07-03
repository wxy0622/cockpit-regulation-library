# 智能座舱法规设计知识库

这是可直接发布的纯静态应用。`index.html` 内嵌规则数据、样式与脚本；图标与法规 PDF 以外部资源按需加载。

## 目录结构

- `index.html` — 主入口（约 290 KB）
- `icons/` — 标准图标 PNG（按需加载）
- `assets/gb4094-2016.pdf` — 法规原文 PDF（打开法规库时加载）

## 使用

- 本地使用：双击 `index.html`（需保持 `icons/` 与 `assets/` 文件夹在同一目录）。
- 静态托管：将整个文件夹上传至 Netlify、GitHub Pages、Cloudflare Pages 或内部静态服务器。
- 入口文件必须保持名称为 `index.html`。
