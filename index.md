<!DOCTYPE html>
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
//alert (closed);
//alert(window.defaultStatus);//设置或返回窗口状态栏中的默认文//本
//alert(window.document);	///对 Document 对象的只读引用。请参阅 //Document 对象。
//alert(window.history);//对 History 对象的只读引用。请参数 //History 对象。
//*(innerheight)	返回窗口的文档显示区的高度。
//(innerwidth)	返回窗口的文档显示区的宽度。
//location	用于窗口或框架的 Location 对象。请参阅 Location //对象。
//name	    设置或返回窗口的名称。
document.write("<p>CodeName: ")
document.write(navigator.javaEnabled() + "</p>")	
//对 Navigator 对象的只读引用。请参数 
//Navigator 对象。
//opener	    返回对创建此窗口的窗口的引用。
//outerheight	返回窗口的外部高度。
//outerwidth	返回窗口的外部宽度。
//pageXOffset	设置或返回当前页面相对于窗口显示区左上角的 X //位置。
//pageYOffset	设置或返回当前页面相对于窗口显示区左上角的 Y 位置。
//parent	   返回父窗口。
//Screen	   对 Screen 对象的只读引用。请参数 Screen 对象。
//self	  返回对当前窗口的引用。等价于 Window 属性。
//status	   设置窗口状态栏的文本。
//top	    返回最顶层的先辈窗口。
//window
alert(window.length);
</script>

</html>


