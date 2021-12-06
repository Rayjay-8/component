<template>
  <div class="frame-254">
    <div class="frame-252">
      <div class="group-250">
        <div class="badge">
          <p class="novo">{{ novo }}</p>
        </div>
        <div class="line">
          <div class="frame-198">
            <div class="frame">
              <img
                alt=""
                class="vector"
                src="https://static.overlay-tech.com/assets/7f5bce01-f951-44f6-8f9f-40dec5e6f926.svg"
              /><img
                alt=""
                class="vector-stroke"
                src="https://static.overlay-tech.com/assets/9b4d7b2d-9440-4870-9633-f5f56fded978.svg"
              />
            </div>
          </div>
        </div>
      </div>
      <div class="frame-251">
        <p class="licoes-de-escritas">
          {{ licoesDeEscritas }}
        </p>
        <p class="uma-nova-maneira-de-criar-diretrizes-de">
          {{ umaNovaManeiraDeCriarDiretrizesDe }}
        </p>
      </div>
      <div class="group-249">
        <div class="atoms-avatars">
          <img
            alt=""
            class="image-6"
            src="https://static.overlay-tech.com/assets/479bf915-0b36-429d-ba52-3af17a2ba5bb.png"
          />
        </div>
        <div class="atoms-avatars-two">
          <img
            alt=""
            class="image-6"
            src="https://static.overlay-tech.com/assets/315dcd4f-1a48-4b2a-8bba-4d57eb559dca.png"
          />
        </div>
        <div class="atoms-avatars-three">
          <p class="num-2">{{ num2 }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Frame254",
  props: {
    licoesDeEscritas: {
      type: String,
      default: "lições de escritas"
    },
    novo: { type: String, default: "Novo" },
    num2: { type: String, default: "2&#43;" },
    umaNovaManeiraDeCriarDiretrizesDe: {
      type: String,
      default:
        "Uma nova maneira de criar diretrizes de marca"
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.frame-254 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 20px;
  padding: 30px;
  box-shadow: 0 20px 10px -12px rgba(3, 17, 64, 0.05);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.frame-252 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  align-self: stretch;
}
.group-250 {
  margin-bottom: 20px;
  display: flex;
  align-items: center;
}
.badge {
  background-color: rgba(15, 23, 48, 1);
  margin-right: 237px;
  border-radius: 15px;
  padding: 3px 6px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.novo {
  font-family: "IBM Plex Sans";
  font-size: 14px;
  font-weight: 500;
  line-height: 14px;
  color: rgba(255, 255, 255, 1);
  text-align: center;
  text-transform: uppercase;
}
.line {
  border-radius: 5px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.frame-198 {
  border-radius: 5px;
  padding: 5px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  border: 1px solid rgba(207, 212, 226, 1);
}
.frame {
  padding: 8.54px 2.71px;
  flex: 1;
  align-self: stretch;
  position: relative;
}
.vector {
  width: 66.65%;
  height: 8.35%;
  position: absolute;
  left: 3.33px;
  top: 9.17px;
}
.vector-stroke {
  width: 100%;
  height: 100%;
  position: relative;
}
.frame-251 {
  margin-bottom: 20px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.licoes-de-escritas {
  width: 278px;
  font-family: "IBM Plex Sans";
  font-size: 22px;
  font-weight: 700;
  line-height: normal;
  color: rgba(15, 23, 48, 1);
  margin-bottom: 6px;
}
.uma-nova-maneira-de-criar-diretrizes-de {
  max-width: 320px;
  font-family: "IBM Plex Sans";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(15, 23, 48, 1);
}
.group-249 {
  padding: 0 50px 0 0;
  position: relative;
}
.atoms-avatars {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 50%;
  padding: 6.82px 5.4px 6.11px;
  position: relative;
  border: 1px solid rgba(247, 248, 251, 1);
}
.image-6 {
  width: 100%;
  height: 100%;
}
.atoms-avatars-two {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 50%;
  padding: 5.4px 5.4px 4.69px 4.69px;
  display: flex;
  align-items: center;
  position: absolute;
  left: 25px;
  top: 0;
  border: 1px solid rgba(247, 248, 251, 1);
}
.atoms-avatars-three {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 50%;
  padding: 7.53px 8.47px 7.47px 7.53px;
  display: flex;
  align-items: center;
  position: absolute;
  right: 0;
  top: 0;
  border: 1px solid rgba(247, 248, 251, 1);
}
.num-2 {
  width: 100%;
  font-family: "IBM Plex Sans";
  font-size: 11px;
  font-weight: 500;
  line-height: normal;
  color: rgba(85, 91, 109, 1);
  align-self: stretch;
  text-align: center;
}
</style>