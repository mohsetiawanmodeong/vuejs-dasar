<template>
   <div class="logos-wrapper">
      <h2 class="title-header">CAT&#174; MINESTAR&#8482; SYSTEM</h2>
      <div class="item-logos">
         <img class="logo" alt="Cat Minestar Fleet" src="../assets/fleet.png">
      </div>
      <div class="item-logos">
         <img class="logo" alt="Cat Minestar Terrain" src="../assets/terrain.png">
      </div>
      <div class="item-logos">
         <img class="logo" alt="Cat Minestar Detect" src="../assets/detect.png">
      </div>
      <div class="item-logos">
         <img class="logo" alt="Cat Minestar Health" src="../assets/health.png">
      </div>
      <div class="item-logos">
         <img class="logo" alt="Cat Minestar Command" src="../assets/command.png">
      </div>
   </div>
</template>

<script>
export default {
   // eslint-disable-next-line vue/multi-word-component-names
   name: 'Logos'
}
</script>

<style scoped>
.title-header {
   margin-bottom: 80px;
   text-align: left;
}

.logos-wrapper {
   width: 60%;
   overflow: hidden;
   margin: auto;
}

.logos-wrapper .h2 {
   font-weight: 800;
}

.item-logos {
   float: left;
   margin-right: 70px;
   margin-bottom: 70px;
   width: 150px;
   height: 150px;
}

.item-logos .logo {
   width: 200px;
   height: 150px;
}
</style>