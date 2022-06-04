<template>
 
     <!-- <router-link to="/signin">signin</router-link>
     <router-link to="/signup">signup</router-link> -->

    <Navigation />

     <div class="container">
       <div class="row">
         <div class="col-md-12">
           <router-view></router-view>
         </div>
       </div>
     </div>
     
 
</template>

<script>
import Navigation from './components/Navigation.vue'

export default {
  name: 'App',
  components:{
    Navigation,
   
}

}
</script>
