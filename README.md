# 课序安卓测试版

课序用于查看学习通中未完成的作业，隐藏已结课课程，并支持在应用内打开原作业页面。登录会话在本机保存；平台会话失效后需要重新登录。

此仓库仅发布公开安装包、版本信息、校验文件和更新说明，不保存学习通账号或登录数据。

## 安装与更新

1. 从 [最新发布](https://github.com/leilei0620/courseflow-updates/releases/latest) 下载 APK，在 Android 8.0 及以上手机安装。
2. 已安装旧版的用户请直接覆盖安装，不要先卸载。
3. 安装具备更新功能的版本后，打开课序会自动检查新版本，点击“立即更新”下载。
4. 下载完成并通过校验后，按安卓系统提示确认安装。首次操作可能需要允许课序安装应用。

更新检查与下载依赖联网及 GitHub 可访问性，部分网络下可能较慢或暂时无法连接。

## 发布文件

- `courseflow-*.apk`：安卓安装包。
- `latest.json`：版本号、更新内容、安装包地址、大小和 SHA-256 校验值。
- `SHA256SUMS.txt`：安装包校验值。
- `release-notes.md`：本次更新说明。

固定更新地址：[latest.json](https://github.com/leilei0620/courseflow-updates/releases/latest/download/latest.json)。
