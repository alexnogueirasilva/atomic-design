<template>
  <div class="social-networks">
    <SocialLink
      name="Github"
      to="https://github.com/alexnogueirasilva"
      icon="github.svg"
    />
    <SocialLink
      name="Twitter"
      to="https://github.com/alexnogueirasilva"
      icon="twitter.svg"
    />
    <SocialLink
      name="Facebook"
      to="https://github.com/alexnogueirasilva"
      icon="facebook.svg"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atomos'

export default defineComponent({
  components: { SocialLink }
})
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
