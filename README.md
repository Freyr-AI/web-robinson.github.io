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

原交付包的 SHA256 已核验。为兼容 GitHub Pages 项目路径，两个页面的语言切换链接已改为相对路径，因此当前 HTML 的校验值与原交付校验文件不同。文案、样式及其他交互保持原样。

CSS 与 JavaScript 均内嵌在 HTML 中，共用样式调整时需同步两种语言。联系入口指向 `contact-robinson@robinsonmgt.com`。

顶部 Logo 与浏览器图标位于 `assets/`。联系链接使用 Cloudflare 支持的 `email_off` 标记，避免被改写为依赖解码脚本的邮件保护地址。
