# vue-mg-date-time-selector

## Installation

```
npm i vue-mg-date-time-selector
```

## Usage

app.js

```javascript
import DateTimeSelector from 'vue-mg-date-time-selector'
Vue.component('DateTimeSelector', DateTimeSelector)
```

Example:

```html
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
```

## License

MIT