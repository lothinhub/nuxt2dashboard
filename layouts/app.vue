v<template>
  <div id='app-container' :class='getMenuType'>
    <TopSideBar/>
    <AsideBar/>
     <main>
      <div class='container-fluid'>
        <Nuxt />
      </div>
    </main>
  </div>
</template>
<!--End of Tawk.to Script-->
<script>
import TopSideBar from '~/components/TopSideBar.vue';
import AsideBar from '~/components/AsideBar.vue';
export default {
  components: {
    TopSideBar,
    AsideBar,
  }
}
</script>
