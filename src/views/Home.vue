<template>
  <div class="home">
    <Drawing />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Drawing from "@/components/Drawing.vue"; // @ is an alias to /src

export default defineComponent({
  name: "Home",
  components: {
    Drawing,
  },
});
</script>
