# Legal Pages

App Store Connect 提交所需的法律文档。

## 文件清单

| 文件 | 用途 | App Store Connect 对应字段 |
|---|---|---|
| `privacy-en.md` | 英文隐私政策（主）| **Privacy Policy URL**（必填，全区共用一个 URL；英文是 Apple 接受的国际通用语言）|
| `privacy-zh.md` | 中文隐私政策 | 不直接填 App Store，放 GitHub Pages 供国内用户查阅 |
| `terms-en.md` | 英文用户条款 | **License Agreement**（可选；不填默认走 Apple 标准 EULA）|
| `terms-zh.md` | 中文用户条款 | 同上 |
| `dmca-en.md` | 英文 DMCA 政策 | 放 GitHub Pages，在 App Store Connect "审核备注" 里引用 URL（告知审核员我们有 DMCA 流程 + 24h 响应）|

## 托管方式

**推荐 GitHub Pages**（免费、永久、域名稳定）：

1. 把 `docs/legal/` 内容 push 到 GitHub repo
2. repo Settings → Pages → Build from `main` branch, `/docs` folder
3. 生效后 URL：`https://<username>.github.io/<repo>/legal/privacy-en.html`
4. GitHub Pages 自动把 `.md` 渲染成 `.html`，无需手动转换

**替代方案**：
- 自己的域名（如 `bbrowser.app/privacy`），指向 GitHub Pages 或 Cloudflare Pages
- Notion public page（简单但 URL 丑）
- 其他静态托管（Netlify / Vercel）

## 填充状态

| 字段 | 值 |
|---|---|
| 开发者 | Zeroneo Studio |
| 联系邮箱 | `kirakingdx@hotmail.com` |
| 生效日期 | 2026-04-18 |

Governing Law 章节已删除（中英版条款都去掉了 "适用法律/Governing Law" section，不影响法律效力，简化用户阅读）。DMCA counter-notification 的 jurisdiction 条款保留标准 § 512(g)(3)(D) 表述（海外走"Zeroneo Studio 所在地"），不填具体地区。

## 和 App Store 审核备注的配合

App Store Connect 提交时"审核备注"建议填：

> This app is a privacy-focused browser with Content Blocker Extension
> and file management. Privacy Policy: <PRIVACY-URL>. DMCA Policy:
> <DMCA-URL>. We block media detection on major platforms (YouTube,
> Netflix, TikTok, Instagram, Facebook, Bilibili, etc.) via a built-in
> domain blocklist. DMCA takedown notices are responded to within 24
> hours via kirakingdx@hotmail.com.

把 `<PRIVACY-URL>` / `<DMCA-URL>` 换成实际 GitHub Pages URL。

## 维护提醒

- **每次收到有效 DMCA 投诉**：24h 内回复版权方 + 把投诉域名加入 `bbrowser/Core/DomainPolicy.swift` 的 `blocked` Set，下次发版生效
- **隐私政策有变动**（新增权限 / 新增第三方服务）：改 `privacy-en.md` + `privacy-zh.md` 的"最近更新"日期
