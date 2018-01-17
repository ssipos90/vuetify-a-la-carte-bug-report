<template>
  <v-expansion-panel>
    <v-expansion-panel-content v-for="(item,i) in 5" :key="i">
      <div slot="header">Item</div>
      <p>{{ item }}Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </v-expansion-panel-content>
  </v-expansion-panel>
</template>
<script>
  import { VExpansionPanel } from 'vuetify';
  export default {
    components: {
      VExpansionPanel
    }
  };
</script>
