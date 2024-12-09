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
          <div class="project-text">
            Text
          </div>

          <div class="project-image">
            image
          </div>
        </div>

        <div class="project-body mb-5">
          <div class="project-text">
            Text
          </div>

          <div class="project-image">
            image
          </div>
        </div>

        <div class="project-body mb-5">
          <div class="project-text">
            Text
          </div>

          <div class="project-image">
            image
          </div>
        </div>

        <div class="project-body mb-5">
          <div class="project-text">
            Text
          </div>

          <div class="project-image">
            image
          </div>
        </div>
      </div> 

    <div>

    </div>
  </div>
</template>

<style>
.project {
    height: 1300px;
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
background: #afafaf;
width: 47%;
}
.project-image{
background: white;
width: 47%;
}
</style>