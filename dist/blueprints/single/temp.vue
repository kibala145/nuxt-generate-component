<template>
  <div :class="$style.wrapper"></div>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'

@Component({})
export default class {{(name.split('/')[name.split('/').length-1]) | pascalCase}}Component extends Vue {}
</script>

<style lang="scss" module>
.wrapper {
}
</style>
