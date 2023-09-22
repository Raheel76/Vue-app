<template>
  <div class="hero">
    <div class="left-colum">
      <div class="layout-left">
        <div class="row1">
          <div class="heading">
            <h1 class="text1">
              Most <br />
              Beautiful Flowers
            </h1>
            <div class="para1">
              <p>
                Deadheading is the term used for the removal of fading or dead
                flowers from plants.n a more practical context, "flower shorts"
                might also refer to shorts that people wear when working in
                their gardens.
              </p>
            </div>
          </div>
        </div>
        <div class="row2">
          <div class="layout2">
            <div class="decoder-colum1">
              <img class="img1" src="./images/image2.png" alt="Your Image" />
            </div>
            <div class="decoder-colum2">
              <p class="para2">
                A flower, sometimes known as a bloom or blossom, is the
                reproductive structure found in flowering plants. Flowers
                produce gametophytes, which in flowering plants consist of a few
                haploid cells which produce
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="right-colum">
      <div class="content-Category1">
        <!-- first item -->
        <div class="card-category">
          <label class="label1"><span class="card1">Fresh Flowers</span></label>
          <div class="text-icon">
            <span class="shop-button">Shop Now </span
            ><svg
              class="icon"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
            >
              <path
                d="M15.1397 6L13.6815 7.50351L17 11H3V13H17L13.702 16.5035L15.167 18L21 11.986L15.1397 6Z"
                fill="black"
              />
            </svg>
          </div>
        </div>
        <!-- second item -->
        <div class="card-item">
          <img src="./images/card item.png" alt="" srcset="" />
        </div>
        <!-- third item -->
        <div class="card-category">
          <label class="label1"><span class="card1">Live Plants</span></label>
          <div class="text-icon">
            <span class="shop-button">Shop Now </span
            ><svg
              class="icon"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
            >
              <path
                d="M15.1397 6L13.6815 7.50351L17 11H3V13H17L13.702 16.5035L15.167 18L21 11.986L15.1397 6Z"
                fill="black"
              />
            </svg>
          </div>
        </div>
        <!-- 4th item -->
        <div class="card-item">
          <img src="./images/card item 3.png" alt="" srcset="" />
        </div>
        <!-- 5th item -->
        <div class="card-category">
          <label class="label1"><span class="card">Freshners</span></label>
          <div class="text-icon">
            <span class="shop-button">Shop Now </span
            ><svg
              class="icon"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
            >
              <path
                d="M15.1397 6L13.6815 7.50351L17 11H3V13H17L13.702 16.5035L15.167 18L21 11.986L15.1397 6Z"
                fill="black"
              />
            </svg>
          </div>
        </div>
      </div>
      <div class="content-category2">
        <div class="card-item">
          <img src="./images/card item.png" alt="" srcset="" />
        </div>
        <div class="card-category">
          <label class="label1"><span class="card1">Dried Flowers</span></label>
          <div class="text-icon">
            <span class="shop-button">Shop Now </span
            ><svg
              class="icon"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
            >
              <path
                d="M15.1397 6L13.6815 7.50351L17 11H3V13H17L13.702 16.5035L15.167 18L21 11.986L15.1397 6Z"
                fill="black"
              />
            </svg>
          </div>
        </div>
        <div class="card-item">
          <img src="./images/card item.png" alt="" srcset="" />
        </div>
        <div class="card-category">
          <label class="label1"><span class="card1">Aroma Candles</span></label>
          <div class="text-icon">
            <span class="shop-button">Shop Now </span
            ><svg
              class="icon"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
            >
              <path
                d="M15.1397 6L13.6815 7.50351L17 11H3V13H17L13.702 16.5035L15.167 18L21 11.986L15.1397 6Z"
                fill="black"
              />
            </svg>
          </div>
        </div>
        <div class="card-item">
          <img src="./images/card item.png" alt="" srcset="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeroSection",
};
</script>

