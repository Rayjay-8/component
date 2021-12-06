<template>
  <div class="frame-81">
    <div class="frame-82"><p class="days">Days</p></div>
    <div class="frame-83">
      <div class="dropdown">
        <div class="frame-75">
          <div class="checkbox-input">
            <div class="checkbox">
              <div class="group-6"><Check /></div>
            </div>
            <p class="monday">Monday</p>
          </div>
        </div>
        <div class="frame-76">
          <div class="checkbox-input">
            <div class="checkbox">
              <div class="group-6"><Check /></div>
            </div>
            <p class="monday">Tuesday</p>
          </div>
        </div>
        <div class="frame-75">
          <div class="checkbox-input">
            <div class="checkbox-two">
              <div class="group-6-two">
                <div class="done-black-24dp-1">
                  <img
                    alt=""
                    class="vector"
                    src="https://static.overlay-tech.com/assets/0116f3cb-c022-4a8c-8f28-9fe19e00d9f3.svg"
                  />
                </div>
              </div>
            </div>
            <p class="monday">Wednesday</p>
          </div>
        </div>
        <div class="frame-75">
          <div class="checkbox-input">
            <div class="checkbox">
              <div class="group-6"><Check /></div>
            </div>
            <p class="monday">Thursday</p>
          </div>
        </div>
        <div class="frame-75">
          <div class="checkbox-input">
            <div class="checkbox-two">
              <div class="group-6-two">
                <div class="done-black-24dp-1">
                  <img
                    alt=""
                    class="vector"
                    src="https://static.overlay-tech.com/assets/08aab01d-6e68-45fa-bb04-d41d34b92991.svg"
                  />
                </div>
              </div>
            </div>
            <p class="monday">Friday</p>
          </div>
        </div>
        <div class="frame-75">
          <div class="checkbox-input">
            <div class="checkbox">
              <div class="group-6"><Check /></div>
            </div>
            <p class="monday">Saturday</p>
          </div>
        </div>
        <div class="frame-75">
          <div class="checkbox-input">
            <div class="checkbox">
              <div class="group-6"><Check /></div>
            </div>
            <p class="monday">Sunday</p>
          </div>
        </div>
      </div>
      <div class="solid">
        <p class="label">Remove all filters</p>
      </div>
    </div>
  </div>
</template>

<script>
import { Check } from "components";

export default {
  name: "Frame81",
  components: { Check }
};
</script>

<style lang="scss" scoped>
@import "  ";
.frame-81 {
  background-color: rgba(255, 255, 255, 1);
  border-radius: 16px;
  padding: 24px;
  box-shadow: 0 7px 15px 0 rgba(24, 31, 89, 0.15);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.frame-82 {
  padding: 10px 12px;
  display: flex;
  align-items: flex-start;
  align-self: stretch;
}
.days {
  font-family: "Poppins";
  font-size: 14px;
  font-weight: 700;
  line-height: 20px;
  color: rgba(0, 0, 0, 1);
  letter-spacing: 0.14px;
}
.frame-83 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.dropdown {
  margin-bottom: 8px;
  border-radius: 8px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  width: 181px;
}
.frame-75 {
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
.monday {
  font-family: "Poppins";
  font-size: 14px;
  font-weight: 500;
  line-height: 20px;
  color: rgba(0, 0, 0, 1);
  letter-spacing: 0.14px;
}
.frame-76 {
  background-color: rgba(255, 240, 249, 1);
  border-radius: 4px;
  padding: 11px 7px;
  display: flex;
  align-items: center;
  align-self: stretch;
  border: 1px solid rgba(251, 215, 230, 1);
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
.vector {
  height: 100%;
  flex: 1;
  object-fit: cover;
}
.solid {
  background-color: rgba(0, 0, 0, 1);
  border-radius: 4px;
  padding: 6px 12px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 149px;
  border: 4px solid rgba(64, 52, 186, 0);
}
.label {
  font-family: "Poppins";
  font-size: 14px;
  font-weight: 500;
  line-height: 20px;
  color: rgba(255, 255, 255, 1);
  align-self: stretch;
  text-align: center;
  letter-spacing: 0.14px;
}
</style>