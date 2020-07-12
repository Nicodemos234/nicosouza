<template>
    <div>
        <a target="_blank" class="pe-slide-link" :href="link"><h3 class="ni-slide-title">{{ title }}</h3></a>
        <div class="ni-slide-info">{{ desc }}</div>
        <img :src="src" :alt="alt">
    </div>
</template>
<script>
export default {
    props: ['title', 'src', 'desc', 'alt', 'link']
}
</script>
<style>
.pe-slide-link {
    font-size: 16px;
}
</style>