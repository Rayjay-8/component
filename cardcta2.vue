<template>
  <div class="group-7">
    <p
      class="codigo-aberto-gratis-para-sempre"
      v-html="codigoAbertoGratisParaSempre"
    ></p>
    <p class="aproveite-nossa-versao-completa-e-gratui">
      {{ aproveiteNossaVersaoCompletaeGratui }}
    </p>
    <div class="group-9">
      <div class="group-8">
        <div class="frame">
          <img :src="vector" alt="" class="vector" />
        </div>
        <p class="clone-do-git-hub">{{ cloneDoGitHub }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Cardcta2",
  props: {
    aproveiteNossaVersaoCompletaeGratui: {
      type: String,
      default: "Aproveite nossa versão completa e gratuita."
    },
    cloneDoGitHub: {
      type: String,
      default: "Clone do GitHub"
    },
    codigoAbertoGratisParaSempre: {
      type: String,
      default: "Código aberto.<br /> Grátis para sempre."
    },
    vector: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/12bfe51e-eef8-4359-954c-ff0bab5628ae.svg"
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-7 {
  background-color: $black;
  border-radius: 25px;
  padding: 60px 55px 49px 64px;
  box-shadow: 0 42px 20px -29px $transparent-black;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.codigo-aberto-gratis-para-sempre {
  max-width: 216px;
  width: 75%;
  height: 32.65%;
  color: $silver;
  margin-bottom: 10px;
  margin-left: 6px;
  @include merriweather-22-bold;
}
.aproveite-nossa-versao-completa-e-gratui {
  max-width: 282px;
  width: 97.92%;
  height: 23.47%;
  color: $silver;
  margin-bottom: 28px;
  margin-left: 6px;
  @include mulish-18-regular;
}
.group-9 {
  background-color: $dark-slate-blue;
  border-radius: 10px;
  padding: 13px 35px 13px 20px;
  display: flex;
  align-items: center;
}
.group-8 {
  display: flex;
  align-items: center;
}
.frame {
  width: calc(14.77% - 6.42px);
  margin-right: 5px;
  padding: 2.82px 3.67px 2.75px 2.75px;
  display: flex;
  align-items: center;
  align-self: stretch;
}
.vector {
  flex: 1;
  align-self: stretch;
  object-fit: cover;
}
.clone-do-git-hub {
  width: 81.88%;
  height: 90.91%;
  color: $white;
  @include mulish-16-regular;
}
</style>