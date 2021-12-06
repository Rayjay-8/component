<template>
  <div class="group-2">
    <div class="group-1">
      <p class="obrigado-as-descricoes-de-seus-produt">
        {{ obrigadoAsDescricoesDeSeusProdut }}
      </p>
      <div class="flex-wrapper-one">
        <img :src="ellipse1" alt="" class="ellipse-1" />
        <div class="group-1">
          <p class="ronald-a-freeman">
            {{ ronaldaFreeman }}
          </p>
          <p class="electronic-technician">
            {{ electronicTechnician }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Group2",
  props: {
    electronicTechnician: {
      type: String,
      default: "Electronic technician"
    },
    ellipse1: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/459d2ebe-ec9a-4887-80d7-84736104327e.png"
    },
    obrigadoAsDescricoesDeSeusProdut: {
      type: String,
      default:
        "&#34; Obrigado! As descrições de seus produtos são incríveis e seu serviço é maravilhoso. “"
    },
    ronaldaFreeman: {
      type: String,
      default: "Ronald A. Freeman"
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-2 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 25px;
  padding: 50px 60px;
  display: flex;
  align-items: center;
}
.group-1 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.obrigado-as-descricoes-de-seus-produt {
  height: 59.57%;
  font-family: "IBM Plex Sans";
  font-size: 18px;
  font-weight: 500;
  line-height: 28px;
  color: rgba(21, 21, 47, 1);
  align-self: stretch;
  margin-bottom: 20px;
}
.flex-wrapper-one {
  display: flex;
  align-items: center;
}
.ellipse-1 {
  width: 25.45%;
  align-self: stretch;
  margin-right: 10px;
  border-radius: 50%;
  object-fit: cover;
}
.ronald-a-freeman {
  height: 46.51%;
  font-family: "Merriweather";
  font-size: 16px;
  font-weight: 900;
  line-height: normal;
  color: rgba(21, 21, 47, 1);
  align-self: stretch;
  margin-bottom: 5px;
}
.electronic-technician {
  width: 87.66%;
  height: 41.86%;
  font-family: "IBM Plex Sans";
  font-size: 14px;
  font-weight: 500;
  line-height: normal;
  color: rgba(21, 21, 47, 1);
}
</style>