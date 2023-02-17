<template>
  <div class="container">
    <div class="itemleft">
      <page><template #main>
          <one></one>
        </template></page>
      <page><template #main>
          <two></two>
        </template></page>
    </div>
    <div class="itemRight">
      <page><template #main>
          <three></three>
        </template></page>
      <page><template #main>
          <four></four>
        </template></page>
    </div>
  </div>
</template>

<script lang="ts" setup>
import page from "../../../components/itemPage.vue"
import one from "../../../components/one.vue"
import two from "../../../components/two.vue"
import three from "../../../components/three.vue"
import four from "../../../components/four.vue"
</script>

<style lang="scss">
.container {
  width: 100%;
  margin: 0 auto;
  background-color: gray;
  display: flex;

  .itemleft,
  .itemRight {
    flex: 1;
  }
}
</style>