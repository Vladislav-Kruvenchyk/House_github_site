<template>
  <div class="header">
    <div class="header_left">
      <a href="" class="header_main_logo">HouseVOP</a>
      <a href="" class="header_wrap">ЖИЛОЙ КОМПЛЕКС</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "header",
  components: {},
};
</script>

<style lang="scss">
.header {
  text-align: justify;
  div a {
    display: block;
  }
  &_left div a {
    max-width: 200px;
    max-height: 29px;
    display: block;
    position: fixed;
    flex-grow: 1;
    flex-shrink: 1;
    flex-basis: 0%;
  }
  &_main_logo {
    margin-left: 24rem;
    display: block;
    font-size: 36px;
    font-family: "Jaffna", sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 36px;
    line-height: 54px;
    max-width: 150px;
    color: #aaf;
    height: 3rem;
    z-index: 111;
    width: 200px;
    height: 3rem;
  }
  &_wrap {
    margin-left: 24rem;
    position: fixed;
    display: block;
    font-size: 12px;
    color: #faf;
  }
}
</style>
