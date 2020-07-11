<template>
  <div class="ni-home">
    <div class="ni-home-flex">
      <div>
        <h1>Seja bem-vindo</h1>
        <div class="ni-home-text">
          <p>Olá, meu nome é Nicodemos, tenho 18 anos,
         sou programador, editor de vídeos e
         apaixonado por tecnologia.</p>
        </div>
      </div>
      <img src="/images/nico.png" alt="Nico" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.ni-home {
  padding: 40px;
}
.ni-home-flex {
  display: flex;
  justify-content: space-between;
}
.ni-home-text {
  font-size: 32px;
  padding-top: 20px;
  line-height: 36px;
}
</style>
