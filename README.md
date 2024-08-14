# assignment 2
<!DOCTYPE html>
<html>
<head>
	<title>User Data Form</title>
	<style>
		/* Add some basic styling to make the form look nicer */
		body {
			font-family: Arial, sans-serif;
		}
		
		.form-container {
			width: 50%;
			margin: 40px auto;
			padding: 20px;
			background-color: #f9f9f9;
			border: 1px solid #ddd;
			border-radius: 10px;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		}
		
		.form-control {
			margin-bottom: 20px;
			padding: 10px;
			width: 100%;
		}
		
		.form-control label {
			display: block;
			margin-bottom: 10px;
		}
		
		.form-control input[type="text"],
		.form-control input[type="email"],
		.form-control textarea {
			width: 100%;
			padding: 10px;
			margin-bottom: 20px;
			border: 1px solid #ccc;
		}
		
		.form-control input[type="submit"] {
			background-color: #4CAF50;
			color: #fff;
			padding: 10px 20px;
			border: none;
			border-radius: 5px;
			cursor: pointer;
		}
		
		.form-control input[type="submit"]:hover {
			background-color: #3e8e41;
		}
	</style>
</head>
<body>
	<div class="form-container">
		<h2>User Data Form</h2>
		<form action="submit_form.php" method="post">
			<div class="form-control">
				<label for="name">Name:</label>
				<input type="text" id="name" name="name" required>
			</div>
			<div class="form-control">
				<label for="email">Email:</label>
				<input type="email" id="email" name="email" required>
			</div>
			<div class="form-control">
				<label for="message">Message:</label>
				<textarea id="message" name="message" required></textarea>
			</div>
			<div class="form-control">
				<input type="submit" value="Submit">
			</div>
		</form>
	</div>
</body>
</html>
