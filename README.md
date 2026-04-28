# 咳语录 · The Analects of Keke

> 事到如今，咳的罪恶还数得过来吗？

本仓库收录MC传奇人物 **咳**（Keke）的经典语录，由群友整理记录

## 简介

咳是一位自称"弱小可怜无助"、实则惊人为惊人的老人，尤擅**美式**与**大地**，是为"福大第一魔剑士 / 第一贤者 / 兼职十多个第一"。其语录主要特征为：

## 文件

- [`事到如今，咳的罪恶还数得过来吗.docx`](./事到如今，咳的罪恶还数得过来吗.docx) — 完整语录原文

## 投稿

群友如果有发现咳好玩的语录请直接更新文档后推送到远端仓库。

## 傻瓜式更新推送教程

**前置条件**：电脑已装 [Git](https://git-scm.com/downloads)，有 GitHub 账号，且已被加为本仓库协作者（Collaborator）。

### 第一次用（只做一次）

打开终端（Windows 用 Git Bash，Mac/Linux 用 Terminal），粘贴运行：

```bash
# 1. 配置你的身份（换成你自己的名字和邮箱）
git config --global user.name "你的名字"
git config --global user.email "你的邮箱@example.com"

# 2. 把仓库克隆到本地（会在当前目录下生成 The_Analects_of_Keke 文件夹）
git clone https://github.com/qilianmountain/The_Analects_of_Keke.git
cd The_Analects_of_Keke
```

### 每次更新语录（重复执行）

1. **先拉取最新版本**，避免和别人冲突：

   ```bash
   cd The_Analects_of_Keke
   git pull
   ```

2. **用 Word 打开 `事到如今，咳的罪恶还数得过来吗.docx`**，加上新语录，保存关闭。

3. **提交并推送**：

   ```bash
   git add "事到如今，咳的罪恶还数得过来吗.docx"
   git commit -m "更新语录：简单写一句你加了啥"
   git push
   ```

4. 第一次 push 时会弹出登录窗口，用 GitHub 账号登录授权即可，以后就不用再登了。

### 常见问题

- **push 被拒绝（rejected）**：说明别人先推送了，先跑 `git pull` 合并再 `git push`。
- **docx 打不开 / 显示被占用**：Word 还开着，关掉再 `git add`。
- **不知道自己改了啥**：`git status` 看改动文件，`git diff` 看文本改动（docx 是二进制，看不到内容差异，这正常）。

