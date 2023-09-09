### Lion-Philip 👋



<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<style>
			body{
				width: 500px;
				height: 600px;
				margin: auto;
				position: absolute;
				top: 100px;
				right: 0;
				bottom: 0;
				left: 0;
				padding:100px;
			}
			.container{
				position: relative;
				width: 410px;
				min-height:420px;
				/*background: whitesmoke;*/
				background:url(../img/10.jpg);
				background-repeat: round;
			}
			.container h1{
				width: 400px;
				height: 70px;
				color:  #E9967A;
				text-align: center;
			}
			ul{
				list-style: none;
				float: right;
				margin-right: 20px;
				margin-bottom: 100px;
			}
			.big{
				width: 240px;
				height: 240px;
				border: 1px dashed gray;
				border-radius: 5px;
				box-shadow: 2px 2px 5px gray;
				position: absolute;
				top:90px;
				left: 50px;
				display: none;
			}
			/*第一个big*/
			.first{
				/*z-index: 8888;*/
				display: block;
			}
			
			.small{
				width: 45px;
				height: 45px;
				border-radius: 50%;
				box-shadow: 2px 2px 5px #808080;
				/*透明度*/
				opacity: 0.4;
				
			}
			.container .small:hover+.big{
				display: block;
			}
			
			.one{
				opacity: 1;
			}
			
			.container ul:hover .small{
				opacity: 0.4;
			}
			.container ul li .small:hover{
				opacity: 1;
			}
			
		</style>
	</head>
	<body>
		<div class="container">
			<h1>我的相册</h1>
			<ul>
				<li>
					<img src="https://img-blog.csdnimg.cn/6ee7cacc267b4ec8b570b2ab9c0a0ce1.png"/>
					<img src="https://img-blog.csdnimg.cn/6ee7cacc267b4ec8b570b2ab9c0a0ce1.png"/>
				</li>
				<li>
					<img src="https://img-blog.csdnimg.cn/6ee7cacc267b4ec8b570b2ab9c0a0ce1.png"/>
					<img src="https://img-blog.csdnimg.cn/6ee7cacc267b4ec8b570b2ab9c0a0ce1.png"/>
				</li>
				<li>
					<img src="https://img-blog.csdnimg.cn/6ee7cacc267b4ec8b570b2ab9c0a0ce1.png"/>
					<img src="https://img-blog.csdnimg.cn/6ee7cacc267b4ec8b570b2ab9c0a0ce1.png"/>
				</li>
				<li>
					<img src="https://img-blog.csdnimg.cn/6ee7cacc267b4ec8b570b2ab9c0a0ce1.png"/>
					<img src="https://img-blog.csdnimg.cn/6ee7cacc267b4ec8b570b2ab9c0a0ce1.png"/>
				</li>
			</ul>
		</div>
	</body>
</html>
