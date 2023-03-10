<template>
  <div id="app-container">
    <TopSideBar />
    <AsideBar />
    <main class="m-2">
      <b-container fluid="xxl" class="shadow p-2 rounded bg-primary layout">
        <b-container fluid="xxl" class="shadow p-2 bg-warning layout2">
            <b-container fluid="xxl" class="shadow p-2 bg-light layout3">
            <Nuxt/>
          </b-container>
        </b-container>
      </b-container>
    </main>
  </div>
</template>
<script>
import TopSideBar from "~/components/TopSideBar.vue";
import AsideBar from "~/components/AsideBar.vue";
export default {
  components: {
    TopSideBar,
    AsideBar,
  },
};
</script>
<style>
.layout{
  height: 84vh;
}
.layout2{
  height: 83vh;
}
.layout3{
  height: 82vh;
}
</style>
