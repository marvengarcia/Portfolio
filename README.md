# Portfolio4

<!DOCTYPE html>
<html lang="en">
<head>
  <title>Marven Garcia | Web Developer</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@200;400;500&display=swap" rel="stylesheet"> 
  <link href="https://allfont.net/allfont.css?fonts=league-spartan" rel="stylesheet" type="text/css" />
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100&display=swap" rel="stylesheet"> 
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
  <style>
  html {
    scroll-behavior: smooth;
  }
  body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.8;
    color: #f5f6f7;
  }
  p {font-size: 16px;}
  .margin {margin-bottom: 45px;}
  
   .jumbotron { 
   background-image: url("images/WholeBG.jpg");
   background-size: cover;
   font-family: 'Poppins', sans-serif;
   color: white;
   height:600px;
   }

   .color-overlay{
       background: white;
       position:absolute;
      top:0;
      right:0;
      bottom:0;
      left:0;
      width:100%;
      height:600px;
      opacity:90%;
   }

   .jumbotron h2 {
    font-family: 'Poppins', sans-serif;
    color: gray;
   }


   
   .jumbotron h3 {
   font-family: 'Poppins', sans-serif;
   color: gray;
   font-size: 25px;
   text-align: left;
   }
   
  .bg-2 { 
    background-color: #38ACEC; 
    color: white;
  }
  .bg-2 h1{
    font-family: 'Poppins', sans-serif;
   font-size: 50px;
   color:white;
  }
  .bg-2 p {
    font-family: 'Poppins', sans-serif;
    font-size: 17px;
  }
  .bg-3 { 
    background-color: #F09D51;
    color: white;
  }
  .bg-3 h1{
    font-family: 'Poppins', sans-serif;
   font-size: 50px;
   color: white;
  }
  .bg-4 { 
    background-color: #000000; 
    color: #fff;
  }
  .container-fluid {
    padding-top: 70px;
    padding-bottom: 70px;
    margin-top:-30px;
  }
  .navbar {
    padding-top: 50px;
    border: 0;
    border-radius: 0;
    margin-bottom: 0;
    font-size: 12px;
    letter-spacing: 5px;
  }
  
  #first {
    font-family: 'Poppins', sans-serif;
    color: #F09D51;
    text-align: left;
  }

  #second {
    font-family: 'Poppins', sans-serif;
    color: #38ACEC;
    text-align: left;
    margin-top:-50px;
    margin-bottom: -10px;
  }

  hr {
  border: 2px solid #F09D51;
  }

  input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #F09D51;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #F09D51;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
  color: black;
}
  </style>
</head>
<body>
<!-- Navbar -->

<!-- First Container -->
<div class="jumbotron">
  <div class="color-overlay">
  <nav class="navbar navbar-default">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>                        
        </button>
      </div>
      <div class="collapse navbar-collapse" id="myNavbar">
        <ul class="nav navbar-nav navbar-right">
          <li><a href="#AboutMe">About Me</a></li>
          <li><a href="#Work">My Projects</a></li>
          <li><a href="#ContactMe">Contact Me</a></li>
        </ul>
      </div>
  </nav>
<div class="container-fluid bg-1">
  <div class="col-sm-6 text-center">
    <img src="images/MarvenLogo3.jpg" class="img-circle" width="350" height="300" style="text-align: right; "> 
  </div>
  <div class="col-sm-6">
    <h1 class="margin" id="first"><strong>Hi! Im</strong></h1>
    <h1 class="margin" id="second"><strong>Marven</strong></h1>
    <hr>
    <h3>full-stack web developer | software developer</h3>
    <a href="Resume.pdf" target="_blank"><i class="fa fa-file" style="font-size:40px;color:#0072b1; padding-right: 1em;"></i></a>
    <a href="https://www.linkedin.com/in/rolan-marven-garcia-724bb6192/" target="_blank"><i class="fa fa-linkedin-square" style="font-size:48px;color:#0072b1"></i></a>
