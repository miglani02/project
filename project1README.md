<html>
<head>
 	<title> Form </title>
	<style>
		body	{ background-image:url('https://www.freecodecamp.org/news/content/images/2021/06/w-qjCHPZbeXCQ-unsplash.jpg');background-position:left top; background-repeat:no-repeat; background-attachment:fixed; background-size:1550px 800px;}

		* {
			font-family: "Times New Roman", Times, serif;
  			color: red;
			font-size:12px;
		}
		label { 
			font-family: Arial, Helvetica, sans-serif;
			font-size:14px;
			color:black; 
		}
		
	</style>
</head>
<body> 

<h2 align="center" > REGISTRATION FORM </h2>
<hr>
<form method="GET" action="/cgi-bin/comments.exe">
 <label for="name"> 1. Name of the Participant: </label>  <input type="text" id="name" name="form" placeholder="Enter your name" size="25px" maxlength="30"> <br> <br>
 <label for="address"> 2. Enter your address: </label> <textarea rows="4" cols="60" id="address" name="form" wrap="virtual" placeholder="Enter Address"> </textarea> <br> <br>
 <label for="mail"> 3. E-Mail: </label> <input type="email" id="mail" name="form" placeholder="Enter your E-mail" size="25px" maxlength="30"> <br> <br>
 <label for="number"> 4. Contact Number: </label> <input type="number" id="number" name="form" placeholder="Enter your contact no." size="25px" maxlength="30"> <br> <br>
</form>

<table border="2px" width="50%" cellsapcing="2px" align="center">
	<tr align="center">
		<th> S.No. </th>
		<th> Item Name </th>
		<th> Quantity </th>
	</tr>
	<tr align="center">
		<td> <input type="number" name="serial" placeholder="Enter S.No." size="5px" maxlength="30"> </td>
		<td> <input type="text" name="item" placeholder="Enter Name" size="10px" maxlength="30"> </td>
		<td> <input type="number" name="quan" placeholder="Enter Name" size="10px" maxlength="30"> </td>
	</tr>
	<tr align="center">
		<td> <input type="number" name="serial" placeholder="Enter S.No." size="5px" maxlength="30"> </td>
		<td> <input type="text" name="item" placeholder="Enter Name" size="10px" maxlength="30"> </td>
		<td> <input type="number" name="quan" placeholder="Enter Name" size="10px" maxlength="30"> </td>
	</tr>
</table>
</body>
</html>
