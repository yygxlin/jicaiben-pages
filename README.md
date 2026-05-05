# 记彩本静态页面

这个目录用于部署 App Store 需要的公开网页。

当前页面已包含 iCloud 云同步、StoreKit 内购/订阅状态、本地数据不上传业务服务器等说明；App 内隐私政策和用户协议入口会加载这里的在线页面。协议/隐私正文以本目录为唯一维护源，不要在 iOS App 里再维护本地长文本。PRO 功能文案统一写“多账本切换、关注分类、iCloud 云同步和多设备恢复”。

推荐 GitHub Pages URL：

- `https://<domain>/privacy/`
- `https://<domain>/support/`
- `https://<domain>/terms/`

App Store Connect 可填写：

- Privacy Policy URL: `/privacy/`
- Support URL: `/support/`

如果使用 GitHub 项目页且没有绑定自定义域名，实际路径通常会带仓库名，例如：

- `https://<username>.github.io/<repo>/privacy/`
- `https://<username>.github.io/<repo>/support/`
