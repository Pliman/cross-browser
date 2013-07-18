如果设定了高度，内容过多时，ie6下会自动增加高度、其他浏览器会超出边框
在IE6下面，2个都OK，其他浏览器，第一个not OK，第二个OK

解决：
1.设置overflow:hidden;
2.高度自增height:auto!important;height:100px;