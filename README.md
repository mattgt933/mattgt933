<!DOCTYPE html>
<html>
<head>
<title>ACA SC | Home</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lexend+Tera:wght@100;200;300;400&display=swap" rel="stylesheet"> 
        <style>
          * {
            font-family: 'Lexend Tera', sans-serif;
          }

            *::selection {
                color: #fff;
                background: #ddad69;
                font-weight: lighter;
            }
body {
  font-family: raleway, sans-serif;
}

#home {
 position: fixed;
 top:0px;
 left:0px;
 right:0px;
 z-index: 2;
}

.navbar {
  overflow: hidden;
  background-color: #ddad69;
  height: 65px;
}

.navbar a {
  float: left;
  font-size: 14px;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

.dropdown {
  float: right;
  overflow: hidden;
}

.dropdown .dropbtn {
  font-size: 14px;  
  border: none;
  outline: none;
  color: white;
  padding: 24px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.dropbtn {
right:10px;
}
.dropdown:hover .dropbtn {
  background-color: #103465;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #103465;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  right:250px;
}

.dropdown-content a {
  float: none;
  color: white;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #ddad69;
}

.dropdown:hover .dropdown-content {
  display: block;
}


.dropdown-2 {
  float: right;
  overflow: hidden;
}

.dropdown-2 .dropbtn-2 {
  font-size: 14px;  
  border: none;
  outline: none;
  color: white;
  padding: 24px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.dropbtn-2 {
right:10px;
}
.dropdown-2:hover .dropbtn-2 {
  background-color: #103465;
}

.dropdown-content-2 {
  display: none;
  position: absolute;
  background-color: #103465;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  right: 82px;
}

.dropdown-content-2 a {
  float: none;
  color: white;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content-2 a:hover {
  background-color: #ddad69;
}

.dropdown-2:hover .dropdown-content-2 {
  display: block;
}

.dropdown-3 {
  float: right;
  overflow: hidden;
}

.dropdown-3 .dropbtn-3 {
  font-size: 14px;  
  border: none;
  outline: none;
  color: white;
  padding: 24px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.dropbtn-3 {
right:10px;
}
.dropdown-3:hover .dropbtn-3 {
  background-color: #103465;
}

.dropdown-content-3 {
  display: none;
  position: absolute;
  background-color: #103465;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  right: 0;
}

.dropdown-content-3 a {
  float: none;
  color: white;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content-3 a:hover {
  background-color: #ddad69;
}

.dropdown-3:hover .dropdown-content-3 {
  display: block;
}

.dropdown-4 {
  float: right;
  overflow: hidden;
}

.dropdown-4 .dropbtn-4 {
  font-size: 14px;  
  border: none;
  outline: none;
  color: white;
  padding: 24px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.dropbtn-4 {
right:10px;
}
.dropdown-4:hover .dropbtn-4 {
  background-color: #103465;
}

.dropdown-content-4 {
  display: none;
  position: absolute;
  background-color: #103465;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  right: 5px;
}

.dropdown-content-4 a {
  float: none;
  color: white;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content-4 a:hover {
  background-color: #ddad69;
}

.dropdown-4:hover .dropdown-content-4 {
  display: block;
}

#logo {
position: fixed;
top: -28px;
left: -18px;
}


/* Home Body Content */
/* Home Body Content */
/* Home Body Content */

#home-body {
height: 100%;
background-color: #103465;
position: absolute;
left: 0px;
right: 0px;
top: 0px;

}

#main-title {
background-color: #103465;
font-size: 22px;
text-align: center;
color: white;
padding-top: 100px;
padding-bottom: 15px;
font-weight: 300;
margin-left: auto;
margin-right: auto;
width: 90%;
max-width: 750px;
}

#main-content {
background-color: #103465;
font-size: 15px;
text-align: center;
color: white;
padding-top: 15px;
margin-left: auto;
margin-right: auto;
width: 75%;
max-width: 800px;
font-weight: 200;
}

hr {
width: 40%;
max-width: 375px;
color: #ddad69;
}
</style>
</head>
<body>

<div id="home">
 <div class="navbar">
   <a href="#"><img src="/acasc_logo.png" height="126px" id="logo"></a>
   <div class="dropdown-4">
    <button class="dropbtn-4">Fees
      <i class="fa fa-caret-down"></i>
    </button>
   <div class="dropdown-content-4">
      <a href="#" id="g">Community Days</a>
      <a href="#" id="g">Music Theatre</a>
   </div>
  </div> 
  
 
 </div>
</div>

<div id="home-body">
<h1 id="main-title">Welcome to American Christian Academy! (Lovingly known as &quot;ACA&quot;)</h1><hr>

<h3 id="main-content">American Christian Academy (ACA) is a Private School Satellite Program (PSP) comprised of extension campuses ministering to parents dedicated to homeschooling throughout the United States. <br><br>ACA Sonoma County desires to serve Christian families in maintaining Christ-centered, biblically focused, private, home education based on Deuteronomy 6:5-9, encouraging whole-hearted development of our children so they are equipped to effectively engage the culture for Christ.</h3>

</div>


</body>
</html>

