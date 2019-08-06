<template>
  <section class="container">
    <date-time-selector v-model="date" :title="title" :min-hour="minHour" :max-hour="maxHour"/>
    <div>date: {{date}}</div>
  </section>
</template>

<style lang="scss" scoped>
</style>

<script>
import DateTimeSelector from '../src/vue-mg-date-time-selector'
export default {
  data() {
    return {
      date: '',
      title: '',
      minHour: 0,
      maxHour: 23,
    }
  },
  methods: {
    ///
  },
  components: {
    DateTimeSelector,
  },  
}
</script>