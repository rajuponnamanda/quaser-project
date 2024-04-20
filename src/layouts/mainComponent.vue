<template>
  <q-page-container>
    <q-page class="q-pa-md main-content">
      <div class="row">
        <!-- Main Content Column -->
        <div class="col-12 col-md">
          <div class="content-column" style="margin-left: 10px">
            <div>
              <div
                class="text-container"
                style="
                  background-color: white;
                  height: 22px;
                  width: fit-content;
                  border-radius: 5px;
                  color: #40e2e8;
                  padding: 4px;
                  align-items: center;
                  align-content: center;
                  position: relative; /* Ensure positioning context for absolute positioning */
                "
              >
                <p
                  style="margin-bottom: 0px; font-weight: 700; font-size: 12px"
                >
                  풀타임, 파트타임
                </p>
                <div class="arrow-down">&#9660;</div>
              </div>
            </div>
            <div class="heading-content">
              <h4 class="text-white">
                최고의 실력을 가진 외국인 인재를 찾고 계신가요<strong
                  style="
                    font-weight: 1000;
                    font-family: Verdana, Geneva, Tahoma, sans-serif;
                  "
                  >?</strong
                >
              </h4>
              <div class="sub-title">
                <p class="text-white">
                  법률 및 인사관리 부담없이
                  <strong
                    style="
                      font-weight: bolder;
                      font-family: Impact, Haettenschweiler, 'Arial Narrow Bold',
                        sans-serif;
                      font-size: large;
                    "
                    >1</strong
                  >주일 이내에 원격으로 채용해보세요.
                </p>
              </div>
            </div>
            <div>
              <span class="strong text-white">
                개발자가 필요하신가요
                <strong
                  style="
                    font-weight: 800;
                    font-family: Verdana, Geneva, Tahoma, sans-serif;
                  "
                  >?</strong
                >
              </span>
            </div>
            <div class="salary-section" style="gap: 4px">
              <div>
                <h5
                  class="text-white"
                  style="
                    border-top: 1px solid white;
                    margin-right: 10px;
                    font-size: 12px;
                    font-weight: 500;
                  "
                >
                  평균 월
                  <strong
                    style="
                      font-weight: 900;
                      font-family: system-ui, -apple-system, BlinkMacSystemFont,
                        'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell,
                        'Open Sans', 'Helvetica Neue', sans-serif;
                    "
                    >120</strong
                  >만원
                </h5>
                <p
                  class="text-white"
                  style="font-size: 10px; color: white; margin-top: -14px"
                >
                  임금을 해당 국가를 기준으로 계산합니다.
                </p>
              </div>
              <div>
                <h5
                  class="text-white"
                  style="
                    border-top: 1px solid white;
                    margin-right: 10px;
                    font-size: 12px;
                    font-weight: 500;
                  "
                >
                  평균 월
                  <strong
                    style="
                      font-weight: 900;
                      font-family: system-ui, -apple-system, BlinkMacSystemFont,
                        'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell,
                        'Open Sans', 'Helvetica Neue', sans-serif;
                    "
                    >120</strong
                  >만원
                </h5>
                <p
                  class="text-white"
                  style="font-size: 10px; color: white; margin-top: -14px"
                >
                  임금을 해당 국가를 기준으로 계산합니다.
                </p>
              </div>
              <div>
                <h5
                  class="text-white"
                  style="
                    border-top: 1px solid white;
                    font-size: 12px;
                    font-weight: 500;
                  "
                >
                  평균 월
                  <strong
                    style="
                      font-weight: 900;
                      font-family: system-ui, -apple-system, BlinkMacSystemFont,
                        'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell,
                        'Open Sans', 'Helvetica Neue', sans-serif;
                    "
                    >120</strong
                  >만원
                </h5>
                <p style="font-size: 10px; color: white; margin-top: -14px">
                  임금을 해당 국가를 기준으로 계산합니다.
                </p>
              </div>
            </div>
          </div>
        </div>
        <!-- Carousel Column -->
        <div class="col-12 col-md">
          <div class="carosul">
            <carousel-column />
          </div>
        </div>
      </div>
    </q-page>

    <div
      class="swiper-cards-container"
      style="padding-bottom: 80px; margin-top: -30px"
    >
      <swiperCards />
    </div>
  </q-page-container>
</template>

<script setup>
import carouselColumn from '../layouts/carousel-column.vue';
import swiperCards from '../layouts/swiper-cards.vue';
</script>

<style scoped>
/* Set text color to white for the entire component */
.text-white {
  color: white;
  margin-top: 10px;
  /* padding-left: 8px;
  padding-right: 14px; */
}

/* Display cards in flex */

.carosul {
  display: flex;
}

/* Style for salary-section */
.salary-section {
  display: flex;
}

.text-container {
  position: relative;
  display: inline-block; /* Ensure container wraps around content */
}

.arrow-down {
  position: absolute;
  bottom: -13px; /* Adjust as needed */
  left: 11%;
  transform: translateX(-50%);
  color: white;
}
.salary-section > div {
  flex: 1;
  /* Add border-top to each div inside salary-section */
  padding-top: 20px; /* Add padding-top to create space between h5 and the border */
}

.salary-section > div:first-child {
  border-top: none; /* Remove border-top from the first div to prevent double border */
}

.main-content {
  /* margin-top: 30px; */
  /* margin-right: 40px;
  margin-left: 40px; */
  padding-bottom: 60px;
}
.heading-content {
  height: auto;
  width: 100%;
}
.sub-title {
  margin-top: -20px;
  font-size: 16px;
}
.cards-container {
  overflow-x: hidden;
  position: absolute;
}
/* Media query to hide swiper cards on mobile screens */
@media only screen and (max-width: 600px) {
  .swiper-cards-container {
    display: none;
  }
  .salary-section {
    display: none;
  }
  .strong {
    display: none;
  }
  .text-container {
    background-color: #8bc4ff !important; 
    color: white !important;/* Change background color for mobile screens */
  }
}
@media only screen and (max-width: 600px) {
  .arrow-down {
    color: #8bc4ff;
  }

}
</style>
