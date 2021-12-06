<template>
  <div class="group-3">
    <div class="rectangle-3"></div>
    <div class="group-1">
      <div class="frame">
        <div class="vector"></div>
        <img :src="vector" alt="" class="vector-two" />
      </div>
      <p class="oslo">{{ oslo }}</p>
    </div>
    <p class="wed-nov-24-20121-600-cest">
      {{ wedNov2420121600Cest }}
    </p>
    <p class="sustentabilidade-em-design-de-produto">
      {{ sustentabilidadeEmDesignDeProduto }}
    </p>
    <img
      alt=""
      class="ellipse-1"
      src="https://static.overlay-tech.com/assets/04d7cb33-c45b-416a-8c42-2ac4759581f5.png"
    /><img
      alt=""
      class="ellipse-2"
      src="https://static.overlay-tech.com/assets/d63be84a-71cc-4ff8-aa14-65b3a765ff6e.png"
    /><img
      alt=""
      class="ellipse-3"
      src="https://static.overlay-tech.com/assets/a535b64f-0a5c-44dd-8ab5-08f5bfb1cc2d.png"
    />
    <p class="num-23">&#43;23</p>
    <div class="group-2">
      <p class="comparecer">{{ comparecer }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Group3",
  props: {
    comparecer: { type: String, default: "Comparecer" },
    oslo: { type: String, default: "Oslo" },
    sustentabilidadeEmDesignDeProduto: {
      type: String,
      default: "Sustentabilidade em Design de Produto"
    },
    vector: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/01acd45a-14de-4add-830b-13b99f19702b.svg"
    },
    wedNov2420121600Cest: {
      type: String,
      default: "Wed, Nov 24, 20121 ・6:00 CEST"
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-3 {
  background-color: rgba(51, 63, 107, 1);
  border-radius: 20px;
  padding: 35px;
}
.rectangle-3 {
  width: 100%;
  height: 100%;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 20px;
  position: relative;
}
.group-1 {
  display: flex;
  align-items: center;
  position: absolute;
  left: 85px;
  bottom: 181px;
}
.frame {
  width: calc(38.75% - 10.33px);
  margin-right: 8px;
  padding: 3.88px 5.16px 3.24px 5.17px;
  align-self: stretch;
  position: relative;
}
.vector {
  width: 12.1%;
  height: 12.1%;
  border-radius: 50%;
  position: absolute;
  left: 11.63px;
  top: 10.33px;
  border: 2px solid rgba(19, 33, 82, 1);
}
.vector-two {
  width: 100%;
  height: 100%;
  position: relative;
}
.oslo {
  max-width: 41px;
  width: 51.25%;
  height: 87.1%;
  font-family: "Poppins";
  font-size: 18px;
  font-weight: 600;
  line-height: normal;
  color: rgba(19, 33, 82, 1);
}
.wed-nov-24-20121-600-cest {
  max-width: 249px;
  width: 41.99%;
  height: 5.67%;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 700;
  line-height: normal;
  color: rgba(67, 79, 122, 1);
  position: absolute;
  left: 85px;
  top: 85px;
}
.sustentabilidade-em-design-de-produto {
  max-width: 322px;
  width: 54.3%;
  height: 17.02%;
  font-family: "Poppins";
  font-size: 24px;
  font-weight: 600;
  line-height: normal;
  color: rgba(19, 33, 82, 1);
  position: absolute;
  left: 85px;
  top: 124px;
}
.ellipse-1 {
  width: 6.75%;
  height: 9.46%;
  position: absolute;
  left: 85px;
  bottom: 85px;
  border: 3px solid rgba(255, 255, 255, 1);
  border-radius: 50%;
}
.ellipse-2 {
  width: 6.75%;
  height: 9.46%;
  position: absolute;
  left: 124px;
  bottom: 85px;
  border: 3px solid rgba(255, 255, 255, 1);
  border-radius: 50%;
}
.ellipse-3 {
  width: 6.75%;
  height: 9.46%;
  position: absolute;
  left: 164px;
  bottom: 85px;
  border: 3px solid rgba(255, 255, 255, 1);
  border-radius: 50%;
}
.num-23 {
  max-width: 30px;
  width: 5.06%;
  height: 5.67%;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(67, 79, 122, 1);
  position: absolute;
  left: 220px;
  bottom: 96px;
}
.group-2 {
  background-color: rgba(19, 33, 82, 1);
  border-radius: 5px;
  padding: 14px 12.91px 13px 13px;
  display: flex;
  align-items: center;
  position: absolute;
  right: 56px;
  bottom: 85px;
}
.comparecer {
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(255, 255, 255, 1);
  flex: 1;
  align-self: stretch;
  text-align: center;
}
</style>