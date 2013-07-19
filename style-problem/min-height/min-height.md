ie6不支持min-height、min-width属性，默认height是最小高度，width是最小宽度。

解决：

    使用ie6不支持但其余浏览器支持的属性!important。
	设置属性min-height:200px; height:auto !important; height:200px;
