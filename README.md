# Employee-Registration-form


<!DOCTYPE html>
<html>
<head>
<meta name="viewpoint" content="width=device-width,initial-scale=1">
</head>
<body>
<form>
   <div>
        <center><h1>	Employee Registration form</h1></center>
		<hr>	
		<label>First Name:</label>
		<input type="text"name="firstname"placeholder="firstname"size="10" required/><br><br>
		<label>Middlename:</label>
		<input type="text"name="middlename"placeholder="middlename"size="15" required/><br><br>
		<label>Lastname:</label>
		<input type="text"name="lastname"placeholder="lastname"size="15" required/><br><br>
<div>
<label>
Department:
</label>
<select>
<option value="course">Department</option>
<option value="course">Management</option>
<option value="course">Human Resource</option>
<option value="course">Customer Support</option>
<option value="course">Development</option>
<option value="course">Business</option>
<option value="course">Corporate Finance</option>
</select>
</div><br>
<div>
<label>
Gender:
</label><br>
<input type="radio" value="male" name="gender"checked>male<br>
<input type="radio" value="female" name="gender"checked>female<br>  
<input type="radio" value="other" name="gender"checked>other<br>

</div>
<br>
<label>
phone:
</label>
<input type = "text" name="country code"placeholder="country code"value="+91"size="2"/>
<input type="tel" name="phone"size="25"pattern"[0-9]{4}-[0-9]{6}"placeholder="1234-567890"required>
<br><br>
Current Address:
<textarea cols="80" rows="5" placeholder="current address"value="address" required>

</textarea><br><br>
<label for="myfile">Drop your Resume:</label>
<input type="file"id="myfile"name="myfile"><br><br>
<label for="email"><b>Email</b></label>
<input type="text"placeholder="Enter mail" name="mail"required><br><br>

<label for="psw"><b>password</b></label>
<input type="password"placeholder="enter password"name="psw"required>

<br><br>
<label for="psw-repeat"><b>Re-enter Password</b></label>
<input type="password"placeholder="Re-enter password name="psw-repeat"required><br><br>
<button type="submit"class="reqistration">Register </button>
</form>
</body>
</html>       
                       		 
       	 
