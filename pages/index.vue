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
        <div class="ni-home-social">
          <a target="_blank" href="https://www.twitch.tv/nicodemos234">
            <img src="/images/social/twitch.png" alt="Twitch">
          </a>
          <a target="_blank" href="https://www.youtube.com/c/nicodemos234">
            <img src="/images/social/youtube.png" alt="Youtube">
          </a>
          <a target="_blank" href="https://www.instagram.com/nicodemos.fs/">
            <img src="/images/social/instagram.png" alt="Instagram">
          </a>
          <a target="_blank" href="https://twitter.com/nicodemos234">
            <img src="/images/social/twitter.png" alt="Twitter">
          </a>
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
  align-items: center;
  display: flex;
  justify-content: space-between;
}
.ni-home-text {
  font-size: 32px;
  padding-top: 20px;
  line-height: 36px;
}
.ni-home-social {
  display: flex;
  padding: 10px 0px 0px 0px;
  align-items: center;
}
.ni-home-social a {
  margin: 0px 5px 0px 5px;
}
.ni-home-social img {
  max-width: 40px;
}
</style>
