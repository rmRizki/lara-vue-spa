<template>
  <div>
    <nav class="nav justify-content-center">
      <router-link :to="{name :'posts'}" class="nav-link">Home</router-link>
      <router-link :to="{name :'create'}" class="nav-link">Tambah Post</router-link>
    </nav>
  </div>
</template>

<script>
export default {};
</script>
