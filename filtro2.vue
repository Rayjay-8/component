<template>
  <div class="component-1">
    <div class="atoms-medium-input">
      <div class="frame-211">
        <p class="all-types">All types</p>
        <div class="chevron-down">
          <img
            alt=""
            class="vector"
            src="https://static.overlay-tech.com/assets/b5e817be-813d-413b-9c24-5ca3f516518b.svg"
          />
        </div>
      </div>
    </div>
    <div class="frame-212">
      <div class="frame-82">
        <div class="checkbox-input">
          <div class="checkbox">
            <div class="group-6"><Check /></div>
          </div>
          <p class="descoberta-de-produto">
            {{ descobertaDeProduto }}
          </p>
        </div>
      </div>
      <div class="frame-82">
        <div class="checkbox-input">
          <div class="checkbox-two">
            <div class="group-6-two">
              <div class="done-black-24dp-1">
                <img
                  alt=""
                  class="vector-two"
                  src="https://static.overlay-tech.com/assets/3e3b09d6-ae72-4fe4-ae89-4db47c117cfc.svg"
                />
              </div>
            </div>
          </div>
          <p class="descoberta-de-produto">
            {{ software }}
          </p>
        </div>
      </div>
      <div class="frame-84">
        <div class="checkbox-input">
          <div class="checkbox">
            <div class="group-6"><Check /></div>
          </div>
          <p class="descoberta-de-produto">
            {{ gestaoDeServicos }}
          </p>
        </div>
      </div>
      <div class="frame-82">
        <div class="checkbox-input">
          <div class="checkbox">
            <div class="group-6"><Check /></div>
          </div>
          <p class="descoberta-de-produto">
            {{ negocios }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { Check } from "components";

export default {
  name: "Component1",
  components: { Check },
  props: {
    descobertaDeProduto: {
      type: String,
      default: "Descoberta de produto"
    },
    gestaoDeServicos: {
      type: String,
      default: "Gestão de Serviços"
    },
    negocios: { type: String, default: "Negócios" },
    software: { type: String, default: "Software" }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.component-1 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.atoms-medium-input {
  width: 92.83%;
  height: 17.81%;
  border-radius: 4px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.frame-211 {
  border-radius: 4px;
  padding: 12px 10px 12px 18px;
  display: flex;
  align-items: flex-start;
  align-self: stretch;
  border: 2px solid rgba(0, 0, 0, 1);
}
.all-types {
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(146, 149, 156, 1);
  flex: 1;
  margin-right: 10px;
  letter-spacing: 0.16px;
}
.chevron-down {
  padding: 7.87px 5.5px 7.34px;
  display: flex;
  align-items: center;
  width: 11px;
  height: 6.79px;
}
.vector {
  flex: 1;
  align-self: stretch;
  object-fit: cover;
}
.frame-212 {
  width: calc(92.83% - 32px);
  height: calc(82.19% - 32px);
  background-color: rgba(255, 255, 255, 1);
  margin-left: 22px;
  border-radius: 16px;
  padding: 16px;
  box-shadow: 0 7px 15px 0 rgba(24, 31, 89, 0.15);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.frame-82 {
  border-radius: 4px;
  padding: 12px 8px;
  display: flex;
  align-items: center;
  align-self: stretch;
}
.checkbox-input {
  border-radius: 4px;
  padding: 4px;
  display: flex;
  align-items: center;
  flex: 1;
}
.checkbox {
  margin-right: 6px;
  border-radius: 4px;
  display: flex;
  align-items: center;
  width: 20px;
  height: 20px;
}
.group-6 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 4px;
  padding: 0.82px;
  display: flex;
  align-items: center;
  border: 1px solid rgba(161, 173, 178, 1);
}
.descoberta-de-produto {
  font-family: "Poppins";
  font-size: 14px;
  font-weight: 500;
  line-height: 20px;
  color: rgba(0, 0, 0, 1);
  letter-spacing: 0.14px;
}
.checkbox-two {
  margin-right: 6px;
  border-radius: 4px;
  display: flex;
  align-items: flex-start;
  width: 20px;
  height: 20px;
}
.group-6-two {
  background-color: rgba(248, 110, 176, 1);
  border-radius: 4px;
  padding: 1.82px;
  display: flex;
  align-items: center;
}
.done-black-24dp-1 {
  padding: 3.82px 2.04px 3.4px 2.32px;
  display: flex;
  align-items: center;
  flex: 1;
  align-self: stretch;
}
.vector-two {
  height: 100%;
  flex: 1;
  object-fit: cover;
}
.frame-84 {
  background-color: rgba(255, 240, 249, 1);
  border-radius: 4px;
  padding: 11px 7px;
  display: flex;
  align-items: center;
  align-self: stretch;
  border: 1px solid rgba(251, 215, 230, 1);
}
</style>