# Webapp-image-slider
Web App下图片滑动组件
#用法
1. 将图片宽、高、URL写入json文件
格式：
	"height": 950,`
	"width": 800,
	"img": "img/1.jpg"
2. 引入slide.js文件
3. 创建id为canvas的div块
4. 定义变量，调用$$imageSlider方法
	  var selectId="canvas";
	  var json="js/imgs.json";
	  $imageSlider(selectId,json);
#说明
json文件通过Ajax读取
