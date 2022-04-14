<template>
  <div>
    <div class="firstScreen">
      <Header></Header>
    </div>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
export default {
  components: {
    Header,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>

<style lang="less" scoped>
.firstScreen {
  width: 100%;
  height: 100vh;
  background-color: rgb(235, 205, 205);
}
</style>