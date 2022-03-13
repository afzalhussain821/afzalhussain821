<!DOCTYPE HTML>
<html>
<head>
	<meta charset="UTF-8">
	<title>Sign in</title>
	<link rel="stylesheet" href="style.css">
</head>
<style>
	p1
	{
		color: #87CEFA;
	}
	

	input[type="text"]
	{
		border-color: black;
		width: 220px;
		height: 30px;
		border-radius: 5px 5px 5px 5px;
	}
	button
	{
		width: 100px;
		height: 25px;
		color: white;
		margin-left:300px;
		border-color: black;
		background-color: #1E90FF;
	}
	label
	{
		width: 170px;
		display: inline-block;
		border-radius: 5px 5px 5px 5px;
	}
	p
	{
		font-weight: bold;
	}
	table,th,td
	{
		border: 1px solid black;
		
	}
	#table1
	{
		border-collapse:collapse;
	}
	#table,th 
	{
		color: white;

		width: 200px;
		height: 60px;
		text-align: center;
		background-color:#818589;
	}
	#table,td 
	{
		width: 200px;
		height: 60px;
		text-align: center;
	}
</style>
<body>
	<center>
</------------------------------------- Add Contact -----------------------------------------/>
	

			<h1>Contact Form and Contact List Page</h1>


			<br><br>
			<p style="font-weight: bold;font-size:20px;margin-left:105px">Add Contacts</p>

					<div class="one">
						<label for="Name">Name</label>
						<input type="text" id="Name" name="Name">
					</div>

				<br>

					<div class="two">
						<label for="number">Ph No.</label>
						<input type="text" id="Ph No." name="Ph No.">
					</div>


				<br>

					<div class="three">
						<label for="Email">Email</label>
						<input type="text" id="Email" name="Email">
					</div>
				<br>

					<button>Save</button>
<br><br>
</------------------------------------------My Contact-------------------------------->
<br><br>

	<caption><strong>My Contact</strong></caption>

<table>
<table id="table1">

	<tr>
		<th>Name</th>
		<th>Ph No.</th>
		<th>Email</th>
	</tr>


	<tr>
		<td>Virat Kohli</td>
		<td>9191912321</td>
		<td>viratkohli@bcci.in</td>
	</tr>


	<tr>
		<td>Dhoni</td>
		<td>9122321122</td>
		<td>dhoni@csk.in</td>
	</tr>
</div>
</table>
		
</center>
</body>
</html>
