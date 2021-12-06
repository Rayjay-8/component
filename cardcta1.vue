<template>
  <div class="group-6">
    <p class="quer-avaliar">{{ querAvaliar }}</p>
    <div class="flex-wrapper-one">
      <div class="flex-wrapper-two">
        <p class="experimente-nossa-plataforma-e-comece-a">
          {{ experimenteNossaPlataformaeComecea }}
        </p>
        <div class="group-5">
          <p class="avalie-agora">{{ avalieAgora }}</p>
        </div>
      </div>
      <div class="group-4">
        <div class="group-1">
          <div class="frame">
            <img :src="vector" alt="" class="vector" />
          </div>
          <p class="todos-os-recursos-disponiveis">
            {{ todosOsRecursosDisponiveis }}
          </p>
        </div>
        <div class="group-1">
          <div class="frame-two">
            <img :src="vectorTwo" alt="" class="vector" />
          </div>
          <p class="suporte-da-comunidade">
            {{ suporteDaComunidade }}
          </p>
        </div>
        <div class="group-1">
          <div class="frame-three">
            <img :src="vectorThree" alt="" class="vector" />
          </div>
          <p class="apenas-para-fins-de-teste">
            {{ apenasParaFinsDeTeste }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Group6",
  props: {
    apenasParaFinsDeTeste: {
      type: String,
      default: "Apenas para fins de teste"
    },
    avalieAgora: { type: String, default: "Avalie agora" },
    experimenteNossaPlataformaeComecea: {
      type: String,
      default:
        "Experimente nossa plataforma e comece a desenvolver ideias."
    },
    querAvaliar: { type: String, default: "Quer avaliar?" },
    suporteDaComunidade: {
      type: String,
      default: "Suporte da comunidade"
    },
    todosOsRecursosDisponiveis: {
      type: String,
      default: "Todos os recursos disponíveis"
    },
    vector: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/306abc03-1aea-407d-a5b8-fc993430f4fa.svg"
    },
    vectorThree: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/85afef4d-f5dc-48ef-b66e-39babc29f5ae.svg"
    },
    vectorTwo: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/8cfd76dd-722a-40bf-8f58-a9e7e1cc2142.svg"
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-6 {
  background-color: rgba(28, 23, 46, 1);
  border-radius: 25px;
  padding: 60px 12px 60px 70px;
  box-shadow: 0 42px 20px -29px rgba(22, 18, 39, 0.44);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.quer-avaliar {
  height: 17.42%;
  width: 37%;
  font-family: "Merriweather";
  font-size: 22px;
  font-weight: 700;
  line-height: normal;
  color: rgba(188, 184, 204, 1);
  display: flex;
  margin-bottom: 10px;
}
.flex-wrapper-one {
  padding: 0 0 4px;
  display: flex;
  align-items: flex-start;
}
.flex-wrapper-two {
  margin-right: 90px;
  padding: 4px 0 0;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.experimente-nossa-plataforma-e-comece-a {
  height: 35.66%;
  font-family: "Mulish";
  font-size: 18px;
  font-weight: 400;
  line-height: normal;
  color: rgba(188, 184, 204, 1);
  align-self: stretch;
  margin-bottom: 40px;
}
.group-5 {
  background-color: rgba(73, 41, 187, 1);
  border-radius: 10px;
  padding: 14px 52px 13px 44px;
  display: flex;
  align-items: center;
}
.avalie-agora {
  font-family: "Mulish";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(255, 255, 255, 1);
  flex: 1;
  align-self: stretch;
}
.group-4 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.group-1 {
  display: flex;
  align-items: center;
  &:not(:last-of-type) {
    margin-bottom: 15px;
  }
}
.frame {
  width: calc(8.98% - 8.25px);
  margin-right: 4px;
  padding: 6.42px 3.67px 6.41px 4.58px;
  display: flex;
  align-items: center;
  align-self: stretch;
}
.vector {
  width: 100%;
  align-self: stretch;
  object-fit: cover;
}
.todos-os-recursos-disponiveis {
  width: 89.39%;
  height: 90.91%;
  font-family: "Mulish";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(188, 184, 204, 1);
}
.frame-two {
  width: calc(10.78% - 8.25px);
  margin-right: 4px;
  padding: 6.42px 3.67px 6.41px 4.58px;
  display: flex;
  align-items: center;
  align-self: stretch;
}
.suporte-da-comunidade {
  width: 87.25%;
  height: 90.91%;
  font-family: "Mulish";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(188, 184, 204, 1);
}
.frame-three {
  width: calc(10.19% - 8.25px);
  margin-right: 4px;
  padding: 6.42px 3.67px 6.41px 4.58px;
  display: flex;
  align-items: center;
  align-self: stretch;
}
.apenas-para-fins-de-teste {
  width: 87.96%;
  height: 90.91%;
  font-family: "Mulish";
  font-size: 16px;
  font-weight: 400;
  line-height: normal;
  color: rgba(188, 184, 204, 1);
}
</style>