为Foobar2000播放器的Beefweb Remote Control 插件添加搜索功能。

前端缓存信息并进行搜索，调用api进行播放。

直接替换C:\Users\[YourAccount]\AppData\Roaming\foobar2000-v2\user-components-x64\foo_beefweb\beefweb.root下的index.html即可。


在</body>之前新增了一段javascript脚本实现的。






场景说明:

公司内网一台电脑连接了蓝牙音箱，播放一些大家喜欢的歌曲作为办公室背景音乐，Beefweb Remote Control 0.10 原版没有搜索功能使用体验不好。
通过Gemini实现了搜索功能。
