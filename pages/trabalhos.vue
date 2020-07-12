<template>
  <div>
    <client-only>
      <agile :nav-buttons="false" :autoplay-speed="5000" :speed="2500" fade pause-on-hover pause-on-dots-hover autoplay>
            <ni-slide-content title="Pechinchou Site" desc="O Pechinchou é um site que eu desenvolvi com Wordpress, personalizando um tema completo para ele, e criando diversas ferramentas de 
            administração para os adms do site." link="https://www.pechinchou.com.br" src="/images/pechinchou1.png" alt="Pechinchou Site" />
            <ni-slide-content title="Pechinchou Aplicativo" desc="O aplicativo do Pechinchou, foi desenvolvido em 
            Flutter, sendo uma extensão do site, adicionando funcionalidades como uma lista de desejos, em que os usuários cadastram o que querem receber de notificações, 
            e recebem push notifications com base nos posts e as palavras colocadas." src="/images/pechinchou2.png" alt="Pechinchou Site" />
      </agile>
    </client-only>
  </div>
</template>

<script>
import NiSlideContent from './../components/ni-slide-content'
export default {
    components: {
        'ni-slide-content' : NiSlideContent
    }
};
</script>

<style>
.ni-slide-info {
    padding: 10px 10px 10px 30px;
}
.ni-slide-title {
    padding-left: 20px;
}
.agile__dots {
    bottom: 10px;
    flex-direction: column;
    right: 30px;
    position: absolute;
}
.agile__dot {
    margin: 5px 0;
}
.agile button {
    background-color: transparent;
    border: 1px solid #BD93F9;
    cursor: pointer;
    display: block;
    height: 10px;
    font-size: 0;
    line-height: 0;
    margin: 0;
    padding: 0;
    transition-duration: .3s;
    width: 10px;
}
.agile__dot--current, .agile__dot:hover {
    background-color: #BD93F9;
}
</style>