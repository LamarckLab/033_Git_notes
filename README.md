# 🧭 Git 常用命令与快捷键笔记  
—— *LamarckLab* · 2025.11.2  

![](https://img.shields.io/badge/Tool-Git-blue?style=flat-square)
![](https://img.shields.io/badge/Terminal-GitBash-green?style=flat-square)
![](https://img.shields.io/badge/OS-Windows10-lightgrey?style=flat-square)
![](https://img.shields.io/badge/Status-Complete-success?style=flat-square)

---

## 🧩 Overview
本仓库用于记录 **Git 常用命令** 与 **Git Bash 常用快捷键**，帮助快速掌握版本控制的核心操作与常见终端技巧。

---

## 📁 Repository Structure
| 文件名 | 说明 |
| :------ | :---- |
| `Commands.md` | 收录 Git 的常用命令（配置、初始化、推送等） |
| `HotKeys.md` | 记录 Git Bash 终端的常用快捷键 |
| `README.md` | 当前说明文档 |

---

## ⚙️ Environment Configuration

```bash
# 检查 Git 版本
git -v

# 配置全局用户名和邮箱
git config --global user.name "LamarckLab"
git config --global user.email "704021302@qq.com"

# （可选）配置代理（Clash默认7890，Clash Verge默认7897）
git config --global http.proxy  http://127.0.0.1:7897
git config --global https.proxy http://127.0.0.1:7897

# 查看全局配置列表
git config --global --list
