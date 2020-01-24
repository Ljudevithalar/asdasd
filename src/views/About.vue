<template>
  <div class="about">
     <!-- <Navbar></Navbar> -->
   <div><h1>This is an about page</h1>
   
   <login></login>
</div> 
  </div>
</template>
<script>
// @ is an alias to /src

import Login from "@/components/Login.vue";

export default {
  name: 'about',
  components: {
   Login

  }
}
</script>