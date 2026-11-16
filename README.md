# Daymark 每日探索打卡

一个无需构建工具的静态网站，用来记录每日探索海外网站的打卡情况。

## 使用

直接在浏览器中打开 `index.html`。打卡记录和自定义网站保存在当前浏览器的 `localStorage` 中，不会上传到服务器。更换设备或清除浏览器数据后，记录不会自动同步。

## 发布到 GitHub Pages

仓库包含 GitHub Pages 工作流。推送到 `main` 分支后，GitHub Actions 会将仓库根目录发布到 Pages。首次使用时，在仓库的 **Settings → Pages → Build and deployment** 中选择 **GitHub Actions**。


