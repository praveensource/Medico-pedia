# Medico-pedia<!DOCTYPE html>
<html>
    <script>
        var firstname=document.getElementById("txt").value;
        localStorage.setItem("textvalue",firstname);
        return false;
    </script>
    
<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}


input[type=text], input[type=password] {
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


button {
  background-color: #04AA6D;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

button:hover {
  opacity:1;
}


.cancelbtn {
  padding: 14px 20px;
  background-color: #f44336;
}


.cancelbtn, .signupbtn {
  float: left;
  width: 50%;
}


.container {
  padding: 16px;
}


.modal {
  display: none; 
  position: fixed; 
  z-index: 1;
  left: 0;
  top: 0;
  width: 100%; 
  height: 100%; 
  overflow: auto; 
  background-color: #474e5d;
  padding-top: 50px;
}


.modal-content {
  background-color: #fefefe;
  margin: 5% auto 15% auto; 
  border: 1px solid #888;
  width: 80%; 
}


hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}
 

.close {
  position: absolute;
  right: 35px;
  top: 15px;
  font-size: 40px;
  font-weight: bold;
  color: #f1f1f1;
}

.close:hover,
.close:focus {
  color: #f44336;
  cursor: pointer;
}


.clearfix::after {
  content: "";
  clear: both;
  display: table;
}

@media screen and (max-width: 300px) {
  .cancelbtn, .signupbtn {
     width: 100%;
  }
}
.search
{
  font-size: 140px;
  width: 300px;
  padding-top:10px;
  padding-bottom:10px;
}
.paddi
{
  width:90px;
}


        .header-image
{
  padding-bottom:10px;
  padding-left: 5px;
  background-position: center top;
  width: 100px;
}
h1
{
  font-size: 55px;
  text-align: center;
  padding-top: -60px;
  color: rgb(13, 0, 255);
  
}
.legal
{
  padding-top: 0px;
  font-size: 18px;
}
p
{
  font-size: 18px;
}
.box
{
  background-color: crimson;
  width: 1870px;
  
}
.box1
{
  background-color: lightblue;
  color: black;
  padding: 20px;
  font-family: sans-serif;
}
.dropdown
{
  padding-left: 1790px;
  font-size:20px;
}
.option
{
  font-size: 20px;
  padding-top: 10px;
}
html
{
  background-color:lightblue;
}
.search
{
  font-size: 20px;
}

body {font-family: Arial, Helvetica, sans-serif;}

/* Full-width input fields */
input[type=text], input[type=password] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}


button {
  background-color: #04AA6D;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
}

button:hover {
  opacity: 0.8;
}


.cancelbtn {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
}

.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
  position: relative;
}

img.avatar {
  width: 40%;
  border-radius: 50%;
}

.container {
  padding: 16px;
}

span.psw {
  float: right;
  padding-top: 16px;
}


.modal {
  display: none; 
  position: fixed; 
  z-index: 1; 
  left: 0;
  top: 0;
  width: 100%; 
  height: 100%; 
  overflow: auto; 
  background-color: rgb(0,0,0); 
  background-color: rgba(0,0,0,0.4); 
  padding-top: 60px;
}


.modal-content {
  background-color: #fefefe;
  margin: 5% auto 15% auto; 
  border: 1px solid #888;
  width: 80%; 
}


.close {
  position: absolute;
  right: 25px;
  top: 0;
  color: #000;
  font-size: 35px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: red;
  cursor: pointer;
}


.animate {
  -webkit-animation: animatezoom 0.6s;
  animation: animatezoom 0.6s
}

@-webkit-keyframes animatezoom {
  from {-webkit-transform: scale(0)} 
  to {-webkit-transform: scale(1)}
}
  
@keyframes animatezoom {
  from {transform: scale(0)} 
  to {transform: scale(1)}
}

@media screen and (max-width: 300px) {
  span.psw {
     display: block;
     float: none;
  }
  .cancelbtn {
     width: 100%;
  }
}
.cla
{
  width:auto ;
}
.small
{
  width: auto;
  background-color: peru;
}
</style>
<head>
    <title>Medico-Pedia
    </title>
    <!-- <link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
<script defer src="https://pyscript.net/latest/pyscript.js"></script> -->
</head>
<body>

    <div>
        <img class="header-image" src = "https://www.shutterstock.com/image-vector/pediatric-clinic-logo-vector-illustration-600w-1632141514.jpg"></div>
        <center>
          <h1><b  class="box1"><U>Welcome to  Medicopedia</u></b>
          </h1>
          </center>

          <div>
            
<button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Sign Up</button>

<div id="id01" class="modal" >
  <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
  <form class="modal-content"id="profile-form" action="fitness.html">
    
    <div class="container">
      <h1>Sign Up</h1>
      <p>Please fill in this form to create an account.</p>
      <hr>
      <label for="email"><b>Email</b></label>
      <input type="text" placeholder="Enter Email" name="email" required>

      <label for="psw"><b>Password</b></label>
      <input type="password" placeholder="Enter Password" name="psw" required>

      <label for="psw-repeat"><b>Repeat Password</b></label>
      <input type="password" placeholder="Repeat Password" name="psw-repeat" required>
      
      <label>
        <input type="checkbox" checked="checked" name="remember" style="margin-bottom:15px"> Remember me
      </label>

      <p>By creating an account you agree to our <a href="#" style="color:dodgerblue">Terms & Privacy</a>.</p>
      
      <div class="clearfix">
        
        <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
    
        <button type="submit" class="signupbtn">Sign Up</button></a>
      </div>    
    </div>
  </form>
</div>
 </div>
        <center>
          <form id="searchForm">
    <input class="small" type="text" id="searchInput" placeholder="Enter tablet/disease name">
    <button class ="small" type="submit">Search</button>
  </form>
          <script>
    document.getElementById('searchForm').addEventListener('submit', function(event) {
      event.preventDefault(); 
      const searchQuery = document.getElementById('searchInput').value;
      handleSearch(searchQuery);
    });
    function handleSearch(query) {
      let targetPage;
      switch (query) {
        case 'Paracetamol':
          targetPage = '1.html';
          break;
        case 'ibuprofen':
          targetPage = '2.html';
          break;
          case 'Angiotensin':
          targetPage = '3.html';
          break;
          case 'Dehydroemetine':
          targetPage = '4.html';
          break;
          case 'Antacid':
          targetPage = '5.html';
          break;
          case 'Headache':
          targetPage="headache.html";
          break;
          case 'Stomach pain':
          targetPage="stomach.html";
          break;
          case 'Acidity':
          targetPage="acidity.html";
          break;
        default:
          targetPage = 'default.html';
          break;
      }
      window.location.href = targetPage;
    }
  </script>
        </center>

        
        
<p class ="legal box">
  
    LEGAL DISCLAIMER: <br>The web-site with a view to provide information useful to the people concerning the department at one place. Effects have been made to provide accede and true information on the web-site. However, there may be flaws. It you have to olive for it. You are requited to contact us. We shall make all ended yours to correct or mistakes brought to our notice in order to keep the web-site updated.</br></p>


</body>
</html>
