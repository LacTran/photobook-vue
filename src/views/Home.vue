<template>
  <div class="home">
    <Login />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
// @ is an alias to /src
import Login from "@/components/Login.vue";

export default Vue.extend({
  name: "Home",
  components: {
    Login,
  },
});
</script>
