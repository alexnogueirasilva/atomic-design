<template>
<<<<<<< HEAD
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "./components/HelloWorld.vue";

export default defineComponent({
  name: "App",
  components: {
    HelloWorld,
  },
});
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
=======
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
>>>>>>> 806e438 (criando atomo Logo)
