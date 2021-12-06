<template>
  <div class="group-251">
    <div class="frame-4">
      <div class="atoms-breadcrums-item">
        <p class="home">{{ home }}</p>
        <div class="frame">
          <img
            :src="vectorStroke"
            alt=""
            class="vector-stroke"
          />
        </div>
      </div>
      <div class="atoms-breadcrums-item">
        <p class="home">{{ projects }}</p>
        <div class="frame-two">
          <img
            :src="vectorStrokeTwo"
            alt=""
            class="vector-stroke"
          />
        </div>
      </div>
      <AtomsBreadcrumsItemState4
        class="atoms-breadcrums-item-state4"
      />
    </div>
    <div class="flex-wrapper-one">
      <p class="conceitos-de-locais-definidos">
        {{ conceitosDeLocaisDefinidos }}
      </p>
      <div class="group-249">
        <div class="atoms-avatars">
          <img
            alt=""
            class="image-10"
            src="https://static.overlay-tech.com/assets/c47939cc-f63a-4e73-8dcc-ce35aed6d6b2.png"
          />
        </div>
        <div class="atoms-avatars-two">
          <img
            alt=""
            class="image-9"
            src="https://static.overlay-tech.com/assets/4cf69fec-c2b7-482a-9022-6aaed112b7b5.png"
          />
        </div>
        <div class="atoms-avatars-three">
          <img
            alt=""
            class="image-9-two"
            src="https://static.overlay-tech.com/assets/6811b425-c271-4498-a9eb-c5376cf00864.png"
          />
        </div>
        <div class="atoms-avatars-four">
          <p class="num-2">{{ num2 }}</p>
        </div>
      </div>
    </div>
    <div class="flex-wrapper-two">
      <div class="tab">
        <div class="atoms-button">
          <div class="frame-210">
            <div class="frame-206">
              <p class="timeline">{{ timeline }}</p>
            </div>
          </div>
        </div>
        <div class="atoms-button">
          <div class="frame-210">
            <div class="frame-206-two">
              <p class="issues">{{ issues }}</p>
              <div class="badge">
                <p class="num-2-two">{{ num2Two }}</p>
              </div>
            </div>
          </div>
        </div>
        <div class="atoms-button">
          <div class="frame-210">
            <div class="frame-206-three">
              <p class="timeline">{{ reports }}</p>
            </div>
          </div>
        </div>
        <div class="atoms-button">
          <div class="frame-210">
            <div class="frame-206-three">
              <p class="timeline">{{ activities }}</p>
            </div>
          </div>
        </div>
      </div>
      <div class="frame-255">
        <div class="line">
          <div class="frame-198">
            <div class="frame-197">
              <div class="frame-three">
                <img
                  :src="vectorStrokeThree"
                  alt=""
                  class="vector-stroke-two"
                /><img
                  :src="vectorStrokeFour"
                  alt=""
                  class="vector-stroke-three"
                />
              </div>
              <p class="editar">{{ editar }}</p>
            </div>
          </div>
        </div>
        <div class="line">
          <div class="frame-198-two">
            <div class="frame-197">
              <div class="frame-four">
                <img
                  :src="vectorStrokeFive"
                  alt=""
                  class="vector-stroke-four"
                />
              </div>
              <p class="adicionar-atividade">
                {{ adicionarAtividade }}
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { AtomsBreadcrumsItemState4 } from "components";

