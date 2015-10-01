---
layout: post
title:  "My First Tutorial"
date:   2015-10-01 13:58:37
categories: jekyll markdown
---
#First Tutorial
This is a new post to demostrate the features available in Jekyll, the backend server for GitHub Web Pages.  

Use **pandoc** for everything.  
pandoc is the app I use to convert my files from Microsoft Word to Markdown format.

{% highlight bash %}
pandoc -f docx -t markdown -o README.md README.docx
{% endhighlight %}
Where:  
	-f = input format  
	-t = output format  
	-o = output filename

Try it yourself :+1: