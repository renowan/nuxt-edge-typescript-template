<template>
  <div>
    <div class="my-header">
      here is header
      <nuxt-link to="/">root</nuxt-link> | 
      <nuxt-link to="/user">user</nuxt-link> | 
      <nuxt-link to="/somepage">error</nuxt-link> | 
    </div>
    <nuxt class="my-body" />

    <div class="my-footer">@copy right</div>
  </div>
</template>

<script lang="ts">
export default {

}
</script>

<style>
.my-header {
  /* width: 100%; */
  padding: 10px;
  margin-bottom: 10px;
  border-bottom: 1px solid #eee;
}

.my-footer {
  padding: 10px;
  border-top: 1px solid #eee;
}

.my-body {
  min-height: 200px;
}
</style>
