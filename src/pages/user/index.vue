<template>
  <div>
    <div>this is user page</div>
    <AppInfo></AppInfo>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'nuxt-property-decorator'
import AppInfo from '@/components/Appinfo.vue'

@Component({
  components: {
    AppInfo
  }
})

export default class extends Vue {

}
</script>
