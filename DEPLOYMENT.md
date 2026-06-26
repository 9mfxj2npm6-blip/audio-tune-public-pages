# 伴奏调音公开页面部署包

本目录可上传到任意稳定 HTTPS 静态托管服务，用于 App Store Connect 的必填 URL。

## 文件

- `index.html`：公开页面入口，用于快速检查链接。
- `privacy-policy.html`：填写到 App Store Connect 的 Privacy Policy URL。
- `support.html`：填写到 App Store Connect 的 Support URL。
- `manifest.txt`：本次生成状态。

## 部署后填写

- Privacy Policy URL：`https://你的域名/privacy-policy.html`
- Support URL：`https://你的域名/support.html`

## 上线前检查

- 支持邮箱已替换；公开 URL 仍需在部署完成后回填。
- 两个 URL 都必须可公网访问，并使用 HTTPS。
- 支持页应包含真实可联系邮箱。
- 如果后续隐私政策、支持邮箱或 URL 变更，请重新生成部署包并重新上传。
