<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import { add } from './test.js'
export default defineComponent({
  name: 'IndexPage'
})
const c = add(1, 7)
console.log(c)

</script>
