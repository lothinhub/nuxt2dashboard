v<template>
  <div id='app-container' :class='getMenuType'>
    <TopSideBar/>
    <AsideBar/>
    <main>
      <div class='container-fluid'>
        <Nuxt />
      </div>
    </main>
    <b-overlay :show='inProgress' rounded='sm' variant='dark' z-index='50000' opacity='0.2' no-wrap>
      <template v-slot:overlay>
        <!-- <b-card class="bgColor" body-class="pb-0"> -->
        <div class='text-center text-primary px-5' v-show='overlay'>
          <b-icon icon='box' font-scale='3' animation='spin' class='text-primary mb-3'
            style='width: 80px; height: 40px'></b-icon>
        </div>
        <!-- </b-card> -->
      </template>
    </b-overlay>
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
