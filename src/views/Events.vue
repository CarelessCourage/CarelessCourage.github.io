<template>
  <div class="events">
    <h1>This is an events page</h1>
    <timeline></timeline>
    <footerComponent></footerComponent>
  </div>
</template>

<script>
// @ is an alias to /src
import timeline from '@/components/timeline.vue'
import footerComponent from '@/components/footerComponent.vue'

export default {
  name: 'home',
  components: {
    timeline,
    footerComponent
  }
}

</script>
