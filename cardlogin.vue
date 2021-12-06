<template>
  <div class="group-7">
    <div class="rectangle-4"></div>
    <p class="by-joining-you-agree-to-our-terms-of-se">
      {{ byJoiningYouAgreeToOurTermsOfSe }}
    </p>
    <p class="join-the-community">{{ joinTheCommunity }}</p>
    <p class="take-your-art-to-the-next-level-get-it">
      {{ takeYourArtToTheNextLevelGetIt }}
    </p>
    <div class="group-1">
      <p class="join-with-facebook">
        {{ joinWithFacebook }}
      </p>
    </div>
    <div class="group-6">
      <p class="join-with-facebook">
        {{ createNewAccount }}
      </p>
    </div>
    <div class="group-2">
      <p class="first-name">{{ firstName }}</p>
    </div>
    <div class="group-4">
      <p class="first-name">{{ email }}</p>
    </div>
    <div class="group-5">
      <p class="first-name">{{ password }}</p>
    </div>
    <div class="group-3">
      <p class="first-name">{{ lastName }}</p>
    </div>
    <p class="or">{{ or }}</p>
  </div>
</template>

<script>
export default {
  name: "Group7",
  props: {
    byJoiningYouAgreeToOurTermsOfSe: {
      type: String,
      default:
        "By joining, you agree to our Terms of Service and Privacy Policy"
    },
    createNewAccount: {
      type: String,
      default: "Create New Account"
    },
    email: { type: String, default: "Email" },
    firstName: { type: String, default: "First name" },
    joinTheCommunity: {
      type: String,
      default: "Join the community"
    },
    joinWithFacebook: {
      type: String,
      default: "Join with Facebook"
    },
    lastName: { type: String, default: "Last name" },
    or: { type: String, default: "Or" },
    password: { type: String, default: "Password" },
    takeYourArtToTheNextLevelGetIt: {
      type: String,
      default:
        "Take your art to the next level. Get it seen by millions of people."
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.group-7 {
  background-color: $alice-blue;
  border-radius: 30px;
  padding: 30px;
}
.rectangle-4 {
  width: 100%;
  height: 100%;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 20px;
  box-shadow: 0 22px 35px 0 rgba(5, 27, 105, 0.12);
  position: relative;
}
.by-joining-you-agree-to-our-terms-of-se {
  max-width: 274px;
  width: 39.03%;
  height: 3.87%;
  color: rgba(30, 44, 75, 1);
  text-align: center;
  position: absolute;
  left: 214px;
  bottom: 102px;
  @include mulish-14-regular;
}
.join-the-community {
  max-width: 254px;
  width: 36.18%;
  height: 9.67%;
  color: $midnight-blue;
  text-align: center;
  position: absolute;
  left: 224px;
  top: 120px;
  @include mulish-36-extra-bold;
}
.take-your-art-to-the-next-level-get-it {
  max-width: 381px;
  width: 54.27%;
  height: 5.37%;
  color: $midnight-blue;
  text-align: center;
  position: absolute;
  right: 160px;
  top: 239px;
  @include mulish-20-semi-bold;
}
.group-1 {
  background-color: $steel-blue;
  border-radius: 5px;
  padding: 19px 98px 19px 99px;
  display: flex;
  align-items: center;
  position: absolute;
  right: 161px;
  top: 319px;
}
.join-with-facebook {
  color: rgba(255, 255, 255, 1);
  flex: 1;
  align-self: stretch;
  text-align: center;
  @include mulish-18-extra-bold;
}
.group-6 {
  background-color: rgba(30, 44, 75, 1);
  border-radius: 5px;
  padding: 19px 92px;
  display: flex;
  align-items: center;
  position: absolute;
  right: 161px;
  bottom: 178px;
}
.group-2 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 5px;
  padding: 17px 60px 17px 23px;
  display: flex;
  align-items: center;
  position: absolute;
  left: 177px;
  bottom: 427px;
  border: 2px solid rgba(200, 209, 229, 1);
}
.first-name {
  color: $midnight-blue;
  flex: 1;
  align-self: stretch;
  opacity: 0.5;
  @include mulish-18-semi-bold;
}
.group-4 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 5px;
  padding: 17px 290px 17px 23px;
  display: flex;
  align-items: center;
  position: absolute;
  right: 161px;
  bottom: 344px;
  border: 2px solid rgba(200, 209, 229, 1);
}
.group-5 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 5px;
  padding: 17px 253px 17px 23px;
  display: flex;
  align-items: center;
  position: absolute;
  right: 161px;
  bottom: 261px;
  border: 2px solid rgba(200, 209, 229, 1);
}
.group-3 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 5px;
  padding: 17px 61px 17px 23px;
  display: flex;
  align-items: center;
  position: absolute;
  right: 161px;
  bottom: 427px;
  border: 2px solid rgba(200, 209, 229, 1);
}
.or {
  width: 3.13%;
  height: 2.47%;
  color: rgba(0, 0, 0, 1);
  text-align: center;
  opacity: 0.5;
  position: absolute;
  left: 340px;
  top: 400px;
  @include mulish-18-extra-bold;
}
</style>