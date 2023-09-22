<template>
  <div class="Service-Section">
    <div class="image"></div>
    <div class="left-column">
      <div class="content">
        <div class="text-content">
          <div class="service">Service</div>
          <div class="heading-paragraph">
            <div class="heading">Flower Subcriptions</div>
            <div class="paragraph">
              Experience the convenience and savings of regular flower
              deliveries with our flexible subscription service<br />
              - up to 30% more profitable than one-time purchases.
            </div>
          </div>
        </div>
      </div>
      <div>
        <button class="btn">Subscribe Now</button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "ServiceSection1",
};
</script>
<style scoped>
.btn {
  background-color: white;
  border: none;
  cursor: pointer;
  display: flex;
  height: 56px;
  padding: 16px 24px 14px 24px;
  justify-content: center;
  align-items: center;
  gap: 8px;

  border: 1px solid var(--Black, #121212);
}
.btn:hover {
  background-color: gray;
}
.Service-Section {
  width: 100%;
  height: 720px;
  display: flex;
  align-items: flex-start;
}
.image {
  display: flex;
  width: 720px;
  height: 720px;
  justify-content: center;
  align-items: flex-end;
  background-image: url(./images/image-girl.png);
  border-bottom: 1px solid var(--Black, #121212);
  border-left: 1px solid var(--Black, #121212);
}
.left-column {
  display: flex;
  width: 720px;
  padding: 80px;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  align-self: stretch;
  border-bottom: 1px solid var(--Black, #121212);
  border-left: 1px solid var(--Black, #121212);
}
.content {
  width: 560px;
  height: 312px;
  gap: 64px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 64px;
  align-self: stretch;
}
.text-content {
  width: 560px;
  height: 192px;
  gap: 24px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 24px;
  align-self: stretch;
}
.service {
  width: 54px;
  height: 17px;
  color: var(--Black, #121212);
  text-align: center;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  line-height: 120%;
  text-transform: uppercase;
}
.heading-paragraph {
  width: 560px;
  height: 151px;
  gap: 16px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
  align-self: stretch;
}

.heading {
  width: 560px;
  height: 60px;
  align-self: stretch;
  color: var(--Black, #121212);
  text-align: center;
  font-size: 50px;
  font-style: normal;
  font-weight: 600;
  line-height: 120%;
}
.paragraph {
  color: var(--black-brightness-90, rgba(18, 18, 18, 0.9));
  text-align: center;

  font-size: 18px;
  font-style: normal;
  font-weight: 500;
  line-height: 140%;
}
</style>
