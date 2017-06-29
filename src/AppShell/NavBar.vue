<template>
    <nav class="navbar navbar-toggleable-md navbar-inverse fixed-top bg-inverse">
      <button class="navbar-toggler navbar-toggler-right hidden-lg-up open" type="button" @click="toggleHamburger" v-bind:class="{collapsed:hamburger === false}" data-toggle="collapse" data-target="#navbarsExampleDefault" aria-controls="navbarsExampleDefault" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <a class="navbar-brand" href="/">Real time</a>
 
     
     
      </div>
 
    </nav>

</template>

<script>
export default {
      data(){
        return {
            hamburger:false        
        }
    },
    methods:{
       toggleHamburger(){
           this.hamburger = !this.hamburger
       }
    }

}
</script>

<style>
    

</style>
