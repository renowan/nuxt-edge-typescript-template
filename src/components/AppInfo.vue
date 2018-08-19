<template>
  <div class="app-info">
    <h3>AppInfo component</h3>
    Nuxt-edge,<br>
    Typescript<br>
    tslint<br>
    sass<br>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'

@Component
export default class extends Vue {

}
</script>

<style lang="scss" scoped>
.app-info {
  padding: 10px;
  border: 1px solid #eee;
  margin: 30px 0;
}
</style>
