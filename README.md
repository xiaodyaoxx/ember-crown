# 余烬王冠 · 勇者文字冒险

**在线游玩：https://xiaodyaoxx.github.io/ember-crown/**

一个单文件网页文字冒险游戏（无后端、无外部依赖、支持手机）。

## 玩法

- 鼠标点击选项，或按数字键 1–9；点击正文可跳过逐字显示
- 战斗：普通攻击 / 重斩（7 MP）/ 治疗术（9 MP，Lv3 解锁）/ 火球术（10 MP，Lv5 解锁）/ 道具 / 逃跑（Boss 不能逃）
- 倒下不会结束游戏，但会损失一半金币并在晨曦村醒来
- 三种结局：黎明 / 灰烬 / 独行
- 进度自动保存在浏览器 localStorage

## 本地运行

直接用浏览器打开 `index.html` 即可。

## 部署说明

本站托管在 GitHub Pages（仓库 Settings → Pages，Source = Deploy from a branch，分支 main、目录 /）。
修改 `index.html` 并提交后，约 1 分钟自动生效。
