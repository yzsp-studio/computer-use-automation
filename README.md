<div align="center">

# 🎬 computer-use-automation

## 0-1000 坐标 + 先看后点，桌面自动化不瞎猜
## Stop clicking blind: screenshot first, then automate any Windows app

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

让 AI 真正坐到你电脑前操作 Windows 桌面软件：打开应用、点菜单、填对话框、处理文件选择器、改系统设置，全程不需要你手动代劳。它把整块屏幕映射成 0-1000 的归一化坐标，动手前先截屏确认，动完再验证结果，而不是凭猜测乱点。安全的点击可以批量放进一次调用里跑完，例如一次循环填 12 个单元格再拍一张验证截图。遇到登录、验证码、MFA 这类只能由人完成的步骤，会明确把控制权交还给你，回来后重新观察屏幕再继续。

### ✨ 能做什么

- 列出已安装应用并启动：先用 list_apps() 拿真实 Start 菜单名，再用精确名称 launch_app，路径、URI、大小写不符一律拒绝
- 全屏 0-1000 归一化坐标：从截图上按比例读位置，永不传裸像素
- 单次调用批量操作：一个循环跑完 12 个单元格，最后只拍一张验证截图
- 覆盖点击、双击、三击、右键、悬停、拖拽、滚动、输入、快捷键与剪贴板等桌面动作
- 登录 / 验证码 / MFA 强制用户接管，交还后重新观察整个桌面再推导新坐标
- 用文件系统回读校验结果：确认 report.xlsx 真的存在及文件大小，而不是只看窗口

### 📦 包含的技能

- `computer-use-automation` —— 见 [`computer-use-automation/SKILL.md`](computer-use-automation/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/computer-use-automation.git
cp -r computer-use-automation/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Drives real Windows desktop apps instead of describing the steps: launch them, click menus, fill dialogs, handle file pickers, change system settings. The whole screen maps to a normalized 0-1000 grid, and the agent screenshots before acting and verifies after, rather than clicking from memory. Safe actions batch into a single call, such as filling twelve cells in one loop and taking one verification frame. Sign-in, CAPTCHA and MFA hand control back to you, and the screen is re-observed after control returns. Saves are confirmed by reading the file back, not by trusting the dialog.

### ✨ What it does

- Discover and launch apps by exact Start-menu name; paths, URIs and partial names are refused
- Normalized 0-1000 whole-screen coordinates read off a screenshot, never raw pixels
- Batch safe actions in one call: fill twelve cells, then take a single verification frame
- Click, double-click, triple-click, right-click, hover, drag, scroll, type, hotkeys and clipboard helpers
- Mandatory user takeover for sign-in, CAPTCHA and MFA, with re-observation after control returns
- Verify saves by reading the file system back, including existence and size

### 📦 Skills included

- `computer-use-automation` — [`computer-use-automation/SKILL.md`](computer-use-automation/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/computer-use-automation.git
cp -r computer-use-automation/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
