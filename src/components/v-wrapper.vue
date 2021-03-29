<template>
  <div class="wrapper">
    <vHeader />
    <vNavbar />
  </div>
</template>

<script>
import vHeader from "./v-header";
import vNavbar from "./v-navbar";

export default {
  name: "wrapper",
  components: {
    vHeader,
    vNavbar,
  },
};
</script>
<style scoped lang="scss">
.wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: relative;
  padding: 32px;
  flex-shrink: 0;
}
</style>
