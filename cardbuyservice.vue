<template>
  <div class="frame-10">
    <div class="group-3">
      <p class="select-gift-frequency">
        {{ selectGiftFrequency }}
      </p>
      <div class="frame-4">
        <div class="frame-2">
          <p class="monthly">{{ monthly }}</p>
        </div>
        <div class="frame-3">
          <p class="one-time">{{ oneTime }}</p>
        </div>
      </div>
    </div>
    <div class="group-3">
      <p class="select-amount">{{ selectAmount }}</p>
      <div class="frame-6">
        <div class="frame-2-two">
          <p class="num-12">{{ num12 }}</p>
        </div>
        <div class="frame-5">
          <p class="num-30">{{ num30 }}</p>
        </div>
        <div class="frame-5">
          <p class="num-30">{{ num40 }}</p>
        </div>
        <div class="frame-5">
          <p class="num-30">{{ num50 }}</p>
        </div>
        <div class="frame-5">
          <p class="num-30">{{ num60 }}</p>
        </div>
      </div>
    </div>
    <div class="group-2">
      <div class="rectangle-1"></div>
      <p class="yes-ill-generously-add-0-30-each-mont">
        {{ yesIllGenerouslyAdd030EachMont }}
      </p>
    </div>
    <div class="group-3">
      <div class="group-5">
        <p class="name">{{ name }}</p>
        <div class="group-4">
          <p class="enter-your-name">{{ enterYourName }}</p>
        </div>
      </div>
      <div class="group-5">
        <div class="group-6">
          <p class="email">{{ email }}</p>
          <div class="group-4-two">
            <p class="enter-your-email">
              {{ enterYourEmail }}
            </p>
          </div>
        </div>
        <p class="give-in-honor-to-another-person">
          {{ giveInHonorToAnotherPerson }}
        </p>
      </div>
    </div>
    <div class="frame-2-three">
      <p class="donate-now">{{ donateNow }}</p>
    </div>
    <p
      class="by-donating-you-agree-to-our-terms-of-s"
      v-html="byDonatingYouAgreeToOurTermsOfs"
    ></p>
  </div>
</template>

<script>
export default {
  name: "Frame10",
  props: {
    byDonatingYouAgreeToOurTermsOfs: {
      type: String,
      default:
        'By donating, you agree to our <strong class="by-donating-you-agree-to-our-terms-of-s-emphasis-1">terms of  service </strong>and <strong class="by-donating-you-agree-to-our-terms-of-s-emphasis-1">privacy policy</strong>.'
    },
    donateNow: { type: String, default: "Donate now" },
    email: { type: String, default: "Email" },
    enterYourEmail: {
      type: String,
      default: "Enter your email"
    },
    enterYourName: {
      type: String,
      default: "Enter your name"
    },
    giveInHonorToAnotherPerson: {
      type: String,
      default: "Give in honor to another person"
    },
    monthly: { type: String, default: "Monthly" },
    name: { type: String, default: "Name" },
    num12: { type: String, default: "$12" },
    num30: { type: String, default: "$30" },
    num40: { type: String, default: "$40" },
    num50: { type: String, default: "$50" },
    num60: { type: String, default: "$60" },
    oneTime: { type: String, default: "One time" },
    selectAmount: {
      type: String,
      default: "Select amount"
    },
    selectGiftFrequency: {
      type: String,
      default: "Select gift frequency"
    },
    yesIllGenerouslyAdd030EachMont: {
      type: String,
      default:
        "Yes, I’ll generously add $0.30 each month to cover the transaction fees"
    }
  }
};
</script>

<style lang="scss" scoped>
@import "  ";
.frame-10 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 24px;
  padding: 48px 32px;
  box-shadow: -15px -15px 0 0 rgba(201, 206, 249, 1);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.group-3 {
  margin-bottom: 32px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.select-gift-frequency {
  max-width: 166px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
  margin-bottom: 12px;
}
.frame-4 {
  background-color: rgba(236, 238, 255, 1);
  border-radius: 8px;
  padding: 5px;
  display: flex;
  align-items: flex-start;
  border: 1px solid rgba(201, 206, 249, 1);
}
.frame-2 {
  background-color: rgba(255, 255, 255, 1);
  margin-right: 8px;
  border-radius: 4px;
  padding: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex: 1;
}
.monthly {
  max-width: 65px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
}
.frame-3 {
  border-radius: 4px;
  padding: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex: 1;
}
.one-time {
  max-width: 74px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
}
.select-amount {
  max-width: 118px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
  margin-bottom: 8px;
}
.frame-6 {
  display: flex;
  align-items: flex-start;
}
.frame-2-two {
  background-color: rgba(17, 20, 52, 1);
  margin-right: 8px;
  border-radius: 4px;
  padding: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 40px;
}
.num-12 {
  max-width: 24px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(255, 255, 255, 1);
  text-align: center;
}
.frame-5 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 4px;
  padding: 9px;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  border: 1px solid rgba(201, 206, 249, 1);
  &:not(:last-of-type) {
    margin-right: 8px;
  }
}
.num-30 {
  max-width: 30px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
  text-align: center;
}
.group-2 {
  margin-bottom: 32px;
  display: flex;
  align-items: flex-start;
}
.rectangle-1 {
  width: 23px;
  height: 23px;
  background-color: rgba(255, 255, 255, 1);
  margin-right: 8px;
  border-radius: 4px;
  border: 1px solid rgba(201, 206, 249, 1);
}
.yes-ill-generously-add-0-30-each-mont {
  max-width: 299px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
  margin-top: 1px;
}
.group-5 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  &:not(:last-of-type) {
    margin-bottom: 16px;
  }
}
.name {
  max-width: 49px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
  margin-bottom: 4px;
}
.group-4 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 4px;
  padding: 13px 180px 13px 17px;
  display: flex;
  align-items: center;
  border: 1px solid rgba(201, 206, 249, 1);
}
.enter-your-name {
  max-width: 133px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
  opacity: 0.5;
}
.group-6 {
  margin-bottom: 12px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.email {
  max-width: 44px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
  margin-bottom: 4px;
}
.group-4-two {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 4px;
  padding: 13px 182px 13px 17px;
  display: flex;
  align-items: center;
  border: 1px solid rgba(201, 206, 249, 1);
}
.enter-your-email {
  max-width: 131px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
  opacity: 0.5;
}
.give-in-honor-to-another-person {
  max-width: 223px;
  font-family: "Poppins";
  font-size: 14px;
  font-weight: 500;
  line-height: normal;
  color: rgba(16, 52, 241, 1);
}
.frame-2-three {
  background-color: rgba(17, 20, 52, 1);
  margin-bottom: 32px;
  border-radius: 4px;
  padding: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 312px;
}
.donate-now {
  max-width: 98px;
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 500;
  line-height: normal;
  color: rgba(255, 255, 255, 1);
  text-align: center;
}
.by-donating-you-agree-to-our-terms-of-s {
  width: 287px;
  font-family: "Poppins";
  font-size: 14px;
  font-weight: 500;
  line-height: normal;
  color: rgba(17, 20, 52, 1);
  &
    /deep/
    .by-donating-you-agree-to-our-terms-of-s-emphasis-1 {
    font-family: "Poppins";
    font-size: 14px;
    font-weight: 500;
    line-height: normal;
    color: rgba(16, 52, 241, 1);
  }
}
</style>