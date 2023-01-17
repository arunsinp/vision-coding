<!------Here html page starts  ------->
<!DOCTYPE html>
<html lang="en">


<!-------------------------Header starts here -------------------------------->
<head>
<title>About me</title>
<subtitle>Arun Kumar Pandey</subtitle>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
  
<style>

* {box-sizing: border-box}

.container {
  width: 100%;
  background-color: #ddd;
}

.skills {
  text-align: right;
  padding-top: 10px;
  padding-bottom: 10px;
  color: white;
}

.python {width: 70%; background-color: #1e60a6;}
.machine {width: 35%; background-color: #904231;}
.gnuplot  {width: 50%; background-color: #7A9EA5;}
.html {width: 45%; background-color: #808080;}
.fortran {width: 55%; background-color:  #86C729;}
.swift {width: 30%; background-color: #F2BA7B;}

  
/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}


/* Header/logo Title */
.header {
  padding: 80px;
  text-align: center;
  background: #30460c;
  color: white;
}


/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: rgb(21, 10, 22);
}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned links */
.navbar a.right {
  float: right;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #ddd;
  color: black;
}

/* Column container */
.row {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<!---------------------- Header eds here --------------------------------------->


<!------Here main body starts  ------->
<body>
<div class="header">
    <h1>This is header</h1>
    <img src="yourimage.png" alt="Trulli" width="200" height="150"> 
      <!---src - Specifies the path to the image
      alt - Specifies an alternate text for the image-->
    <p>This is header subtitle.</p>
  </div>

  <div class= “header-image”>
  </div>

  <div class="navbar">
    <a href="https://github.com/arunsinp">GitHub</a>
    <a href="#">Your codes</a>
    <a href="#">Photos</a>
    <a href="#" class="right">Link for something</a>
  </div>
  
  <div class="row">
    <div class="side">

      <h2>About Me</h2>
      This html file is a format file for the website designing.
      <p><img src="somephotos.jpg" alt="Trulli" width="300" height="200"></p>
      Hi there! My name is (insert name) and I am a (insert profession/career field). 
      I have always been passionate about (insert field of interest) and have been 
      working in this industry for (insert number) years. In my free time, I enjoy 
      (insert hobbies/interests). I am excited to meet new people and learn from their
      experiences and perspectives. I believe that we can all learn and grow from each 
      other, and I am always open to hearing new ideas and approaches. I am a hard-working
      and reliable individual, and I am committed to delivering high-quality work in 
      everything I do. Thank you for taking the time to get to know me a little bit better.
      <!-------Add your photos here, if you wish -->
    </div>

    <div class="main">
      <h2>TITLE HEADING</h2>
      <h5>Add some subtitle, if needed</h5>
      <p>
      <h1>Technical Skills<h1/>

<h3>Programming Skills</h3>

<p>Python</p>
<div class="container">
  <div class="skills python"></div>
</div>

<p>Machine-learning</p>
<div class="container">
  <div class="skills machine"></div>
</div>

<p>Gnuplot</p>
<div class="container">
  <div class="skills gnuplot"></div>
</div>

<p>Fortran</p>
<div class="container">
  <div class="skills fortran"></div>
</div>

<p>HTML</p>
<div class="container">
  <div class="skills html"></div>
</div>

<p>SWIFT</p>
<div class="container">
  <div class="skills swift"></div>
</div>

      </p>
      <br>

      <h2>TITLE HEADING</h2>
      <p>Some text..</p>
    </div>
  </div>
  
  <div class="footer">
    <h2>This website is managed by yourname or email id</h2>
  </div>
<!------Here main body ends  ------->
</body>
<!---------------------------Here html page ends ---------------------------------->
</html>
