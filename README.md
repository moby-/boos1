# boos1
ajax请求后台
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
		<style type="text/css">
		*{
			margin: 0 auto;
			font-family: "微软雅黑";
		}
		.bground{
		     background-image: url(img/background.jpg);
             width: 100%;
             height: 667px;
             margin: 0 auto;
             overflow: hidden;
		     }
		.surface{
		     width: 480px;
			height: 390px;
			background-color: #e7f7dc;
			margin: auto ;
			margin-top: 120px;	
			}
		.logo{
			width:480px;
			height: 190px;
			background-color: #55b8da;
			
		}
		.img{
			display: block;
			margin:auto;
		}
		.input{
			color: #015b99;
			font-size: 17px;
			font-weight: bold;
			margin-left: 100px;
		}
		
		.text{
			width: 210px;
			height: 30px;
			margin-left: 10px;
			margin-top: 20px;
		}	
		.input1{
			border: 0px;
			width: 200px;
			height: 30px;
			background-color: #4da1f7;
			color: white;
			border-radius: 4px;
			margin-left: 60px;
			display: block;
			margin-top: 20px;
			
		}
		#register{
			font-size: 13px;
			margin-left: 10px;
		}
		a#register:active{color: #2c84de;}
		</style>
		<script type="text/javascript">
         window.onload=function(){
         	var log=document.getElementById("log");
         	log.onmouseover=function(){
         		this.style.backgroundColor="#7ebbf9";
         	};
         	log.onmouseout=function(){
         		this.style.backgroundColor="#4da1f7";
         	}
         	log.onmousedown=function(){
         		this.style.backgroundColor="#2c84de"
         	}
         	log.onmouseup=function(){
         		this.style.backgroundColor="#7ebbf9"
         	}
         	log.onclick=function(){
//       		this.style.backgroundColor="#2c84de"
         		window.location.href="http://127.0.0.1:8020/%E5%AE%9E%E9%AA%8C%E5%AE%A4%E4%BD%9C%E4%B8%9A/zhuye.html";
         	}
         }
		</script>
	</head>
	<body>
		<div class="bground">
			<div class="surface">
				<div class="logo"><img class="img" src="img/logo.jpg"/></div>
				<form class="input" >账号：<input type="text" placeholder="请输入账号" name="账号" class="text"/><a id="register" href="http://127.0.0.1:8020/%E5%AE%9E%E9%AA%8C%E5%AE%A4%E4%BD%9C%E4%B8%9A/register.html">注册账号</a><br />
					密码：<input type="password" placeholder="密码" name="password" class="text"/>
				<input type="submit" id="log" value="登陆" class="input1"></input>
				</form>
				
			</div>
		</div>
		
	</body>
</html>
