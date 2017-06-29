<template>
  <div id="app">
    <navBar></navBar>
    <div class="container-fluid">
      <div class="row">
       <sideMenu></sideMenu>
        <main class="col-sm-9 offset-sm-3 col-md-10 offset-md-2 pt-3">
           <h1>Realtime.vue Component</h1>

           <div class="row">
             <div class="col-md-4">
                <real-time></real-time>
             </div>
              <div class="col-md-4">
               <real-time></real-time>
             </div>
              <div class="col-md-4">
               <real-time></real-time>
             </div>
           </div>

            <div class="row">
             <div class="col-md-4">
                <real-time></real-time>
             </div>
              <div class="col-md-4">
               <real-time></real-time>
             </div>
              <div class="col-md-4">
               <real-time></real-time>
             </div>
           </div>

            <div class="row">
             <div class="col-md-4">
                <real-time></real-time>
             </div>
              <div class="col-md-4">
               <real-time></real-time>
             </div>
              <div class="col-md-4">
               <real-time></real-time>
             </div>
           </div>

        </main>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from './NavBar.vue'
import SideMenu from './SideMenu.vue'
import RealTime from '../Components/RealTime.vue'

export default {
    components:{  navBar:NavBar, sideMenu:SideMenu, 'real-time':RealTime }
}
</script>

<style>
 @import url("https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.0.0-alpha.6/css/bootstrap.min.css");
 @import url("https://v4-alpha.getbootstrap.com/examples/dashboard/dashboard.css");
 @import url("https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css");

 .card{
   margin-bottom: 20px;
 }
</style>
