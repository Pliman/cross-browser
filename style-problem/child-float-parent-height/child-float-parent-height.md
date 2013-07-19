子容器都float以后，父容器没有设定高度,父容器将不会扩展

解决：

	只需要添加一个clear:both的div，代码如下：
	<div style="border:1px solid #333;width:204px">
	    <div style="width:100px;border:1px solid #333; float:left; ">子容器a</div>
	    <div style="width:100px;border:1px solid #333; float:left;">子容器b</div>
	    <div style="clear:both"></div>
	</div>

	在现代浏览器中，可以给父容器添加样式
	.container:after{
		display: table;
		line-height: 0;
		content: "";
		clear: both
	}