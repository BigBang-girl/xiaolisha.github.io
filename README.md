# xiaolisha.github.io
<!doctype html>
<html>
<head>
	<meta charset="utf-8"/>
	<meta name="viewport" content="maximum-scale=1.0,minimum-scale=1.0,user-scalable=0,width=device-width,initial-scale=1.0"/>
    <meta name="format-detection" content="telephone=no,email=no,date=no,address=no">
    <link rel="stylesheet" href="./css/aui.css"/>
	<link rel="stylesheet" href="./css/aui-slider-full.css" />
	<link rel="stylesheet" href="./css/aui-flex.css" />
	<link rel="stylesheet" href="https://github.com/username/username.github.io" />
	<style type="text/css">
		p{
			color:#000;
		}
		.pic{
			background:url('./image/pic11.jpg');
			height:100%;
			width:100%;
			background-size:cover;
			background-repeat: no-repeat;
		}
		.pic p{
			padding-top:200px;
			padding-left:20px;
			font-size: 20px;
			color:#a70005;
			z-index: 1;
			padding-right:20px;
		}
		.ins{
			background:url('./image/pic17.jpg');
			height:100%;
			width:100%;
			background-size:cover;
			background-repeat: no-repeat;
		}
		.time{
			font-size: 20px;
			padding-top:100px;
			padding-left: 50px;
			color:#4ca295;
			padding-bottom:50px;
			padding-right: 30px;
		}
		.fade-in{
			margin-left: 100px;
		}
		.fade-in p{
			font-size: 20px;
			margin-bottom:25px;
			color:#4ca295;
		}
		@keyframes fade-in{
			0%{ opacity: 0;}
    		100%{opacity:1;}
		}
		@-webkit-keyframes fade-in{
    		0%{ opacity: 0;}
    		100%{opacity:1;}
		}
		@-ms-keyframes fade-in{
    		0%{ opacity: 0;}
    		100%{opacity:1;}
		}
		@-o-keyframes fade-in{
   			0%{ opacity: 0;}
    		100%{opacity:1;}
		}
		@-moz-keyframes fade-in{
    		0%{ opacity: 0;}
    		100%{opacity:1;}
		}
		.first-words{ 
    		opacity: 0;      /*实先规定文字的状态是不显示的*/
    		animation: fade-in 4s ease 0s 1;    /*调用名称为fade-in的动画，全程动画显示时间4S，进入方式为ease，延时0S进入，播放次数1次*/
		    -webkit-animation: fade-in 4s ease 0s 1;
		    -moz-animation: fade-in 4s ease 0s 1;
		    -o-animation: fade-in 4s ease 0s 1;
		    -ms-animation: fade-in 4s ease 0s 1;
    
		    /*规定动画的最后状态为结束状态*/
		    animation-fill-mode:forwards;
		    -webkit-animation-fill-mode: forwards;  
		    -o-animation-fill-mode: forwards; 
		    -ms-animation-fill-mode: forwards;   
		    -moz-animation-fill-mode: forwards; 
		}
		.second-words{ 
		    opacity: 0;    
		    animation: fade-in 4s ease 2s 1;
		    -webkit-animation: fade-in 4s ease 2s 1;
		    -moz-animation: fade-in 4s ease 2s 1;
		    -o-animation: fade-in 4s ease 2s 1;
		    -ms-animation: fade-in 4s ease 2s 1;
		    
		    /*规定动画的最后状态为结束状态*/
		    animation-fill-mode:forwards;
		    -webkit-animation-fill-mode: forwards;  
		    -o-animation-fill-mode: forwards; 
		    -ms-animation-fill-mode: forwards;   
		    -moz-animation-fill-mode: forwards; 
		}
		.third-words{ 
		    opacity: 0;    
		    animation: fade-in 4s ease 4s 1;
		    -webkit-animation: fade-in 4s ease 4s 1;
		    -moz-animation: fade-in 4s ease 4s 1;
		    -o-animation: fade-in 4s ease 4s 1;
		    -ms-animation: fade-in 4s ease 4s 1;
		    
		    /*规定动画的最后状态为结束状态*/
		    animation-fill-mode:forwards;
		    -webkit-animation-fill-mode: forwards;  
		    -o-animation-fill-mode: forwards; 
		    -ms-animation-fill-mode: forwards;   
		    -moz-animation-fill-mode: forwards; 
		}
		.four-words{ 
		    opacity: 0;    
		    animation: fade-in 4s ease 6s 1;
		    -webkit-animation: fade-in 4s ease 6s 1;
		    -moz-animation: fade-in 4s ease 6s 1;
		    -o-animation: fade-in 4s ease 6s 1;
		    -ms-animation: fade-in 4s ease 6s 1;
		    
		    /*规定动画的最后状态为结束状态*/
		    animation-fill-mode:forwards;
		    -webkit-animation-fill-mode: forwards;  
		    -o-animation-fill-mode: forwards; 
		    -ms-animation-fill-mode: forwards;   
		    -moz-animation-fill-mode: forwards; 
		}
		.first{
			font-size: 20px;
			padding-top:10px;
			padding-left: 10px;
			color:#527392;
		}
		.wrp{
			background: url('./image/pic12.jpg');
			height:100%;
			width:100%;
			background-size: cover;
			background-repeat: no-repeat;
		}
		.wrp p{
			color:#527392;
		}
		.title{
			padding:10px 0;
			font-size: 15px;
		}
		.word{
			text-indent:2em;
			padding:15px 20px;
			font-size: 15px;
		}
		.fade-out{
			padding:0 50px; 
		}
		.fade-out p{
			font-size: 15px;
			margin-bottom: 10px;
			padding:0 30px;
		}
		.list{
			background: url('./image/pic14.jpg');
			height:100%;
			width:100%;
			background-size: cover;
			background-repeat: no-repeat;
		}
		.fea{
			color:#26c8b7;
			font-size: 20px;
			padding-top:10px;
			padding-left: 10px;
		}
		.pre{
			font-size: 20px;
			padding:10px 30px;
			color:#26c8b7;
		}
		.hot{
			margin-bottom: 20px;
			padding:20px 30px;
		}
		.hot p{
			font-size: 15px;
			padding:10px 0;
			color:#26c8b7;
		}
		.img{
			background: url('./image/pic15.jpg');
			height:100%;
			width:100%;
			background-size: cover;
			background-repeat: no-repeat;
		}
		.one{
			font-size: 25px;
			padding-top: 100px;
			padding-left: 50px;
		}
		.menu{
			padding-top: 50px;
			padding-left: 50px;
		}
		.menu p{
			font-size: 23px;
			padding:10px;
			color:#5e0536;
		}
		.res{
			background: url('./image/pic16.jpg');
			height:100%;
			width:100%;
			background-size: cover;
			background-repeat: no-repeat;
		}
		.second{
			font-size: 25px;
			padding-top: 150px;
			padding-left: 50px;
		}
		.two{
			margin-top:80px;
			margin-left: 50px;
		}
		.two p{
			font-size: 20px;
			padding-bottom: 10px;
		}
	</style>
