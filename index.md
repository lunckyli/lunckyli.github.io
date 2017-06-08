<!DOCTYPE html>
<html lang="zh">
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"> 
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>jquery仿旅游网站侧边栏多级菜单代码</title>
	<link rel="stylesheet" type="text/css" href="css/normalize.css" />
	<link rel="stylesheet" type="text/css" href="css/niuqiqi-demo.css">
	<link rel="stylesheet" type="text/css" href="css/style.css" />
	<!--[if IE 6]>
	<script type="text/javascript" language="javascript" src="js/png.js"></script>
	<![endif]-->
	<script src="http://cdn.bootcss.com/jquery/1.11.0/jquery.min.js" type="text/javascript"></script>
	<!--<script>window.jQuery || document.write('<script src="js/jquery-1.11.0.min.js"><\/script>')</script>-->
	<!--<script type="text/javascript" src="js/web.js"></script>-->
</head>
<body>
	<div class="niuqiqi-container">

		<div class="product_sort fl">
			<div class="hd">旅游产品导航</div>
			<div class="bd">
				<div class="item">
					<div class="title one"><a href="#"><i></i>出境游</a></div>
					<div class="list">
						<a href="#">泰国</a>
						<a href="#">首尔</a>
						<a href="#">曼谷</a>
						<a href="#">大阪</a>
						<a href="#">普吉岛</a>
					</div>
					<div class="arrow">&gt;</div>
					<div class="line"></div>
					<div class="subitem">
						<div class="inner">
							<div class="tit tit1">
								<div class="name">泰国</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
							<div class="tit">
								<div class="name">印度尼西亚</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
				
				<div class="item">
					<div class="title two"><a href="#"><i></i>国内游</a></div>
					<div class="list">
						<a href="#">泰国</a>
						<a href="#">首尔</a>
						<a href="#">曼谷</a>
						<a href="#">大阪</a>
						<a href="#">普吉岛</a>
					</div>
					<div class="arrow">&gt;</div>
					<div class="line"></div>
					<div class="subitem">
						<div class="inner">
							<div class="tit tit1">
								<div class="name">泰国</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
							<div class="tit">
								<div class="name">印度尼西亚</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
				
				<div class="item">
					<div class="title three"><a href="#"><i></i>周边游</a></div>
					<div class="list">
						<a href="#">泰国</a>
						<a href="#">首尔</a>
						<a href="#">曼谷</a>
						<a href="#">大阪</a>
						<a href="#">普吉岛</a>
					</div>
					<div class="arrow">&gt;</div>
					<div class="line"></div>
					<div class="subitem">
						<div class="inner">
							<div class="tit tit1">
								<div class="name">泰国</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
							<div class="tit">
								<div class="name">印度尼西亚</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
				
				<div class="item">
					<div class="title four"><a href="#"><i></i>邮轮</a></div>
					<div class="list">
						<a href="#">泰国</a>
						<a href="#">首尔</a>
						<a href="#">曼谷</a>
						<a href="#">大阪</a>
						<a href="#">普吉岛</a>
					</div>
					<div class="arrow">&gt;</div>
					<div class="line"></div>
					<div class="subitem">
						<div class="inner">
							<div class="tit tit1">
								<div class="name">泰国</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
							<div class="tit">
								<div class="name">印度尼西亚</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
				
				<div class="item">
					<div class="title five"><a href="#"><i></i>东南亚</a></div>
					<div class="list">
						<a href="#">泰国</a>
						<a href="#">首尔</a>
						<a href="#">曼谷</a>
						<a href="#">大阪</a>
						<a href="#">普吉岛</a>
					</div>
					<div class="arrow">&gt;</div>
					<div class="line"></div>
					<div class="subitem">
						<div class="inner">
							<div class="tit tit1">
								<div class="name">泰国</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
							<div class="tit">
								<div class="name">印度尼西亚</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
				
				<div class="item">
					<div class="title six"><a href="#"><i></i>日本、韩国、朝鲜</a></div>
					<div class="list">
						<a href="#">泰国</a>
						<a href="#">首尔</a>
						<a href="#">曼谷</a>
						<a href="#">大阪</a>
						<a href="#">普吉岛</a>
					</div>
					<div class="arrow">&gt;</div>
					<div class="line"></div>
					<div class="subitem">
						<div class="inner">
							<div class="tit tit1">
								<div class="name">泰国</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
							<div class="tit">
								<div class="name">印度尼西亚</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
				
				<div class="item">
					<div class="title seven"><a href="#"><i></i>欧美</a></div>
					<div class="list">
						<a href="#">泰国</a>
						<a href="#">首尔</a>
						<a href="#">曼谷</a>
						<a href="#">大阪</a>
						<a href="#">普吉岛</a>
					</div>
					<div class="arrow">&gt;</div>
					<div class="line"></div>
					<div class="subitem">
						<div class="inner">
							<div class="tit tit1">
								<div class="name">泰国</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
							<div class="tit">
								<div class="name">印度尼西亚</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
				
				<div class="item">
					<div class="title eight"><a href="#"><i></i>澳洲</a></div>
					<div class="list">
						<a href="#">泰国</a>
						<a href="#">首尔</a>
						<a href="#">曼谷</a>
						<a href="#">大阪</a>
						<a href="#">普吉岛</a>
					</div>
					<div class="arrow">&gt;</div>
					<div class="line"></div>
					<div class="subitem">
						<div class="inner">
							<div class="tit tit1">
								<div class="name">泰国</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
							<div class="tit">
								<div class="name">印度尼西亚</div>
								<ul>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">新加坡</a></li>
									<li><a href="#">菲律宾</a></li>
									<li><a href="#">沙巴</a></li>
									<li><a href="#">文莱</a></li>
									<li><a href="#">蓝梦岛</a></li>
									<li><a href="#">吉隆坡</a></li>
									<li><a href="#">塞班岛</a></li>
									<li><a href="#">柬埔寨</a></li>
									<li><a href="#">马来西亚</a></li>
									<li><a href="#">越南</a></li>
									<li><a href="#">下龙湾</a></li>
									<li><a href="#">吴哥</a></li>
									<li><a href="#">芽庄</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
				
			</div>
		</div>
	</div>
	
	<script type="text/javascript">
	$(function(){
		//首页旅游产品分类
		$(".product_sort .bd .item").hover(function(){
			$(this).addClass("layer");
		},function(){
			$(this).removeClass("layer");
		});
	})
	</script>
<!--readem 以下非正文信息-->
<div style="clear:both;height:10px;"></div>
<div class="rem" style="width:80%;margin:30px auto 10px auto;font-size:14px;">
<p style="border-top:1px solid #ccc;padding-top:10px;"><a href="http://www.niuqiqi.com/" target="_blank">返回首页</a> / 代码整理：<a href="http://www.niuqiqi.com/" target="_blank">牛七七</a></p>
<p style="font-size:14px;">◎ 尊重他人劳动成果,转载请自觉注明出处！注：此代码仅供学习交流,请勿用于商业用途。</p>
</div>
<!--end readem-->	
</body>
</html>



