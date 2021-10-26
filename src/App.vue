<template>
  <div>
    父组件：{{obj}}
    <Son :obj="obj"/>
  </div>

</template>

<script>
import Son from './Son.vue'
export default {
  name: 'App',
  components: {
    Son,
  },
  data() {
    return {
      obj: 0
    }
  }
}
</script>