</head>
<body>
	<div class="aui-slider-full">
		<div class="aui-slider-list text aui-bg-primary  aui-text-center">
			<div class="pic">
				<p><b>《黑龙江省全民健身实施计划（2016-2020年）》将于近期下发了，下面让我们了解一下《《黑龙江省全民健身实施计划（2016-2020年）》有哪些具体内容。</b></p>
			</div>
		</div>
		<div class="aui-slider-list aui-flex-col aui-flex-middle">
			<div class="ins">
				<p class="time">《黑龙江省全民健身实施计划（2016-2020年）》即将正式发布，其中包括几方面内容。</p>
				<div class="fade-in">
					<p class="first-words">总体要求——极其明确</p>
					<p class="second-words">目标任务——非常全面</p>
					<p class="third-words">主要措施——相当齐全</p>
					<p class="four-words">实施保障——十分靠谱</p>
				</div>
			</div>
		</div>
		<div class="aui-slider-list aui-flex-col aui-flex-middle">
			<div class="wrp">
				<p class="first"><b>一、总体要求</b></p>
				<p class="title"><b>（一）指导思想</b></p>
				<p class="word">深入贯彻落实党的十八大三中、四中、五中会议和省委十一届六次全会的有关精神，以“四个全面”战略布局为统领，以增强人民体质、提高健康水平为根本目标，以满足广大人民群众日益增长的健身需求为出发点，坚持创新、协调、绿色、开放、共享的发展理念，坚持体育事业公益性，逐步完善符合省情、比较完整、覆盖城乡、可持续的全民健身公共服务体系，保障公民参加体育健身活动的合法权益，大力开展全民健身运动，优化群众体育发展环境，促进全民健身与竞技体育协调发展，提高人民群众的身体素质、健康水平和生活质量，努力奠定建设体育强省的坚实基础。</p>
				<p class="title"><b>（二）主要原则</b></p>
				<div class="fade-out">
					<p class="first-list">坚持改革引领，创新驱动</p>
					<p class="second-list">坚持以人为本，注重实效</p>
					<p class="third-list">坚持统筹兼顾，分类指导</p>
					<p class="four-list">坚持依法治体，确保基本</p>
					<p class="five-list">坚持突出重点，全面发展</p>
				</div>
			</div>
		</div>
		<div class="aui-slider-list text ">
			<div class="list">
				<p class="fea"><b>二、目标任务</b></p>
				<p class="pre">到2020年要实现以下目标</p>
				<div class="hot">
					<p>1.经常参加体育锻炼的人数占人口比例达到36%。</p>
					<p>2.人均体育场地面积达到1.65平方米。</p>
					<p>3.乡居民达到《国民体质测定标准》合格以上的人数比例达到92%。</p>
					<p>4.充分发挥全民健身的核心功能与多元化功能，全民健身的教育、经济和社会等功能进一步发挥，与各项社会事业互促发展的局面基本形成，提高全民健身消费在体育产业中的比重。</p>
					<p>5.建成与黑龙江省经济、社会发展水平相协调，基本满足广大居民体育健身需求、覆盖城乡、设施齐全、活动丰富的高水平的全民健身公共服务体系。</p>
					<p>6.全民健身成为健康龙江行动的有力支撑，群众体育事业达到新水平。</p>
				</div>
			</div>
		</div>
		<div class="aui-slider-list text  ">
			<div class="img">
				<p class="one">三、主要措施</p>
				<div class="menu">
					<p>创新全民健身治理体制</p>
					<p>完善全民健身工作机制</p>
					<P>建立全民健身评价体系</P>
					<p>创新全民健身激励机制</p>
				</div>
			</div>
		</div>
		<div class="aui-slider-list text  ">
			<div class="res">
				<p class="second">四、实施保障</p>
				<div class="two">
					<p>1.加强组织领导与协调</p>
					<p>2.加大资金投入与管理</p>
					<p>3.完善政策与法治保障</p>
					<p>4.严格过程监管与绩效评估</p>
				</div>
			</div>
		</div>
		<span class="aui-slider-up">
			<i class="aui-iconfont aui-icon-fold"></i>
		</span>
	</div>
	<script src="./script/api.js"></script>
	<script src="./script/aui-slider-full.js"></script>
	<script type="text/javascript">
		apiready = function(){
			api.parseTapmode();
		}
		var sliderFull = new auiSliderFull({
			direction:'y'
		});
		// $aui.sliderUp($api.byId("sliderNav"));
	</script>
</body>
</html>
