<template>
  <div class="component-1">
    <div class="group-1">
      <p class="free">{{ free }}</p>
      <div class="flex-wrapper-one">
        <p class="dollar">{{ dollar }}</p>
        <p class="">{{}}</p>
      </div>
      <p class="free-for-your-whole-team">
        {{ freeForYourWholeTeam }}
      </p>
      <p class="for-individuals-or-teams-looking-to-orga">
        {{ forIndividualsOrTeamsLookingToOrga }}
      </p>
      <div class="frame-2">
        <p class="get-started">{{ getStarted }}</p>
      </div>
    </div>
    <div class="group-1">
      <p class="standard">{{ standard }}</p>
      <div class="flex-wrapper-one">
        <p class="dollar">{{ dollarTwo }}</p>
        <p class="">{{ num6 }}</p>
      </div>
      <p class="per-user-per-month">
        {{ perUserPerMonth }}
      </p>
      <p class="for-individuals-or-teams-looking-to-orga">
        {{ forTeamsThatNeedToManageMoreWork }}
      </p>
      <div class="frame-2-two">
        <p class="get-started">{{ upgradeNow }}</p>
      </div>
    </div>
    <div class="group-1">
      <p class="premium">{{ premium }}</p>
      <div class="flex-wrapper-one">
        <p class="two">{{ dollarThree }}</p>
        <p class="num-12">{{ num12 }}</p>
      </div>
      <p class="per-user-per-month">
        {{ perUserPerMonthTwo }}
      </p>
      <p class="for-individuals-or-teams-looking-to-orga">
        {{ bestForTeamsThatNeedToTrackMultip }}
      </p>
      <div class="frame-2-three">
        <p class="get-started">{{ tryForFree }}</p>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "Component1",
  props: {
  : { type: String, default: '0' },
  bestForTeamsThatNeedToTrackMultip: { type: String, default: 'Best for teams that need to track multiple projects.' },
  dollar: { type: String, default: '$' },
  dollarThree: { type: String, default: '$' },
  dollarTwo: { type: String, default: '$' },
  forIndividualsOrTeamsLookingToOrga: { type: String, default: 'For individuals or teams looking to organize anything.' },
  forTeamsThatNeedToManageMoreWork: { type: String, default: 'For teams that need to manage more work.' },
  free: { type: String, default: 'Free' },
  freeForYourWholeTeam: { type: String, default: 'Free for your whole team' },
  getStarted: { type: String, default: 'Get started' },
  num12: { type: String, default: '12' },
  num6: { type: String, default: '6' },
  perUserPerMonth: { type: String, default: 'Per user per month' },
  perUserPerMonthTwo: { type: String, default: 'Per user per month' },
  premium: { type: String, default: 'Premium' },
  standard: { type: String, default: 'Standard' },
  tryForFree: { type: String, default: 'Try for free' },
  upgradeNow: { type: String, default: 'Upgrade Now' },
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.component-1 {
  background-color: $transparent-white;
  border-radius: 30px;
  padding: 70px;
  display: flex;
  align-items: center;
  border: 20px solid $white;
}
.group-1 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  &:not(:last-of-type) {
    margin-right: 45px;
  }
}
.free {
  width: 21.01%;
  height: 9.07%;
  color: $midnight-blue;
  margin-bottom: 21px;
  @include merriweather-26-bold;
}
.flex-wrapper-one {
  display: flex;
  align-items: flex-start;
}
.dollar {
  width: 34.38%;
  height: 58.02%;
  font-family: "IBM Plex Sans";
  font-size: 36px;
  font-weight: 700;
  line-height: normal;
  color: $midnight-blue;
  margin-top: 24px;
  margin-right: 4px;
}
. {
  width: 59.38%;
  font-family: "IBM Plex Sans";
  font-size: 62px;
  font-weight: 700;
  line-height: normal;
  color: $midnight-blue;
  align-self: stretch;
}
.free-for-your-whole-team {
  width: 66.3%;
  height: 5.77%;
  font-family: "IBM Plex Sans";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: $midnight-blue;
  margin-bottom: 40px;
}
.for-individuals-or-teams-looking-to-orga {
  height: 14.29%;
  font-family: "IBM Plex Sans";
  font-size: 20px;
  font-weight: 500;
  line-height: normal;
  color: $midnight-blue;
  align-self: stretch;
  margin-bottom: 50px;
}
.frame-2 {
  width: calc(52.17% - 40px);
  height: calc(18.13% - 40px);
  background-color: $lavender;
  border-radius: 10px;
  padding: 20px;
  display: flex;
  align-items: flex-start;
}
.get-started {
  font-family: "IBM Plex Sans";
  font-size: 20px;
  font-weight: 500;
  line-height: normal;
  color: $black;
}
.standard {
  width: 43.12%;
  height: 9.07%;
  color: $midnight-blue;
  margin-bottom: 21px;
  @include merriweather-26-bold;
}
.per-user-per-month {
  width: 51.09%;
  height: 5.77%;
  font-family: "IBM Plex Sans";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: $midnight-blue;
  margin-bottom: 40px;
}
.frame-2-two {
  width: calc(59.42% - 40px);
  height: calc(18.13% - 40px);
  background-color: $pale-turquoise;
  border-radius: 10px;
  padding: 20px;
  display: flex;
  align-items: flex-start;
}
.premium {
  width: 44.57%;
  height: 9.07%;
  color: $midnight-blue;
  margin-bottom: 21px;
  @include merriweather-26-bold;
}
.two {
  width: 21.78%;
  height: 58.02%;
  font-family: "IBM Plex Sans";
  font-size: 36px;
  font-weight: 700;
  line-height: normal;
  color: $midnight-blue;
  margin-top: 24px;
  margin-right: 4px;
}
.num-12 {
  width: 74.26%;
  font-family: "IBM Plex Sans";
  font-size: 62px;
  font-weight: 700;
  line-height: normal;
  color: $midnight-blue;
  align-self: stretch;
}
.frame-2-three {
  width: calc(51.09% - 40px);
  height: calc(18.13% - 40px);
  background-color: $peach-puff;
  border-radius: 10px;
  padding: 20px;
  display: flex;
  align-items: flex-start;
}
</style>