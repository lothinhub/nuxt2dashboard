<template>
  <div>
    <card />
    <dastables/>
    <!-- <notification /> -->
  </div>
</template>

<script>
import card from './card/card.vue';
import dastables from './components/table/dastables.vue';
import notification from './components/notification/notification.vue';
export default {
  layout: 'app',
  components: {
    card,
    notification,
    dastables,
  }
}
</script>

<style></style>
