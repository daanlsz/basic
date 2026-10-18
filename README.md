# 📌我发布了一条关于GitHub入门者的小指南
Github study
***

## 📌 学习路径总览



```
Git 基础 → GitHub 入门 → 核心工作流 → 协作与开源 → 个人品牌 → 实战项目
```



***

## 🟢 第一阶段：Git 基础

> 目标：理解 Git 的核心概念，能本地管理代码版本。

### 1.1 什么是 Git / GitHub



| 概念                | 说明                             |
| ----------------- | ------------------------------ |
| **Git**           | 分布式版本控制系统，本地运行，负责记录代码历史        |
| **GitHub**        | 基于 Git 的代码托管平台，提供云端仓库、协作、社区等功能 |
| **仓库 Repository** | 存放项目文件与历史记录的地方                 |
| **Commit（提交）**    | 一次代码变更的快照                      |
| **Branch（分支）**    | 独立开发的代码线                       |
| **Clone（克隆）**     | 把远程仓库完整复制到本地                   |

### 本地基础命令（重要）



```
# 初始化仓库
git init

# 查看状态
git status

# 添加到暂存区
git add <文件名>          # 单个文件
git add .                 # 所有变更

# 提交
git commit -m "提交说明"

# 查看历史
git log --oneline --graph

# 查看改动
git diff
```

### 练习



* [ ] 本地创建仓库，做 5 次以上 commit

* [ ] 练习 `add / commit / status / log` 常用命令

* [ ] 学会用 `git checkout -- <文件>` 与 `git reset` 撤销改动



***

## 🟢 第二阶段：GitHub 入门

> 目标：注册账号，连接远程仓库，掌握 push /pull/clone。

### &#x20;连接远程仓库



```
# 关联远程仓库
git remote add origin <仓库地址>

# 推送本地到远程
git push -u origin main

# 拉取远程到本地
git pull

# 克隆远程仓库
git clone <仓库地址>
```
