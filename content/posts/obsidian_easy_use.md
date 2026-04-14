# 教程网站

[markdown常用语法](https://markdown.com.cn/editor)
[obsidian官方文档](https://obsidian.md/help/syntax)
[Markdown 教程 | 菜鸟教程](https://www.runoob.com/markdown/md-tutorial.html) ^d1c588

# 常用markdown语法

- 标题

```markdown
# 我是一级标题 -> 一级标题
...
###### 我是六级标题 -> 最多六级标题
```
- 加粗

```markdown
两个下划线__或者两个**
__我是粗体__
**我是粗体**
```
- 斜体

```markdown
一个*
*我是斜体*
```
- 删除线

```markdown
两个波浪线~~
~~我被删除了~~
```
- 列表(缩进控制子列表)

```markdown
无序列表用-   有序列表用1.  tab缩进控制子列表
- 一级无序
	- 二级无序
		- 三级无序
			- 四级无序
1. 一级有序
	1. 二级有序
		1. 三级有序
			1. 四级有序
```
- 引用

```markdown
一个大于符号>
> 鲁迅曾经说过
```
- 分界线

```markdown
三个---
---  -> 分界线
```
- 链接

```markdown
用[标题](链接)来实现
```
- 代码

```markdown
用三个```实现，第一排后面加代码的名称可高亮对应的语法信息
```
- 任务列表

```markdown
用 - [] 表示   也可以用快捷键 ctrl + L
- [] 今天好好学习！
```

# obsidian 的特殊语法
- 双链
	- 用这个[[]]实现笔记之间的链接
	- 用 # 可以链接到笔记的某个标题
	- 用 ^ 可以链接到某个文本块
	- 用 | 可以重命名这个笔记的显示
	- 用 ！可以显示出这个笔记的内容
	- 使用示例：![[markdown语法测试#^8f11e8 | 我的markdown语法测试]]
- ezLaTex
	- $\alpha$
	- TODO