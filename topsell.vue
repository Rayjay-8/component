<template>
  <div class="group-198">
    <div class="flex-wrapper-one">
      <p class="mais-vendidas">{{ maisVendidas }}</p>
      <ButtonsOutlinedSmall
        class="buttons-outlined-small"
      />
    </div>
    <ComponentsListItem3
      class="components-list-item-3"
    /><ComponentsListItem4
      class="components-list-item-3"
    /><ComponentsListItem2 class="components-list-item-3" />
  </div>
</template>

<script>
import {
  ButtonsOutlinedSmall,
  ComponentsListItem3,
  ComponentsListItem4,
  ComponentsListItem2
} from "components";

export default {
  name: "Topsell",
  components: {
    ButtonsOutlinedSmall,
    ComponentsListItem3,
    ComponentsListItem4,
    ComponentsListItem2
  },
  props: {
    maisVendidas: { type: String, default: "Mais vendidas" }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-198 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 20px;
  padding: 35px 15px 76px;
  box-shadow: 0 20px 10px -12px rgba(3, 17, 64, 0.05);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.flex-wrapper-one {
  margin-bottom: 21px;
  padding: 0 0 0 15px;
  display: flex;
  align-items: flex-start;
}
.mais-vendidas {
  width: 20.41%;
  height: 71.88%;
  font-family: "IBM Plex Sans";
  font-size: 18px;
  font-weight: 600;
  line-height: normal;
  color: rgba(15, 23, 48, 1);
  margin-right: 447px;
}
.buttons-outlined-small {
  align-self: stretch;
}
.components-list-item-3 {
  align-self: stretch;
  &:not(:last-of-type) {
    margin-bottom: 10px;
  }
}
</style>