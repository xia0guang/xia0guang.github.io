---
layout: post
title: "Top Ten Shortcuts for intelliJ IDEA"
description: ""
category: productivity
tags: [intelliJ-IDEA, Shortcuts]
---
{% include JB/setup %}  
转载于[十大Intellij IDEA快捷键](http://blog.csdn.net/dc_726/article/details/42784275)  

----------------    
之前所有的使用软件的习惯都是想用什么区查什么, 然后顺便记住, 但是当我使用 intelliJ-IDEA 的过程中发现想要记住这玩意儿的快捷键真的是一项浩大的工程, 不亚于学会一门新的语言, 所以现在特地从网上找了一篇专门介绍快捷键的文章, 以便于参考, 以下便是摘录:  


1. 智能提示:  
	`Ctrl` + `Space`: 基本的代码提示  
	`Ctrl` + `Shift` + `Space`: 智能地按类型信息提示  
		* 但因为Intellij总是随着我们敲击而自动提示，所以很多时候都不会手动敲这两个快捷键(除非提示框消失了)  
	`F2` / `Shift` + `F2`: 移动到有错误的代码  
	`Alt` + `Enter`: 快速修复, 这个比 eclipse 方便, 很多时候都不需要按快捷键就已经自动添加了  
	`Command` + `Shift` + `Enter`: 当智能提示为我们自动补全方法名时，我们通常要自己补上行尾的反括号和分号，当括号嵌套很多层时会很麻烦，这时我们只需敲这组快捷键就能自动补全末尾的字符。而且不只是括号，例如敲完if/for时也可以自动补上{}花括号  
		* 最后要说一点，Intellij能够智能感知Spring、Hibernate等主流框架的配置文件和类，以静制动，在看似“静态”的外表下，智能地扫描理解你的项目是如何构造和配置的  
  
2. 重构:  
	* Intellij重构是另一完爆Eclipse的功能，其智能程度令人瞠目结舌，比如提取变量时自动检查到所有匹配同时提取成一个变量等  
	* 推荐书目:《重构-改善既有代码设计》  
	
	* `Command` + `Shift` + `Alt` + `T`: Refactor this, 大多数可以直接用这个, 如果一些功能太常用的话, 也可以直接记单独的快捷键, 比如:  
     	* `Shift` + `F6`: Rename  
		* `Command` + `Alt` + `V`: 提取变量  
  
<!--more-->  
  
3. 代码生成:  
	`fori`/`sout`/`psvm` + `Tab`: 可生成循环、System.out、main方法等boilerplate样板代码 
		* 另外，Intellij IDEA 13中加入了后缀自动补全功能(Postfix Completion)，比模板生成更加灵活和强大。例如要输入for(User user : users)只需输入user.for+Tab。再比如，要输入Date birthday = user.getBirthday();只需输入user.getBirthday().var+Tab即可   
		
	`Command` + `J`: 查看所有模板  
	`Command` + `O`: Override  
	
4. 编辑:  
	`Command` + `W`/`Command` + `Shift` + `W`: 自动按语法选中代码或反向选中  
	`Command` + `Y`: 删除行  
	`Command` + `D`: 复制行  
	`Command` + `<`/`>`: 折叠代码  
	
5. 查找打开:  
	`Command` + `O`/`Command` + `Shift` + `O`: 类似Eclipse, 可以打开类或资源, 但Intellij更加智能一些，我们输入的任何字符都将看作模糊匹配，省却了Eclipse中还有输入*的麻烦。最新版本的IDEA还加入了Search Everywhere功能，只需按Shift+Shift即可在一个弹出框中搜索任何东西，包括类、资源、配置项、方法等等  
	`Ctrl` + `H`: 打开类层次窗口  
	`Command` + `B`/`Command` + `Alt` + `B`: 分别对应父类或父方法declaration和子类或子方法implementation  
	
	
6. 其他辅助:  
	`Command` + `Shift` + `A`: 可以查找所有Intellij的命令，并且每个命令后面还有其快捷键。所以它不仅是一大神键，也是查找学习快捷键的工具  
	`Ctrl` + `Alt` + `O`: 格式化 import 列表  
	`Command` + `Alt` + `L`: 格式化代码  
	`Command` + `F4`: 关闭当前标签  
	`Shift` + `F10`/`Shift` + `Alt` + `F10`: 运行当前程序/选择程序运行  
	`F7`,`F8`,`F9`: 分别对应 Step into，Step over，Continue  
	
7. 最终榜单:  
  * Top #10切来切去：`Ctrl`+`Tab`
  * Top #9选你所想：`Command`+`W`
  * Top #8代码生成：`Template/Postfix` +`Tab`
  * Top #7发号施令：`Command`+`Shift`+`A`
  * Top #6无处藏身(search in every where)：`Shift`+`Shift`
  * Top #5自动完成：`Command`+`Shift`+`Enter`
  * Top #4创造万物：`Alt`+`Insert`  
 (太难割舍，前三名并列吧！)
  * Top #1智能补全：`Ctrl`+`Shift`+`Space`
  * Top #1自我修复：`Alt`+`Enter`
  * Top #1重构一切：`Command`+`Shift`+`Alt`+`T`  

  
  