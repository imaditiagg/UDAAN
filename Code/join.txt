<!DOCTYPE html>
<html>
<title>UDAAN</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"> 


<style>
body,h1,h2,h3,h4,h5,h6,table {font-family: Georgia, sans-serif}
.w3-bar,h1,button {font-family: "Georgia", sans-serif}
input[type=text],input[type=email],input[type=date],input[type=tel],input[type=file], select, textarea {
    width: 80%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    resize: vertical;
}

label {
    padding: 12px 12px 12px 200px;
    display: inline-block;
}

input[type=submit] {
    background-color: #4CAF50;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    
}
input[type=submit]:hover {
    background-color: #45a049;
}
.container {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
}

.col-25 {
    float:left;
    width: 25%;
    margin-top: 6px;
}

.col-75 {
    float: left;
    width: 75%;
    margin-top: 6px;
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}
@media screen and (max-width: 600px) {
    .col-25, .col-75, input[type=submit] {
        width: 100%;
        margin-top: 0;
    }
}
</style>
<body>

<!-- Navbar -->
<div class="w3-top" >
  <div class="w3-bar w3-blue w3-card w3-left-align w3-large" >
    <a class="w3-bar-item w3-button w3-hide-medium w3-hide-large w3-right w3-padding-large w3-hover-white w3-large w3-red" href="javascript:void(0);" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
    <a href="home.html" class="w3-bar-item w3-button w3-padding-large w3-hover-white">HOME</a>
    <a href="about.html" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">ABOUT US</a>
    <a href="analysis.html" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">ANALYSIS</a>
    <a href="join.php" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">JOIN US</a>
    <a href="contact.php" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">CONTACT US</a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium w3-large">
    <a href="home.html" class="w3-bar-item w3-button w3-padding-large">HOME</a>
    <a href="about.html" class="w3-bar-item w3-button w3-padding-large">ABOUT US</a>
    <a href="analysis.html" class="w3-bar-item w3-button w3-padding-large">ANALYSIS</a>
    <a href="join.php" class="w3-bar-item w3-button w3-padding-large">JOIN US</a>
    <a href="contact.php" class="w3-bar-item w3-button w3-padding-large">CONTACT US</a>
  </div>
  </div>
</div>


<!-- Header -->


<header  class="w3-container w3-center  w3-padding-64" style="padding:128px 16px">
  <div class="w3-row-padding w3-padding-64 w3-container" style="background-image: url(12.png);background-size: contain; padding:158px 16px>
   <div class="w3-content">

 <div class="w3-center " style="font-family:goudy old style;font-weight: bold;color:white;font-size:10px">
<br><br><br>
      <h1>'GIVE HAPPINESS TO GET HAPPINESS'</h1>
<h3>Cheers!! Take a bow, you are doing well in life. To help others becomes an asset to the nation, join us !! Impart knowledge to the younger generation and help them broom.</h3>
<br><br><br>
    </div>
  </div>
</div>
</header>


<!-- First Grid -->

<div class="w3-row-padding w3-padding-64 w3-container">
   <div class="w3-content">

 <div class="w3-center ">

      <h2 style="font-family:goudy old style;font-weight: bold">‘KNOWLEDGE IS THE KEY’</h2>
<h5>If you would like to join us, fill up the form below and attach your resume. We'll contact you for further details.</h5>
    </div>
  </div>
</div>
<!--Second grid -->

