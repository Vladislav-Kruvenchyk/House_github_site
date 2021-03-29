<template>
  <div class="content">
    <div class="content_header">
      <div class="wrap">
        <div class="content_item">
          <h2 class="content_header_text">Хотите посмотреть?</h2>
        </div>
        <p class="text">
          Lorem Ipsum - это текст-"рыба", часто используемый в печати и <br />
          вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов
          <br />
          на латинице с начала XVI века. В то время некий безымянный
          <br />
          печатник создал большую коллекцию размеров и форм шрифтов, <br />
          используя Lorem Ipsum для распечатки образцов.
        </p>
      </div>
      <div class="wrapper">
        <div class="content_btn">Ваше имя</div>
        <div class="content_btn_phone">Ваш телефон</div>
        <div class="content_text_bottom">
          *Мы никому не передаем ваши данные. И не сохраняем ваш номер в базу.
        </div>
        <div class="content_btn_two">Посмотреть район</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "content",
};
</script>

<style lang="scss">
.content_item {
  display: block;
}

.content_header_text {
  display: block;
  text-align: end;
  padding-right: 7rem;
  flex-wrap: wrap;
  font-family: "PlayfairDisplay";
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 48px;
  color: #d4c17f;
}

.wrap {
  width: 50%;
  display: block;
  padding-right: 3rem;
}

.wrapper {
  width: 50%;
  width: 540px;
  height: 9rem;
  justify-content: center;
  text-align: center;
  align-items: center;
  display: flex;
  flex-wrap: wrap;
  margin-left: 8px;
}

.content_btn_phone {
  width: 245px;
  height: 50px;
  justify-content: center;
  text-align: center;
  padding: 10px;
  margin-left: 2rem;
  font-family: "Conv_Raleway-Italic";
  background: #ffffff;
  opacity: 0.2;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 27px;
  color: #bebebe;
}

.content_btn {
  font-family: "Conv_Raleway-Italic";
  background: #ffffff;
  opacity: 0.2;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 27px;
  padding: 10px;
  width: 245px;
  height: 50px;
  text-align: center;
  justify-content: center;
  align-items: center;
  color: #bebebe;
}

.content_wrap_two {
  width: 245px;
  height: 50px;
  margin-left: 2rem;
  padding: 10px;
  text-align: center;
}

.content_text_bottom {
  font-family: "Conv_Raleway-Italic";
  color: #e7e7e7;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 16px;
  width: 245px;
  height: 50px;
  font-size: 14px;
  text-align: center;
  justify-content: center;
  align-items: center;
}

.content_btn_two {
  background: #d4c17f;
  color: #ffffff;
  font-family: "Conv_Raleway-Italic";
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 27px;
  width: 245px;
  height: 50px;
  margin-left: 2rem;
  padding: 10px;
}

.content {
  overflow: hidden;
  width: 100%;
  max-height: 560px;
  background: linear-gradient(
      180deg,
      #242b33 10.42%,
      rgba(36, 43, 51, 0) 50.52%,
      #242b33 90.1%
    ),
    url("../assets/img/block four/Rectangle.png") #c4c4c4;
  background-size: cover;
}

.content_header {
  height: 100vh;
  display: flex;
  overflow-x: hidden;
  margin-top: 16rem;
}

.text {
  font-family: "Conv_Raleway-Italic";
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 24px;
  color: #fff;
  justify-content: end;
  margin-top: 1rem;
  display: grid;
}
</style>
