# 余烬王冠 · 勇者文字冒险

一个单文件网页文字冒险游戏（无后端、无外部依赖）。

## 部署到 GitHub Pages

1. 登录 GitHub，右上角 + → New repository
2. Repository name 填 `ember-crown`，选 **Public**，不要勾 README → Create repository
3. 在新仓库页点 **uploading an existing file**，把本文件夹里的 `index.html` 拖进去 → Commit changes
4. 仓库 Settings → 左侧 Pages → Source 选 **Deploy from a branch**
   → Branch 选 `main`，目录选 `/(root)` → Save
5. 等 1–2 分钟，访问 `https://<你的用户名>.github.io/ember-crown/`

## 注意

- 文件名必须保持 `index.html`，否则根路径会 404
- 存档存在浏览器 localStorage 里，按域名隔离；换域名进度不通用
- 手机上可「添加到主屏幕」，像 App 一样全屏运行
