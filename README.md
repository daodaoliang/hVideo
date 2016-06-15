基于html5的播放器
====================
### 引入相应js和css,然后实例化即可使用
### 在head标签内引入fz-video.css与iconfont.css
		<link rel="stylesheet" href="./fz-video.css">
		<link rel="stylesheet" href="./font/iconfont.css">

### 在body底部引入fz-video.js
		<script src="./fz-video.js"></script>

### 随后实例化播放器即可
		<script>
			var test = new createVideo(
	 		"testBox",	//容器的id
		 		{
		 			url 		: 'http://171.15.197.89/xdispatch/o8t28neoq.bkt.clouddn.com/test.mp4', 	//视频地址
		 			autoplay	: true			//是否自动播放
		 		}
	 		);
	 	</script>
