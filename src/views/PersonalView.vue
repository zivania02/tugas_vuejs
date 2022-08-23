<script setup>
import Personal from "@/components/Personal.vue";
</script>
<template>
  <div class="container1">
       <div class="contact">
         <p>+62 81281904726</p>
         <p>zivania04@gmail.com</p>
         <p>Depok, West Java</p>
       </div>
    <div class="personal">
      <h1>About Me</h1>
      <p>
        My name is Zivani Aidin, I study at SMK TARUNA BHAKTI majoring in RPL
        (Engineering Software)
      </p>
    </div>
    <div class="education">
      <h1>Education</h1>
      <p>2020 - 2023</p>
      <p>SMK TARUNA BHAKTI</p>
    </div>
    <div class="experience">
      <h1>Experience</h1>
      <p>Agenda</p>
      <p>Sarpras</p>
    </div>
  </div>
</template>

<style scoped>
/* .container1{
     background-color:#42855B;
} */
.contact {
  display: flex;
  justify-content: right;
}
.contact p {
  margin-left: 20px;
}

.container1{
     background-color: #D7A86E;
     padding: 40px;
     color: white;
     /* border-radius: 30px; */
     margin-top: -50px;
}
.personal{
     margin-bottom: 30px;
}

.education{
     line-height: 10px;
}

.experience{
     line-height: 10px;
}
</style>
