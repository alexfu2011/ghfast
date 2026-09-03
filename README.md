# ghfast • 长期有效

GitHub 全资源极速加速工具，支持 GitHub 仓库、Raw 文件、Release 附件及源码压缩包的快速访问。

## ✨ 功能特性

> 使用 `gh.goghx.top` 加速访问 GitHub 仓库、Raw 文件、Release 附件及源码压缩包。

## ✨ 使用方法

将 GitHub 原始链接中的域名替换为 `gh.goghx.top` 即可。

例如，原始链接：

```text
https://github.com/user/repo.git
```

替换为：

```text
https://gh.goghx.top/user/repo.git
```

## ✨ 使用场景

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
