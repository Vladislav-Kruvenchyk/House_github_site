<template>
  <div class="question">
    <div class="question_wrapper">
      <h1 class="question_text">Есть вопросы?</h1>
      <!-- <ul class="question_wrap"> -->
      <p class="question_text_item">
        *Мы никому не передаем ваши данные. И не сохраняем ваш номер в базу.
      </p>
      <input class="question_input" placeholder="Ваше имя" />
      <input class="question_input" placeholder="Ваш телефон" />
      <button class="question_btn">Посмотреть район</button>
      <!-- </ul> -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'question',
}
</script>

<style lang="scss" scoped>
.question_text {
  text-align: start;
  padding-left: 1rem;
  font-family: 'PlayfairDisplay';
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 48px;
  color: #d4c17f;
}
.question {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  background-color: #242b33;
  justify-content: center;
  display: flex;
  text-align: center;
  align-items: center;
  width: 100%;
  min-height: 500px;
}

.question_wrapper {
  justify-content: center;
  display: flex;
  text-align: center;
  flex-wrap: wrap;
  display: flex;
  width: 1115px;
  min-height: 136px;
}

.question_input {
  text-align: center;
  margin-top: 1rem;
  margin-left: 1.5rem;
  width: 255px;
  height: 50px;
  font-family: 'Conv_Raleway-Italic';
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 27px;
  color: #bebebe;
  background: #ffffff;
  opacity: 0.2;
}

.question_btn {
  text-align: center;
  margin-top: 1rem;
  margin-left: 1.5rem;
  width: 255px;
  height: 50px;
  font-family: 'Conv_Raleway-Italic';
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 27px;
  color: #fff;
  background: #d4c17f;
}

.question_text_item {
  margin-top: 1rem;
  width: 255px;
  overflow: hidden;
  padding: 10px;
  height: 50px;
  font-family: sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 16px;
  text-align: center;
  color: #e7e7e7;
}
</style>
