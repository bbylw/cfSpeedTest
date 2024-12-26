# CloudflareSpeedTest UI

一个优雅的 Cloudflare IP 优选工具聚合页面，集成了多个数据源的测速结果，提供实时的 Cloudflare CDN 优选 IP 信息。

## 项目说明

本项目是一个前端聚合页面，整合了以下两个优秀的 Cloudflare IP 测速服务：

- [CF Speed DNS](https://ip.164746.xyz/) - 提供每5分钟自动更新的优选 IP
- [WeTest](https://www.wetest.vip/page/cloudflare/address_v4.html) - 提供详细的 IP 测速数据

特别感谢以上服务提供者为社区做出的贡献！

## 功能特点

- 📊 同时展示两个数据源的测速结果
- 🔄 实时数据更新
- 🔗 便捷的源站访问链接
- 📱 响应式设计，完美支持移动端
- 🎨 现代化的深色主题 UI

## UI 设计

- **配色方案**：采用深色主题设计
  - 主题色：橙色 (#ff9000)
  - 背景色：黑色 (#000000)
  - 次要背景：深灰 (#282828)

- **布局设计**：
  - 顶部 Logo 区域
  - 快捷访问源站链接
  - 双列数据展示（移动端自动切换为单列）
  - 自适应高度的内容区域

## 部署说明

1. Fork 本仓库到您的 GitHub 账号

2. 开启 GitHub Pages：
   - 进入仓库设置 (Settings)
   - 找到 Pages 选项
   - 在 Source 中选择 `main` 分支
   - 选择 root 目录 `/(root)`
   - 点击 Save

3. 等待部署完成后，您可以通过以下地址访问：

```plaintext
https://[您的用户名].github.io/[仓库名]/
```

## 本地开发

1. 克隆仓库：

```bash
git clone https://github.com/[您的用户名]/[仓库名].git
```

1. 使用任意 Web 服务器运行项目，例如：
   - 使用 Python：`python -m http.server 8080`
   - 使用 Node.js：`npx serve`
   - 或直接在浏览器中打开 `index.html`

## 技术栈

- HTML5
- CSS3 (使用现代特性如 CSS Grid, clamp() 等)
- 原生 JavaScript

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge
- 其他现代浏览器

## 许可证

MIT License

## 贡献

欢迎提交 Issue 和 Pull Request！ 