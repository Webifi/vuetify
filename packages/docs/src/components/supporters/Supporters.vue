<template>
  <v-container
    fluid
    pa-0
  >

    <supporters-sub-github />

    <supporters-sub-open-collective />

    <supporters-sub-tidelift />

    <supporters-sub-paypal />

    <v-flex xs12>
      <base-heading>sponsors</base-heading>
    </v-flex>

    <v-flex
      xs12
      my-2
      tag="v-divider"
    />

    <supporters-sponsors />
  </v-container>
</template>

<script>
  export default {
    inheritAttrs: false,
  }
</script>
