# ll

Skip to content
Pull requests
Issues
Marketplace
Explore
@Hulaos
Hulaos /
ll
Public

Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights

    Settings

ll/时钟.html
@Hulaos
Hulaos kk
Latest commit 59d4cf0 5 hours ago
History
1 contributor
134 lines (106 sloc) 3.28 KB
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
<html>
  <head>
    <meta charset="UTF-8">
    <title>OK解析</title>
	<meta http-equiv="keywords" content="OK视频解析,视频解析,vip解析,解析源码,API解析接口,CK解析,全网vip视频解析,全网vip在线解析">
	<meta http-equiv="description" content="OK视频解析,视频解析,vip解析,解析源码,API解析接口,CK解析,全网vip视频解析,全网vip在线解析">
    <script src="https://cdn.jsdelivr.net/gh/okjx666/okjx/include/jquery.js" type="text/javascript"></script>
    <link href="https://cdn.jsdelivr.net/gh/okjx666/okjx/include/swiper.min.css" rel="stylesheet" type="text/css"/>
    <meta name="viewport" content="width=device-width,initial-scale=1.0,maximum-scale=1.0">
    <script src="https://cdn.jsdelivr.net/gh/okjx666/okjx/include/swiper.min.js" type="text/javascript"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/okjx666/okjx/include/style1.css" media="screen" type="text/css" />
    <style type="text/css">
	a:link{color:red;}
	a:visited{color:white;}
    </style>
    <style>

	#audio_btn{
		position:absolute;
		top:0px;
		left:0px;
		z-index:999999;
	}
	input {
		display: block;
		width: 100%;
		border: none;
		font-size: 1em;
		line-height: 1.5em;
		margin: 0;
		padding: 0.5em;
		resize: none;
		font-family: inherit;
		color: inherit;
		box-sizing: border-box;
	}
	.send-btn {
		float: left;
	}
	ul{padding:0px;
	   margin:0px;}
	li{list-style:none;
	   padding:0px;
	   margin:0px;
	   width:100%;
	}
	#conts p{
		width:100%;
		word-break:break-all;
		padding:3px 0px 3px 0px;
		margin:0px;

	}

	.dm .d_screen 
	.d_del{width:38px;height:38px;background:#600;display:block;text-align:center;line-height:38px;
		   text-decoration:none;font-size:20px;color:#fff;border-radius:19px;border:1px solid #fff;position:absolute;top:10px;right:20px;z-index:3;display:none;}
	.dm .d_screen .d_del:hover{background:#f00;}
	.dm .d_screen .d_mask{width:100%;height:100%;position:absolute;top:0;left:0;opacity:0.5;
						  filter:alpha(opacity=50) ;z-index:1;}
	.dm .d_screen .d_show{position: relative;z-index:2;}
	.dm .d_screen .d_show div{font-weight:500;color:#fff;position:absolute;left:0;top:0;}
	#showmeg p{
		font-weight:bold;
		text-align:center;
	}
	.d_show div{
		width:230px;
		heigth:50px;				
	}
	.d_show p{
		heigth:50px;
		text-overflow:ellipsis	;
	}
#audio_btn{
		position:absolute;
		top:0px;
		left:0px;
		z-index:999999;
	}

</style>
  </head>
  
<body> 

<div class="fill">

  <div class="reference"></div>

  <div class="clock" id="utility-clock">

    <div class="centre">

      <div class="dynamic"></div>

      <div class="expand round circle-1"></div>

      <div class="anchor hour">

        <div class="element thin-hand"></div>

        <div class="element fat-hand"></div>

      </div>

      <div class="anchor minute">

        <div class="element thin-hand"></div>

        <div class="element fat-hand minute-hand"></div>

      </div>

      <div class="anchor second">

        <div class="element second-hand"></div>

      </div>

      <div class="expand round circle-2"></div>

      <div class="expand round circle-3"></div>

    </div>

  </div>
</div>
 
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/okjx666/okjx/include/script.js"></script>

</body>
</html>

    © 2022 GitHub, Inc.

    Terms
    Privacy
    Security
    Status
    Docs
    Contact GitHub
    Pricing
    API
    Training
    Blog
    About

