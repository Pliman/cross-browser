这个bug产生的充要条件是li的子元素浮动并且li设置了以下CSS属性之一：width、height、zoom、padding-top、padding-bottom、margin-top、margin-bottom。

解决：

	1、div设置clear:left|both，这时li不能设置width、height、zoom。
	2、li设置float:left，这时li可以设置width、height、zoom。
	3、li设置clear:left|both，这时li不能设置width、height、zoom。
	4、IE6/IE7的这个Bug可以通过给li中的div设置vertical-align:top|middle|bottom解决。
