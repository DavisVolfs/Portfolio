<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>
<template>
<div class="text">
  <div class="greetings">
  <h1 class="text">{{ msg }}</h1>
    <h1 class="intro">
      Hello I am Davis !</h1>
      <br>
      <h1 class="intro">
      Multimedia Design Student | Social Media Maneger
      </h1>
      <p class="box1"> I am goal and development oriented. Good at learning new skills and I can very easily adapt to the environment. I love job with work with technologies and design, and I have mathematical thinking. I can plan my job by myself and I like to achieve my set goals. I am good at listening and decision making. I can substantiate my opinion reasonably I have more than a year of experience working in a car tuning company where I perform all work tasks, both technical and marketing-related, participating in all levels of work to gain as much experience as possible in both technical and digital technologies in this industry.</p>
  </div>
  <hr>
  <div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">2012 – 2024       Secondary Education, Talsi Chistian Secondary School Areas of focus: Ademic education Business development Project management Language skills Benefits: Used to work project and practice oriented Learned the public speech Learned to substantiate opinion reasonable</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="img_snow_wide.jpg" style="width:100%">
  <div class="text">2012 – 2024       Secondary Education, Talsi Chistian Secondary School Areas of focus: Ademic education Business development Project management Language skills Benefits: Used to work project and practice oriented Learned the public speech Learned to substantiate opinion reasonable</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="img_mountains_wide.jpg" style="width:100%">
  <div class="text">2012 – 2024       Secondary Education, Talsi Chistian Secondary School Areas of focus: Ademic education Business development Project management Language skills Benefits: Used to work project and practice oriented Learned the public speech Learned to substantiate opinion reasonable</div>
</div>

<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>
  <div>
    <h1 class="education">EDUCATION</h1>
    <div>
    <p class="edu1">2012 – 2024       Secondary Education, Talsi Chistian Secondary School
  Areas of focus:
  Ademic education
  Business development
  Project management
  Language skills
  Benefits:
  Used to work project and practice oriented
  Learned the public speech
  Learned to substantiate opinion reasonable</p>
    </div>
    <div>
    <p class="edu2">
      2024      Multimedia Design course, EASV
  Areas of focus:
  work professionally with design
  development of web solutions
  games and mobile services
  communication through social media
  digital video
  programming plus innovation and idea development
    </p>
    </div>
    <div>
    <p class="edu3">
      2015 – 2023       Talsi Regional Sports School, Floorball Club "FK Talsi"
  Areas of focus:
  Achieving high sporting goals
  Developing discipline and a high sense of responsibility
    </p>
    </div>
    <img class="arrows" src="./assets/arrow.svg" alt="" width="125" height="125">
    <img class="arrows" src="./assets/arrow.svg" alt="" width="125" height="125">
    <img class="arrows" src="./assets/arrow.svg" alt="" width="125" height="125">
    <img class="arrows" src="./assets/arrow.svg" alt="" width="125" height="125">
    <img class="arrows" src="./assets/arrow.svg" alt="" width="125" height="125">
    <img class="arrows" src="./assets/arrow.svg" alt="" width="125" height="125">
  </div> 
  <hr>
  <div class="text">
  <div class="greetings">
  <h1 class="work">
    WORK EXPERIENCE
  </h1>
  </div>
  <div>
  <p class="job1">
  2021 - 2023      Summer job, AS JJ Detailing
  Tasks:
  Take care for customer cars
  I received training and continued to work independently in car polishing and ceramic coating.
  </p>
  </div>
  <div>
    <p class="job2">
  2023     Ordinary employee , AS JJ Detailing
  Tasks:
  Take care for customer cars
  Follow up on plan realization
  Follow marketing activities in the company
    </p>
  </div>
  <img class="arrows" src="./assets/arrow.svg" alt="me" width="125" height="125">
  <img class="arrows" src="./assets/arrow.svg" alt="me" width="125" height="125">
  <img class="arrows" src="./assets/arrow.svg" alt="me" width="125" height="125">
  <img class="arrows" src="./assets/arrow.svg" alt="me" width="125" height="125">
  <div class="jj">
  <img class="video" src="./assets/jj.png" alt=""width="400" height="600">
  </div>
  <div>
    <h2 class="infobox" href="https://jjdetailing.dk/">More Info</h2>
  </div>
  </div>
  <hr>
  <div class="text">
  <div>
  <h1 class="skills">
    SKILLS
  </h1>
  </div>
  <div>
    <h2 class="skill">
      IT MS Office – Super user
  Work professionally with design
  Communication through social media
  Development of web solutions -
  Photoshop, InDesign, Illustrator, After Effects, Figma, WordPress, Visual Studio Code, Photography, videography, Branding, UX, and content creation
    </h2>
  </div>
  <div>
    <img class="id" src="./assets/id.png" alt="" width="125" height="125">
  </div>
  <div>
    <img class="ps" src="./assets/ps.png" alt="" width="125" height="125">
  </div>
  <div>
    <img class="ai" src="./assets/ai.png" alt="" width="125" height="125">
  </div>
  <div>
    <img class="pro" src="./src/assets/pro.png" alt="" width="125" height="125">
  </div>
  <hr>
  <div class="text">
    <h1 class="projects">
      PROJECTS
    </h1>
  </div>
  <div class="project1">
    <img src="./src/components/arrow.svg" alt="" width="125" height="125">
    <img src="./assets/arrow.svg" alt="" width="125" height="125">
    <img src="./assets/recipe.png" alt="" width="125" height="125">
    <img src="" alt="" width="125" height="125">
  </div>
  <div class="project2">
    <img src="./public/image/arrow.svg" alt="" width="125" height="125">
    <img src="./assets/arrow.svg" alt="" width="125" height="125">
    <img src="./assets/poster.png" alt="" width="125" height="125">
    <img src="" alt="" width="125" height="125">
  </div>
  <div class="project3">
    <img src="./assets/arrow.svg" alt="" width="125" height="125">
    <img src="./assets/arrow.svg" alt="" width="125" height="125">
    <img src="./assets/webpage1.png" alt="" width="125" height="125">
    <img src="" alt="" width="125" height="125">
  </div>
  <div class="project4">
    <img src="./src/components/assets/arrow.svg" alt="" width="125" height="125">
    <img src="./assets/arrow.svg" alt="" width="125" height="125">
    <img src="./assets/greenlife.png" alt="" width="125" height="125">
    <img src="" alt="" width="125" height="125">
  </div>
  </div>
