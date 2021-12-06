<template>
  <div class="group-253">
    <div class="group-252">
      <div class="atoms-pie">
        <img :src="group205" alt="" class="group-205" />
      </div>
      <p class="num-18">{{ num18 }}</p>
    </div>
    <p class="taxa-livre">{{ taxaLivre }}</p>
  </div>
</template>

<script>
export default {
  name: "Group253",
  props: {
    group205: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/9826ad1c-0894-4932-9e32-7c6b0c7635fc.svg"
    },
    num18: { type: String, default: "18%" },
    taxaLivre: { type: String, default: "Taxa livre" }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-253 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 20px;
  padding: 30px 85px 30px 30px;
  box-shadow: 0 20px 10px -12px rgba(3, 17, 64, 0.05);
  display: flex;
  align-items: center;
}
.group-252 {
  margin-right: 15px;
  position: relative;
}
.atoms-pie {
  width: calc(100% - 5.8px);
  height: calc(100% - 5.8px);
  padding: 2.9px;
  position: relative;
}
.group-205 {
  width: 52.2px;
  height: 52.2px;
}
.num-18 {
  width: 53.45%;
  height: 31.03%;
  font-family: "IBM Plex Sans";
  font-size: 14px;
  font-weight: 500;
  line-height: normal;
  color: rgba(15, 23, 48, 1);
  text-align: center;
  position: absolute;
  left: 13px;
  top: 20px;
  letter-spacing: 0.14px;
}
.taxa-livre {
  width: 52.9%;
  height: 39.66%;
  font-family: "IBM Plex Sans";
  font-size: 18px;
  font-weight: 700;
  line-height: normal;
  color: rgba(15, 23, 48, 1);
}
</style>