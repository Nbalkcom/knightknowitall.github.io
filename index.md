<!DOCTYPE html>
<html>
<head>
<title>KKIA Homepage</title>
<link rel="icon" href="images/MGA_Logo2.png">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    * {
      box-sizing: border-box;
    }
    .header{
        float:left;
        width:100%;
        background-image:linear-gradient(#5a5a5a,#5a5a5a,#5a5a5a3f);
        color: white;
    }
    .header h1{
        width:80%;
        text-align:center;
        float:right;
        font-size:250%;
        padding:32px;
    }
    .menu {
      float:left;
      width:40%;
      text-align:center;
      font-size:160%;
    }
    .menu a {
      background-color:#5f009e;
      padding:45px;
      margin-top:10px;
      display:block;
      width:100%;
      color:rgb(255, 255, 255);
      text-decoration: none;
    }
    .menu a:hover{
      background-color:#8901e4;
    }
    .main {
      float:left;
      width:60%;
      padding:0 20px;
      text-align:center;
      font-size:150%;
      color: white;
    }
    .footer {
      background-image:linear-gradient(#5a5a5a7a,#5a5a5a);
      float:left;
      width:100%;
      padding:15px;
      margin-top:7px;
      text-align:center;
    }
    
    @media only screen and (max-width:620px) {
      /* For mobile phones: */
      .main{
        width:100%;
      }
      .menu{
        width: 90%;
        padding-left:10%;
      }
      .menu a{
          margin-top:7px;
      }
      .header img{
        padding-left:30%;
        padding-right: 30%;
        width: 40%;
        box-sizing: unset;
      }
      .header h1{
          float:none;
          width:100%;
      }
    }
    </style>
</head>
<body style="background-image:linear-gradient(black,black,#5a5a5a); margin:0;">
<div style="overflow:auto">
    
    <div class="header">
      <a href="#">
        <img title="Knight Know It All" src="images/MGA_Logo2.png" alt="Middle Georgia State University" width="150" height="150">
      </a>
      <h1>Knight Know It All</h1>
    </div>
    
    <div class="main">
        <h2>Main Hub for New Students</h2>
        <h3>Select any of these topics you wish to learn more about!</h3>
        <h3>Currently there are only a few videos with informational text available.</h3>
    </div>
    
    <div class="menu">
      <a href="Webpages/Access_D2L.html">How to Access D2L</a>
      <a href="Webpages/Navigate_D2L.html">How to Navigate D2L</a>
      <a href="Webpages/Access_Syllabus.html">How To Access The Syllabus</a>
      <a href="Webpages/Navigate_Syllabus.html">How To Navigate The Syllabus</a>
      <a href="Webpages/Course_Materials.html">How To Find Required Course Material (Books)</a>
      <a href="Webpages/Class_Schedule.html">How To Access The Class Schedule</a>
      <a href="Webpages/Email_Professor.html">How To Email The Professor</a>
    </div>
  
    <div class="footer">
      <h2>Team</h2>
      <p>Developed by Group 3.</p>
      <h4>Web Development: Nick Balkcom</h4>
      <h4>Video Creator: Deion Williams</h4>
      <h4>Text Writer: Spencer Smith</h4>
    </div>

</div>
</body>
</html>