</div>
<footer class="footer">
    <div class="contact">
        <h2>Contact me:</h2>
        <h3>davisvolfs@gmail.com</h3>
        <h3>+45 123 456 789</h3>
    </div>
    <div class="follow">
        <h2>Follow me:</h2>
        <h3><a href="https://www.linkedin.com/in/davis-volfs">Linked In</a></h3>
        <h3><a href="https://www.instagram.com/davis.volfs/?hl=en">Instagram</a></h3>
    </div>
</footer>
</template>
<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>
<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
  margin-left: 70px;
}

h3 {
  font-size: 1.2rem;
}

.greetings{
  margin-top: 50px;
}

.greetings h1,
.greetings h3 {
  text-align: center;
  color: white;
}


.intro{
  margin-top: 80px;
  margin-bottom: 100px;
  margin-left: 70px;
}

.box1{
  text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 800px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 70px;
  border-radius: 25px;
  margin-left: 150px;
}

.education{
  text-align: center;
  margin-top: 50px;
  color: white;
  margin-left: 50px;
}



.edu1{
  text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 400px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 100px;
}

.edu2{
  text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 400px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 600px;
  margin-top: -312px;
}

.edu3{
  text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 400px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 350px;
}

.work{
text-align: center;
margin-top: 50px;
margin-left: 50px;
}

.job1{
align-items: center;
text-align: center;
background-color: rgba(183, 183, 182, 1);
  width: 400px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 100px;
}

.job2{
  text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 400px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 100px;
}

.jj{
  background-color: rgb(0, 0, 0);
  width: 400px;
  height: 600px;
  border: 2px solid rgb(244, 244, 35);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 600px;
  margin-top: -1010px;
}

.video{
  margin-left: -52px;
  margin-top: -53px;
}

.infobox{
text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 200px;
  height: 40px;
  border: 2px solid rgba(183, 183, 182, 1);
  margin: 120px;
  border-radius: 15px;
  margin-top: -140px;
  margin-left: 200px;
}

.skills{
text-align: center;
margin-top: 50px;
color: white;
margin-left: 50px;
}

.skill{
  text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 800px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 40px;
  border-radius: 25px;
  margin-left: 150px;
  margin-top: 300px;
  margin-bottom: -20px;
}

.projects{
  text-align: center;
  margin-top: 50px;
  color: white;
  margin-left: 50px;
}

.project1{
  text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 400px;
  height: 200px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 100px;
}

.project2{
  text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 400px;
  height: 200px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 100px;
}

.project3{
  text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 400px;
  height: 200px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 600px;
  margin-top: -500px;
}

.project4{
  text-align: center;
  background-color: rgba(183, 183, 182, 1);
  width: 400px;
  height: 200px;
  border: 2px solid rgba(183, 183, 182, 1);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 600px;
  margin-top: 0px;
  margin-bottom: 70px;
}

.footer {
    display: flex;
    justify-content: space-between;
    background-color:rgba(246, 185, 19, 1);
    padding: 20px;
    width: 100%;
    text-align: center;
}

.contact, .follow {
    color:rgba(14, 5, 89, 1);
}

h2 {
    margin: 0 0 10px;
}
a {
    text-decoration: none;
    color:rgba(14, 5, 89, 1);
}
a:hover {
    color: white;
}

.arrows{
  display: block;
}




@media (min-width: 1024px) {
}
</style>
