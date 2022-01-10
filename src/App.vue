<template lang="pug">
.app Welcome to our Project
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api';

const App = defineComponent({
  // setup() {},
});

export default App;
</script>

<style lang="scss">
// .app {}
// SETUP PRIMARY AND SECONDARY COLOR HERE
:root {
  // 900 / 500
  --color-primary-100: #989386;
  --color-primary-200: #8E897B;
  --color-primary-300: #797567;
  --color-primary-400: #635F55;
  --color-primary-500: #4D4A42;
  --color-primary-600: #37352F;
  --color-primary-700: #191815;
  --color-primary-800: #000000;
  --color-primary-900: #000000;

  // --color-secondary-100: #E9EFF9;
  // --color-secondary-200: #C7D7F1;
  // --color-secondary-300: #A5BFE8;
  // --color-secondary-400: #6290D7;
  // --color-secondary-500: #1F60C6;
  // --color-secondary-600: #1C56B2;
  // --color-secondary-700: #133A77;
  // --color-secondary-800: #0E2B59;
  // --color-secondary-900: #091D3B;
}
</style>
