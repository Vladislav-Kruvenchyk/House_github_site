<template>
  <div class="strict">
    <div class="strict_content">
      <span class="strict_text">Район на карте</span>
      <ol type="III" class="strict_figure">
        <li>V</li>
      </ol>
      <div class="strict_map">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d40667.177298395814!2d30.5627311!3d50.4280873!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40d4cf0b371a3ecd%3A0x7b942a840e62e26c!2z0J_QtdGH0LXRgNGB0LrQuNC5INGA0LDQudC-0L0sINCa0LjQtdCyLCAwMjAwMA!5e0!3m2!1sru!2sua!4v1612354413204!5m2!1sru!2sua"
          width="1110"
          height="358"
          frameborder="0"
          style="border:0; width: 1100px;height: 358px;"
          allowfullscreen=""
          aria-hidden="false"
          tabindex="0"
        ></iframe>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "strict",
};
</script>

<style lang="scss" scoped>
.strict {
  overflow: hidden;
  position: relative;
  justify-content: center;
  background-color: #242b33;
  width: 100%;
  min-height: 500px;
}

.strict_figure {
  font-family: "Playfair Display";
  list-style-type: upper-roman;
  font-style: normal;
  font-weight: bold;
  font-size: 400px;
  line-height: 533px;
  color: #ffffff;
  opacity: 0.02;
  position: absolute;
  width: 464px;
  margin-left: 13rem;
  transform: translateY(-118px);
  height: 548px;
  overflow: hidden;
}

.strict_content {
  margin-top: 4rem;
}

.strict_text {
  text-align: center;
  padding-right: 53rem;
  font-family: "PlayfairDisplay";
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 48px;
  color: #d4c17f;
}

.strict_map {
  overflow: hidden;
  margin-top: 3rem;
  height: 358px;
  text-align: center;
}
</style>
