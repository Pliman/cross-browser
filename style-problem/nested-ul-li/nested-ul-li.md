ie的bug，嵌套使用ul、li时，里层的li设置float以后，外层li不设置float, 里面的ul顶部和它外面的li总是有一段间距

解决：

	设置里面的ul的zoom:1

(firefox正常，chrome也有bug: 待解决)