<div class="w3-container">
  <form method="POST" action="join.php" enctype="multipart/form-data">
     <div class="row">
      <div class="col-25">
        <label for="name">Name</label>
      </div>
      <div class="col-75">
        <input type="text" id="name" name="name" placeholder="Your name.." required>
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="gender">Gender</label>
      </div>
      <div class="col-75">
        <input type="radio" id="gender" name="gender" value="male">Male
        &#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;
        <input type="radio" id="gender" name="gender" value="female">Female
        
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="dob">Date of Birth</label>
      </div>
      <div class="col-75">
        <input type="date" id="dob" name="dob" placeholder="Your DOB.." required>
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="email">Email</label >
      </div>
      <div class="col-75">
        <input type="email" id="email" name="email" placeholder="Your Email.." required>
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="contact">Contact No</label>
      </div>
      <div class="col-75">
        <input type="tel" id="contact" name="contact" placeholder="Your Contact.." required>
      </div>
    </div>
     <div class="row">
      <div class="col-25">
        <label for="qualification">Qualifications
        </label>
      </div>
      <div class="col-75">
        <input type="text" id="qualification" name="qualification" placeholder="Your Qualifications.." required>
      </div>
    </div>
    <div class="col-25">
        <label for="address">Address</label>
      </div>
      <div class="col-75">
        <textarea id="address" name="address" placeholder="Your Address.." style="height:150px"></textarea>
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="city">City</label>
      </div>
      <div class="col-75">
        <input type="text" id="city" name="city" placeholder="Your City.." required>
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="state">State</label>
      </div>
      <div class="col-75">
        <input type="text" id="state" name="state" placeholder="Your State.." required>
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="pincode">Pin Code
        </label>
      </div>
      <div class="col-75">
        <input type="text" id="pincode" name="pincode" placeholder="Your Pin Code.." required>
      </div>
    </div>
     <div class="row">
      <div class="col-25">
        <label for="cv">Upload your CV
        </label>
      </div>
      <div class="col-75">
        <input type="file" id="cv" name="cv" required>
      </div>
    </div>
   
    <br><br>
   <center> <div class="row">
      <input type="submit" name="submit" value="Submit">
    </div></center>
  </form>
<br><br>
  </div>

<!-- Third grid -->


  <div class="w3-container w3-black w3-center w3-opacity w3-padding-64">
    <h3> WHAT DO YOU THINK ?<br> </h3>
    <h4>You can help too. Join our initiative and help us reform INDIA.</h4>
    <br>
    <a href="join.php" class="w3-button w3-blue w3-padding-large w3-large w3-margin-top">JOIN US</a>
</div>

<!-- Footer -->
<footer class="w3-container w3-padding-32 w3-center w3-opacity">  
  <div class="w3-xlarge w3-padding-32">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
 </div>

</footer>

<script>
// Used to toggle the menu on small screens when clicking on the menu button
function myFunction() {
    var x = document.getElementById("navDemo");
    if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
    } else { 
        x.className = x.className.replace(" w3-show", "");
    }
}
</script>
</body>
</html>

<?php
$servername = "localhost";
$username = "root";
$password = "";

try {
  try{
    $conn = new PDO("mysql:host=$servername;dbname=innervedb", $username, $password);
    // set the PDO error mode to exception
    $conn->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);
    
}
 catch(PDOException $e)
    {
    echo $sql . "<br>" . $e->getMessage();
    }
if(isset($_POST["submit"]))
{
  $name=$_POST['name'];
  $gender=$_POST['gender'];
  $dob=$_POST['dob'];
  $email=$_POST['email'];
  $contact=$_POST['contact'];
  $qualification=$_POST['qualification'];
  $address=$_POST['address'];
  $city=$_POST['city'];
  $state=$_POST['state'];
  $pincode=$_POST['pincode'];
  $file_name1=$_FILES["cv"]["name"];
  $filename2=$_FILES["cv"]["tmp_name"];
  $target_path1 = "documents/".$file_name1;
  if(move_uploaded_file($filename2, $target_path1))
{
  $sql =" INSERT INTO  joins VALUES ('$email','$name','$gender','$dob','$contact','$qualification','$address','$city','$state','$pincode',
  '$target_path1') " ;
    $conn->exec($sql);
    echo "<script> alert('Thank You for your response.. We will get back to you soon') </script>";
}
}
}

    catch(PDOException $e)
    {
    echo $sql . "<br>" . $e->getMessage();
    }

    $conn = null;
?>