<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calcutta Public School > Photogallery</title>
    <style>
html{
overflow-x:hidden;
overflow-y:scroll;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Verdana; 
}

body {
    display: flex;
    justify-content: center;
    align-items: start;
    min-height: 100vh;
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

#table1 {
    border-collapse: collapse; 
    background-image: url('images/bg_watermark.jpg'); 
    background-size: 780px 434px; 
    background-repeat: repeat-y; 
    background-position: cover; 
    width: 780px; 
    max-width: 100%;
}

p {
    margin: 0 0 20px; 
    line-height: 1.5; 
    color: #fff;
    font-size: 13px;
}

img {
    display: block; 
    width: 100%; 
}

#mainImg {
    background-image: url('images/extra.jpg');
    width: 159px;  
    height: 299px; 
    background-size: contain; 
    background-repeat: repeat; 
    background-position: center; 
    padding: 5px; 
    overflow: hidden; 
}

#chaimanImg {
    width: 250px;
    height: 164px;
    float: right;
    margin: 30px 15px 5px 7px;
}

.bottom-img {
    background-image: url('images/bottom_img.jpg');
    width: 780px;
    height: 27px;
    background-repeat: no-repeat;
}

.history-img {
    background-image: url('images/history_img.jpg');
    width: 621px;
    height: 34px;
    background-repeat: no-repeat;
}

.content {
    padding: 15px 17px; 
}

.content p {
    line-height:20px;
    word-spacing:1.5px;
    font-size: 13px;
}

.content span {
    color: #F8D448; 
    font-size: 20px; 
}

.nav-links {
    position: absolute; 
    top: 120px; 
    list-style-type: none; 
    padding: 0; 
    line-height: .5; 
    background:transparent;
    z-index: 1000; 
}

.nav-links li {
    padding: 5px 0; 
}

.vision {
    width: 100%;
    height: 34px;
    color: #FFD700; 
    padding: 5.5px 20px 0px;
    font-weight: 900;
    letter-spacing: 1.6px;
    font-size: 13.9px;  
    overflow: hidden; 
}

.vision-border {
    margin-left: 0px;
    margin-top: -32px;
    display: inline-block;
    background: rgb(7,13,86);
    background: linear-gradient(131deg, rgba(7,13,86,1) 1%, rgba(45,68,136,1) 8%, rgba(46,60,135,1) 90%, rgba(7,13,86,1) 94%);
    height:1px;
    padding-left:210px;
}

/*----------------------------------------- Updated Modal CSS---------------------------------------- */


.modal-table {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 21.1%;
    top: 25.8%;
    width: 780px;
    height: 450px;
  max-width: 780px;
max-height:auto;
    background-color: gray;
    table-layout: fixed;
border:1px solid #949494;
}


.modal-content {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%; 
}

.modal-content img {
margin-left: auto;
  margin-right: auto;
display:block;
  width: 515px;
  height: 338px;
    margin-top: -20px;
    margin-bottom: -30px;
border-radius:5px;
}


.caption-container {
    width: 100%;
    text-align: center;
}
.caption-container p {
    text-align: center; 
    font-size: 16px; 
    margin-top: -15px; 
    margin-bottom: 20px;
}

.prev, .next {
    position: absolute;
    top: 40%;
    padding: 16px;

    color: white;
    font-size: 20px;
    font-weight: bold;
    cursor: pointer;
    background-color:rgba(0, 0, 0, 0.4);
transition:all 0.2s ease-in-out;
}
.prev:hover, .next:hover {
background-color: rgba(0, 0, 0, 0.7);
color:#fff;
border-radius:50%;
margin:0px 0.5px;
}

.prev {
    left: 0;
}

.next {
    right: 0;
}

.close {
    position: absolute;
    top: 5px;
    right: 10px;
    color: white;
    font-size: 30px;
    font-weight: bold;
    cursor: pointer;
    transition: color 0.3s ease-in-out;
}

.close:hover{
color: #000;

}
.modal-content img.boy-gif {
width:246px;
height:375px;
margin-left: auto;
  margin-right: auto;
display:block;
}


.image-popup{
cursor:pointer;
filter:contrast(115%);
}
.image-popup:hover{
cursor:pointer;
filter:contrast(100%);
}
.special{ 
width:246px;
height:375px;
}

 /* Modal CSS for Firefox */

