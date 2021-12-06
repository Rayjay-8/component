<template>
  <div class="group-9">
    <p class="filter">{{ filter }}</p>
    <div class="group-1">
      <p class="location">{{ location }}</p>
      <div class="flex-wrapper-one">
        <div class="frame">
          <div class="vector"></div>
          <img
            alt=""
            class="vector-two"
            src="https://static.overlay-tech.com/assets/c7b051d9-52b2-48c7-a51a-59b788d94fc1.svg"
          />
        </div>
        <p class="eg-london">{{ egLondon }}</p>
      </div>
    </div>
    <div class="group-1">
      <p class="experience-level">{{ experienceLevel }}</p>
      <div class="flex-wrapper-two">
        <div class="group-3">
          <div class="rectangle-4"></div>
          <p class="num-1-2-years">{{ num12Years }}</p>
        </div>
        <div class="group-3">
          <div class="rectangle-4"></div>
          <p class="num-1-2-years">{{ num35Years }}</p>
        </div>
      </div>
      <div class="flex-wrapper-two">
        <div class="group-3">
          <div class="rectangle-4"></div>
          <p class="num-1-2-years">{{ num68Years }}</p>
        </div>
        <div class="group-3">
          <div class="rectangle-4-two"></div>
          <p class="num-9-years">{{ num9Years }}</p>
        </div>
      </div>
    </div>
    <div class="group-1">
      <p class="target">{{ target }}</p>
      <div class="flex-wrapper-four">
        <div class="group-3-two">
          <div class="rectangle-4-three"></div>
          <p class="freelancer">{{ freelancer }}</p>
        </div>
        <div class="group-3-two">
          <div class="rectangle-4-four"></div>
          <p class="agency">Agency</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Group9",
  props: {
    egLondon: { type: String, default: "Eg. London" },
    experienceLevel: {
      type: String,
      default: "Experience level"
    },
    filter: { type: String, default: "Filter" },
    freelancer: { type: String, default: "Freelancer" },
    location: { type: String, default: "Location" },
    num12Years: { type: String, default: "1-2 years" },
    num35Years: { type: String, default: "3-5 years" },
    num68Years: { type: String, default: "6-8 years" },
    num9Years: { type: String, default: "9&#43; years" },
    target: { type: String, default: "Target" }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-9 {
  background-color: rgba(31, 31, 60, 1);
  border-radius: 25px;
  padding: 60px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.filter {
  width: 20.61%;
  height: 6.98%;
  font-family: "Merriweather";
  font-size: 22px;
  font-weight: 700;
  line-height: normal;
  color: rgba(189, 189, 211, 1);
  margin-bottom: 24px;
}
.group-1 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  &:not(:last-of-type) {
    margin-bottom: 40px;
  }
}
.location {
  width: 22.3%;
  height: 23.53%;
  font-family: "Mulish";
  font-size: 16px;
  font-weight: 700;
  line-height: normal;
  color: rgba(189, 189, 211, 1);
  margin-bottom: 8px;
}
.flex-wrapper-one {
  background-color: rgba(42, 42, 71, 1);
  border-radius: 5px;
  padding: 11px 143px 10px 13px;
  display: flex;
  align-items: center;
  border: 2px solid rgba(56, 56, 95, 1);
}
.frame {
  width: calc(23.53% - 10.67px);
  margin-right: 10px;
  padding: 4px 5.34px 3.35px 5.33px;
  align-self: stretch;
  position: relative;
}
.vector {
  width: 12.5%;
  height: 12.5%;
  border-radius: 50%;
  position: absolute;
  left: 12px;
  top: 10.67px;
  border: 2px solid rgba(105, 105, 152, 1);
}
.vector-two {
  width: 100%;
  height: 100%;
  position: relative;
}
.eg-london {
  width: 69.12%;
  height: 71.88%;
  font-family: "Mulish";
  font-size: 18px;
  font-weight: 600;
  line-height: normal;
  color: rgba(105, 105, 152, 1);
}
.experience-level {
  width: 41.22%;
  height: 16.81%;
  font-family: "Mulish";
  font-size: 16px;
  font-weight: 700;
  line-height: normal;
  color: rgba(189, 189, 211, 1);
  margin-bottom: 15px;
}
.flex-wrapper-two {
  display: flex;
  align-items: flex-start;
  &:not(:last-of-type) {
    margin-bottom: 24px;
  }
}
.group-3 {
  display: flex;
  align-items: flex-start;
  &:not(:last-of-type) {
    margin-right: 52px;
  }
}
.rectangle-4 {
  width: 21.31%;
  height: 86.67%;
  background-color: rgba(42, 42, 71, 1);
  margin-right: 11px;
  border-radius: 5px;
  border: 2px solid rgba(56, 56, 95, 1);
}
.num-1-2-years {
  width: 66.39%;
  height: 76.67%;
  font-family: "Mulish";
  font-size: 18px;
  font-weight: 600;
  line-height: normal;
  color: rgba(189, 189, 211, 1);
  margin-top: 4px;
}
.rectangle-4-two {
  width: 22.81%;
  height: 86.67%;
  background-color: rgba(42, 42, 71, 1);
  margin-right: 11px;
  border-radius: 5px;
  border: 2px solid rgba(56, 56, 95, 1);
}
.num-9-years {
  width: 64.04%;
  height: 76.67%;
  font-family: "Mulish";
  font-size: 18px;
  font-weight: 600;
  line-height: normal;
  color: rgba(189, 189, 211, 1);
  margin-top: 4px;
}
.target {
  width: 17.92%;
  height: 30.77%;
  font-family: "Mulish";
  font-size: 16px;
  font-weight: 700;
  line-height: normal;
  color: rgba(189, 189, 211, 1);
  margin-bottom: 15px;
}
.flex-wrapper-four {
  display: flex;
  align-items: flex-start;
}
.group-3-two {
  display: flex;
  align-items: flex-start;
  &:not(:last-of-type) {
    margin-right: 45px;
  }
}
.rectangle-4-three {
  width: 20.16%;
  height: 86.67%;
  background-color: rgba(42, 42, 71, 1);
  margin-right: 11px;
  border-radius: 5px;
  border: 2px solid rgba(56, 56, 95, 1);
}
.freelancer {
  width: 68.22%;
  height: 76.67%;
  font-family: "Mulish";
  font-size: 18px;
  font-weight: 600;
  line-height: normal;
  color: rgba(189, 189, 211, 1);
  margin-top: 4px;
}
.rectangle-4-four {
  width: 24.76%;
  height: 86.67%;
  background-color: rgba(42, 42, 71, 1);
  margin-right: 11px;
  border-radius: 5px;
  border: 2px solid rgba(56, 56, 95, 1);
}
.agency {
  width: 60.95%;
  height: 76.67%;
  font-family: "Mulish";
  font-size: 18px;
  font-weight: 600;
  line-height: normal;
  color: rgba(189, 189, 211, 1);
  margin-top: 4px;
}
</style>