<style scoped>
.hero {
  border-top: none;
  display: flex;
  align-items: flex-start;
  box-sizing: border-box;
  width: 100%;
  /* height: 100%; */
  /* overflow: hidden; */
}
/* right colum */
.right-colum {
  width: 100%;
  /* height: 100%; */
  display: flex;
  overflow: hidden;
  align-items: flex-start;
}
.content-category1 {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.content-category2 {
  width: 360px;
  height: 1800px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.label1 {
  width: 312px;
  height: 46px;
  display: flex;
  justify-content: center;
  align-items: center;
  align-self: stretch;
}
.card-category {
  display: flex;
  width: 100%;
  height: 359px;
  /* padding: 24px; */
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border-bottom: 1px solid var(--Black, #121212);
  border-left: 1px solid var(--Black, #121212);
}
.card1 {
  width: 100%;
  height: 46px;
  flex: 1 0 0;
  color: var(--Black, #121212);
  text-align: center;
  font-size: 38px;
  font-style: normal;
  font-weight: 500;
  line-height: 120%;
}

.text-icon {
  width: 104px;
  height: 24px;
  gap: 4px;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 4px;
  left: 128px;
  bottom: 24px;
}
.shop-button {
  width: 76px;
  height: 19px;
  color: var(--Black, #121212);
  font-family: Gilroy;
  font-size: 16px;
  font-style: normal;
  font-weight: 600;
  line-height: 120%;
  letter-spacing: 0.4px;
  cursor: pointer;
}
.icon {
  width: 24px;
  height: 24px;
}
/* card-item */
.card-item {
  display: flex;
  width: 100%;
  height: 360px;
  /* padding: 24px; */
  flex-direction: column;
  justify-content: flex-end;
  align-items: center;
  /* border-bottom: 1px solid var(--Black, #121212); */
  /* border-left: 1px solid var(--Black, #121212); */
}
/* left colum */
.left-colum {
  width: 100%;
  height: 50%;
  padding: 5px;
  border-bottom: 1px solid var(--Black, #121212);
}
.row1 {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
  flex: 1 0 0;
  align-self: stretch;
  /* width: 560px; */
  /* height: 280px; */
  gap: 16px;
}
.heading {
  width: 560px;
  height: 160px;
}
.text1 {
  width: 560px;
  height: 160px;
  color: #121212;
  color: var(--Black, #121212);
  font-size: 67px;
  font-style: normal;
  font-weight: 600;
  line-height: 100%;
}
.layout-left {
  display: flex;
  width: 50%;
  height: 720px;
  padding: 1px;
  flex-direction: column;
  align-items: flex-start;
  background: var(--White, #fff);
}
.right-colum {
  width: 100%;
  /* height: 100%; */
  /* border-top: 1px solid var(--Black, #121212); */
}
.para1 {
  width: 100%;
  height: 50px;
  align-self: stretch;
  color: var(--black-brightness-90, rgba(18, 18, 18, 0.9));
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 140%;
  font-style: italic;
}

.layout2 {
  display: flex;
  padding-top: 24px;
  justify-content: flex-end;
  align-items: flex-end;
  flex: 1 0 0;
  align-self: stretch;
  border-top: 1px solid var(--Black, #121212);
}
.row2 {
  width: 560px;
  height: 280px;
  padding: 24px, 0px, 0px, 0px;
  border: 1px, 0px, 0px, 0px;
}
.decoder-colum1 {
  display: flex;
  padding-right: 0px;
  align-items: flex-start;
  flex: 1 0 0;
  align-self: stretch;
  width: 280px;
  height: 256px;
  padding: 0px, 0px, 0px, 24px;
  border-right: 1px solid var(--Black, #121212);
}
.decoder-colum2 {
  display: flex;
  padding-left: 0px;
  align-items: flex-end;
  flex: 1 0 0;
  align-self: stretch;
  width: 256px;
  height: 256px;
}
.img {
  width: 256px;
  height: 256px;
  background: #ffffff26;
}

.para2 {
  display: flex;
  align-items: flex-end;
  flex: 1 0 0;
  align-self: stretch;
  width: 280px;
  height: 236px;
  padding-left: 24px;
  font-style: italic;
}
</style>
