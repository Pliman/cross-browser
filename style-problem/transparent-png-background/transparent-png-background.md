在ie6下透明的png图片会带一个背景色

解决：

	background-image: url(icon_home.png);
	background-repeat: no-repeat;
	_filter:progid:DXImageTransform.Microsoft.AlphaImageLoader(src='icon_home.png');
	_background-image: none;

(实验时没有重现出来)