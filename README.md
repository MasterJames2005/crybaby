
<!DOCTYPE html> 
 <html> 
 <head> 
         <title>R | Valencia</title> 
         <link rel="stylesheet" href="style.css"> 
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css" integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ==" crossorigin="anonymous" referrerpolicy="no-referrer" /> 
         <link rel = "icon" href = "https://img.icons8.com/avantgarde/256/r.png" type = "image/x-icon"> 
 </head> 
  
 <body> 
  
         <main> 
                  
                 <div class="card"> 
  
                         <div class="card1"> 
                                  
  
                                 <img src="./img/IMG_0001.PNG" alt="Picture"> 
  
                                         <div class="profilet"> 
                                                 <h1 style="font-family: 'Roboto', sans-serif;">Renz Vincent M. Valencia</h1> 
                                                 <span class="br"></span> 
                                                 <hr color="#c4c4c4"> 
                                                 <span class="br"></span> 
                                                 <p style="text-align:justify; font-family: 'Roboto', sans-serif;" >I'm a second-year college student at Trinity University of Asia, 21 years of age. I'm taking Information Technologies with a focus on mobile, web, and software development.</p> 
                                  
                                         </div> 
  
  
                                         <div class="mainbody"> 
  
                                                         <div class="skills"> 
                                          
                                                                         <h3>SKILLS</h3> 
                                                                         <span class="br"></span> 
  
                                                                 <ul> 
                                                                         <li>Photography</li> 
                                                                         <li>Social&nbsp;Media</li> 
                                                                         <li>Java</li> 
                                                                         <li>HTML/CSS</li> 
                                                                         <li>C++</li> 
                                                                 </ul> 
  
                                                         </div> 
  
                                                         <div class="line"></div> 
  
                                                         <div class="hobbies"> 
  
                                                                 <h3>HOBBIES</h3> 
                                                                 <span class="br"></span> 
  
                                                                 <ul> 
                                                                         <li>Games</li> 
                                                                         <li>Photos</li> 
                                                                         <li>Coding</li> 
                                                                         <li>Movies</li> 
                                                                         <li>Tiktok</li> 
                                                                 </ul> 
                                                         </div> 
  
                                         </div> 
  
                                                 <div class="socmed"> 
                                                         <a href="https://www.facebook.com/rvvalenciaa"><i class="fa-brands fa-facebook"></i></a> 
                                                         <a href="https://www.messenger.com/t/100014170920969/"><i class="fa-brands fa-facebook-messenger"></i></a> 
                                                         <a href="https://www.instagram.com/whos.mastershiru/?igshid=NDk5N2NlZjQ%3D"><i class="fa-brands fa-instagram"></i></a> 
                                                         <a href="https://www.tiktok.com/@mastershiruu?_t=8Zwf9oRmAwT&_r=1"><i class="fa-brands fa-tiktok"></i></a> 
                                                         <a href="mailto:rvalencia994@yahoo.com"><i class="fa-solid fa-envelope"></i></a> 
                                                 </div> 
  
                         </div> 
                 </div>                 
                  
         </main> 
  
 </body> 
 </html>

@import url('https://fonts.googleapis.com/css2?family=Zeyada&display=swap'); 
 *{ 
 padding: 0; 
 margin: 0; 
 box-sizing: border-box; 
 background-size: cover; 
 font-family: 'Roboto', sans-serif; 
 } 
 main{ 
     justify-content: center; 
     background-image: url(./img/bg.jpg); 
     height: 100vh; 
     width: 100%; 
     display: flex; 
     align-items: center; 
     background-size: cover; 
     background-repeat: no-repeat; 
     background-position: center center; 
 } 
 .card{ 
     height: 100vh; 
     width: 100%; 
     opacity: .8; 
     background-color: rgba(0, 0, 0, .3); 
     backdrop-filter: blur(20px); 
 } 
 main .card1{ 
     width: 450px; 
     height: 500px; 
     border-radius: 2%;  
     position: relative; 
     border: 1px solid rgb(96, 126, 151); 
     background-color: rgba(0, 0, 0, .3); 
     box-shadow: 0px 0px 700px 50px black; 
 } 
 .card, .card1{ 
     display: flex; 
     align-items: center; 
     justify-content: center; 
     flex-direction: column; 
 } 
 img{ 
     left: 50%; 
     top: -70px; 
     transform: translate(-50%); 
     border-radius: 50%; 
     width: 150px; 
     height: 150px; 
     cursor: pointer; 
     position:absolute; 
     border: 1px solid rgb(96, 126, 151); 
 } 
 .card1, .profilet{ 
     display: flex; 
     align-items: center; 
     justify-content: center; 
 } 
 .profilet{ 
     color:#c4c4c4; 
     margin-top: 50px; 
     margin-left:50px; 
     margin-right: 50px; 
     flex-direction: column; 
 } 
 .line { 
     display: flex; 
     align-items: center; 
     border-left: 2px solid #c4c4c4; 
     height: 100px; 
     opacity: .5; 
     margin-top: 40px; 
     border-radius: 50%; 
 } 
 hr{ 
     height: 2px; 
     width: 390px; 
     opacity: .5; 
     margin: 5px; 
      
 } 
 .card1, .mainbody{ 
     display: flex; 
     align-items: center; 
     justify-content: center; 
     color:#c4c4c4; 
 } 
 .skills, .hobbies{ 
     margin-right: 80px; 
     margin-left: 80px; 
     margin-top: 20px; 
 } 
  
 .br { 
     display: block; 
     margin-bottom: 0.4em; 
 } 
 .socmed{ 
     display: flex; 
     align-items: center; 
     justify-content: space-evenly; 
     margin-top: 20px; 
 } 
 i{ 
     font-size: 40px; 
     cursor: pointer; 
     transition: .4s; 
 } 
 i:hover{ 
     color: rgb(28, 199, 199); 
     transform: scale(1.5); 
 } 
 a{ 
     color: rgb(96, 126, 151); 
     margin: 20px; 
 }