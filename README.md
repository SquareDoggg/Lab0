# Lab0: Git

本仓库用于完成复旦大学《计算机系统基础（2026年秋季学期）》Lab0实验。

## 实验目的

本实验主要用于熟悉Git和GitHub的基本使用方法，包括：

- Git仓库的克隆与基本配置
- 文件修改、暂存与提交
- 分支的创建与切换
- 不同分支上的独立修改
- 分支合并与冲突处理
- 将本地提交推送至GitHub
- 使用规范的Commit Message记录修改

## 实验内容

本次实验主要完成以下任务：

1. 使用课程提供的模板仓库建立个人仓库。
2. 修改`main.c`中的TODO内容并进行提交。
3. 创建`feature`分支，并分别在`feature`和`main`分支修改`main.c`。
4. 合并`feature`分支到`main`分支。
5. 人为制造并解决merge conflict。
6. 将实验报告提交到`main`分支。
7. 将最终结果推送至GitHub。

## 仓库结构

```text
Lab0/
├── .github/
│   └── workflows/
├── coroutine/
│   ├── main.c
│   ├── context.c
│   ├── context.h
│   ├── context_asm.S
│   └── Makefile
├── README.md
└── Lab0_Report.pdf
