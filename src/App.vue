<template>
  <div class="component">
    <Search />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Search } from '@/components/molecules'

export default defineComponent({
  components: { Search }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>