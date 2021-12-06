<template>
  <div class="group-1">
    <p class="category">{{ category }}</p>
    <div class="flex-wrapper-one">
      <div class="flex-wrapper-two">
        <div class="rectangle-3"></div>
        <div class="rectangle-4"></div>
        <div class="rectangle-5"></div>
        <div class="rectangle-3"></div>
        <div class="rectangle-3"></div>
        <div class="rectangle-3"></div>
        <div class="rectangle-3"></div>
        <div class="rectangle-4"></div>
        <div class="rectangle-3"></div>
        <div class="rectangle-5"></div>
        <div class="rectangle-4"></div>
        <div class="rectangle-5"></div>
        <div class="rectangle-3"></div>
      </div>
      <p
        class="bracelets-65-brooches-pins-18-cand"
        v-html="bracelets65BroochesPins18Cand"
      ></p>
    </div>
  </div>
</template>

<script>
export default {
  name: "CategoriasFiltro",
  props: {
    bracelets65BroochesPins18Cand: {
      type: String,
      default:
        "Bracelets ∙ 65<br /> Brooches &#43; Pins ∙ 18<br /> Candles &#43; Diffusers ∙ 179<br /> Cushions &#43; Throws ∙ 299<br /> Decorative Objects ∙ 92<br /> Earrings ∙ 418<br /> Necklaces ∙ 225<br /> Notebooks &#43; Stationery ∙ 94<br /> Rings ∙ 131<br /> Tools &#43; Gadgets ∙ 50<br /> Wall Decor ∙ 33<br /> Watches ∙ 117<br /> Writing Tools ∙ 27"
    },
    category: { type: String, default: "Category" }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-1 {
  background-color: rgba(57, 64, 91, 1);
  border-radius: 10px;
  padding: 50px 68px 100px 50px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.category {
  width: 35.37%;
  height: 4.37%;
  font-family: "Merriweather";
  font-size: 18px;
  font-weight: 700;
  line-height: normal;
  color: rgba(255, 255, 255, 1);
  margin-bottom: 35px;
}
.flex-wrapper-one {
  display: flex;
  align-items: flex-start;
}
.flex-wrapper-two {
  margin-right: 12px;
  padding: 9px 0 0;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.rectangle-3 {
  height: 3.86%;
  background-color: rgba(37, 43, 69, 1);
  border-radius: 3px;
  align-self: stretch;
  border: 1px solid rgba(156, 165, 199, 1);
  &:not(:last-of-type) {
    margin-bottom: 17px;
  }
}
.rectangle-4 {
  height: 3.86%;
  background-color: rgba(37, 43, 69, 1);
  margin-bottom: 16px;
  border-radius: 3px;
  align-self: stretch;
  border: 1px solid rgba(156, 165, 199, 1);
}
.rectangle-5 {
  height: 3.86%;
  background-color: rgba(37, 43, 69, 1);
  margin-bottom: 18px;
  border-radius: 3px;
  align-self: stretch;
  border: 1px solid rgba(156, 165, 199, 1);
}
.bracelets-65-brooches-pins-18-cand {
  max-width: 200px;
  width: 87.34%;
  font-family: "IBM Plex Sans";
  font-size: 16px;
  font-weight: 400;
  line-height: 36px;
  color: rgba(255, 255, 255, 1);
  align-self: stretch;
}
</style>