<template>
  <div class="testimonials">
    <div class="testimonials_content">
      <ul class="testimonials_wrapper">
        <div class="testimonials_wrap">
          <img
            src="../assets/img/block two/bench.png"
            alt=""
            class="testimonials_img"
          />
          <li class="testimonials_list">
            Рядом исторические <br />
            парки и скверы
          </li>
        </div>

        <div class="testimonials_wrap">
          <img
            src="../assets/img/block two/bicycle.png"
            alt=""
            class="testimonials_img"
          />
          <li class="testimonials_list">
            Полностью <br />
            обустроенный
          </li>
        </div>
        <div class="testimonials_wrap">
          <img
            src="../assets/img/block two/building.png"
            alt=""
            class="testimonials_img"
          />
          <li class="testimonials_list">
            10 фонтанов <br />
            на территории
          </li>
        </div>
        <div class="testimonials_wrap">
          <img
            src="../assets/img/block two/fountain.png"
            alt=""
            class="testimonials_img"
          />
          <li class="testimonials_list">
            6 км <br />
            велодорожек
          </li>
        </div>
      </ul>
      <ol type="I" class="testimonials_figure">
        <li>II</li>
      </ol>
    </div>
  </div>
</template>

<script>
export default {
  name: "testimonials",
};
</script>

<style lang="scss">
.testimonials_wrap {
  display: block;
  flex-basis: 24%;
  width: auto;
  margin-top: 22rem;
}

.testimonials_list {
  display: block;
  margin-top: 30px;
  height: 12rem;
  font-family: Roboto;
  font-style: normal;
  font-weight: 300;
  font-size: 19px;
  line-height: 27px;
  text-align: center;
  color: #ffffff;
  text-align: center;
  color: #ffffff;
}

.testimonials {
  min-height: 800px;
  width: 100%;
  background-color: #242b33;
  justify-content: center;
}

.testimonials_figure {
  margin-top: 12rem;
  font-family: "Playfair Display";
  list-style-type: upper-roman;
  font-style: normal;
  font-weight: bold;
  font-size: 400px;
  line-height: 533px;
  color: #ffffff;
  opacity: 0.02;
  width: 301px;
  height: 507px;
  overflow: hidden;
}

.testimonials_wrapper {
  display: flex;
  justify-content: center;
  text-align: center;
  align-items: center;
  height: 44rem;
  flex-basis: 50%;
}
.testimonials_content {
  margin-left: 6rem;
  width: 100%;
  height: 106%;
  display: flex;
  justify-content: center;
}

img {
  width: 80px;
  height: 80px;
}
</style>
