<template>
  <div class="Section-Benefits">
    <div class="div-title">
      <div class="title">Why choose us ?</div>
    </div>
    <div class="right-colum">
      <div class="benefit-block1">
        <div class="header1">Stylish bouquets by florists</div>
        <div class="text1">
          <p>
            At our floral studio, our professional florists craft the most
            elegant and stylish bouquets using only the freshest and highest
            quality materials available. We stay up-to-date with the latest
            floral design trends and offer unique arrangements that are sure to
            impress. Let us brighten up your day with our stunning bouquets and
            same-day delivery service.
          </p>
        </div>
      </div>
      <div class="benefit-block2">
        <div class="header1">On-time delivery</div>
        <div class="text1">
          <p>
            Never miss a moment with our on-time flower delivery service. Our
            couriers will deliver your bouquet personally, without boxes, to
            ensure it arrives in perfect condition. Trust us to deliver your
            thoughtful gift reliably.
          </p>
        </div>
      </div>
      <div class="benefit-block3">
        <div class="header1">Safe payment</div>
        <div class="text1">
          <p>
            You can feel secure when placing an order with us, as we use
            industry-standard security measures to protect your payment
            information. Your transaction will be safe and hassle-free, so you
            can shop with confidence.
          </p>
        </div>
      </div>
      <div class="benefit-block4">
        <div class="header1">Subscription by your needs</div>
        <div class="text1">
          <p>
            With our subscription service tailored to your specific needs, you
            can enjoy the convenience of having beautiful bouquets delivered
            straight to your door at regular intervals. Our flexible service is
            perfect for busy individuals or those who want to ensure they always
            have fresh flowers on hand. You'll save time and money with this
            hassle-free solution to your floral needs.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "SectionBenefit",
};
</script>
<style scoped>
.Section-Benefits {
  width: 100%;
  /* height: 1440px; */
  display: flex;
  align-items: flex-start;
}
.div-title {
  width: 520px;
  height: 220px;
  padding: 80px;
  /* border: 1px, 0px, 0px, 0px; */
  gap: 16px;
  border-top: 1px solid #121212;
}
.title {
  width: 386px;
  height: 60px;
  color: var(--Black, #121212);
  font-size: 50px;
  font-style: normal;
  font-weight: 600;
  line-height: 120%;
}
.right-colum {
  width: 50%;
  height: 1440px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  border-top: 1px solid #121212;
}
.benefit-block1 {
  display: flex;
  width: 50%;
  padding: 80px;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
  border: 0px, 0px, 1px, 1px;
  border-bottom: 1px solid var(--Black, #121212);
  border-left: 1px solid var(--Black, #121212);
}
.benefit-block2 {
  display: flex;
  width: 50%;
  height: 288px;
  padding: 80px;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
  border-bottom: 1px solid var(--Black, #121212);
  border-left: 1px solid var(--Black, #121212);
}
.benefit-block3 {
  display: flex;
  width: 50%;
  padding: 80px;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
  border: 0px, 0px, 1px, 1px;
  border-bottom: 1px solid var(--Black, #121212);
  border-left: 1px solid var(--Black, #121212);
}
.benefit-block4 {
  padding: 80px;
  border: 0px, 0px, 1px, 1px;
  gap: 16px;
  display: flex;
  width: 50%;
  height: 332px;
  flex-direction: column;
  align-items: flex-start;
  border-bottom: 1px solid var(--Black, #121212);
  border-left: 1px solid var(--Black, #121212);
}
.header1 {
  width: 560px;
  height: 46px;
  align-self: stretch;
  color: var(--Black, #121212);
  font-size: 38px;
  font-style: normal;
  font-weight: 500;
  line-height: 120%;
}
.text1 {
  align-self: stretch;
  color: var(--black-brightness-90, rgba(18, 18, 18, 0.9));
  font-family: Gilroy;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 140%;
  width: 560px;
  height: 110px;
}
</style>
