<template>
  <div >
      <TopSideBar/>
      <AsideBarVue/>
      <main>
          <Nuxt/>
      </main>
  </div>
</template>

<script>
import TopSideBar from '~/components/TopSideBar.vue';
import AsideBarVue from '~/components/AsideBar.vue';
export default {
  components: {
    TopSideBar,
    AsideBarVue
  }
}
</script>

<style></style>
