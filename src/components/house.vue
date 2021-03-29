<template>
  <div class="house">
    <div class="house_text">
      <h1 class="house_text_item">Наши квартиры</h1>
    </div>
    <ol type="II" class="description_figure">
      <li>III</li>
    </ol>
    <div class="house_description_one">
      <div class="description_one">
        <img
          src="../assets/img/block tree/Rectangle_one.png"
          alt=""
          class="description_img_one"
        />
        <img
          src="../assets/img/block tree/Rectangle_two.png"
          alt=""
          class="description_img_one"
        />
      </div>
    </div>
    <div class="house_description_two">
      <div class="description_two">
        <img
          src="../assets/img/block tree/Rectangle_one.png"
          alt=""
          class="description_img_two"
        />
        <img
          src="../assets/img/block tree/Rectangle_two.png"
          alt=""
          class="description_img_two"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "house",
};
</script>

<style lang="scss">
.house {
  min-height: 800px;
  width: 100%;
  background-color: #242b33;
  justify-content: center;
  position: relative;
}

.house_description_one,
.house_description_two {
  display: flex;
}

.description_one,
.description_two {
  justify-content: center;
  text-align: center;
  flex-basis: 100%;
  margin-top: 4rem;
}

.description_img_one,
.description_img_two {
  width: 536px;
  height: 320px;
  padding: 10px;
}
.description_figure {
  position: absolute;
  font-family: "Playfair Display";
  list-style-type: upper-roman;
  font-style: normal;
  font-weight: bold;
  font-size: 400px;
  line-height: 533px;
  color: #ffffff;
  opacity: 0.02;
  width: 452px;
  height: 507px;
  overflow: hidden;
  padding-bottom: 36rem;
  margin-left: 10rem;
  transform: translateY(-109px);
}

.house_text {
  margin-left: 2rem;
  display: flex;
}

.house_text_item {
  flex-basis: 55%;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 48px;
  color: #d4c17f;
}
</style>
