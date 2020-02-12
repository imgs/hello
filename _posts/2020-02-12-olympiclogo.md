---
layout: post
title: "Olympic Logo"
description: "2020.01.30"
category: 
tags: [] 
---

> **Olympic Logo**  

**奥运五环LOGO+渐变文字页面居中**

```html
<html>
	<head>
		<meta charset="utf-8" />
		<title>Olympic logo</title>
		<link rel="stylesheet" href="./css/olympiclogo.css">
	</head>
	<body>
		<div class="wrapper">
			<div class="c1"></div>
			<div class="c2"></div>
			<div class="c3"></div>
			<div class="c4"></div>
			<div class="c5"></div>
			<div class="c6">人民有信仰 民族有希望 国家有力量</div>
		</div>
	</body>
</html>
```

```CSS
*{
	margin: 0;
	padding: 0;
}
.wrapper{
	position: fixed;
	transform-style: preserve-3d;
	width: 380px;
	height: 220px;
	background-color: transparent;
	left: 50%;
	top: 50%;
	margin-left: -190px;
	margin-top: -110px;
}
.c1,.c2,.c3,.c4,.c5{
	position: absolute;
	width: 100px;
	height: 100px;
	border: 10px solid transparent;
	border-radius: 50%;
}

.c1{
	border-color: #0081c2;
	left: 0px;
	transform: rotateY(-1deg);
}
.c2{
	border-color: #000;
	left: 130px;
	transform: rotateY(-1deg); 
}
.c3{
	border-color: #f00;
	left: 260px;
	transform: rotateY(-1deg);
}
.c4{
	border-color: #edbe00;
	left: 65px;
	top: 70px;
	transform: rotateY(1deg);
}
.c5{
	border-color: #0da045;
	left: 195px;
	top: 70px;
	transform: rotateY(1deg);
}
.c6{
	width: auto;
	height: 30px;
	margin-top: 190px ;
	font-size: 24px;
}
.c6:hover{
	background: linear-gradient(to right,red,#123);
	-webkit-background-clip: text;
	color: transparent;
}
```
  
