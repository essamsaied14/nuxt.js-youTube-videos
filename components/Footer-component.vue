<template>
 <div>
<footer color="blue" class="font-small pt-4 mt-4 bg-dark" >
    <b-container class="text-left">
      <b-row>
        <b-col sm="6">
          <h5 class="title">Footer Content</h5>
          <p>Here you can use rows and columns here to organize your footer content.</p>
        </b-col>
        <b-col sm="6">
          <h5 class="title">Links</h5>
          <ul>
            <li class="list-unstyled"><a href="#">Link 1</a></li>
            <li class="list-unstyled"><a href="#">Link 2</a></li>
            <li class="list-unstyled"><a href="#">Link 3</a></li>
            <li class="list-unstyled"><a href="#">Link 4</a></li>
          </ul>
        </b-col>
      </b-row>
    </b-container>
    <div class="footer-copyright text-center py-3">
      <b-container fluid>
        &copy; 2020 Copyright: <a href="https://nuxtjs.org/" target="_blank"> Nuxt JS </a>
      </b-container>
    </div>
  </footer>
 </div>
  
  <!-- Footer -->
</template>
<script>

export default {
  name : "footer-component"
}
</script>