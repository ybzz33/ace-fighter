---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: fdad55838e3a77a4c4ef6f10b60dfb55_4c959edda5d011f1903b525400f8a581
    ReservedCode1: /XpVwQHYUnlTeqC9mryRS/vbm9uRWXNMbV8/z9KTZnrQFG1VRl7MATiZCEKz5UGLCorI78OsaqYAUq0h6IteR3/EhEfPf6BEv1wYCELBCuWRL1Vp92GJLN2nwGWJbfM2K4cEV7ya+RhRlmxR2JWniz9Us+zjnIyXvM0ngif3ggavjhYKknUXBdZPY+I=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: fdad55838e3a77a4c4ef6f10b60dfb55_4c959edda5d011f1903b525400f8a581
    ReservedCode2: /XpVwQHYUnlTeqC9mryRS/vbm9uRWXNMbV8/z9KTZnrQFG1VRl7MATiZCEKz5UGLCorI78OsaqYAUq0h6IteR3/EhEfPf6BEv1wYCELBCuWRL1Vp92GJLN2nwGWJbfM2K4cEV7ya+RhRlmxR2JWniz9Us+zjnIyXvM0ngif3ggavjhYKknUXBdZPY+I=
---

# ✈ 毅博老师 · 飞机大战（Ace Fighter）

一款画面精美、带打击音效的纵版飞机大战小游戏，专为课堂演示打造。单文件 HTML5 Canvas 实现，**全部资源（画面、音效、背景音乐）均为程序化生成，无需任何外部文件**，双击即可游玩，也可一键部署到 GitHub Pages 在线分享。

---

## 🎮 玩法与操作

| 操作 | 按键 |
|---|---|
| 移动 | 方向键 / WASD / 鼠标（鼠标跟随） |
| 射击 | 空格（可按住连射）/ 鼠标左键 |
| 技能1 能量护盾 | 数字键 `1`（5 秒无敌，触碰即摧毁敌机） |
| 技能2 全屏歼灭 | 数字键 `2`（清空敌弹、全屏重创） |
| 技能3 火力全开 | 数字键 `3`（8 秒多弹道高速连射） |
| 暂停 / 静音 | `P` / `M` |
| 开始 / 重开 | `Enter` 或 空格 |

## ⭐ 游戏特性

- **标题"毅博老师"**：主菜单与游戏内 HUD 均展示"毅博老师 · 飞机大战"
- **玩家血量**：100 HP 血条（实时渐变显示），受击扣血、碰撞重伤、击毁坠落
- **三大技能**：护盾 / 全屏轰炸 / 火力全开，带冷却时间与 HUD 技能栏
- **打击音效**：射击、命中、爆炸、受击、技能、升级、Boss 登场、游戏结束等十余种音效，均由 Web Audio 实时合成，并配有轻量背景音乐
- **画面表现**：多层视差星空、星云、尾焰粒子、爆炸粒子与冲击环、屏幕震动、Boss 战
- **敌人体系**：4 种敌机（普通/快速/轰炸/坦克）+ 偶数波 Boss，波次与难度递增
- **局外系统**：连击加分、掉落物（回血/火力强化）、历史最高分本地存档

## 🚀 本地运行

直接双击 `index.html`，或拖入浏览器打开即可，无需安装任何环境。

## ☁️ 部署到 GitHub Pages（在线游玩）

### 方式一：网页直接上传（无需命令行，推荐）

1. 在 GitHub 新建一个仓库（Repository），名称随意，如 `ace-fighter`（公开 Public）；
2. 进入仓库页 → 点击 **Add file → Upload files**；
3. 把本目录的 `index.html` 和 `README.md` 拖入上传，Commit；
4. 进入 **Settings → Pages**，在 "Branch" 处选择 `main` 分支、`/ (root)` 目录，点 Save；
5. 等 1~2 分钟，即可通过 `https://<你的用户名>.github.io/<仓库名>/` 在线游玩。

### 方式二：Git 命令行

```bash
# 在项目目录内
git init
git add index.html README.md
git commit -m "飞机大战 Ace Fighter"
git branch -M main
git remote add origin https://github.com/<你的用户名>/<仓库名>.git
git push -u origin main
# 然后在仓库 Settings → Pages 中启用 main 分支的 Pages 即可
```

> 部署完成后线上链接 1~2 分钟内生效，如浏览器有缓存可强制刷新（Ctrl+F5）查看最新版本。

## 📁 文件说明

| 文件 | 说明 |
|---|---|
| `index.html` | 游戏本体（单文件，含全部代码与资源） |
| `README.md` | 本说明文档 |

## 🛠 技术栈

HTML5 Canvas 2D · 原生 JavaScript · Web Audio API（音效合成）· CSS（居中响应式布局）

---

© 2026 毅博老师课堂演示项目 · Made with ❤
*（内容由AI生成，仅供参考）*
