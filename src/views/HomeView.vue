<template>
  <div>
    <h1>This is Home page</h1>
    <gorgeousDevelop title="Hometitle" />
  </div>
</template>

<script>
import gorgeousDevelop from '@/components/gorgeousDevelop.vue';

export default {
  components: {
    gorgeousDevelop
},
  data() {
    return {
      name: 'Gorgeous Develop'
    }
  }
  
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>