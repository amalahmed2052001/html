# html
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
 }

* {
  box-sizing: border-box;
}

/* Add padding to containers */
.container {
  padding: 16px;
  background-color: white;
}

/* Full-width input fields */
input[type=text1]{
  width: 30%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}
    
    
    textarea#w3review{
        
         width: 50%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1; 
    }
    select{
        
     width: 50%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}
    
    
    input[type=text]{
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}
    
    
    
    
    input[type=password] {
  width: 100%;
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

/* Overwrite default styles of hr */
hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}

/* Set a style for the submit button */
.registerbtn {
  background-color: #4CAF50;
  color: white;
  padding: 16px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

.registerbtn:hover {
  opacity: 1;
}

 a {
  color: dodgerblue;
}

 
.signin {
  background-color: #f1f1f1;
  text-align: center;
}
    
    
 span.helper-text1 {
    margin-left: 30.5em;
     color: gray;
}
   span.helper-text {
     color: gray;
       }
    
</style>
</head>
<body>

<form action="/action_page.php">
  <div class="container">
    <h1>Coustmer Details</h1>
     <hr>
   
      
      
    <label for="text"><b>Fullname</b>
 
 </label>
      <br>
      
    <input type="text1"  name="Fullname" id="Fullname" required>
       

    <input type="text1"  name="Fullname" id="Fullname" required>
 <br>
              <span class="helper-text" data-error="wrong" data-success="right">FirstName</span>  
             <span class="helper-text1" data-error="wrong" data-success="right">LastName</span>

      <br>
      <Br>
    <label for="text"><b>Address</b></label>
    <input type="text"  name="Fullname" id="Fullname" required>
           <br>
              <span class="helper-text" data-error="wrong" data-success="right">Street Address</span>  
<br>
        <br>

      
         <input type="text1"  name="city" id="Fullname" required>
  <br>
           <br>
 
          
              <span class="helper-text" data-error="wrong" data-success="right">Street Address Line 2</span>  
          
          <br>
          
          
          
    <input type="text1"  name="state" id="Fullname" required>
    <input type="text1"  name="state" id="Fullname" required>
 <br>
              <span class="helper-text" data-error="wrong" data-success="right">City </span>  
             <span class="helper-text1" data-error="wrong" data-success="right">State /Province</span>

      <br>
          <br>
          
          
     
          <input type="text"  name="postl/zip code" id="Fullname" required>

          
          
        <br>
           <br>
 
          
              <span class="helper-text" data-error="wrong" data-success="right">Postal/Zip Code</span>  
          <br>
          <br>
        <label for="text1"><b>phoneNumber</b></label>
      <br>
      
    <input type="text1"  name="phoneNumber" id="phoneNumber" required>
 
      <br>
      
           <label for="text1"><b>Email</b></label>
      <br>
      
    <input type="text1"  name="Email" id="Email" required>
  <br>
      <hr>
      
              <label for="text"><b>How Did you Hear About Us</b></label>
<br>
      
      <select name=Select  style="max-width:90%;">
 <option value=af>please Select</option>
 <option value=af>please Select</option>
 ...
 <option value=af>please Select</option>
 ...
</select>
      
      <br>
      
      
              <label for="text"><b>Feedback about Us</b></label>
      
      <br>
      
<textarea id="w3review" name="w3review" rows="4" cols="50">
   </textarea>
      
      
      
      
            <br>
      
      
              <label for="text"><b>Suggestions if any for future improvment</b></label>
      
      <br>
      
<textarea id="w3review" name="w3review" rows="4" cols="50">
   </textarea>
      
      
      <br>
                    <label for="text"><b>Will you be willing to recommend us</b></label>

      <br>
      
        <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> Yes</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> No</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> Maybe</label><br><br>
      
    <button type="submit" class="registerbtn">Submit</button>
  </div>
  
  
    
    
</form>

</body>
</html>

