<template>
  <div class="group-2">
    <p class="sort-by">Sort by</p>
    <div class="flex-wrapper-two">
      <p class="alphabetically-a-z">
        {{ alphabeticallyaz }}
      </p>
      <div class="frame">
        <img :src="vector" alt="" class="vector" />
      </div>
    </div>
    <div class="flex-wrapper-one">
      <div class="rectangle-16"></div>
      <p
        class="bestselling-featured-price-low-to-high"
        v-html="bestsellingFeaturedPriceLowToHigh"
      ></p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Filtro3",
  props: {
    alphabeticallyaz: {
      type: String,
      default: "Alphabetically: A-Z"
    },
    bestsellingFeaturedPriceLowToHigh: {
      type: String,
      default:
        "Bestselling<br /> Featured<br /> Price: Low to High<br /> Price: High to Low<br /> Alphabetically: A-Z<br /> Alphabetically: Z-A<br /> Date: New to Old<br /> Date: Old to New"
    },
    vector: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/d78f74be-664d-47e3-80bb-0530ca912658.svg"
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-2 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.sort-by {
  width: 20.16%;
  height: 4.82%;
  font-family: "IBM Plex Sans";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(255, 255, 255, 1);
  margin-bottom: 11px;
}
.flex-wrapper-two {
  background-color: rgba(37, 43, 69, 1);
  margin-bottom: 5px;
  border-radius: 3px;
  padding: 19px 29px 18px;
  display: flex;
  align-items: center;
  border: 1px solid rgba(156, 165, 199, 1);
}
.alphabetically-a-z {
  width: 70.47%;
  height: 65.63%;
  font-family: "IBM Plex Sans";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(255, 255, 255, 1);
  margin-right: 25px;
}
.frame {
  width: calc(16.58% - 16px);
  padding: 12px 8px;
  display: flex;
  align-items: center;
  align-self: stretch;
}
.vector {
  flex: 1;
  align-self: stretch;
  object-fit: cover;
}
.flex-wrapper-one {
  background-color: rgba(57, 64, 91, 1);
  border-radius: 10px;
  padding: 20px 87px 20px 30px;
  box-shadow: 0 8px 28px -12px rgba(7, 11, 28, 1);
  position: relative;
}
.rectangle-16 {
  width: 96.05%;
  height: 11.28%;
  background-color: rgba(37, 43, 69, 1);
  border-radius: 5px;
  position: absolute;
  left: 5px;
  top: 164px;
}
.bestselling-featured-price-low-to-high {
  max-width: 136px;
  width: 100%;
  height: 100%;
  font-family: "IBM Plex Sans";
  font-size: 16px;
  font-weight: 400;
  line-height: 36px;
  color: rgba(255, 255, 255, 1);
  position: relative;
}
</style>