@-moz-document url-prefix() {
.modal-table {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 21.1%;
    top: 25.8%;
    width: 780px;
    height: 450px;
   
    background-color: gray;
    table-layout: fixed;
border:1px solid #949494;
}


.modal-content {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%; 
}

.modal-content img {
margin-left: auto;
  margin-right: auto;
display:block;
  width: 515px;
  height: 338px;
    margin-top: -10px;
    margin-bottom: -10px;
border-radius:5px;
}


.caption-container {
    width: 100%;
    text-align: center;
    
}
.caption-container p {
    text-align: center; 
    font-size: 16px; 
    margin-top: -15px; 
    margin-bottom: -20px;
}
#caption{
margin-top:50px;

}

.modal-content img.boy-gif {
width:246px;
height:375px;
margin-bottom:-46px;
margin-left: auto;
  margin-right: auto;
display:block;
}

}

    </style>
</head>

<body>
    <table id="table1" border="0" cellspacing="0" cellpadding="0" align="center">
        <tr>
            <td>
                <table width="780px" border="0" cellspacing="0" cellpadding="0">
                    <tr>
                        <td width="780">
                            <img src="images/top.jpg" height="108" alt="Top Image">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <table border="0" cellpadding="0" cellspacing="0" width="780">
                                <tr>
                                    <td width="159px" height="299px" style="background-image: url('images/extra.jpg'); background-size: contain; background-position:cover; background-repeat: repeat;">
                                        <ul class="nav-links" style="margin-left: 14.3px;">
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
                                    </td>
                                    <td width="621" valign="top">
                                        <table border="0" cellpadding="0" cellspacing="0" width="620">
                                            <tr>
                                                <td class="vision">
                                                    <font face="Verdana">Photogallery</font>
                                                </td>
                                            </tr>
                                            <tr>
                                                <td class="vision-border"><td></tr>
                                            </tr>
                                            <tr>
                                                <td class="content">
                                                    <p style="display:flex;justify-content:space-evenly;align-items:center; margin-top:-13px;">
                                                        <b>ANNUAL FUNCTION</b>
                                                    </p>
                                                    <p style="display:flex;justify-content:space-evenly;align-items:center;">
                                                        <img src="images/stage.gif" alt="ANNUAL FUNCTION" style="width:250px; height:164px;" class="image-popup">
                                                        <img src="images/drama_4.gif" alt="ANNUAL FUNCTION" style="width:250px; height:164px;" class="image-popup">
                                                    </p>
                                                    <p style="display:flex;justify-content:space-evenly;align-items:center;">
                                                      <img src="images/drama_3.gif" alt="ANNUAL FUNCTION" style="width:250px; height:164px;"  class="image-popup">
                                                      <img src="images/dance.gif" alt="ANNUAL FUNCTION" style="width:250px; height:164px;" class="image-popup">
                                                    </p>
                                                    <p style="display:flex;justify-content:space-evenly; align-items:center; gap:40px; padding-right:40px;">
                                                      <img src="images/drama2.gif" alt="ANNUAL FUNCTION" style="width:250px; height:164px;" class="image-popup">
                                                      <img src="images/boy.gif" alt="ANNUAL FUNCTION" style="width:164px; height:250px;" class="image-popup special">
                                                      </p>
                                                      
                                                      <p style="display:flex;justify-content:space-evenly;align-items:center;">
                                                      <b>LABS</b>
                                                      
                                                      </p>   
                                                                                                          <p style="margin-top:0px;padding-left:2px;">
                                                                                                             <p style="display:flex;justify-content:space-evenly;align-items:center;">
                                                      <img src="images/lab_3.gif" alt="BIOLOGY LAB" style="width:250px; height:164px;" class="image-popup">
                                                      <img src="images/lab_6.gif" alt="PHYSICS LAB" style="width:250px; height:164px;" class="image-popup">
                                                      </p>
                                                      <p style="display:flex;justify-content:space-evenly;align-items:center; gap:65px;">
                                                      <b>BIOLOGY LAB</b>
                                                      <b>PHYSICS LAB</b>
                                                      </p>  
                                                      <p style="display:flex;justify-content:space-evenly;align-items:center; margin-top:-10px;">
                                                      <b>RECTOR</b>
                                                      
                                                      </p>   
                                                                                                          <p style="margin-top:0px;padding-left:2px;">
                                                                                                             <p style="display:flex;justify-content:space-evenly;align-items:center;">
                                                      <img src="images/pricipal.gif" alt="RECTOR" style="width:250px; height:164px;" class="image-popup">
                                                      
                                                      </p>
                                                </td>
                                            </tr>
                                        </table>
                                    </td>
                                </tr>
                            </table>
                        </td>
                    </tr>
                </table>
                <tr>
                  <td colspan="2" height="27px" class="bottom-img">
                      <span style="font-weight:800; font-size:10px; padding-left:13px; display:flex; align-items:center; color:#000;">Powered by&nbsp;
                          <a style="text-decoration:none" href="https://www.google.com" target="_blank" class="afoot">Google.com</a>
                      </span>
                  </td>
              </tr>
            </td>
        </tr>
    </table>

    <!-- Modal Structure  -->


    <table id="myModal" class="modal-table">
        <tr>
            <td>
                <span class="close" title="Close">&times;</span>
                <table class="modal-content" border="0" cellpadding="0" cellspacing="0">
                    <tr>
                        <td><img id="modalImg" src=""></td>
                    </tr>
                </table>
                <table class="caption-container" style="width: 100%; text-align: center;">
                    <tr>
                        <td >
                            <p id="caption" style="color: #000; font-weight:900; font-family:Verdana;"></p>
                        </td>

                    </tr>
                </table>
                <a class="prev" title="Previous">&#10094;</a>
                <a class="next" title="Next">&#10095;</a>
            </td>
        </tr>
    </table>

    <script>
        const modal = document.getElementById("myModal");
