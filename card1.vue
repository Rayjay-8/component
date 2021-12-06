<template>
  <div class="group-5">
    <div class="flex-wrapper-one">
      <div class="group-1">
        <div class="frame">
          <img
            alt=""
            class="vector"
            src="https://static.overlay-tech.com/assets/1dc31051-9f95-4672-ab2a-ec93caade3c0.svg"
          />
        </div>
      </div>
    </div>
    <div class="group-2">
      <p class="kr599">{{ kr599 }}</p>
      <div class="flex-wrapper-two">
        <p class="kr189">{{ kr189 }}</p>
        <div class="frame-2">
          <p class="num-68-off">{{ num68Off }}</p>
        </div>
      </div>
    </div>
    <div class="group-3">
      <p class="compre-agora">Compre Agora</p>
    </div>
    <div class="group-4">
      <p class="adicionar-ao-carrinho">
        Adicionar ao Carrinho
      </p>
    </div>
    <p class="garantia-de-devolucao-do-dinheiro-em-30">
      Garantia de devolução do dinheiro em 30 dias
    </p>
    <p class="inclui">{{ inclui }}</p>
    <p
      class="num-35-horas-de-video-sob-demanda-acesso-vi"
      v-html="num35HorasDeVideoSobDemandaAcessoVi"
    ></p>
  </div>
</template>

<script>
export default {
  name: "Group5",
  props: {
    inclui: { type: String, default: "Inclui" },
    kr189: { type: String, default: "Kr189" },
    kr599: { type: String, default: "Kr599" },
    num35HorasDeVideoSobDemandaAcessoVi: {
      type: String,
      default:
        "3,5 horas de vídeo sob demanda<br /> Acesso vitalício completo<br /> Arquivos de exercícios<br /> Acesso de qualquer lugar<br /> Certificado de conclusão"
    },
    num68Off: { type: String, default: "68% off" }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-5 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 25px;
  padding: 40px 33px 36px 31px;
  box-shadow: 0 12px 1px -5px rgba(205, 218, 243, 1);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.flex-wrapper-one {
  background-size: 100% 100%;
  background-position: center;
  background: url("https://static.overlay-tech.com/assets/4b8d671c-786b-4dde-884e-f205db09a17b.png"),
    rgba(25, 30, 69, 0.3);
  margin-bottom: 29px;
  margin-left: 9px;
  border-radius: 20px;
  padding: 57px 110px 57px 111px;
  box-shadow: 0 17px 17px -10px rgba(110, 107, 255, 0.4);
  display: flex;
  align-items: center;
}
.group-1 {
  background-color: rgba(255, 255, 255, 0.6);
  border-radius: 50%;
  padding: 11px;
  display: flex;
  align-items: center;
}
.frame {
  padding: 7.33px 7.34px 7.34px 12.83px;
  display: flex;
  align-items: center;
  flex: 1;
  align-self: stretch;
}
.vector {
  width: 100%;
  align-self: stretch;
  object-fit: cover;
}
.group-2 {
  margin-bottom: 29px;
  margin-left: 9px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.kr599 {
  width: 27.4%;
  height: 35.29%;
  font-family: "Mulish";
  font-size: 14px;
  font-weight: 600;
  line-height: normal;
  color: $dark-slate-gray-2;
  text-decoration: line-through;
  margin-bottom: 5px;
}
.flex-wrapper-two {
  display: flex;
  align-items: flex-start;
}
.kr189 {
  width: 43.15%;
  color: $midnight-blue;
  align-self: stretch;
  margin-right: 10px;
  @include mulish-22-bold;
}
.frame-2 {
  width: calc(50% - 20px);
  background-color: $olive-drab;
  border-radius: 20px;
  padding: 5px 10px;
  display: flex;
  align-items: flex-start;
  align-self: stretch;
}
.num-68-off {
  color: rgba(255, 255, 255, 1);
  @include mulish-14-bold-2;
}
.group-3 {
  background-color: $medium-slate-blue;
  margin-bottom: 15px;
  margin-left: 9px;
  border-radius: 5px;
  padding: 18px 88px 17px 89px;
  box-shadow: 0 4px 0 0 $royal-blue;
  display: flex;
  align-items: center;
}
.compre-agora {
  font-family: "Mulish";
  font-size: 16px;
  font-weight: 600;
  line-height: normal;
  color: rgba(255, 255, 255, 1);
  flex: 1;
  align-self: stretch;
  text-align: center;
}
.group-4 {
  background-color: rgba(233, 233, 255, 1);
  margin-bottom: 16px;
  margin-left: 9px;
  border-radius: 5px;
  padding: 18px 60px 17px 62px;
  display: flex;
  align-items: center;
}
.adicionar-ao-carrinho {
  font-family: "Mulish";
  font-size: 16px;
  font-weight: 600;
  line-height: normal;
  color: $medium-slate-blue;
  flex: 1;
  align-self: stretch;
  text-align: center;
}
.garantia-de-devolucao-do-dinheiro-em-30 {
  width: 99.67%;
  height: 2.82%;
  font-family: "Mulish";
  font-size: 14px;
  font-weight: 600;
  line-height: normal;
  color: $dark-slate-gray-2;
  text-align: center;
  margin-bottom: 56px;
  margin-left: 1px;
}
.inclui {
  width: 17.82%;
  height: 2.98%;
  color: $midnight-blue;
  text-transform: uppercase;
  margin-bottom: 10px;
  margin-left: 9px;
  letter-spacing: 1.61px;
  @include mulish-14-bold;
}
.num-35-horas-de-video-sob-demanda-acesso-vi {
  max-width: 273px;
  width: 90.1%;
  height: 16.46%;
  font-family: "Mulish";
  font-size: 16px;
  font-weight: 600;
  line-height: 21px;
  color: $midnight-blue;
}
</style>