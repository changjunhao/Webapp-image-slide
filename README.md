# Webapp-image-slider
Web App下图片滑动组件
#用法
<p>1.将图片宽、高、URL写入json文件</p>
<p>格式：</p>
<pre><code>
"height": 950,`
"width": 800,
"img": "img/1.jpg"
</code></pre>
<p>2.引入slide.js文件</p>
<p>3.创建id为canvas的div块</p>
<p>4.定义变量，调用$imageSlider方法</p>
<pre><code>
var selectId="canvas";
var json="js/imgs.json";
$imageSlider(selectId,json);
</code></pre>	  
#说明
json文件通过Ajax读取
