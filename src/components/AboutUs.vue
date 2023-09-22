<template>
  <div class="about-us">
    <div class="about-title">
      <span>About Us</span>
    </div>
    <div class="aboutright-colum">
      <div class="text-content">
        <div class="text-title">our story</div>
        <div class="heading-paragraph">
          <div class="heading">Kyiv LuxeBouquets</div>
          <div class="content">
            <p>
              We are a modern local floral studio, which specializes in the
              design and delivery of unique bouquets. We have the best florists
              who carefully select each look, our studio cooperates directly
              with farms for growing different flowers, so we always have fresh
              flowers, which are collected by our florists in exquisite
              bouquets. We have a collection of fresh bouquets, collections of
              dried bouquets, house plants, as well as fragrant candles from
              luxury brands to create the perfect atmosphere. Make someone's day
              amazing by sending flowers, plants and gifts the same or next day.
              Ordering flowers online has never been easier.
            </p>
          </div>
        </div>
      </div>
      <div class="button">Leran More</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutUs",
};
</script>
<style scoped>
.about-us {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: flex-start;
}
.about-title {
  display: flex;
  width: 100%;
  height: 100%;
  padding: 40px;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  gap: 64px;
  border-top: 1px solid var(--Black, #121212);
}
span {
  width: 576px;
  color: var(--Black, #121212);
  font-size: 50px;
  font-style: normal;
  font-weight: 600;
  line-height: 120%;
}
.aboutright-colum {
  display: flex;
  width: 100%;
  height: 100%;
  padding: 32px;
  flex-direction: column;
  align-items: flex-start;
  gap: 64px;
  /* border-top: 1px solid var(--Black, #121212); */
  border-left: 1px solid var(--Black, #121212);
}
.text-content {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  width: 543.5px;
  height: 301px;
  gap: 24px;
  color: #121212;
}
.text-title {
  width: 76px;
  height: 17px;
  color: var(--Black, #121212);
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  line-height: 120%;
  text-transform: uppercase;
}
.heading-paragraph {
  width: 543.5px;
  height: 260px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
  color: #121212;
}
.heading {
  width: 543.5px;
  color: var(--Black, #121212);
  height: 46px;
  font-size: 38px;
  font-style: normal;
  font-weight: 500;
  line-height: 120%;
}
.content {
  width: 543.5px;
  height: 198px;
  color: var(--black-brightness-90, rgba(18, 18, 18, 0.9));
  font-family: Gilroy;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 140%;
}
.button {
  display: flex;
  width: 175px;
  height: 56px;
  padding: 16px 24px 14px 24px;
  justify-content: center;
  align-items: center;
  gap: 8px;
  border: 1px solid var(--Black, #121212);
}
</style>