export default {
  name: "Group251",
  components: { AtomsBreadcrumsItemState4 },
  props: {
    activities: { type: String, default: "Activities" },
    adicionarAtividade: {
      type: String,
      default: "Adicionar atividade"
    },
    conceitosDeLocaisDefinidos: {
      type: String,
      default: "Conceitos de locais definidos"
    },
    editar: { type: String, default: "Editar" },
    home: { type: String, default: "Home" },
    issues: { type: String, default: "Issues" },
    num2: { type: String, default: "2&#43;" },
    num2Two: { type: String, default: "2" },
    projects: { type: String, default: "Projects" },
    reports: { type: String, default: "Reports" },
    timeline: { type: String, default: "Timeline" },
    vectorStroke: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/c392647f-9c6a-440d-b17f-676e9af67c18.svg"
    },
    vectorStrokeFive: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/6eae2f84-f905-41da-b1b2-4c3de1d258b8.svg"
    },
    vectorStrokeFour: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/65abef8f-6b92-4cfe-9bc4-44e321517df6.svg"
    },
    vectorStrokeThree: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/3a48725e-ddaa-47be-9d36-a2b48b262dad.svg"
    },
    vectorStrokeTwo: {
      type: String,
      default:
        "https://static.overlay-tech.com/assets/d146fd19-6932-4b7a-b567-cad3205c2ccd.svg"
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-251 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 20px;
  padding: 30px 40px 0 25px;
  box-shadow: 0 20px 10px -12px rgba(3, 17, 64, 0.05);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.frame-4 {
  margin-bottom: 10px;
  margin-left: 15px;
  display: flex;
  align-items: flex-start;
}
.atoms-breadcrums-item {
  margin-right: 5px;
  display: flex;
  align-items: center;
}
.home {
  font-family: "IBM Plex Sans";
  font-size: 14px;
  font-weight: 500;
  line-height: 24px;
  color: rgba(66, 73, 237, 1);
  margin-right: 5px;
  letter-spacing: 0.14px;
}
.frame {
  width: calc(26.67% - 11px);
  height: calc(66.67% - 7px);
  padding: 3.5px 5.5px;
  display: flex;
  align-items: center;
}
.vector-stroke {
  flex: 1;
  align-self: stretch;
  object-fit: cover;
}
.frame-two {
  width: calc(21.33% - 11px);
  height: calc(66.67% - 7px);
  padding: 3.5px 5.5px;
  display: flex;
  align-items: center;
}
.atoms-breadcrums-item-state4 {
  width: 33px;
  height: 24px;
}
.flex-wrapper-one {
  margin-bottom: 29px;
  padding: 0 0 0 15px;
  display: flex;
  align-items: flex-start;
}
.conceitos-de-locais-definidos {
  width: 60.88%;
  height: 90%;
  font-family: "IBM Plex Sans";
  font-size: 28px;
  font-weight: 700;
  line-height: normal;
  color: rgba(15, 23, 48, 1);
  margin-right: 183px;
}
.group-249 {
  padding: 0 94px 0 0;
  position: relative;
}
.atoms-avatars {
  width: calc(90% - 10.22px);
  height: calc(90% - 10.22px);
  background-color: rgba(255, 255, 255, 1);
  border-radius: 50%;
  padding: 5.11px;
  position: relative;
  border: 2px solid rgba(247, 248, 251, 1);
}
.image-10 {
  width: 100%;
  height: 100%;
  border-radius: 23px;
}
.atoms-avatars-two {
  width: calc(26.87% - 11.11px);
  height: calc(90% - 11.11px);
  background-color: rgba(255, 255, 255, 1);
  border-radius: 50%;
  padding: 6px 6px 5.11px 5.11px;
  display: flex;
  align-items: center;
  position: absolute;
  left: 31.5px;
  top: 0;
  border: 2px solid rgba(247, 248, 251, 1);
}
.image-9 {
  flex: 1;
  align-self: stretch;
  border-radius: 22px;
  object-fit: cover;
}
.atoms-avatars-three {
  width: calc(26.87% - 11.11px);
  height: calc(90% - 11.11px);
  background-color: rgba(255, 255, 255, 1);
  border-radius: 50%;
  padding: 6px 6px 5.11px 5.11px;
  display: flex;
  align-items: center;
  position: absolute;
  left: 62.75px;
  top: 0;
  border: 2px solid rgba(247, 248, 251, 1);
}
.image-9-two {
  flex: 1;
  align-self: stretch;
  border-radius: 23px;
  object-fit: cover;
}
.atoms-avatars-four {
  width: calc(26.87% - 18px);
  height: calc(90% - 18px);
  background-color: rgba(255, 255, 255, 1);
  border-radius: 50%;
  padding: 8.67px 10.33px 9.33px 7.67px;
  display: flex;
  align-items: center;
  position: absolute;
  left: 94px;
  top: 0;
  border: 2px solid rgba(247, 248, 251, 1);
}
.num-2 {
  font-family: "IBM Plex Sans";
  font-size: 14px;
  font-weight: 500;
  line-height: normal;
  color: rgba(85, 91, 109, 1);
  flex: 1;
  align-self: stretch;
  text-align: center;
}
.flex-wrapper-two {
  display: flex;
  align-items: flex-start;
}
.tab {
  width: 48.13%;
  height: 82.26%;
  margin-top: 11px;
  margin-right: 120px;
  display: flex;
  align-items: flex-start;
}
.atoms-button {
  padding: 15px 0 0;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.frame-210 {
  padding: 0 0 11px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  border-bottom: 4px solid rgba(15, 23, 48, 1);
}
.frame-206 {
  padding: 0 15px;
  display: flex;
  align-items: flex-start;
}
.timeline {
  font-family: "IBM Plex Sans";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(15, 23, 48, 1);
}
.frame-206-two {
  opacity: 0.7;
  padding: 0 15px;
  display: flex;
  align-items: center;
}
.issues {
  font-family: "IBM Plex Sans";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(15, 23, 48, 1);
  margin-right: 5px;
}
.badge {
  background-color: rgba(15, 23, 48, 1);
  border-radius: 15px;
  padding: 0 6px;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 20px;
}
.num-2-two {
  font-family: "IBM Plex Sans";
  font-size: 14px;
  font-weight: 500;
  line-height: 14px;
  color: rgba(255, 255, 255, 1);
  text-align: center;
  text-transform: uppercase;
}
.frame-206-three {
  opacity: 0.7;
  padding: 0 15px;
  display: flex;
  align-items: flex-start;
}
.frame-255 {
  width: 36.91%;
  height: 51.61%;
  display: flex;
  align-items: flex-start;
}
.line {
  border-radius: 5px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  &:not(:last-of-type) {
    margin-right: 10px;
  }
}
.frame-198 {
  border-radius: 5px;
  padding: 1px 14px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  border: 1px solid rgba(207, 212, 226, 1);
}
.frame-197 {
  display: flex;
  align-items: center;
  height: 28px;
}
.frame-three {
  width: calc(27.03% - 5.98px);
  height: calc(71.43% - 5.98px);
  margin-right: 10px;
  padding: 3.27px 3.27px 2.71px 2.71px;
  position: relative;
}
.vector-stroke-two {
  width: 100%;
  height: 100%;
  position: relative;
}
.vector-stroke-three {
  width: 22.9%;
  height: 22.9%;
  position: absolute;
  right: 4.79px;
  top: 4.79px;
}
.editar {
  font-family: "IBM Plex Sans";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(85, 91, 109, 1);
}
.frame-198-two {
  background-color: rgba(15, 23, 48, 1);
  border-radius: 5px;
  padding: 2px 15px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.frame-four {
  width: calc(13.16% - 3.75px);
  height: calc(71.43% - 5.42px);
  margin-right: 5px;
  padding: 2.71px 1.87px 2.71px 1.88px;
  display: flex;
  align-items: center;
}
.vector-stroke-four {
  height: 100%;
  flex: 1;
  object-fit: cover;
}
.adicionar-atividade {
  font-family: "IBM Plex Sans";
  font-size: 14px;
  font-weight: 500;
  line-height: normal;
  color: rgba(255, 255, 255, 1);
  letter-spacing: 0.14px;
}
</style>