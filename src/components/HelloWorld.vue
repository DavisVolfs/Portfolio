<script setup>
const props = defineProps({
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
</div>
<br>
  <div>
    <h1 class="education">EDUCATION</h1>
    <div>
    <p class="edu1">
        <img class="tks" src="../assets/image/tks1.png" alt="" width="300" height="160">
    2012 – 2024       Secondary Education, Talsi Chistian Secondary School
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
        <img class="easv" src="../assets/image/easv1.png" alt="" width="300" height="160">
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
        <img class="floor" src="../assets/image/floorball1.jpg" alt="" width="300" height="160">
      2015 – 2023       Talsi Regional Sports School, Floorball Club "FK Talsi"
  Areas of focus:
  Achieving high sporting goals
  Developing discipline and a high sense of responsibility
    </p>
    </div>
  </div> 

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
  <div class="jj">
    <a href="https://www.instagram.com/jjdetailingcrew/" target="_blank">
  <img class="video" src="../assets/image/jj.png" alt=""width="400" height="600">
  </a>
  </div>
  <div>
    <a href="https://jjdetailing.dk" target="_blank">
    <h2 class="infobox">More Info</h2>
  </a>
  </div>
  </div>
  <div class="text">
  <div>
  <h1 class="skills">
    SKILLS
  </h1>
  </div>
   <div>
    <img class="id" src="../assets/image/id.png" alt="" width="125" height="125">
  </div>
  <div>
    <img class="ps" src="../assets/image/ps.png" alt="" width="125" height="125">
  </div>
  <div>
    <img class="ai" src="../assets/image/ai.png" alt="" width="125" height="125">
  </div>
  <div>
    <img class="pro" src="../assets/image/pro.png" alt="" width="125" height="125">
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
  
  <div class="text">
    <h1 class="projects">
      PROJECTS
    </h1>
  </div>
  <div class="recipepage">
    <h3 class="txt1">RecipeWebpage</h3>
    <img class="project1" src="../assets/image/recipepage.svg" alt="" width="300" height="125">
  </div>
  <div class="webpage">
    <h3 class="txt2">GreenLife</h3>
    <img class="project2" src="../assets/image/web2.png" alt="" width="125" height="125">
  </div>
  <div class="CV">
    <h3 class="txt3">Personal CV</h3>
    <img class="project3" src="../assets/image/CV.png" alt="" width="125" height="125">
  </div>
  <div class="card">
    <h3 class="txt4">BuisnessCard</h3>
    <img class="project4" src="../assets/image/buisnesscard.png" alt="" width="125" height="125">
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
  margin-top: -475px;
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
  margin-bottom: -510px;
}

.jj{
  background-color: rgb(0, 0, 0);
  width: 420px;
  height: 620px;
  border: 2px solid rgb(244, 244, 35);
  padding: 50px;
  margin: 50px;
  border-radius: 25px;
  margin-left: 600px;
}

.video{
  margin-left: -42px;
  margin-top: -43px;
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


.id{
  margin-left: 120px;
  margin-bottom: -217px;
}

.ps{
  margin-left: 370px;
margin-bottom: -195px;
}

.ai{
  margin-left: 620px;
margin-bottom: -172px;
}

.pro{
  margin-left: 870px;
margin-bottom: -150px;
}

.projects{
  text-align: center;
  margin-top: 50px;
  color: white;
  margin-left: 50px;
}

.recipepage{
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

.webpage{
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

.CV{
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

.card{
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

.txt1{
  margin-top: -30px;
}

.txt2{
  margin-top: -30px;
}

.txt3{
  margin-top: -30px;
}

.txt4{
  margin-top: -30px;
}

.project1{
margin-top: 0px;
}

.project2{
margin-top: 0px;
}

.project3{
margin-top: 0px;
}

.project4{
margin-top: 0px;
}

.footer {
    display: flex;
    justify-content: space-between;
    background-color:rgba(246, 185, 19, 1);
    padding: 20px;
    width: 100%;
    text-align: center;
}

.contact{
    color:rgba(14, 5, 89, 1);
}
.follow{
  color:rgba(14, 5, 89, 1);
  margin-right: 200px;
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
