<template>
    <q-page class="flex flex-center">
      <img alt="Quasar logo" src="statics/Pandora.png" width="200rem">
      <q-btn color="blue-grey-10"
        class="full-width"
        label="Iniciar Realidade Aumentada"
        @click="routeModify()"/>
  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex',
  methods: {
    routeModify () {
      this.$router.push({ name: 'aframe' })
    }
  }
}
</script>
