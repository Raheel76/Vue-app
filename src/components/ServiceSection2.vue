<template>
  <div class="section2">
    <div class="image">
      <div class="content">
        <div class="text-content">
          <div class="service">service</div>
          <div class="heading-paragraph">
            <div class="wedding">Wedding & Event Decor</div>
            <div class="text1">
              Let our team of expert florists and designers create stunning,
              on-trend floral décor for your special day. Trust us to bring your
              vision to life.
            </div>
          </div>
          <div><button class="btn">Inquire Now</button></div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "ServiceSection2",
};
</script>
<style scoped>
.btn {
  display: flex;
  width: 175px;
  height: 56px;
  padding: 16px 24px 14px 24px;
  justify-content: center;
  align-items: center;
  gap: 8px;
  color: white;
  cursor: pointer;
  background-color: transparent;
}
.btn:hover {
  background-color: gray;
}
.text1 {
  width: 586px;
  height: 50px;
  color: var(--White, #fff);
  text-align: center;
  font-size: 18px;
  font-style: normal;
  font-weight: 500;
  line-height: 140%;
}
.wedding {
  width: 549px;
  height: 60px;
  color: var(--White, #fff);
  font-size: 50px;
  font-style: normal;
  font-weight: 600;
  line-height: 120%;
}
.heading-paragraph {
  width: 586px;
  height: 126px;
  gap: 16px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 16px;
}
.text-content {
  width: 586px;
  height: 167px;
  gap: 24px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 24px;
}
.service {
  width: 54px;
  height: 17px;
  color: var(--White, #fff);
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  line-height: 120%;
  text-transform: uppercase;
}

.section2 {
  display: flex;
  background-repeat: no-repeat;
  width: 100%;
  height: 720px;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.image {
  width: 100%;
  height: 720px;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  background-image: url(./images/back.png);
  background-size: cover;
}
.content {
  display: flex;
  padding: 80px;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 64px;
  flex: 1 0 0;
  align-self: stretch;
}
</style>
