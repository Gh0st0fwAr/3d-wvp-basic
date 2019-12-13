<template lang="pug">
   .someanotherdiv
      mainApp()
      .anotherdiv Hello world! App.vue
</template>

<script>
export default {
   components: {
      mainApp: () => import("./scripts/vue/mainapp.vue"),
   }
}
</script>