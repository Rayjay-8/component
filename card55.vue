<template>
  <div class="group-10">
    <p class="popular">{{ popular }}</p>
    <p class="explore-some-of-the-most-popular-product">
      {{ exploreSomeOfTheMostPopularProduct }}
    </p>
    <div class="flex-wrapper-one">
      <div class="group-8">
        <p class="virtual-machines">
          {{ virtualMachines }}
        </p>
        <p class="provision-windows-and-linux-in-seconds">
          {{ provisionWindowsAndLinuxInSeconds }}
        </p>
      </div>
      <div class="group-9">
        <p class="virtual-desktop">{{ virtualDesktop }}</p>
        <p class="provision-windows-and-linux-in-seconds">
          {{ enableaSecureRemoteDesktopExperien }}
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Group10",
  props: {
    enableaSecureRemoteDesktopExperien: {
      type: String,
      default:
        "Enable a secure, remote desktop experience from anywhere."
    },
    exploreSomeOfTheMostPopularProduct: {
      type: String,
      default: "Explore some of the most popular products"
    },
    popular: { type: String, default: "Popular" },
    provisionWindowsAndLinuxInSeconds: {
      type: String,
      default: "Provision Windows and Linux in seconds."
    },
    virtualDesktop: {
      type: String,
      default: "Virtual Desktop"
    },
    virtualMachines: {
      type: String,
      default: "Virtual Machines"
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-10 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.popular {
  width: 12.82%;
  height: 12.83%;
  color: $white;
  margin-bottom: 5px;
  margin-left: 2px;
  @include ibm-plex-sans-26-semi-bold;
}
.explore-some-of-the-most-popular-product {
  width: 53.31%;
  height: 9.81%;
  color: $white;
  margin-bottom: 40px;
  margin-left: 2px;
  @include ibm-plex-sans-20-medium;
}
.flex-wrapper-one {
  display: flex;
  align-items: flex-start;
}
.group-8 {
  background-color: $dark-slate-gray;
  margin-right: 25px;
  border-radius: 10px;
  padding: 40px;
  box-shadow: 0 14px 21px -5px $transparent-black;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.virtual-machines {
  width: 51.08%;
  height: 28.75%;
  color: $white;
  text-decoration: underline;
  margin-bottom: 15px;
  @include ibm-plex-sans-18-bold;
}
.provision-windows-and-linux-in-seconds {
  height: 52.5%;
  color: $white;
  align-self: stretch;
  @include ibm-plex-sans-16-medium;
}
.group-9 {
  background-color: $dark-slate-gray-2;
  border-radius: 10px;
  padding: 40px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.virtual-desktop {
  width: 47.48%;
  height: 28.75%;
  color: $white;
  margin-bottom: 15px;
  @include ibm-plex-sans-18-bold;
}
</style>