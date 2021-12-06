<template>
  <div class="group-7">
    <p class="app-services">{{ appServices }}</p>
    <p class="build-deploy-and-scale-web-apps-on-a-f">
      {{ buildDeployAndScaleWebAppsOnaf }}
    </p>
    <div class="frame-2">
      <p class="view-services">{{ viewServices }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Group7",
  props: {
    appServices: { type: String, default: "App Services" },
    buildDeployAndScaleWebAppsOnaf: {
      type: String,
      default:
        "Build, deploy, and scale web apps on a fully managed platform,"
    },
    viewServices: { type: String, default: "View services" }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-7 {
  background-color: rgba(53, 56, 84, 1);
  border-radius: 10px;
  padding: 50px 25px;
  box-shadow: 0 14px 21px -5px $transparent-black;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.app-services {
  width: 52.36%;
  height: 10.45%;
  color: $white;
  text-align: center;
  margin-bottom: 35px;
  @include ibm-plex-sans-18-bold;
}
.build-deploy-and-scale-web-apps-on-a-f {
  height: 34.55%;
  color: $white;
  align-self: stretch;
  display: flex;
  text-align: center;
  margin-bottom: 35px;
  @include ibm-plex-sans-16-medium;
}
.frame-2 {
  width: calc(71.7% - 50px);
  height: calc(23.18% - 30px);
  background-color: $sandy-brown;
  border-radius: 5px;
  padding: 15px 25px;
  display: flex;
  align-items: flex-start;
}
.view-services {
  color: rgba(42, 44, 67, 1);
  text-align: center;
  @include ibm-plex-sans-16-semi-bold;
}
</style>