---
title: Git的常用命令
date: 2024-2-6
tags: 计算机、常用工具
categories: 学习笔记
keywords: Git
description: Git是一个分布式版本控制系统，用于跟踪文件和项目的变化。它最初由Linus Torvalds创建，用于管理Linux内核的开发。Git的主要目标是提供一种高效、灵活、可靠的版本控制系统，能够处理从小型项目到大型项目的所有需求。
cover: /imgs/git.gif
---

# 什么是Git

Git是一个分布式版本控制系统，用于跟踪文件和项目的变化。它最初由Linus Torvalds创建，用于管理Linux内核的开发。Git的主要目标是提供一种高效、灵活、可靠的版本控制系统，能够处理从小型项目到大型项目的所有需求。
# 我们为什么要使用Git
作为计算机行业的人员，会使用Git做版本控制是一件很好的事情，节省了很多不必要的麻烦。
# Git的常用命令
## Git初始设置

```bash
git config --global user.name '自己想起的名字'
git config --global user.email '邮箱'
```
## Git常用命令
```bash
git init                                        #初始化Git仓库
git add .                                       #添加文件到暂存区
git add README.md                               #添加一份仓库说明文件
git commit -m "这里填写提交记录"                  #提交记录
git clone https://xxx.xxx/xxx.git               #拉取仓库内容
git pull <master>                               #推送到远程库
git remote add master <remote_url>              #绑定远程库地址
git log [--online] [--graph] 显示提交过的版本信息
```
## Git分支管理
```bash
git branch xxx                                  #创建新的分支
git branch -r                                   #查看本地的所有分支
git branch -a                                   #查看所有的分支
git branch -d xxx                               #删除分支
git branch -m old new                           #为分支改名
git checkout <branch_name>                      #切换分支
```