const modalImg = document.getElementById("modalImg");
const captionText = document.getElementById("caption");
const closeModal = document.getElementsByClassName("close")[0];
const images = document.querySelectorAll(".image-popup");

let currentIndex = 0;

images.forEach((img, index) => {
    img.addEventListener("click", function () {
        currentIndex = index; 
        showModal();
    });
});

closeModal.addEventListener("click", function () {
    modal.style.display = "none";
});

function showModal() {
    modal.style.display = "table";
    modalImg.src = images[currentIndex].src;
    captionText.innerHTML = images[currentIndex].alt;

    // Set specific class for boy.gif


    if (images[currentIndex].src.includes('boy.gif')) {
        modalImg.classList.add('boy-gif'); 
    } else {
        modalImg.classList.remove('boy-gif'); 
    }
toggleButtons();
}

function updateModal() {
    modalImg.src = images[currentIndex].src;
    captionText.innerHTML = images[currentIndex].alt;

    // Set specific class for boy.gif
    if (images[currentIndex].src.includes('boy.gif')) {
        modalImg.classList.add('boy-gif'); 
    } else {
        modalImg.classList.remove('boy-gif'); 
    }
toggleButtons();
}

document.addEventListener("keydown", function (event) {
    if (event.key === "Escape") {
        modal.style.display = "none"; 
    }
});

window.addEventListener('keydown', event => {
  if (event.key == "ArrowLeft") {
    currentIndex = (currentIndex === 0) ? images.length - 1 : currentIndex - 1;
    updateModal();
  } else if (event.key == "ArrowRight") {
   currentIndex = (currentIndex === images.length - 1) ? 0 : currentIndex + 1;
    updateModal();
  }
});

// Next and Previous functionality
document.querySelector(".prev").addEventListener("click", function () {
    currentIndex = (currentIndex === 0) ? images.length - 1 : currentIndex - 1;
    updateModal();
});

document.querySelector(".next").addEventListener("click", function () {
    currentIndex = (currentIndex === images.length - 1) ? 0 : currentIndex + 1;
    updateModal();
});

function toggleButtons(){

//document.querySelector(".prev").style.display="inline-block";
//document.querySelector(".next").style.display="inline-block";

if(currentIndex===0){
document.querySelector(".prev").style.display="none";	
}else{
document.querySelector(".prev").style.display="inline-block";
}

if(currentIndex===images.length - 1){
document.querySelector(".next").style.display="none";
}else{
document.querySelector(".next").style.display="inline-block";
}
}



    </script>
</body>
</html>
