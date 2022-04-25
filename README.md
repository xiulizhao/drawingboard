# drawingboard
简易画布绘图元素<br>
<img src="http://www.wware.org/img/drawimg1.jpg?_5302" width="500px"><br>
普通属性<br>
data-toolbar	设置显示哪些绘画小工具	<br>
data-controlsPosition	小工具栏显示的位置	左上角<br>
data-size	初始画笔的粗细，以像素为单位，(此处不写单位)，例：2	10<br>
data-background	初始化画布背景色，可以'#fff'或者rgba(0,0,0,1) 2种形式，要想背景色透明可以设置rgba(0,0,0,0.5),透明度：0-1,注意：如果设置了透明背景，橡皮工具将失去作用	#fff<br>
data-webStorage	是否本地缓存已有绘图，是：将绘图缓存到本地，即：只要不清理缓存，刷新页面绘图还存在，否：每次打开，都是最初的画布状态	<br>
data-selectid	当一个页面同时使用多个元素时使用，需将页面div中的id与这里的设置的对应相同<br>
输出属性<br>
data-x-progressnow	以64编码形式，输出当前的图片<br>
