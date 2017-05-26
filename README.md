# 项目目的
练习和实战，积累经验
# 项目名称
致美创意
# 遇到的问题
```
/*遇到问题，用dbdh加margin无法生效，只能z6加padding*/
.z6{
	height:200px;
	padding-top:30px;
}
/*底部导航*/
.dbdh{
	width:400px;
	height:40px;
	margin:0 auto;
}
.dbdh ul{
	margin:0;
	padding:0;
	list-style:none;
}
.dbdh li{
	float:left;
	width:99px;
	height:40px;
	/*margin:30px auto; 是无法生效的*/
	text-align:center;
	font:20px/40px "simhei";
	border-right:1px solid black;
}
```
# 特殊字体
```
/*引用自己的字体*/
/*开始引入路径不对，习惯性的在CSS里面不找上一级*/
 @font-face {
	
	/*创建字体的名字：叫 myFont，后面就可以使用这个字体了*/
	font-family: myFont; 
	/*引入字体文件的路径*/
	src: url("../Bodoni.ttf");
}  

.z1 span{
	/*myFont 自己字体的名字*/
	font-family: myFont;
}
```
# 把0写成了O是常见的错误；
```
.z3{
	width:100%;
	height:400px;
/*把0写成O*/
	background:url("../img/3.gif")no-repeat center 0;
	background-size:100% 100%;
}
```
# /*往背景图片里面添加一个标签*/
```
/*往背景图片里面添加一个标签*/
.zmcy{
	width:415px;
	height:80px;
	border:1px solid red;
	margin:0 auto;
}
.zmcy p{
	float:left;
}
.p1{
	height:40px;
	background:red;
	width:50px;
	color:white;
	margin:10px;
	padding:10px;
	text-align:center;
	font:20px/20px "simhei";
	font-weight:bold;
}
.p2{
	width:225px;
	height:80px;
	color:white;
	font:55px/80px "simsun";
	margin:0;
	font-weight:bold;
}
.p3{
	width:80px;
	height:60px;
	color:white;
	margin:0;
	padding:10px;
	text-align:center;
	font:20px/30px "simhei";
}
```
# 项目结构（7部分组成）
1.顶部通栏
2.顶部导航栏
3.通栏背景图片
4.首页链接
5.底部公司介绍
6.企业文化
7.结尾商标
# 完成日期
2017.5.26项目完成，测试效果OK！提交杰哥！