<template>
  <div>
      <card/>
      <notification/>
  </div>
</template>

<script>
import card from './card/card.vue';
import notification from './components/notification/notification.vue';
export default {
  layout: 'app',
  components: {
    card,
    notification
  }
}
</script>

<style>

</style>
