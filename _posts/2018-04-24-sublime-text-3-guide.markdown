---
layout: post
title: "Sublime Text 3 guide"
date:   2018-04-24 18:05:25 +0800
comments: true
categories: "Sublime Text 3"
---
***
# 按键符号
* Command `⌘`
* Shift `⇧`
* Option `⌥`
* Control `⌃`
* Caps Lock `⇪`
* Fn

# 选择
## 列选择

 * 鼠标
	- 添加：`⌘`
	- 取消：`⇧`+`⌘`
 * 键盘
 	- 添加：`^`+`⇧`+`Up/Down`

## 行选择
- `⌘`+`L` (line)

## 多选
- 多选：`⌘`+`^`+`Left`
- 撤销选择: `⌘`+`U`
- 选择块的多行：`⌘`+`⇧`+`L` (line)
- 选择下一个词：`⌘`+`D` (down)
- 跳过下一个词:`⌘`+`K`，`⌘`+`D` (skip)
- 选择全部：`⌃`+`⌘`+`G` (global)
- 取消多选：`Esc`
- 选择当前位置到开头：`⌘`+`⇧`+`Up`
- 选择当前位置到末尾：`⌘`+`⇧`+`Down`

## 自动填充
- 切换填充项：`^`+`Space`
- Tab填充：`Tab`
- 插入Tab：`⇧`+`Tab`

## 其他选择
- 选择词：`⌥`+`⇧`+`方向键`
- 选择括号：`^`+`⇧`+`M`
- 将选择扩大到缩进：`⌘`+`⇧`+`J`
- 扩大选择范围：`⌘`+`⇧`+`Space`

## 交换
- 交换两个字母：`^`+`T`
- 交换行：`⌘`+`^`+`Up/Down`

# 搜索与替换
## 搜索
- 单文件搜索：`⌘`+`F` (find)
- 查找下一个：`⌘`+`G`
- 查找上一个：`⇧`+`Enter`
- 查找全部： `⌥`+`Enter`
- 切换正则表达式：`⌘`+`⌥`+`R` (regular)
- 切换大小写敏感：`⌘`+`⌥`+`C` (case)
- 切换完全匹配：`⌘`+`⌥`+`W` (whole)
- 单次搜索：`⌘`+`I` (incremental)
- 快速搜索：`⌘`+`⌥`+`G`
- 快速搜索全部：`⌘`+`^`+`G`
- 使用选择作为搜索：`⌘`+`E`


Show content：显示内容

Use buffer：搜索结果在新Tab打开

## 替换
- 打开替换面板：`⌘`+`⌥`+`F` (find)
- 替换下一个：`⌘`+`⌥`+`E`
- 替换全部：`^`+`⌥`+`Enter`
- 使用选择作为替换：`⌘`+`⇧`+`E`

# 跳转
- 跳转到文件：`⌘`+`P`
- 跳转到函数：`⌘`+`R`，`@`
- 跳转到当前工程的函数：`⌘`+`R`
- 跳转到定义：`⌘`+`⌥`+`Down`
- 跳转到行： `^`+`G`，`:`
- 跳转到单词：`#`
- 跳转到开头：`⌘`+`Up`
- 跳转到首行：`⌘`+`Down`
- 跳转到行首：`⌘`+`Left`
- 跳转到行末：`⌘`+`Right`sss
- 向后跳转：`^`+`-`
- 向前跳转：`^`+`⇧`+`-`
- 跳转到块：`^`+`M`

# 滚动
- 滚动到选择：`^`+`L`

# 命令面板
- 打开命令面板：`⌘`+`⇧`+`P`

# 界面
## 布局
- 设置N个列：`⌘`+`⌥`+`Number`
- 设置N个行：`⌘`+`⌥`+`⇧`+`Number`
- 网格：`⌘`+`⌥`+`5`

## 组
**组是布局的集合**
- 分组：多个窗格的集合
- 新分组：`⌘`+`K`，`⌘`+`⇧`+`Up`
- 移动文件到新分组：`⌘`+`K`，`⌘`+`Up`
- 关闭分组：`⌘`+`K`，`⌘`+`Down`
- 上一个分组：`⌘`+`K`，`⌘`+`Left`
- 下一个分组：`⌘`+`K`，`⌘`+`Right`
- 移动文件到上一个分组：`⌘`+`K`，`⌘`+`⇧`+`Left`
- 移动文件到下一个分组：`⌘`+`K`，`⌘`+`⇧`+`Right`

## 窗格
- 跳转到第N个窗格：`⌘`+`Number`

## 全屏
- 进入全屏：`⌘`+`^`+`F`
- 进入无干扰全屏：`⌘`+`^`+`⇧`+`F`

## 侧边栏
- 显示/隐藏侧边栏：`⌘`+`K`，`⌘`+`B`

# 编辑
## 行
- 复制行：`⌘`+`⇧`+`D` (duplicate)
- 删除行：`^`+`⇧`+`K`
- 合并行：`⌘`+`J` (join)
- 添加缩进：`⌘`+`]`
- 删除缩进：`⌘`+`[`
- 删除当前到行首：`⌘`+`Delete`
- 删除当前到行末：`^`+`K`

## 注释
- 添加/取消注释：`⌘`+`/`

## 代码折叠
- 全部折叠：`⌘`+`⌥`+`[`
- 全部展开：`⌘`+`⌥`+`]`
- 折叠N层：`⌘`+`K`，`⌘`+`Number`
- 折叠标签属性：`⌘`+`K`，`⌘`+`T`

## 大小写转换
- 转换为大写：`⌘`+`K`，`⌘`+`U` (upper)
- 转换为小写：`⌘`+`K`，`⌘`+`L` (lower)

## 换行
- 段折叠：`⌘`+`⌥`+`Q`

## 排序
- 行排序：`Fn`+`F5`
- 行排序(大小写敏感)：`Fn`+`^`+`F5`

## Emoji与符号
- `⌘`+`^`+`Spa`

# 标记
**标记用于在当前编辑窗口的2个位置快速切换**
- 切换标记：`⌘`+`K`，`⌘`+`X`
- 删除到标记：`⌘`+`K`，`⌘`+`W`
- 清除标记：`⌘`+`K`，`⌘`+`G`
- 设置标记：`⌘`+`K`，`⌘`+`Space`
- 选择到标记：`⌘`+`K`，`⌘`+`A`

# 书签
**书签用于在当前编辑窗口的多个位置快速切换**
- 添加/清除书签：`^`+`⇧`+`R`
- 下一个书签：`^`+`R`
- 上一个书签：`Fn`+`F2`
- 清除所有书签：`Fn`+`⌘`+`⇧`+`F2`

# 宏
**宏指一系列操作的集合**
- 录制宏：`^`+`Q`
- 播放宏：`^`+`⇧`+`Q`

# 编译
- 编译：`⌘`+`B` (build)
- 编译于：`⌘`+`⇧`+`B` (build)

# 工程
**工程是不同文件夹与文件的集合**

# 工作区
**工作区保存了当前Sublime Text的状态**