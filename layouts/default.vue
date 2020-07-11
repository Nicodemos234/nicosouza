<template>
  <div>
    <b-container>
      <div class="ni-main-menu">
        <img class="ni-logo" src="/images/nicosouza.png" alt="NicoSouza logo">
         <div>
           <b-nav>
             <b-nav-item>
               <nuxt-link to="/">Início</nuxt-link>
             </b-nav-item>
              <b-nav-item>
               <nuxt-link to="/trabalhos">Trabalhos</nuxt-link>
             </b-nav-item>
              <b-nav-item>
               <nuxt-link to="/contato">Contato</nuxt-link>
             </b-nav-item>
           </b-nav>
         </div>
      </div>
      <Nuxt />
    </b-container>
    <!-- <div class="ni-footer">Todos os direitos reservados</div> -->
  </div>
</template>
<script>
export default {
  
}
</script>
<style>
@import '../assets/styles/reset.css';
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap');
body {
  background-color: #282A36;
  font-family: 'Roboto', sans-serif;
  color: #BCC2CD;
}
a {
  color: #BCC2CD;
  font-size: 30px;
}
a:hover {
  color: #BD93F9;
  text-decoration: none;
}
.ni-main-menu {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}
.ni-logo {
  max-width: 200px;
}

h1 {
  font-size: 64px;
}
</style>
