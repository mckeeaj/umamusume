<template>
  <div :class="$style.home">
    <h1>Under development.</h1>
    <h3>Contact me on Discord: AMcKee#4171</h3>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({
  components: {}
})
export default class Home extends Vue {}
</script>

<style lang="scss" module>
.home {
  padding-top: 20%;
}
</style>
