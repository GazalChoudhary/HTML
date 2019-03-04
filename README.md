<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<title>Registration Form</title>
<style type="text/css">
.container {
	padding: 10px;
	color: "white";
}

.container signin{
		width:70%;
		}
input[type=text], input[type=password] {
	width: 70%;
	padding: 15px;
	margin: 5px 0 22px 0;
	display: inline-block;
	border: none;
	background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
	background-color: #ddd;
	outline: none;
}


.registerbtn {
	background-color: #000000;
	color: white;
	padding: 16px 20px;
	margin: 8px 0;
	border: none;
	cursor: pointer;
	width: 70%;
	opacity: 0.9;
}

fieldset {
	font-size: 12px;
	padding: 10px;
	width: 500px;
	line-height: 2;
	align: "center";
}

.registerbtn:hover {
	opacity: 1;
}

/* Add a blue text color to links */
a {
	color: dodgerblue;
}

.col-75 {
	float: left;
	width: 75%;
	margin-top: 6px;
}

.body {
	color:#FFD700;
	
}

#footer {
	background-color: black;
	color: white;
	clear: both;
	text-align: center;
	padding: 5px;
}

.signin {
	background-color: #f1f1f1;
	text-align: center;
	width: 40%;
}

fieldset {
	text-align: "center";
	margin: 0 auto;
}
</style>
</head>
<body class="body">
<body background="C:\Users\Training\Desktop\kl.png">

	<fieldset class="fieldset"><legend align="center"><h1 ><b>Library Registration</b></h1></legend>
			<div class="container">
				
				<h2><p>Please fill in this form to create an account.</p></h2>
				<hr width="100%" align="left">
				<label for="name"><b>Name</b></label> <input type="text"
					placeholder="Enter your name" name="name" required> <br>
				<label for="email"><b>Email</b></label> <input type="text"
					placeholder="Enter Email" name="email" required> <br>
					
					<label for="date"><b>Birth date:</b></label><BR>

<input type="date" id="date" name="Birth date"
       value="2001-01-01"
       min="1970-01-01" max="2017-12-31">
					
			<br>	<label for="gender"><b>Gender</b></label> <input type="radio"
					name="gender" value="male" checked> Male <input
					type="radio" name="gender" value="female"> Female <input
					type="radio" name="gender" value="other"> Other <br>
				<div class="col-75">
				<label for="country"><b>College</b></label>
					<select id="College" name="College">
						<option value="Manav Rachna University">Manav Rachna
							University</option>
						<option value="Amity University">Amity University</option>
						<option value="Chandigarh University">Chandigarh
							University</option>
						<option value="MVN University">MVN University</option>
					</select>
				</div><br>

				<BR> <label for="psw"><b>Password</b></label> <input
					type="password" placeholder="Enter Password" name="psw" required>
				<br> <label for="psw-repeat"><b>Repeat Password</b></label> <input
					type="password" placeholder="Repeat Password" name="psw-repeat"
					required>
				<br><label for="txt"><b>Special Needs</b></label>	
				<font><i><textarea rows="4" cols="50">Type here name of your favourite authors and books!!</textarea></i></font>
				<hr width="100%" align="left">
				

				<p>
					By creating an account you agree to our <a href="#">Terms &
						Privacy</a>.
				</p>
				<button type="submit" class="registerbtn"><b>Register</b></button>
			</div>

			<div width: 100%>
				<p>
					Already have an account? <a href="#">Sign in</a>.
				</p>
			</div>
			</fieldset>
	</form>
<div id="footer">copyright@ Elibrary.com</div>
</body>
</body>
</html>
