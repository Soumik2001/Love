<!DOCTYPE html>
<html>
  <head>
    <title>Calcutta Public School > Vision</title>
<link rel="stylesheet" href="vision.css">
  </head>
  <body>

<!------------Header section Start------------------->
<div id="fullpage">
<header>
<div class="logo"><img src="images/top.jpg" alt="logo"></div>
</header>


<div class="parent">
    <div class="div1"><nav id="nav" >
 <ul class="nav-links">
                                            <li><a href="index.html">Home</a></li>
                                            <li><a href="vision.html">Vision</a></li>
                                            <li><a href="history.html">History</a></li>
                                            <li><a href="location.html">Location</a></li>
                                            <li><a href="organisation.html">Organisation</a></li>
                                            <li><a href="curriculum.html">Curriculum</a></li>
                                            <li><a href="school_uniform.html">School Uniform</a></li>
                                            <li><a href="teaching_staff.html">Teaching Staff</a></li>
                                            <li><a href="facilities.html">Facilities</a></li>
                                            <li><a href="activities.html">Activities</a></li>
                                            <li><a href="rules.html">Rules</a></li>
                                            <li><a href="register_online.html">Register online</a></li>
                                            <li><a href="photogallery.html">Photogallery</a></li>
                                            <li><a href="contact_us.html">Contact Us</a></li>
                                            <li><a href="site_map.html">Site Map</a></li>
</ul>
</nav>
</div>
    <div class="div2"><p><font><strong class="vision">Vision</font></strong><div class="vision-border"></div></p>
</div>
    <div class="div3"><p class="para1"><strong class="strong">W</strong>ith the enduring words of the Bhagavad <img src="images/chairman.gif" alt="logo" class="chairman">Gita “Action is better than inaction”, Calcutta Public School was founded by Shri Bhogendra Jha in 1998 at Aswininagar, Baguiati, Kolkata – 59. It has its own ambitious vision for education.</p>

<p class="para2">In the fast changing scenario of education, which aims at the infrastructure activities and career orientation, this school moves fast and wishes to foster substantial moral leadership that accounts for individual direction and persistence of efforts towards attaining a goal. That goal is not to look at in isolation. It has its own integrated information and comprehension in imparting best quality and productivity in the sphere of education, improving education so that the growing children can triumph over the most prestigious competitions. The school faces a multitude of aggressive bottlenecks, yet it has “The ability to produce novel and useful ideas”.</p>

<p class="para3">The school has a sound facilitating teamwork and work culture. The management, the teachers, and the students move on with unstinted efforts to get at what has been thought best in learning. Learning involves change, and the change has been brought from concept to skills. The school has its own committed workforce, and the teachers are quite conscientious in honest labor, while the children are adventurous in the quest for knowledge. The school, with its own mental map, moves apace and learns; “Every great and commanding movement in the annals of the world is the triumph of enthusiasm” - Emerson.</p></div>
    <div class="div4"><footer class="footer">
<p>Powered by&nbsp<a href="https://www.google.com" target="_blank" class="afoot">Google.com</a></p>
</footer></div>
</div>
    

</div>
  </body>
</html>




*{
margin:0;
padding:0;
box-sizing:border-box;
font-family: Verdana; 
}

html{
display:flex;
justify-content:center;
align-items: start;
overflow-x:hidden;
overflow-y:scroll;
}

body{
overflow:hidden;
}

.logo img{
width:780px;
height:108px;
}

img{
display:block;
width:100%;
}

#fullpage{
background:url('images/bg_watermark.jpg') repeat-y;
width:780px;
height:auto;

}

a {
    text-decoration: none;
    color: #f8cf44;
    font-size: 10px;
    font-weight: 700;
    transition: color 0.3s ease;
}

.afoot {
    color: #000;
}

.afoot:hover {
    color: red;
}

a:hover {
    color: #fff;
}

.vision {
position:absolute;
            width: 100%;
            height: 34px;
            color: #FFD700; 
            padding: 12px 10px 0px;
            font-weight: 900;
            letter-spacing: 1.6px;
            font-size: 13.9px;  
            overflow: hidden; 
        }


.vision-border{
margin-top:29px;
margin-left: 0px;
display: inline-block;
background: rgb(7,13,86);
background: linear-gradient(131deg, rgba(7,13,86,1) 1%, rgba(45,68,136,1) 8%, rgba(46,60,135,1) 90%, rgba(7,13,86,1) 94%);
height:1px;
padding-left:210px;
}

p{
font-family:Verdana;
font-size:13px;
color:#fff;
line-height:16px;
word-spacing:1px;
}
ul{
margin-top:-8px;
}

ul li{
list-style-type:none;
}

#nav{
background:url('images/extra.jpg') repeat;
min-width:159px;
min-height:523px;
padding:14px;
}

.nav-links{
position:sticky;


}

.main{
display:flex;
justify-content:space-evenly;
align-items: center;
}

.para1{

}

.strong{
color: #f8cf44;
font-weight:800;
font-size:20px;
}



.footer{
background:url('images/bottom_img.jpg') no-repeat;
width:780px;
height:27px;

}


.footer p{
color:#000;
font-weight:900;
font-size:10px;
padding-top:5px;
padding-left:12px;
display:flex;
align-items:center;
}



.para1, .para2, .para3{
padding-bottom:20px;
font-size:13px;
}

.chairman{
float:right;
width:250px;
height:164px;
margin:12px;
}












.parent {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(6, 1fr);
    gap: 0px;
}
    
.div1 {
width:169px !important;
    grid-column: span 2 / span 2;
    grid-row: span 5 / span 5;
}

.div2 {
width:621px !important;
height:40px;
    grid-column: span 3 / span 3;
    grid-column-start: 3;
}

.div3 {
margin-top:-65px;
padding:10px 10px 0px 10px;
margin-right:20px;
//background:red;
    grid-column: span 3 / span 3;
    grid-row: span 4 / span 4;
    grid-column-start: 3;
    grid-row-start: 2;
}

.div4 {
margin-top:-5px;
    grid-column: span 5 / span 5;
    grid-row-start: 6;
overflow:hidden;
}
        





