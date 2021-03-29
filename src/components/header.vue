<template>
  <div class="header">
    <div class="hero_icon"></div>
    <main>
      <nav class="header_navigation">
        <ul class="wrapper">
          <li class="logo">HouseVOP</li>
          <li class="logo_two">ЖИЛОЙ КОМПЛЕКС</li>
        </ul>
        <ul class="navigation">
          <li class="navigation_item"><a class="navbar_li">О комплексе</a></li>
          <li class="navigation_item"><a class="navbar_li">Район</a></li>
          <li class="navigation_item">
            <a class="navbar_li">Каталог квартир</a>
          </li>
          <li class="navigation_item"><a class="navbar_li">Ипотека</a></li>
          <li class="navigation_item"><a class="navbar_li">Контакты</a></li>
        </ul>
      </nav>

      <div class="header_content">
        <ul class="header_wrapper">
          <h1 class="header_text">
            Жилой комплекс
            <br />
            в историческом центре
          </h1>
        </ul>
      </div>

      <div class="header_footer">
        <ul class="footer_item">
          <img
            src="../assets/img/block one/Vector.png"
            alt=""
            class="footer_img_one"
          />
          <li class="footer_list_one">Наб. реки Фонтанки 10-15</li>
          <img
            src="../assets/img/block one/Phone.png"
            alt=""
            class="footer_img"
          />
          <li class="footer_list_two">8 (812) 123-45-67</li>
        </ul>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "header",
  components: {},
};
</script>

<style lang="scss">
.testimonials_wrapper {
  width: 794px;
  height: 180px;
  top: 4rem;
  text-align: center;
  justify-content: center;
}
.testimonials_content {
  background: #242b33;
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
}

img {
  width: 80px;
  height: 80px;
}

.header_footer {
  position: absolute;
  z-index: 1;
  height: 100%;
  width: 100%;
  top: 346px;
  display: flex;
  justify-content: center;
  text-align: center;
  align-items: center;
  flex-direction: column;
  margin: 0 auto;
}
.footer_item {
  position: absolute;
  height: 55px;
  display: flex;
  justify-content: center;
}

.footer_img {
  width: 14px;
  height: 20px;
}
.footer_img_one {
  width: 14px;
  height: 20px;
  margin-right: 25px;
}
.footer_list_one {
  height: 50px;
  width: 343px;
  font-family: "Conv_Raleway-Italic";
  text-align: justify;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 21px;
  color: #fff;
}

.footer_list_two {
  width: 181px;
  height: 50px;
  font-family: "Conv_Raleway-Italic";
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 21px;
  color: #fff;
}

.header_content {
  overflow: hidden;
  position: absolute;
  z-index: 1;
  height: 100%;
  width: 100%;
  top: 0;
  display: flex;
  justify-content: center;
  text-align: center;
  flex-direction: column;
  margin: 0 auto;
}

.header_wrapper {
  margin-top: -5rem;
}

.header_text {
  font-family: "Playfair Display_two";
  font-style: normal;
  font-weight: bold;
  font-size: 48px;
  line-height: 64px;
  color: #d4c17f;
}

a {
  text-decoration: none;
  color: #fff;
  z-index: 111111;
}

.hero_icon {
  display: flex;
  width: 1920px;
  height: 840px;
  background: linear-gradient(
      180deg,
      #242b33 11.98%,
      rgba(45, 52, 60, 0.38) 51.04%,
      #242b33 92.19%
    ),
    url("../assets/img/block one/Rectangle.jpg");
  background-size: cover;
  z-index: 1;
  overflow: hidden;
}

.navigation {
  display: flex;
  justify-content: space-between;
  flex-basis: 36%;
  padding-top: 0rem;
  margin-right: 18rem;
  width: 100px;
  height: 110px;
  color: #fff;
}

.header_navigation {
  overflow: hidden;
  z-index: 1111;
  position: fixed;
  height: 100px;
  width: 100%;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  color: #fff;
  display: flex;
  justify-content: space-between;
}

.logo {
  display: block;
  justify-content: flex-end;
  text-align: end;
  font-family: "Jaffna", sans-serif;
  padding-top: 0rem;
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 54px;
}

.logo_two {
  justify-content: flex-end;
  text-align: end;
  display: flex;
  z-index: 222;
  padding-bottom: 2rem;
  font-family: "Raleway";
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 14px;
  letter-spacing: 0.12em;
  color: #ffffff;
}
.wrapper {
  display: flex;
  justify-content: space-between;
  flex-basis: 29%;
  padding-bottom: 3rem;
  flex-direction: column;
  width: 20rem;
  height: 10rem;
}
.navigation_item {
  position: fixed;
  position: relative;
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

.navbar_li {
  color: #fff;
}
</style>
