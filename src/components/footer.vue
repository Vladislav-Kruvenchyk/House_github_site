<template>
  <div class="footer">
    <div class="footer_container">
      <div class="footer_left">
        <li class="footer_text_left">HouseVOP</li>
        <li class="footer_text_left_two">ЖИЛОЙ КОМПЛЕКС</li>
      </div>
      <div class="footer_middle">
        <li>О комплексе</li>
        <li>Район</li>
        <li>Каталог квартир</li>
        <li>Ипотека</li>
        <li>Контакты</li>
      </div>
      <div class="footer_right">
        <li>О комплексе</li>
        <li>Район</li>
        <li>Каталог квартир</li>
        <li>Ипотека</li>
        <li>Контакты</li>
      </div>
      <div class="footer_data">
        <li>Адрес: Наб. реки Фонтанки 10-15</li>
        <li>Телефон: 8 (812) 123-45-67</li>
        <li>Отдел продаж: 10:00 - 20:00</li>
        <li>E-mail: <a href="" class="footer_email"> vip@housevip.ru</a></li>
        <ul class="footer_icon">
          <li class="youtube"><a href=""></a></li>
          <li class="vkontakte"><a href=""></a></li>
          <li class="facebook"><a href=""></a></li>
          <li class="instagram"><a href=""></a></li>
          <li class="instagram_border"><a href=""></a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "footer",
};
</script>

<style lang="scss" scoped>
.footer_icon {
  overflow: hidden;
  width: 11rem;
  height: 2rem;
  display: flex;
  align-items: center;
}

.instagram_border {
  position: relative;
  z-index: 111;
  overflow: hidden;
  width: 10px;
  height: 10px;
  transform: translateX(-15px);
  background-image: url("../assets/img/block six/instagram.png");
  background-size: cover;
}
.instagram {
  margin-left: 25px;
  overflow: hidden;
  width: 20px;
  height: 20px;
  background-image: url("../assets/img/block six/instagram_border.png");
  background-size: cover;
}
.facebook {
  margin-left: 25px;
  overflow: hidden;
  width: 10px;
  height: 18px;
  background-image: url("../assets/img/block six/facebook.png");
  background-size: cover;
}

.vkontakte {
  margin-left: 25px;
  overflow: hidden;
  width: 28px;
  height: 16px;
  background-image: url("../assets/img/block six/vk.png");
  background-size: cover;
}

.youtube {
  overflow: hidden;
  width: 25px;
  height: 17px;
  background-image: url("../assets/img/block six/Vector.png");
  background-size: cover;
}

.footer {
  width: 100%;
  min-height: 245px;
  background: #2d343c;
  justify-content: center;
  display: flex;
  list-style-type: none;
}
.footer_container {
  display: inherit;
  height: 100%;
  padding-top: 3rem;
  width: 1600px;
  justify-content: center;
}

.footer_left {
  max-width: 355px;
  padding-left: 4rem;
}

.footer_middle {
  flex-shrink: 1;
  width: 285px;
}
.footer_right {
  flex-shrink: 1;
  width: 257px;
}

.footer_data {
  flex-shrink: 01;
  width: 300px;
}

.footer_text_left {
  font-family: "Jaffna";
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 54px;
  color: #ffffff;
}

.footer_text_left_two {
  font-family: sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 14px;
  letter-spacing: 0.12em;
  color: #ffffff;
}

.footer_middle,
.footer_right,
.footer_data {
  font-family: "Conv_Raleway-Italic";
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 30px;
  letter-spacing: 0.05em;

  color: #ffffff;
}

.footer_email {
  color: #d4c17f;
}
</style>