</div>
</div>
</div>
</div>

<!-- Second Container -->
<div class="container-fluid bg-2">
  <a id="AboutMe"><h1 class="margin text-center"><strong>About Me</strong></h1></a>
  <div class="col-sm-6">
  <p style="margin-top: 20px;"><strong>A recent graduate of the University of the Fraser Valley. Finished with a Bachelors degree in Computer Information Systems. With knowledge and experience in creating websites using HTML, CSS, Bootstrap and JavaScript. Also has experience in Software Development with knowledge in programming languages such as Java, Python and C++.</strong></p>
  </div>
  <div class="col-sm-6">
    <p style="margin-top: -15px;"><strong>Skills:</strong></p>
<div class="skills">
  <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:95%">
      <strong>HTML</strong>
    </div>
    <br>
    <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:95%">
      <strong>CSS</strong>
    </div>
    <br>
    <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:70%">
      <strong>JavaScript</strong>
    </div>
    <br>
    <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:90%">
      <strong>Bootstrap</strong>
    </div>
    <br>
    <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:70%">
      <strong>PHP</strong>
    </div>
    <br>
    <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:60%">
      <strong>SQL</strong>
    </div>
    <br>
    <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:85%">
      <strong>Java</strong>
    </div>
    <br>
    <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:65%">
      <strong>Python</strong>
    </div>
    <br>
    <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:55%">
      <strong>C++</strong>
    </div>
    <br>
    <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width:85%">
      <strong>Problem-solving and Analytical Skills</strong>
    </div>
    <br>
    
    
    
</div>
</div>
</div>

<!-- Third Container (Grid) -->
<div class="container-fluid bg-3">    
  <a id="Work"><h1 class="margin text-center"><strong>Projects</strong></h1><br></a>
  <h2 class="margin text-center"><strong>Website</strong></h2>
  <div class="row">
    <div class="col-md-4">
      <div class="thumbnail">
        <a href="https://sag.ufvsoca.ca/sag/2019/04/26/interpret-2019/" target="_blank">
          <img src="images/Work1.jpg" style="height:370px;width:100%">
      </div>
    </div>
    <div class="col-md-4">
      <div class="thumbnail">
        <a href="https://sag.ufvsoca.ca/sag/2019/09/06/illuminations/" target="_blank">
          <img src="images/Work2.jpg" style="height:370px;width:100%">
        </a>
      </div>
    </div>
    <div class="col-md-4">
      <div class="thumbnail">
        <a href="images/Work5.png" target="_blank">
          <img src="images/Work5.png" style="height:370px; width:100%">
        </a>
      </div>
    </div>
  </div>
  <h2 class="margin text-center"><strong>Digital Media</strong></h2>
  <div class="row">
    <div class="col-md-4">
      <div class="thumbnail">
        <a href="files/Work4PDF.pdf" target="_blank">
          <img src="images/Work4.jpg" style="height:370px; width:100%">
        </a>
      </div>
    </div>
    <div class="col-md-4">
      <div class="thumbnail">
        <a href="files/BrochureAssignment7.pdf" target="_blank">
          <img src="images/Work3.jpg" style="height:370px; width:100%">
        </a>
      </div>
    </div>
    <div class="col-md-4">
      <div class="thumbnail">
        <a href="files/CMNS375NewsLetterFinal5.pdf" target="_blank">
          <img src="images/Work6.jpg" style="height: 370px; width:100%">
        </a>
      </div>
    </div>
  </div>
 
</div>
<div class="container">
  <a id="ContactMe"><h1><strong>Contact Me *Not Working At the Moment*</strong></h1></a>
  <form action="/action_page.php">
    <label for="fname">Name</label>
    <input type="text" id="name" name="fullname" placeholder="Your name..">

    <label for="lname">Email</label>
    <input type="text" id="email" name="email" placeholder="Your email..">


    <label for="subject">Message</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">
  </form>
</div>

</body>
</html>
