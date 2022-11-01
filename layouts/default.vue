<template>
    <div>
        <!-- <header>
            <h1>{{ $route.name }} 페이지</h1>
            <nuxt-link to="/">홈페이지</nuxt-link>     
            <nuxt-link to="/main">메인 페이지</nuxt-link>     
            <nuxt-link to="/product">상품 페이지</nuxt-link>     
        </header> -->

        <header class="title">
            <NuxtLink class="logo" to="/">Nuxt Shopping</NuxtLink>
        </header>
        
        <Nuxt />
    </div>
  
</template>

<script>
export default {
    // created() {
    //     console.log(this.$route);
    // }
}
</script>

<style scoped>

/* header 관련 스타일  */
header {
  height: 60px;
  display: flex;
  align-items: center;
  padding: 0 0.5rem;
}
.logo {
  font-weight: 900;
}
.logo:visited {
  color: inherit;
}
</style>