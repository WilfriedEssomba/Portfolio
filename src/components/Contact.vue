<script setup>

</script>

<template>
  <div class="contact" id="contact">
    <div class="head pt-3">
      <h1 class="text-center">Contact</h1>
      <hr class="line">
    </div>
    
    <div class="contact-container mb-3">
      <form action="" method="post" class=" py-4 form-control">
        <label for="" class="mx-4">Name</label>
        <input type="text" class="form-control mt-2 mb-4  py-2">
        <label for="" class="mx-4">Email</label>
        <input type="email" class="form-control mt-2 mb-4 py-2">
        <label for="" class="mx-4">Telephone</label>
        <input type="telephone" class="form-control mt-2 mb-4 py-2">
        <label for="" class="mx-4">Message</label>
        <textarea name="" id="" cols="30" rows="5" class="form-control mt-2 mb-4 py-2"></textarea>
        <input type="submit" value="Submit" class="submit-btn btn btn-primary mx-4 px-5">
      </form>
    </div>
    
  </div>
</template>

<style>
.contact {
    height: 730px;
    background: rgb(236, 236, 236);
}
.head .line{
  width: 3%;
  border: 2px solid rgb(0, 128, 255);
  position: relative;
  top: 0px;
  left: 48.5%;
}

.contact-container{
  height: 600px;
  width: 45%;
  margin: auto;
}
label{
  font-size: 17px;
  font-weight: 600;
}
.submit-btn{
  font-weight: 600;
  font-size: 18px;
}
</style>