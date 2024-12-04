<script setup>

</script>

<template>
  <nav class="navbar fixed-top navbar-expand-lg navbar-dark shadow" style="background-color:white;">
    <div class="container px-4">
      <a class="navbar-brand" href="#home">
        <span style="color:black; font-size:28px; font-weight:bold; letter-spacing: 1px;font-family:sans-serif">XXXXXXX XXXXXXXX</span>
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"><span
          class="navbar-toggler-icon"></span></button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active tex-light underline" style="color:black;font-size:18px;font-weight:500;" aria-current="page" href="#home">Home </a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" style="color:black;font-size:18px;font-weight:500;" aria-current="page" href="#about">About me </a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" style="color:black;font-size:18px;font-weight:500;" aria-current="page" href="#project">Projects </a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link active" style="color:black;font-size:18px;font-weight:500;" aria-current="page" href="#contact">Contact </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

</template>

<style>
  .nav-item:hover{
      border-bottom: 2px solid rgb(0, 128, 255);
      border-bottom-right-radius: 5px;
      border-bottom-left-radius: 5px; 
  }
</style>
