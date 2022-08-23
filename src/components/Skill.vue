<script setup>
// import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <div class="container">
    <div class="isi">
      <div class="bar">
       <div class="kiri">
         <h4>html</h4>
       </div>
        <div class="kanan">
            <div class="progress">
  <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">80%</div>
</div>
        </div>
      </div>
      <div class="bar">
        <h4>css</h4>
          <div class="progress">
  <div class="progress-bar" role="progressbar" style="width: 75%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">75%</div>
</div>
      </div>
      <div class="bar">
        <h4>figma</h4>
         <div class="progress">
  <div class="progress-bar" role="progressbar" style="width: 90%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">90%</div>
</div>
      </div>
      <div class="bar">
        <h4>laravel</h4>
          <div class="progress">
  <div class="progress-bar" role="progressbar" style="width: 50%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">50%</div>
</div>
      </div>
    </div>
  </div>
</template>
<style scope>
.container {
  background-color: #D7A86E;
  margin-top: -50px;
  height: 500px;
  padding-top: 80px;
}

.isi {
  /* display: flex; */
  justify-content: space-evenly;
}
</style>
