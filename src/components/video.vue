<template>
  <div class="video">
    <div class="video_wrapper">
      <video
        width="300"
        height="300"
        poster="../assets/img/block five/Rectangle 2.png"
        class="video_wrap"
      >
        <source src="" type="" />
      </video>
      <ol type="III" class="video_figure">
        <li>IV</li>
      </ol>
    </div>
  </div>
</template>

<script>
export default {
  name: "video",
};
</script>

<style lang="scss" scoped>
.video {
  background-color: #242b33;
  width: 100%;
  min-height: 700px;
}

.video_wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 100%;
  height: 100%;
  padding-left: 5rem;
}

.video_wrap {
  width: 719px;
  height: 650px;
}

.video_figure {
  font-family: "Playfair Display";
  list-style-type: upper-roman;
  font-style: normal;
  font-weight: bold;
  font-size: 400px;
  line-height: 533px;
  color: #ffffff;
  opacity: 0.02;
  width: 464px;
  height: 507px;
  overflow: hidden;
}
</style>
