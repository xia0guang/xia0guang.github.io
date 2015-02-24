---
layout: post
title: "Basic MarkDown Syntax for Jekyll"
description: ""
category: Instruction
tags: [First, MarkDown]
disqus: false
---
{% include JB/setup %}

###### this is repost from [kramdown syntax documentation](http://kramdown.gettalong.org/syntax.html#line-wrapping)

####Paragraphs
~~~
On July 2, an alien mothership entered Earth's orbit and deployed several dozen saucer-shaped "destroyer" spacecraft, each 15 miles (24 km) wide.
~~~

####Headings
	# The largest heading (an <h1> tag)   
	## The second largest heading (an <h2> tag)  
	###### The 6th largest heading (an <h6> tag)  

####Blockquotes
~~~
>In the words of Abraham Lincoln: 
>> Pardon my french
~~~

<!--more-->

####Styling text
* __Bold__: `**` or `__`
* *Italic*: * or _

####Lists
	1. ordered list  
	  1. Item 1
	2. unordered list  
	  * Item 1
	  - Item 2

####Code formatting
inline: \` `  
multiple lines: \~~~
	
####Code Highlight
~~~
{ % highlight python %}
{ % endhighlight %}
~~~
display as:  

{% highlight python %}
def func(a = 1, b = 2):  
    retrun a + b
{% endhighlight %}

####Links
	[Display Text](Links)
	
####Tables 
~~~
|First Header  | Second Header 
------------- | ------------- 
|Content Cell  | Content Cell 
|Content Cell  | Content Cell|	 
~~~
display as: 

|First Header  | Second Header 
|:------------ |:------------
|Content Cell  | Content Cell 
|Content Cell  | Content Cell|





