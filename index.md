
<html>
<head>
<meta charset="gb2312" />
<title>无标题文档</title>
<style>
body,ul,li{margin:0;
	padding:0;
	font:12px/1.5 arial;}

ul,li{list-style:none;}

.wrap{width:500px; 
margin:20px auto;}

.hide{display:none;}

#tab_t{height:25px;
border-bottom:1px solid #FF0000;}

#tab_t li{
float:left;
width:80px; 
height:24px; 
line-height:24px; 
margin:0px; 
text-align:center; 
border:1px solid #000000; 
border-bottom:none; 
background:#FF00FF; 
cursor:pointer}

#tab_t .act{ 
position:relative;
height:25px; 
margin-bottom:-1px;
background:#000080;}

#tab_c{
border:1px solid #800000; 
border-top:none;
padding:20px;}


</style>
</head>
<body>
<div class="wrap">
 <ul id="tab_t">
 <li class="act">选择1</li>
 <li>选择2</li>
 <li>选择3</li>
 <li>选择4</li>
 </ul>
 <div id="tab_c">
 <div>内容1</div>
 <div class="hide">内容2</div>
 <div class="hide">内容3</div>
 <div class="hide">内容4</div>
 </div>
</div> 
</body>
<script>

alert(window.length);
</script>

</html>


