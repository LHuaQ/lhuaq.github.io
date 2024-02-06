---
title: vim
date: 2024-02-06 23:15:00
tags: 计算机、常用工具
keyword: Vim
cover: /imgs/vim.png
---

# Vim是什么

Vim（Vi Improved的缩写）是一款高度可定制的文本编辑器，是Unix和类Unix系统中常用的文本编辑工具之一。它是Vi编辑器的改进版本，提供了许多额外的功能和改进，使得用户能够更高效地编辑文本文件。

## Vim的特点包括：

1. **模式切换：** Vim具有不同的编辑模式，包括普通模式、插入模式、可视模式等。在不同的模式下，键盘的操作会有不同的效果。
2. **快速移动和编辑：** Vim提供了许多快速移动和编辑文本的命令，可以通过键盘快捷键完成大量的操作，而无需使用鼠标。
3. **插件支持：** Vim支持丰富的插件，用户可以根据自己的需要安装和配置插件，以扩展编辑器的功能。
4. **脚本语言：** Vim脚本语言允许用户编写脚本来自定义编辑器的行为，使其更符合个人需求。
5. **跨平台：** Vim可以在多种操作系统上运行，包括Unix、Linux、Windows等。

### 普通模式 (Normal Mode):

1. **移动光标:**
   
    - `h` - 左移一个字符
    - `j` - 下移一行
    - `k` - 上移一行
    - `l` - 右移一个字符
    - `0` - 移动到行首
    - `$` - 移动到行尾
    - `gg` - 移动到文件开头
    - `G` - 移动到文件末尾
2. **文本操作:**
   
    - `x` - 删除当前字符
    - `dd` - 删除当前行
    - `yy` - 复制当前行
    - `p` - 粘贴
3. **撤销和重做:**
   
    - `u` - 撤销
    - `Ctrl + r` - 重做
4. **查找和替换:**
   
    - `/pattern` - 向前搜索
    - `?pattern` - 向后搜索
    - `:s/pattern/replacement/g` - 替换（一行）
    - `:%s/pattern/replacement/g` - 替换（整个文件）
5. **保存和退出:**
   
    - `:w` - 保存
    - `:q` - 退出
    - `:wq` - 保存并退出
    - `:q!` - 强制退出，不保存修改
6. **分割窗口:**
   
    - `:split` - 水平分割
    - `:vsplit` - 垂直分割
    - `Ctrl + w + w` - 在分割窗口之间切换

### 插入模式 (Insert Mode):

1. 进入插入模式：
   
    - `i` - 在光标前插入
    - `I` - 在行首插入
    - `a` - 在光标后插入
    - `A` - 在行尾插入
    - `o` - 在当前行下方插入新行
    - `O` - 在当前行上方插入新行
2. 退出插入模式：
   
    - `Esc` - 退出插入模式

### 可视模式 (Visual Mode):

1. 进入可视模式：
   
    - `v` - 逐字符选择
    - `V` - 逐行选择
    - `Ctrl + v` - 块选择
2. 在可视模式中操作：
   
    - 使用方向键或`h`, `j`, `k`, `l`来选择文本
    - 操作选中的文本，如删除、复制、替换等