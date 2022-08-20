官方提供了帮助文档：https://publish.obsidian.md/help/Index

分享Common CSS Hacks（小技巧）：https://forum.obsidian.md/c/share-showcase/9

# 1 front matter

可以在文件的最开始设置，目前支持tags、aliases，分别在标签和引用的时候可以看到

```
---
date: {{date:YYYY-MM-DD HH:mm}}
tags:
- tag
aliases: 
- alias
---
```



# 2 快捷键设置-与Typora保持一致

**高频快捷键**：

链接：Ctrl+Shift+L
内部链接：Ctrl+L
嵌入内容：Ctrl+Shift+I
打开设置：Ctrl+Shift+，
返回：Alt+<-
前进：Alt+->
左侧面板：Ctrl+<-
右侧面板：Ctrl+->
关闭当前面板：Ctrl+W
快速打开：Ctrl+O
命令面板：Ctrl+P
插入模板：Alt+T
粗体：Ctrl+B
高亮：Ctrl+H
斜体：Ctrl+I
删除段落：Ctrl+D
所有文件中搜索：Ctrl+Shift+F
删除线：Ctrl+`
有序列表：`Ctrl+Shift+[`
无序列表：`Ctrl+Shift+]`
新建笔记：Ctrl+N
引用：Ctrl+Q
上下行互换：Alt+上键/下键
当前笔记查找：Ctrl+F
当前笔记查找并替换：Ctrl+R
新面板中新建笔记：Ctrl+Shift+N
折叠标题：Ctrl+Shift+ J
展开标题：Ctrl+ J
快速浏览：Alt + E

其他快捷键：
关闭所有其他面板：Ctrl+Shift+W
幻灯片：Ctrl+F5
插入当前时间：Ctrl+Shift+T
插入当前日期：Ctrl+Shift+D
切换编辑/预览：Ctrl+E
切换待办标签状态：Ctrl+Enter

嵌入内容：可以嵌入文档、视频、音频、表格等
插入链接：例子：`[百度](www.baidu.com)`
插入内部链接：例子：`[测试笔记](测试笔记.md)`
出链：打开当前笔记的出链面板
出链：显示出链标签页
反向链接：打开当前笔记的反向链接面板
反向链接：显示反向链接标签页
反向链接：在页面中显示反向链接面板


# 3 链接、嵌入引用

自定义快捷键：

```
链接：Ctrl+Shift+L
内部链接：Ctrl+L
嵌入内容：Ctrl+Shift+I
```

Obsidian 支持多种「超链接语法」，这些功能也是「现代笔记管理」的必备技能。几种常见的语法如下：

- 双向链接：`[[Note Name]]`
- 标题引用：`[[Note Name #header]]`
- 别名引用：`[[Note Name |Alias]]`
- 嵌入引用：`！[[Note Name]]` 嵌入md、pdf、音频、视频
- 块引用：`[[Note Name ^]]`
- 脚注：^[脚注内容]



# 4 文件与链接

新建笔记的存放位置：当前打开文件所在的文件夹

内部链接类型：插入基于当前笔记的相对路径

使用Wiki链接：关闭

新建附件的默认位置：当前文件夹下指定的子文件

子文件夹名称：images

**Obsidian和Typora互通**：通过上面的设置，使用Typora打开也是没有问题的



# 5 主题

主题一：**blue topaz**



# 6 核心插件和三方插件

**核心插件**：	

除了ZK卡片和漫游笔记，其他都可以打开

**三方插件**：

calendar

icon：给文件夹或文件加上Emoji表情

```
地址：https://github.com/FlorianWoelki/obsidian-icon-folder
Twemoji for Emojis as folders：
    Right-click the folder
    Click Change icon
    Open your OS-specific emoji dialog
    	Mac OSX: Control + Command + Space
    	Windows: Windows + ;
    Select the option Use twemoji emoji
```

number-headings-obsidian：给标题加序号

obsidian-day-planner

obsidian-hotkeys-for-specific-files

obsidian-icon-folder

obsidian-proxy-github

obsidian-remember-cursor-position

table-editor：[github]ganesshkumar/obsidian-table-editor

typora-keybanding



Code block enhancer：代码块增强，显示行号

Collapse ALL：折叠所有文件夹

Core search Assistant：正则搜索

Easy typing：中英文之间添加空格，英文首字母大写，标点与文本间智能空格等

File explorer Note Count ：统计文件数量

Image toolkit: 插入的图片放大缩小

Open all type files and highlight：可以打开所有的类型文件 

Recent files：显示最近打开文件，右键显示文件位置

Show current file path

quick-explorer：快速浏览，快捷键Alt + e



# 7 日记

简单模板：

```
**创建时间：**

**项目：**

**代号：**

**事件：**

**工作进度：**

**时间：**

**完成时间：**


```



# 8 模板

简单模板：

````
**创建时间：** {{date:YYY-MM-DD}} {{time:HH:MM:SS}}
**主题：**
**议题：**
**参会人员：**

**当前任务：**
- [ ] 任务一：
- [ ] 任务二：

**工作列表：**

<font color=red>紧急问题：</font>

遗留问题：
```text
请补充问题

```

以上是会议模板，如有更新请通知同步！

````



# 9 导出

右上角可以到处为PDF，可以使用Typora导出PDF带有标题索引



# 10 标签和嵌套标签

标签示例： #标签名

嵌套标签：#标签名/嵌套标签名



# 11 其他设置

折叠标题、折叠缩进

template目录：存放模板和日志模板

dailynote目录：存放日记

images目录：存放图片及其他新增附件



文件都自动保存有快照，可以选择恢复
