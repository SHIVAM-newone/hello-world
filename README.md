<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
      <script src="https://code.jquery.com/jquery-3.4.1.js"></script>
</head>
<body>
	<nav>
		<ul>
			<li class="logo"><a href="">ShivamCodes</a></li>
			<div class="items">
				<li><a href="#">Home</a></li>
				<li><a href="#">About </a></li>
				<li><a href="#">Services</a></li>
				<li><a href="#">Contact Us</a></li>
				
			</div>
			<div class="searchbar">
				<input type="text" placeholder="Search..">
				<label >
					<span class="fas fa-search"></span>
				</label>
			</div>
			<div class="login">
				<button class="log">Login</button>
				<button class="log2">Sign in</button>
			</div>
		</ul>
	</nav>
	<style>
	  @import url('https://fonts.googleapis.com/css?family=Montserrat:400,500,600,700&display=swap');
		*{
			
  margin: 0;
  padding: 0;
  color: #f2f2f2;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
  text-decoration: none;
		}
		nav{
			background: black;
			color: #fff;
			border: 1px solid #000;
			border-left: none;
			border-right: none;
			text-decoration: none;

		}
		nav ul{
			display: flex;
			flex-wrap: wrap;
			align-items: center;
			justify-content: center;
			font-size: 18px;
			text-decoration: none;
		}
		nav ul li{
			list-style: none;
		}
		nav ul .logo{
			flex: 1;
			font-weight: 700;
			margin-left: 60px;
			font-size: 30px;
		}
		nav ul .items {
			display: inline-flex;
			padding: 5px 20px 5px 20px;
		}
nav ul .items li{
	padding: 5px 20px 5px 20px;
}
nav ul .items li a {
	font-size: 18px;
	transition: .4s;
}
nav ul .items li a:hover{
	color: cyan;
}
nav ul .searchbar{
	width: 300px;
	display: flex;
	align-items: center;
	height: 50px;
	margin-right: 100px;
}
	nav ul .searchbar input{
		width: 100%;
		padding: 10px;
		color: black;
		height: 40px;
		outline: none;
		border: none;
		

	}	
	nav ul .searchbar label{
		background: #fff;
		display: flex;
		align-items: center;
		justify-content: center;
		height: 40px;
		  background: #f2f2f2;
cursor: pointer;
		width: 50px;
		
	}
	nav ul .searchbar label:hover{
		background: #e6e6e6;
	}
nav ul .searchbar label span{
color: black;
	
}
.login{
	display: flex;
	align-items: center;
	margin-right: 30px;
	margin-left: 30px;
	padding: 20px;
}
.login .log{
font-size: 18px;
 background: #dc3545;
width: 100px;
cursor: pointer;
border: none;
transition: .3s;
outline: none;
height: 30px;
border-radius: 8px;

}
.login .log:hover{
	background: red;
}
.login .log2{
	font-size: 18px;
 background: #dc3545;
width: 100px;
border: none;
outline: none;
cursor: pointer;
transition: .3s;
height: 30px;
margin-left: 20px;
border-radius: 8px;
}
.login .log2:hover{
	background: red;
}
</style>
</body>
</html>
