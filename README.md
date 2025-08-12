# MoonTV Cordova Android TV App

本项目将 MoonTV 网站打包为 Android TV APK，并通过 GitHub Actions 自动构建与发布。

## 使用方法

1. Fork 或 Clone 本仓库
2. 修改 `www/index.html` 中的远程网址为你的 MoonTV 地址
3. 提交代码并推送 tag
   ```bash
   git tag v1.0.0
   git push origin v1.0.0
   ```
4. 等待 GitHub Actions 完成构建，在 Release 页面下载 APK
