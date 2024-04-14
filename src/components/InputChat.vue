<template>
  <div>
    <v-form>
        <v-text-area
            v-model="firstname"
            :counter="10"
            label="First name"
            hide-details
            required
        >
        </v-text-area>
    </v-form>
  </div>
</template>

<script>
export default {
  name: 'InputChat',
  data() {
    return {
      // Vos données ici
    }
  },
  methods: {
    // Vos méthodes ici
  }
};
</script>

<style scoped>
/* Votre CSS ici */
</style>