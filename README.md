# first_html
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title>test1</title>
	<link rel="stylesheet" href="">
	<style>
		#dd{
			padding: 0px;
			margin:200px auto;
			width:200px;
			height:200px;
			border:1px solid #000;
			text-align: center;
		}
		p{
			margin:0px;
			height:100%;
			line-height:200px;
		}
	</style>
	<script>
		window.onload=function(){
			var cc = document.getElementById('dd');
			cc.onclick = function(){
				cc.style.background = 'blue';	
			}
		}
	</script>
</head>
<body>
	<div id="dd">
		<p>点我变色!</p>
	</div>	
</body>
</html>
