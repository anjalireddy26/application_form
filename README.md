# application_form
<!DOCTYPE html>
<html>
<body bgcolor="lightblue">
    <head> 
        <script type = "text/javascript">
        function fun() {
           alert ("This is an alert dialog box");
        }
  </script>
        </head>
<h2><center>Application Form</center></h2>
<hr>

<form>
  <p><label>First name:<input type='text' value=""/></label></p>
  <p><label>Last name:<input type="text" value=""/></label></p>
  <p><label>DOB: <input type="date"/></label></p>
  <p><label>Age:<input type="text" value=""/></label></p>
  
  <p><label>Branch:</label>
  <input type="text"></p>
  <p>Gender:
  <label >Male<input type="radio" name="gender" value="male"/></label>
<label >Female<input type="radio" name="gender" value="female"/></label></p>
<p><label>Email:<input type="text"/></label></p>  
<p><label for="fname">Father's first name:</label>
  <input type="text" value="">
  <label for="lname">Father's last name:</label>
  <input type="text"  value=""></p>
  <p>Occupation:
  <label>Private Employee<input type="checkbox"/></label>
  <label>Government Employee<input type="checkbox"/></label>
  <label>Farmer<input type="checkbox"/></label>
  <label>Business Men<input type="checkbox"/></label>
</p>
<p><label>Address<input type="text"/></label></p>
<p><label>For Alret!!! Message</label></p>
<input type = "button" value = "Click me" onclick = "fun();" />
</form>
</body>
</html>
