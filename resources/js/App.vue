
<template>
  <div>
    <NavComponent></NavComponent>
    <main>
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
import NavComponent from "./components/posts/Nav.vue";
export default {
  components: {
    NavComponent,
  },
};
</script>
