ie6中设置浮动，同时又设置margin时，会出现双倍边距的问题
例float:left;width:100px;margin:0 100px;

解决：

	设置display:inline;

(在实验时没有重现出问题)