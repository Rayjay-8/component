<template>
  <div class="group-1">
    <div class="frame-2">
      <p class="sort-by-popularity">
        {{ sortByPopularity }}
      </p>
    </div>
    <div class="frame-7">
      <div class="frame-3">
        <p class="filtro-por-padrao">
          {{ filtroPorPadrao }}
        </p>
      </div>
      <div class="frame-6">
        <p class="filtro-por-padrao">{{ az }}</p>
      </div>
      <div class="frame-3">
        <p class="populares">{{ populares }}</p>
        <div class="frame">
          <img :src="vector" alt="" class="vector" />
        </div>
      </div>
      <div class="frame-3">
        <p class="filtro-por-padrao">{{ ultimos }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Group1",
  props: {
    az: { type: String, default: "A-Z" },
    filtroPorPadrao: {
      type: String,
      default: "Filtro por padrão"
    },
    populares: { type: String, default: "Populares" },
    sortByPopularity: {
      type: String,
      default: "Sort by Popularity"
    },
    ultimos: { type: String, default: "Ultimos" },
    vector: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/ade99771-921f-4d5f-8396-245047b98cfa.svg"
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-1 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.frame-2 {
  width: calc(64.09% - 26px);
  height: calc(16.29% - 26px);
  background-color: rgba(255, 255, 255, 1);
  margin-bottom: 7px;
  margin-left: 89px;
  border-radius: 5px;
  padding: 13px;
  display: flex;
  align-items: flex-start;
  border: 2px solid rgba(102, 139, 250, 1);
}
.sort-by-popularity {
  max-width: 140px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(33, 50, 100, 1);
}
.frame-7 {
  height: calc(80.13% - 30px);
  background-color: rgba(255, 255, 255, 1);
  border-radius: 10px;
  padding: 15px;
  box-shadow: 0 14px 34px 0 rgba(158, 176, 228, 0.3);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  align-self: stretch;
}
.frame-3 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 5px;
  padding: 15px;
  display: flex;
  align-items: flex-start;
  width: 199px;
}
.filtro-por-padrao {
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(33, 50, 100, 1);
  flex: 1;
}
.frame-6 {
  background-color: rgba(233, 238, 253, 1);
  border-radius: 5px;
  padding: 15px;
  display: flex;
  align-items: flex-start;
  width: 199px;
}
.populares {
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(33, 50, 100, 1);
  flex: 1;
  margin-right: 10px;
}
.frame {
  padding: 6.42px 3.67px 6.41px 4.58px;
  display: flex;
  align-items: center;
  width: 13.75px;
  height: 9.17px;
}
.vector {
  width: 100%;
  align-self: stretch;
  object-fit: cover;
}
</style>