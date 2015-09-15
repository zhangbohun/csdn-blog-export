# CSDN 博客导出工具

一个用python2.7写的博客导出工具，导出为markdown或者html。

## 使用

### 依赖
	
	Python 2.7
		beautifulsoup4

此外，在导出markdown格式的时候使用了开源项目[html2text](https://github.com/aaronsw/html2text)

### 使用方法
	
	main.py -u <username> [-f <format>] [-p <page>] [-o <outputDirectory>]
		<format>： html | markdown，缺省为markdown
		<page>为导出特定页面的文章，缺省导出所有文章

### Example

如果想导出[http://blog.csdn.net/cecesjtu](http://blog.csdn.net/cecesjtu)的文章，格式为markdown，命令为：

	./main.py -u cecesjtu -f markdown
	or
	./main.py -u cecesjtu

格式为html，命令为：

	./main.py -u cecesjtu -f html

## To Do

~~1. pdf导出支持~~由于字体问题，放弃实现╮(╯_╰)╭

## Licence

GPLv3
