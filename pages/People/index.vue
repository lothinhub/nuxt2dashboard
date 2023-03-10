<template>
  <div>
    Modal
    <modal/>
    <tables/>
  </div>
</template>

<script>
import tables from './component/tables/tables.vue';
import modal from './component/modal/modal.vue';
export default {
  layout: 'app',
  components: {
    tables,
    modal
  }
}
</script>

<style>

</style>
