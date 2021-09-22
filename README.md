<!DOCTYPE html>
<html lang="vi">
<head>
	<meta charset="UTF-8">
	<title>Login</title>
	<link rel="stylesheet" href="css/login-style.css">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">		
	<script type="text/javascript" src="js/login.js" async></script>
</head>
<body>
	<div>
		<div class="login-page" id="login">
			<h1>Login</h1>
			<div class="input-box">
				<i class="fa fa-user-o"></i>
				<input type="text" placeholder="User Name" id="user">
			</div>
			<div class="input-box">
				<i class="fa fa-key"></i>
				<input type="password" placeholder="Password" id="pwd">
				<span class="eye" id="eye-icon">
					<i class="fa fa-eye" id="hide-eye"></i>
					<i class="fa fa-eye-slash" id="hide-eye-slash"></i>
				</span>
			</div>
			<button type="button" class="login-button" onclick="loginClick()">Login</button>
			<footer class= "login-footer">
				<p class="login-help">Need <a href="" style="color: #2196F3;">help?</a></p>
			</footer>
		</div>

		<div class="login-page" id="hello">
			<h3>Hi!</h3>
			<h1 id="user-name">User Name</h1>
			<p><a href="#" onclick="logoutClick()">Logout?</a></p>
		</div>
	</div>
</body>
</html>
