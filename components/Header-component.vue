<template>
     <div >
        <header>
           <b-navbar toggleable="lg" type="dark" variant="dark" >
           
                <b-navbar-brand href="#" >NuxT JS </b-navbar-brand> 
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
                
            <b-navbar-nav  class="float-right">
                <b-nav-item class="active" href="#">Home</b-nav-item>
                <b-nav-item href="#">Contact US</b-nav-item>
                <b-nav-item href="#">About Us</b-nav-item>
               
            </b-navbar-nav> 
            <!-- right  nav items  -->
            
            </b-collapse>
            
           
        </b-navbar>
        </header>
       
       
    </div>
</template>
<script>

export default {
  name : "header-component"
}
</script>
<style>

  
</style>