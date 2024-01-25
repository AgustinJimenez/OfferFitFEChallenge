<template>
  <div class="dashboard">
    <!-- your components -->
    <v-card class="mx-auto" max-width="344" variant="outlined">
      <v-card-item>
        <div>
          <div class="text-overline mb-1">OVERLINE</div>
          <div class="text-h6 mb-1">Headline</div>
          <div class="text-caption">
            Greyhound divisely hello coldly fonwderfully
          </div>
        </div>
      </v-card-item>

      <v-card-actions>
        <v-btn variant="outlined"> Button </v-btn>
      </v-card-actions>
    </v-card>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "ClientDashboard",
  setup() {
    // your code
  },
});
</script>
<style lang="scss"></style>
