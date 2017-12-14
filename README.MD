<!DOCTYPE html>
<html>
<head>?
<meta?charset="utf-8">?
<title>菜鸟教程(runoob.com)</title>?
</head>
<body>
	
<form action="demo-form.php" method="get">
<input list="browsers" name="browser">
<datalist id="browsers">
  <option value="Internet Explorer">
  <option value="Firefox">
  <option value="Chrome">
  <option value="Opera">
  <option value="Safari">
</datalist>
<input type="submit">
</form>
<!DOCTYPE html>
<html>
<head>?
<meta?charset="utf-8">?
<title>菜鸟教程(runoob.com)</title>?
</head>
<body>
<!DOCTYPE html>
<html>
<head>?
<meta?charset="utf-8">?
<title>菜鸟教程(runoob.com)</title>?
</head>
<body>
<p id="demo">点击按钮获取您当前坐标（可能需要比较长的时间获取）：</p>
<button onclick="getLocation()">点我</button>
<script>
var x=document.getElementById("demo");
function getLocation()
{
	if (navigator.geolocation)
	{
		navigator.geolocation.getCurrentPosition(showPosition);
	}
	else
	{
		x.innerHTML="该浏览器不支持获取地理位置。";
	}
}

function showPosition(position)
{
	x.innerHTML="纬度: " + position.coords.latitude + 
	"<br>经度: " + position.coords.longitude;	
}
</script>
</body>
</html>
<section>
  <h1>WWF</h1>
  <p>The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the environment, formerly named the World Wildlife Fund. WWF was founded in 1961.</p>
</section>

<section>
  <h1>WWF's Panda symbol</h1>
  <p>The Panda has become the symbol of WWF. The well-known panda logo of WWF originated from a panda named Chi Chi that was transferred from the Beijing Zoo to the London Zoo in the same year of the establishment of WWF.</p>
</section>

</body>
</html>