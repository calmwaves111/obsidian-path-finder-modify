# Obsidian Path Finder Plugin（modified by calmwaves）

添加了随机起点和终点的功能，采用的是 shortest_path 模式

现在的bug是时不时报错：某某md文件不存在 does not exist or is filtered out!
但是明明库里面有

找到原因了，孤立文件不能当头尾，所以添加了一个筛选非孤立文件，但是这个筛选太慢了，我现在两千多md笔记，要卡十几秒
