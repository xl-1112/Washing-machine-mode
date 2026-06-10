# e洁小程序模式统计原型

这是可发布到 GitHub 和 Tencent Cloud EdgeOne Pages 的静态单文件版本。

## 文件

- `index.html`：已内联 CSS 和 JavaScript，可作为静态站点入口直接托管。

## GitHub 发布建议

1. 新建 GitHub 仓库，例如 `e-clean-mode-statistics-prototype`。
2. 将本目录中的 `index.html` 提交到仓库根目录。
3. 若使用 EdgeOne Pages 的 GitHub 集成，选择该仓库作为部署源。

## EdgeOne Pages 配置

如果通过 GitHub 导入：

- Framework preset：None / Static
- Build command：留空
- Output directory：`/`
- Entry file：`index.html`

如果直接上传：

- 上传 `index.html` 或包含 `index.html` 的 zip 包。
