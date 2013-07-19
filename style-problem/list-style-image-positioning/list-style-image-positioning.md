li前设置图片时，图片与其后的文字对齐问题

解决：

	1、采用背景定位 和 字符缩进的方法
	background:url() no-repeat left center; text-index:16px;
	2、采用相对定位方法
	li 设置list-style:url();
	li的子元素position:relative;top:-5px;
