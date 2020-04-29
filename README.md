<!doctype html>
<html>
<head>
<meta charset="utf-8">
<style>
div{
    
    text-align:center;
    
}
</style>

<link rel="icon" type="image/x-ico" href="images/LOGO.gif" />
<link rel="stylesheet" type="text/css" href="css/all.css">
<title>星河工作室</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
</head>

<body>
	<!--<audio src="images/All Falls Down.mp3" autoplay></audio>--> 
	<div><h1><font color = "blue"> <font face = "楷体"><b>星河工作室</b></font></font></h1></div> 
	<div id="box"> <h2>让更多人，了解编程</h2></div>
	<div id="box"> <h2>C++，PYTHON，SCRATCH，HTML等</h2></div>
    	<script>
        	var i = 1;
        	var flag = true;
        	function fade() {
            	var box = document.getElementById('box');
            	if (document.all) {
                	box.style.filter = "alpha(opacity='+i+')";
            	} else {
                	box.style.opacity = parseFloat(i / 100);
            	}
            	if (i < 100 && flag) {
                	i += 5;
            	}
            	else {
                	flag = false;
           	}
            	if (i > 0 && !flag) {
                	i -= 5;
            	}
            	else {
                	flag = true;
            	}
            	setTimeout('fade()', 50);
        	}
        	fade();
    	</script>
	</script>
	<div id="background" style="position:absolute;z-index:-1;width:100%;height:100%;top:0px;left:0px;">
		<img src="images/timg.jpg" width="100%" height="100%"/>
	</div>
	<div id="content">

	<br>
	<br>
	<p align="left"><font color = "red"> <font face = "宋体">星河工作室是一个成立半年的工作室,半年的沉淀使得星河工作室一跃上前,<br>
	成为社区前三工作室, 星河工作室一直要求:"高质量,高科技,高素养"<br>
 	我们工作室曾经遇到许多挫折,甚至倒闭过一段时间,但是...<br>
 	我们撑下来了,我们一起努力,一起呐喊; 有难同当,有福同享;<br>
 	最后,我们成功的走到了现在! 一个工作室的核心不是人数,也不是技术,是团结!</font></font></p>
	<h1>星河作品：</h1>
	<input type="button" value="扑克牌匹配4.0🎴(星河)" onclick="window.open('https://code.xueersi.com/home/project/detail?lang=code&pid=1970564&version=2.0&form=cpp&langType=cpp')">
	<input type="button" value="购房计划(星河)" onclick="window.open('https://code.xueersi.com/home/project/detail?lang=code&pid=4618900&version=cpp&form=cpp&langType=cpp')">
	<input type="button" value="21点 小游戏(星河)" onclick="window.open('https://code.xueersi.com/home/project/detail?lang=code&pid=4443050&version=cpp&form=cpp&langType=cpp')">
	<input type="button" value="论当代的slow函数(星河)" onclick="window.open('https://code.xueersi.com/home/project/detail?lang=code&pid=5144772&version=cpp&form=cpp&langType=cpp')">
	<br>
	<br>
	<h1>联系我们...</h1>
	<br>
	<a href="mailto:Kstvgudu@163.com">向我们发送邮件</a>
	</content>
	</content>

</body>
</html>
