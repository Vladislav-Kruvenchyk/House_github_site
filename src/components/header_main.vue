<template>
  <div class="header">
    <div class="img"></div>

    <main>
      <nav class="navigation_header">
        <ul class="navigation_wrap">
          <li class="navigation_item_one">HouseVOP</li>
          <li class="navigation_item_two">ЖИЛОЙ КОМПЛЕКС</li>
        </ul>
        <ul class="navigation_wrapper">
          <li class="navigation_list">О комплексе</li>
          <li class="navigation_list">Район</li>
          <li class="navigation_list">Каталог квартир</li>
          <li class="navigation_list">Ипотека</li>
          <li class="navigation_list">Контакты</li>
        </ul>
      </nav>
      <div class="header_content">
        <ul class="header_wrapper">
          <li class="header_text">
            Жилой комплекс <br />
            в историческом центре
          </li>
        </ul>
      </div>

      <div class="header_footer">
        <ul class="footer_item">
          <li class="footer_list_one">
            <img
              src="../assets/img/block one/Vector.png"
              alt=""
              class="footer_img_one"
            />Наб. реки Фонтанки 10-15
          </li>
          <li class="footer_list_two">
            <img
              src="../assets/img/block one/Phone.png"
              alt=""
              class="footer_img_two"
            />8 (812) 123-45-67
          </li>
        </ul>
      </div>
    </main>
    <testimonials />
    <house />
    <vContent />
    <vVideo />
    <vStrict />
    <vQuestion />
    <vFooter />
  </div>
</template>

<script>
import house from "./house";
import testimonials from "./testimonials";
import vContent from "./content";
import vVideo from "./video";
import vStrict from "./strict";
import vQuestion from "./questin";
import vFooter from "./footer";
export default {
  name: "header",
  components: {
    testimonials,
    house,
    vContent,
    vVideo,
    vStrict,
    vQuestion,
    vFooter,
  },
};
</script>

<style lang="scss">
.footer_img_one,
.footer_img_two {
  width: 17px;
  height: 20px;
  margin-right: 1rem;
}

.header {
  width: 100%;
  min-height: 800px;
}

.header_footer {
  position: absolute;
  display: flex;
  top: 50rem;
  justify-content: center;
  text-align: center;
}

.footer_item {
  display: flex;
  text-align: left;
  align-items: center;
  justify-content: center;
  flex-basis: 33%;
  font-family: "Conv_Raleway-Italic";
  text-align: center;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  color: #fff;
}
.header_content {
  top: 19rem;
  font-family: "Playfair Display_two";
  font-style: normal;
  font-weight: bold;
  font-size: 48px;
  line-height: 64px;
  color: #d4c17f;
  position: absolute;
  display: flex;
  justify-content: center;
  text-align: center;
}

.header_wrapper {
  width: 600px;
  height: 150px;
}

.img {
  height: 840px;
  width: 1940px;
  top: 0;
  left: 0;
  z-index: 1;
  overflow: hidden;
  background-size: cover;
  background-image: url("../assets/img/block one/Rectangle.jpg");
}

.navigation_header {
  overflow: hidden;
  z-index: 1111;
  position: fixed;
  height: 75px;
  width: 100%;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  display: flex;
  justify-content: flex-end;
}

.navigation_wrap {
  text-align: center;
  justify-content: center;
}

.navigation_item_one {
  font-family: "Jaffna", sans-serif;
  padding-top: 0rem;
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 54px;
  color: #fff;
}

.navigation_item_two {
  font-family: "Raleway";
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 14px;
  letter-spacing: 0.12em;
  color: #fff;
}
.navigation_wrapper {
  display: flex;
  justify-content: space-between;
  flex-basis: 70%;
  width: 100px;
  height: 75px;
  margin-right: 15rem;
}

.navigation_list {
  overflow: hidden;
  font-family: "Conv_Raleway-Italic";
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  letter-spacing: 0.05em;
  display: flex;
  justify-content: center;
  text-align: center;
  align-items: center;
  color: #fff;
}
</style>
