<template>
   <div class="profile">
      <div class="container">
         <div class="row justify-content-center">
            <div class="col-lg-6">
               <div class="d-flex text-start">
                  <img src="../assets/minestar.png" class="user-pic me-3" />
                  <div>
                     <h5 class="mt-0">
                        CAT&#174; MINESTAR&#8482; SYSTEM
                     </h5>
                     <p>
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                        blanditiis soluta, praesentium, facilis repellendus!
                     </p>
                  </div>
               </div>
            </div>
         </div>
      </div>

   </div>
</template>

<script>

import 'bootstrap/dist/css/bootstrap.css'

export default {
   // eslint-disable-next-line vue/multi-word-component-names
   name: 'Profile',
   components: {
   }
}
</script>

<style scoped>
.user-pic {
   border-radius: 200%;
   height: 90px;
   width: 90px;
}
</style>
