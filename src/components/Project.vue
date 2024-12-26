<script setup>

</script>

<template>
  <div class="project" id="project">
    <div class="head pt-3">
      <h1 class="text-center">Projects</h1>
      <hr class="line">
    </div>
      <div class="container">
        <div class="project-body mb-5">
          <div class="project-text rounded shadow">
            <h2>Kiya Shop</h2>
            <p>
              E-commerce mobile app that connects users and an online shop proposing different articles. <br>
              Developed using flutter and dart for the mobile interfaces and laravel for the backend that 
              is the authentication system and all the operations and functionalities needed in an e-commerce app.
            </p>
            <div>

            </div>
          </div>

          <div class="project-image">
            <img src="@/assets/e-com-app.jpg" alt="">
          </div>
        </div>

        <div class="project-body mb-5">
          <div class="project-text rounded shadow">
            <h2>Blood Donation</h2>
            <p>
              A web application that allows users and hospitals to find blood donors and request blood. <br>
              Developed using flutter and dart for the mobile interfaces and laravel for the backend that 
              is the authentication system and all the operations and functionalities needed in a blood donation app.
            </p>
            <div>

            </div>
          </div>

          <div class="project-image">
            <img src="@/assets/Bloodhome.png" alt="">
          </div>
        </div>

        <div class="project-body mb-5">
          <div class="project-text rounded shadow">
            <h2>APEX</h2>
            <p>
              A web application that allows users to create, read, update, and delete tasks. <br>
              Developed using Laravel for the backend and Vue.js for the frontend.
            </p>
            <div>

            </div>
          </div>

          <div class="project-image">
            <img src="@/assets/task-Image.jpg" alt="">
          </div>
        </div>

      </div> 

    <div>

    </div>
  </div>
</template>

<style>
.project {
    height: 1000px;
    background: rgb(224, 224, 224);
}
.project-body{
  height: 250px;
  display: flex;
  flex-direction: row;

}
.project-body:nth-child(odd){
  display: flex;
  flex-direction: row-reverse;
}
.project-text{
background: rgb(236, 236, 236);
width: 50%;
padding: 2%;
}
.project-image{
background: transparent;
width: 47%;
}
img{
  width: 100%;
  height: 100%;
  object-fit: contain;
}
</style>