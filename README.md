# ghfast

GitHub 全资源极速加速工具，支持 GitHub 仓库、Raw 文件、Release 附件及源码压缩包的快速访问。

## ✨ 功能特性

- Git 仓库克隆加速
- Git 仓库推送加速
- Release 附件下载加速
- Raw 文件访问加速
- 仓库源码 ZIP 下载加速
- 支持完整 GitHub 链接直接加速
- 支持公开仓库及 Token 鉴权访问
- 无需安装客户端，直接替换域名即可使用

## 🌐 服务地址

```text
https://gh.goghx.top
```

## 使用说明 · 命令示例

| 场景 | 用法 |
|---|---|
| Git 克隆 | `git clone https://gh.goghx.top/user/repo.git` |
| Git 推送 | `git push https://gh.goghx.top/user/repo.git` |
| Release 附件 | `curl -L -O https://gh.goghx.top/user/repo/releases/download/v1.0/app.zip` |
| 源码压缩包 | `curl -L -O https://gh.goghx.top/user/repo/archive/refs/heads/main.zip` |
| Raw 文件 | `curl -L https://gh.goghx.top/user/repo/raw/main/script.sh \| bash` |
| 完整链接直贴 | `https://gh.goghx.top/https://github.com/user/repo/releases/download/v1.0/app.zip` |
| Git 全局加速 | `git config --global url."https://gh.goghx.top/".insteadOf "https://github.com/"` |
| 私有仓库 | `git clone https://TOKEN@gh.goghx.top/user/repo.git` |
