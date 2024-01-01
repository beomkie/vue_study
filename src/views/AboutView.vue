<template>
  <div class="about">
    <h1>This is an about page</h1>
    <gorgeousDevelop>
      <template #header="{ gorgeous }">
        <p>header11</p> {{ gorgeous }}       
      </template>
      <template #default>
        hello1
      </template>
    </gorgeousDevelop>
  </div>
</template>

<script>
import gorgeousDevelop from '@/components/gorgeousDevelop.vue'

export default {
  components: {
    gorgeousDevelop
  }  
}
</script>

