# SYLVIE.RS

一个仅使用原生 HTML 和 CSS 的最小个人主页。页面无构建步骤、外部依赖或 CDN。

## 本地预览

最简单的方式是直接用浏览器打开 `index.html`。

也可以在项目目录启动静态文件服务器：

```powershell
cd D:\Code\web
python -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库，将本目录中的 `index.html` 和 `README.md` 提交并推送到仓库默认分支。
2. 打开仓库的 **Settings → Pages**。
3. 在 **Build and deployment** 中选择 **Deploy from a branch**。
4. 选择默认分支和根目录 `/ (root)`，然后保存。
5. 等待 GitHub Pages 发布完成，页面会提供站点地址。

如需绑定 `sylvie.rs`，在 Pages 设置的 **Custom domain** 中填写域名，并按照 GitHub 给出的记录配置域名 DNS。建议在 DNS 生效后启用 **Enforce HTTPS**。

## 修改 GitHub 链接

部署前，将 `index.html` 中的 `https://github.com/` 替换成你的 GitHub 个人主页地址。
