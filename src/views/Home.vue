<template>
  <div class="home">
    <Home2 />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Home2 from "@/components/Home2.vue"; // @ is an alias to /src

export default defineComponent({
  name: "Home",
  components: {
    Home2,
  },
});
</script>
