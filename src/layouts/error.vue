<template>
  <div>
    this is error page: {{error.statusCode}}
  </div>
</template>

<script lang="js">
export default {
  props: {
    error: {
      type: Object, default: () => {}
    }
  },
  layout: 'other'
}
</script>

<style>
.my-footer {
  padding: 10px;
  border-top: 1px solid #eee;
}

.my-body {
  min-height: 200px;
}
</style>