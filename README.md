# Markdown是什么
markdown是一种**标记性语言**，以纯文本编写而最终以**HTML**格式发布。即以MRKDOWN语法编写的语言向HTML的转化。（但是由此我就不禁想到了，应该也会有word转markdown的工具吧，手动滑稽~_~）
#创造者
1.Aaron Swartz
2.John Gruber
#为什么使用
跨平台		
易读易写
#主要语法
- 标题
- 段落 
- 区块 
- 代码区 
- 强调 
- 列表 
- 分割线 
- 链接 
- 图片 
- 反斜杠 
- 符号

###标题

	#一级标题
	##二级标题
	###三级标题
	####四级标题
	#####五级标题
	######六级标题

#####效果

#一级标题
##二级标题
###三级标题
####四级标题
#####五级标题
######六级标题

###段落
前后要有空行，强制换行使用两个以上空格加回车。

###区块
在段落的每行或者第一行使用符号>，还可以嵌套使用。	
#####文本范例

	>区块引用
	>>嵌套引用

#####效果
>区块引用
>>嵌套引用

###代码区
代码区要与普通段落之间有空行，代码区的建立是在每行加上4个空格或者一个制表符。
#####普通段落
void main()
{
	printf("Hello,Markdown.");
}
#####代码效果

		void main()
	{
		printf("Hello,Markdown.");
	}

###强调
在强调内容两侧分别加上`*`或`_`
#####文本范例
	*斜体*	or	_斜体_
	**粗体**	or	__粗体__
#####效果
*斜体* _斜体_  
**粗体** __粗体__
###列表
使用`·`、`+`（常用）、或`-`标记**无序列表**。与其他段落有空行，与`+`之间有空格。


	+ 第一项
	+ 第二项
	+ 第三项
#####`+`效果:

+ 第一项
+ 第二项
+ 第三项

也可以制**有序表**（第一个打出`1.something`然后后面的数字会自动填充的）：

	1. 第一项
	2. 第二项
	3. 第三项
#####效果：

1. 第一项
2. 第二项
3. 第三项

###分割线
最常使用就是三个或以上`*`，还可以使用-和_。

	***
	---
	___
#####效果：
***
###链接
链接可以由两种形式生成：行内式和参考式。
#####行内式：

	[本人的github主页](https://github.com/dirtycomputer)
#####行内式的效果：
[本人的github主页](https://github.com/dirtycomputer)
#####参考式：

	[本人的github主页][1]  
	[本人github的一个项目][2]
	[1]:https://github.com/dirtycomputer
	[2]:https://github.com/dirtycomputer/Learning-materials
#####参考式的效果：
[younghz的Markdown库1][1]  
[younghz的Markdown库2][2]
[1]:https://github.com/dirtycomputer
[2]:https://github.com/dirtycomputer/Learning-materials

###图片
跟插入链接没什么区别，只是多加了一个`!`

	![当图片找不到时的替代文字](图片链接 "鼠标悬置于图片上会出现的标题文字，可以不写")

温馨提示：**图床**是个好东西！

#####效果：
![404图片找不到了](https://avatars1.githubusercontent.com/u/48406770?s=400&u=4e2b3298d6f65f8bd228845d812b092890b62cc3&v=4)

###反斜杠
类似于C语言中实现反转义，使符号成为普通符号。

	\#哈哈
#####效果：
\#哈哈

###符号'`'
起标记作用

	`Command+V`

#####效果：
`Command+V`

#都有谁在使用Markdown
+ Github
+ 简书
+ Stack Overflow
+ Apollo
+ Moodle
+ Reddit
+ Wordpress

#关于Markdown的快捷键
博主也是写完这篇问了下度娘，结果还有快捷键！？！？  

![404 not found](https://t1.picb.cc/uploads/2019/05/28/giIvk8.png)