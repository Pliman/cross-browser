块元素中含有图片时，ie6-7中会出现图片下有空隙

解决：

	1、在源代码中让</div>和<img>在同一行
	2、将图片转换为块级对象display:block;
	3、设置图片的垂直对齐方式  vertical-align:top/middle/bottom
	4、改变父对象的属性，如果父对象的宽、高固定，图片大小随父对象而定，那么可以对父元素设置： overflow:hidden;
	5、设置图片的浮动属性  float:left;
