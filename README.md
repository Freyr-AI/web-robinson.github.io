# Robinson 网站

Robinson Asset Management Pte. Ltd. 中英文静态网站。

- 英文首页：https://www.robinsonmgt.com/
- 中文页面：https://www.robinsonmgt.com/zh/

该项目通过 `CNAME` 配置正式域名 `www.robinsonmgt.com`。

## 部署与维护

网站无需安装依赖或构建。GitHub Pages 从 `main` 分支根目录发布；推送更新后自动部署。

- `index.html`：英文首页
- `zh/index.html`：中文页面
- `.nojekyll`：直接发布静态文件
- `docs/`：原始交付说明、文案及原文件 SHA256 校验值

当前版本为 2026 年 11 月 12 日交付包 V17，四个源文件的 SHA256 已核验。网站使用正式域名根目录路径。HTML 仅补充 Cloudflare `email_off` 标记，因此其校验值与原交付校验文件不同；文案及样式按 V17 保持原样。

CSS 与 JavaScript 均内嵌在 HTML 中，共用样式调整时需同步两种语言。联系入口指向 `contact-robinson@robinsonmgt.com`。

顶部 Logo 为 `assets/robinson-wordmark.png`，浏览器图标为 `assets/robinson-icon.png`。联系链接使用 Cloudflare 支持的 `email_off` 标记，避免被改写为依赖解码脚本的邮件保护地址。
