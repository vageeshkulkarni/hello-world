<html>
<head>
<script>




</script>
</head>

<body>

<form action="action_page.php" oninput="x.value=parseInt(a.value)+parseInt(b.value)">
  <fieldset>
    <legend>Personal information:</legend>
  First name:<br>
  <input type="text" name="firstname" value="Mickey">
  <br>
  Last name:<br>
  <input type="text" name="lastname" value="Mouse">
  <br>
  

  <input type="radio" name="gender" value="male" checked> Male<br>
  <input type="radio" name="gender" value="female"> Female<br>
  <input type="radio" name="gender" value="other"> Other<br>

  <input type="range" id="a" name="a" value="50">
  100 +
  <input type="number" id="b" name="b" value="50">
  =
  <output name="x" for="a b"></output>

  <select name="cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="fiat">Fiat</option>
    <option value="audi" selected>Audi</option>
  </select> 
  <br>

  <p>write about your hobbies </p>
  <textarea name="message" rows="10" cols="30"></textarea>

  <button type="button" onclick="alert('do you  written all fields!')">before sumbit click me!</button><br>

  </fieldset>
  <br><br>

  <fieldset>
      <legend>your Personal Computer information:</legend>
      <p> write which browser you using </p>
  <input list="browsers" name="browser">
  <datalist id="browsers">
    <option value="Internet Explorer">
    <option value="Firefox">
    <option value="Chrome">
    <option value="Opera">
    <option value="Safari">
  </datalist>
 
  <p>write other specifications about your PC </p>
  <textarea name="message" rows="10" cols="30"></textarea>

  </fieldset>

  <br><br>




  <input type="submit" value="Submit">

</form> 

<p>If you click the "Submit" button, the form-data will be sent to a page called "action_page.php".</p>

</body>
</html>
