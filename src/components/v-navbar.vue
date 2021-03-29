<template>
  <nav class="header_navigation">
    <ul class="navigation">
      <li class="navigation_item">
        <a href="" class="navigation_link">О комплексе</a>
      </li>
      <li class="navigation_item">
        <a href="" class="navigation_link">Район</a>
      </li>
      <li class="navigation_item">
        <a href="" class="navigation_link">Каталог квартир</a>
      </li>
      <li class="navigation_item">
        <a href="" class="navigation_link">Ипотека</a>
      </li>
      <li class="navigation_item">
        <a href="" class="navigation_link">Контакты</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "navbar",
};
</script>

<style lang="scss" scoped>
.header_navigation {
  text-align: justify;
  margin-right: 40px;
}

nav {
  display: block;
}

li {
  list-style: none;
}

ul li {
  max-width: 150px;
  max-height: 30px;
  display: inline-block;
  text-align: left;
}
.navigation_item_two,
.navigation_item_four {
  width: 110px;
  height: 30px;
}
.navigation {
  display: flex;
  &_item {
    margin-right: 20px;
    position: relative;
    width: 20px;
    height: 20px;
  }
  &_link {
    height: 2rem;
    display: block;
    font-size: 14px;
    letter-spacing: 0.05em;
    // text-transform: uppercase;
    line-height: 16px;
    color: #dcf;
    font-weight: normal;
    text-decoration: none;
    white-space: nowrap;
    cursor: pointer;
    pointer-events: auto;
    overflow: visible;
    position: fixed;
    padding-bottom: 0;
    margin-top: 10px;
  }
}
// .navigation_item_one li {
//     margin: 94px 16px;
// }
</style>
