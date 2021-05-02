<template>
  <div class="component">
    <NavItem text="Home" to="/home" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { NavItem } from '@/components/atomos'

export default defineComponent({
  components: { NavItem }
})
</script>

<style lang="scss" scoped>
.component {
}
</style>