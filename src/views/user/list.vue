<template>
    <div>{{ demo.name }}</div>
</template>

<script lang="ts">
import { Component, Vue, Watch } from 'vue-property-decorator'
import { Route } from 'vue-router'

@Component({
  name: 'UserList',
  components: {
  }
})
export default class extends Vue {
  private demo = {
    name: 'Hello Account System'
  }
}
</script>

<style lang="scss" scoped>

</style>
