<template>
  <div>
    <div class="my-header">
      here is other layout [ <nuxt-link to="/">go root</nuxt-link> ]
    </div>
    <nuxt class="my-body" />

    <div class="my-footer">other layout footer, @copy right</div>
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
