<template>
  <div class="component">
    <Logo />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Logo } from '@/components/atomos'

export default defineComponent({
  components: { Logo }
})
</script>

<style lang="scss" scoped>
.component {
}
</style>