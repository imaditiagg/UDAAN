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
};
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
<!--header -->
<header  class="w3-container w3-center  w3-padding-64" style="padding:128px 16px">
  <div class="w3-row-padding w3-padding-64 w3-container"  style="background-image: url(20.png);background-size: 100% 100%; padding:156px 16px">
   <div class="w3-content">

 <div class="w3-center " >
<br><br><br>
      <h1 style="font-size:56px;font-family:goudy old style;font-weight: bold;color:white">CONTACT US </h1>
<br><br><br><br>
    </div>
  </div>
</div>
</header>


<div class="w3-row-padding w3-padding-64 w3-container">
   <div class="w3-content ">

 <div class="w3-half ">
 <h3>	Wanna connect with us ? <br>
Drop us a message now, we'll get back to you. </h3>
 	<form method="POST" action="contact.php">
 		<input type="text" placeholder="Your Name *" class="form-control" name="name" id="name" required><br><br>
        <input type="email" placeholder="Your Email" class="form-control" name="email" id="email" ><br><br>
         <input type="tel" pattern='([\+]?)(\d{2})?[\d]{10}' placeholder="Your Phone number *" class="form-control" name="phone" id="phone" required><br><br>
         <input type="text" placeholder="Subject *" class="form-control" name="subject" id="subject" required><br><br>
         <textarea rows="6" placeholder="Message *" class="form-control" name="message" id="message" required></textarea>  <br><br>
         <input type="submit" id="contact-submit" name="submit" value="Send Message" style=" background-color: #4CAF50;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    "><br>
</form>
 	</div>
 	<div class="w3-half ">
 <center>	<h3>FIND US</h3></center>
 <br>  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3500.827443046241!2d77.23215831438614!3d28.664884982405006!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390cfd04014bc31b%3A0x776d29e1c94c7468!2sIndira+Gandhi+Delhi+Technical+University+For+Women!5e0!3m2!1sen!2sin!4v1524890574456" width="600" height="490" frameborder="0" style="border:0;" allowfullscreen></iframe>
</div>
</div>
</div>
</header>


  <table>
  <tr>
    <td> &#160;&#160;</td>
  <td class=" w3-black  w3-padding-32 w3-container" style="opacity: 0.25;padding:150px"> 

  	  <center><i class="fa fa-map-marker" style="font-size: 80px ; color:white;"></i> </center> 
        <span style="font-size:16px">
         IGDTUW  
<br>

         Kashmere Gate <br>
        
         New Delhi, Delhi 110006</span>
</td>
<td>&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;</td>
<td class=" w3-black  w3-row-padding w3-padding-64 w3-container" style="opacity: 0.25;padding:150px">
 
<center><i class="fa fa-envelope" style="font-size: 80px ; color:white; "></i> </center>


<span style="font-size:17px">udaan.india@gmail.com</span>
</td>
<td>&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;</td>
<td class=" w3-black  w3-row-padding w3-padding-64 w3-container" style="opacity: 0.25;padding:150px">
 
 <center><i class="fa fa-phone" style="font-size: 80px ; color:white; "></i> </center>
<span style="font-size:16px">+91 99999-11111 <br>
+91 11111-99999</span>
 </td>
 </tr>
</table>
</div>
<br><br>

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
$name = $_POST["name"];
$email =$_POST["email"];
$phone=$_POST["phone"];
$subject=$_POST["subject"];
$message=$_POST["message"];
$sql =" INSERT INTO  contact VALUES ('$email','$name','$phone','$subject',
      '$message')";
    $conn->exec($sql);
    echo "<script> alert('Thanks for contacting.. We will get back to you soon') </script>";
    }
}
    catch(PDOException $e)
    {
    echo $sql . "<br>" . $e->getMessage();
    }

    $conn = null;
?>


