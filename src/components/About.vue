<script setup>

</script>

<template>
  <div class="about" id="about">
    <div class="head text-center mb-5 pt-3">
      <h2>ABOUT ME</h2>
      <hr class="line">
      <span>Here you will find more information about me, what I do, and my current skills mostly in terms <br> of programming and technology</span>
    </div>
    <div class="body d-flex">
      <div class="one">
        <h4>Get to know me</h4>
        <div>
          I am a software engineer with a passion for crafting innovative and efficient solutions. With a good foundation in core programming languages such as Python, Javascript, and PHP, I am continously sharpening my skills in various software development methodologies and technologies.
          <br>
          <br>
          I am actively engaged in web development projects, focusing on creating user-friendly and responsive web applications. My expertise extends to backend development, frontend development, and full-stack development, enabling me to deliver comprehensive solutions.
          <br>
          <br>
          I am committed to staying up-to-date with the latest industry trends and technologies. I thrive in collaborative environments and enjoy working with cross-functional teams to achieve project goals. My strong problem-solving abilities and attention to detail ensure high-quality deliverables
        </div>
        <a class="contact-btn btn btn-primary py-2 px-4" href="#contact">Contact Me</a>
      </div>

      <div class="two">
        <h4>skills</h4>
        <div>
          <div class="skill">
            <span>HTML</span> <span>CSS</span> <span>BOOTSTRAP</span>
          </div>
          <div class="skill">
            <span>JAVASCRIPT</span> <span>VUE JS</span> <span>JQUERY</span>
          </div>
          <div class="skill">
            <span>PHP</span> <span>LARAVEL</span> <span>WORRDPRESS</span>
          </div>
          <div class="skill">
            <span>PYTHON</span> <span>DJANGO</span> 
          </div>
          <div class="skill">
            <span>DART</span> <span>FLUTTER</span>
          </div>
          <div class="skill">
            <span>GIT</span> <span>DOCKER</span> <span>JENKINS</span>  
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.about {
    height: 800px;
    background: rgb(236, 236, 236);
}
.about .head span{
  font-size: 22px;
}
.about h2{
  font-weight: 700;
  margin-bottom: 30px;
}
.about .body .one{
  flex-basis: 60%;
  padding-left: 100px;
  padding-right: 150px;
  text-align: justify;
}
.about .body .one h4{
  margin-bottom: 25px;
}
.about .body .one div{
  font-size: 18px;
}
.about .body .one .contact-btn{
  margin-top: 20px;
  /* height: 45px;
  width: 150px; */
  font-size: 18px;
  font-weight: 600;
}
.about .body .two{
  flex-basis: 40%;
  height: 400px;
}
.about .body .two span{
  width: 50px;
  background: rgb(209, 209, 209);
  color: rgb(113, 113, 113);
  padding: 10px 20px 10px 20px;
  margin-right: 20px;
  border-radius: 5px;
  font-weight: 600;
}
.about .body .two h4{
  margin-bottom: 35px;

}
.skill{
  margin-bottom: 30px;
}

</style>
