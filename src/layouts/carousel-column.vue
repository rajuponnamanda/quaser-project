<template>
  <div class="container">
    <div class="text-container">
      <div
        style="
          background-color: white;
          display: flex;
          border-radius: 6px;
          align-items: center;
          justify-content: center;
          margin-right: 110px;
        "
         class="offer"
      >
        <div
          style="
            display: flex;
            align-items: center;
            padding-left: 6px;
            padding-right: 4px;
            padding-top: 2px;
            padding-bottom: 2px;
          "
         
        >
          <svg
            width="18"
            height="18"
            viewBox="0 0 27 27"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <circle cx="13.7607" cy="13.5" r="13" fill="#BBF3D2" />
            <path
              d="M17.9441 9.60332C17.3592 9.60332 16.9024 9.13165 16.5905 8.63687C16.5455 8.56539 16.496 8.49643 16.442 8.42998C16.1812 8.10063 15.8279 7.85361 15.3819 7.68893C14.9358 7.52426 14.4281 7.44192 13.8586 7.44192C13.2616 7.44192 12.7367 7.53455 12.2838 7.71981C11.831 7.90507 11.481 8.16581 11.234 8.50203C10.987 8.83139 10.8635 9.20877 10.8635 9.63419C10.8635 10.2655 11.1208 10.7526 11.6354 11.0957C12.1569 11.4319 12.8053 11.6927 13.5807 11.8779L15.0113 12.2587C16.2533 12.5675 17.2791 13.041 18.0887 13.6791C18.9053 14.3172 19.3135 15.247 19.3135 16.4683C19.3135 17.3123 19.094 18.0671 18.6548 18.7326C18.2225 19.3914 17.5878 19.906 16.7507 20.2765C15.9205 20.647 14.9324 20.8323 13.7865 20.8323C12.675 20.8323 11.7109 20.6539 10.8944 20.2971C10.0847 19.9403 9.44658 19.436 8.98 18.7841C8.7372 18.4398 8.55086 18.0611 8.42099 17.648C8.22397 17.0212 8.76291 16.458 9.41988 16.458C10.0143 16.458 10.4742 16.9427 10.7681 17.4593C10.8313 17.5704 10.9042 17.6757 10.987 17.7755C11.2889 18.1323 11.68 18.3999 12.1603 18.5783C12.6475 18.7567 13.1861 18.8424 13.7762 18.8356C14.4075 18.8356 14.9736 18.7361 15.4745 18.5371C15.9754 18.3381 16.3665 18.0568 16.6478 17.6931C16.9291 17.3295 17.0698 16.9075 17.0698 16.4272C17.0698 16.0155 16.9532 15.6655 16.7199 15.3773C16.4866 15.0891 16.1675 14.8559 15.7627 14.6775C15.3578 14.4991 14.8569 14.3309 14.26 14.1731L12.4897 13.71C11.2409 13.3669 10.2803 12.8763 9.60783 12.2382C8.94226 11.5932 8.6129 10.7664 8.61976 9.7577C8.61976 8.91373 8.8462 8.16581 9.29906 7.51396C9.75879 6.86211 10.3901 6.36122 11.1929 6.01128C12.0025 5.65448 12.9083 5.47607 13.91 5.47607C14.905 5.47607 15.7935 5.65448 16.5758 6.01128C17.3648 6.36122 17.979 6.85182 18.4181 7.48309C18.6365 7.78891 18.8031 8.11449 18.9179 8.45983C19.1195 9.06655 18.5834 9.60332 17.9441 9.60332Z"
              fill="#00C696"
            />
            <path
              d="M13.9512 4.5L13.9512 6.3291"
              stroke="#00C696"
              stroke-width="2"
              stroke-linecap="round"
            />
            <path
              d="M13.9512 19.918L13.9512 21.7471"
              stroke="#00C696"
              stroke-width="2"
              stroke-linecap="round"
            />
          </svg>
          <span
            style="
              font-weight: 900;
              font-family: system-ui, -apple-system, BlinkMacSystemFont,
                'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans',
                'Helvetica Neue', sans-serif;
              height: fit-content;
              width: fit-content;
              color: #40e2e8;
              font-weight: 500;
              font-size: 12px;
              padding-bottom: 2px;
              padding-left: 4px;
              padding-right: 4px;
              padding-top: 2px;
              position: relative;
            "
          >
            월
            <strong
              style="
                color: #40e2e8;
                font-weight: 900;
                font-family: system-ui, -apple-system, BlinkMacSystemFont,
                  'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans',
                  'Helvetica Neue', sans-serif;
              "
              >100</strong
            >만원</span
          >
        </div>
      </div>
      <div class="arrow-down">&#9660;</div>
    </div>
    <div class="card-slider">
      <div class="arrow arrow-left" @click="prevCard">
        <svg
          width="20"
          height="20"
          viewBox="0 0 32 32"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <g clip-path="url(#clip0_2_8352)">
            <path
              d="M20.0943 26.6665C20.3583 26.6607 20.6105 26.5561 20.801 26.3732C20.9882 26.1857 21.0934 25.9315 21.0934 25.6665C21.0934 25.4015 20.9882 25.1473 20.801 24.9598L12.001 16.1598L20.8143 7.01316C21.0016 6.82566 21.1068 6.57149 21.1068 6.30649C21.1068 6.04149 21.0016 5.78733 20.8143 5.59983C20.6268 5.41256 20.3726 5.30737 20.1076 5.30737C19.8426 5.30737 19.5885 5.41256 19.401 5.59983L9.90763 15.4665C9.81531 15.5582 9.74205 15.6673 9.69205 15.7874C9.64205 15.9075 9.61631 16.0364 9.61631 16.1665C9.61631 16.2966 9.64205 16.4255 9.69205 16.5456C9.74205 16.6657 9.81531 16.7748 9.90763 16.8665L19.3876 26.3865C19.5787 26.5668 19.8316 26.667 20.0943 26.6665Z"
              fill="white"
            />
          </g>
          <defs>
            <clipPath id="clip0_2_8352">
              <rect
                width="32"
                height="32"
                fill="white"
                transform="matrix(-1 0 0 1 32 0)"
              />
            </clipPath>
          </defs>
        </svg>
      </div>
      <div class="swiper-container">
        <div class="swiper-wrapper">
          <div
            v-for="(card, index) in cards"
            :key="index"
            class="swiper-slide"
            :class="{ active: index === currentIndex }"
            @click="currentIndex = index"
          >
            <!-- Card Content -->
            <div class="card">
              <div>
                <div class="card-image">
                  <img :src="card.image" alt="Card Image" />
                </div>
                <img class="flag-image" :src="card.flag" alt="Flag Image" />
              </div>
              <div class="card-content">
                <div class="title text-color-2f" style="font-size: 20px">
                  Abhishek Gupta
                </div>

                <div class="text-color-ff" style="font-size: 16px">
                  마케팅 <strong class="sub-title">· 2y+</strong>
                </div>
                <div
                  class="text-color-f column"
                  style="gap: 4px; font-size: 16px"
                >
                  <div class="column items-center" style="gap: 4px">
                    <div
                      class="q-py-xs q-px-sm"
                      style="
                        border: solid;
                        width: fit-content;
                        border-radius: 6px;
                        border-color: #c1c5cf;
                      "
                    >
                      마케팅 콘텐츠 제작
                    </div>
                    <div
                      class="q-py-xs q-px-sm"
                      style="
                        border: solid;
                        width: fit-content;
                        border-radius: 6px;
                        border-color: #c1c5cf;
                      "
                    >
                      인스타그램 관리
                    </div>
                  </div>
                  <div class="row justify-center flex" style="gap: 4px">
                    <div
                      class="q-py-xs q-px-sm"
                      style="
                        border: solid;
                        width: fit-content;
                        border-radius: 6px;
                        border-color: #c1c5cf;
                        font-size: xx-small;
                      "
                    >
                      트위터 관리
                    </div>
                    <div
                      class="q-py-xs q-px-sm"
                      style="
                        border: solid;
                        width: fit-content;
                        border-radius: 6px;
                        border-color: #c1c5cf;
                        font-size: xx-small;
                      "
                    >
                      블로그 글 작성
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="arrow arrow-right" @click="nextCard">
        <svg
          width="20"
          height="20"
          viewBox="0 0 32 32"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <g clip-path="url(#clip0_2_8351)">
            <path
              d="M11.9057 26.6665C11.6417 26.6607 11.3895 26.5561 11.199 26.3732C11.0117 26.1857 10.9066 25.9315 10.9066 25.6665C10.9066 25.4015 11.0117 25.1473 11.199 24.9598L19.999 16.1598L11.1857 7.01316C10.9984 6.82566 10.8932 6.57149 10.8932 6.30649C10.8932 6.04149 10.9984 5.78733 11.1857 5.59983C11.3732 5.41256 11.6273 5.30737 11.8924 5.30737C12.1574 5.30737 12.4115 5.41256 12.599 5.59983L22.0923 15.4665C22.1847 15.5582 22.2579 15.6673 22.3079 15.7874C22.3579 15.9075 22.3837 16.0364 22.3837 16.1665C22.3837 16.2966 22.3579 16.4255 22.3079 16.5456C22.2579 16.6657 22.1847 16.7748 22.0923 16.8665L12.6124 26.3865C12.4213 26.5668 12.1684 26.667 11.9057 26.6665Z"
              fill="white"
            />
          </g>
          <defs>
            <clipPath id="clip0_2_8351">
              <rect width="32" height="32" fill="white" />
            </clipPath>
          </defs>
        </svg>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue';

const cards = ref([
  {
    image: 'src/assets/icons/Ellipse 12.png',
    flag: 'src/assets/icons/flag.png',
  },
  {
    image: 'src/assets/icons/Ellipse 12.png',
    flag: 'src/assets/icons/flag.png',
  },
  {
    image: 'src/assets/icons/Ellipse 12.png',
    flag: 'src/assets/icons/flag.png',
  },
]);

let currentIndex = ref(0);

const prevCard = () => {
  if (currentIndex.value > 0) {
    currentIndex.value -= 1;
    updateSlider();
  }
};

const nextCard = () => {
  if (currentIndex.value < cards.value.length - 1) {
    currentIndex.value += 1;
    updateSlider();
  }
};

const updateSlider = () => {
  const swiperWrapper = document.querySelector('.swiper-wrapper');
  const cardWidth = document.querySelector('.swiper-slide').offsetWidth;
  swiperWrapper.style.transform = `translateX(-${
    currentIndex.value * cardWidth
  }px)`;

  // Check if the first card is centered
  if (currentIndex.value === 0) {
    document.querySelector('.arrow-left').classList.add('disabled');
  } else {
    document.querySelector('.arrow-left').classList.remove('disabled');
  }

  // Check if the last card is centered
  if (currentIndex.value === cards.value.length - 1) {
    document.querySelector('.arrow-right').classList.add('disabled');
  } else {
    document.querySelector('.arrow-right').classList.remove('disabled');
  }
};

onMounted(() => {
  updateSlider();
});
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: -60px;
  height: auto;
}

.text-container {
  position: relative;
  display: inline-block; /* Ensure container wraps around content */
}

.arrow-down {
  position: relative;
  bottom: 8px;
  left: 71%;
  transform: translateX(-50%);
  color: white;
}
.card-slider {
  display: flex;
  height: 380px;
  width: 400px;
}

.arrow {
  cursor: pointer;
  font-size: 24px;
  color: white;
  align-content: center;
  align-items: center;
  margin-bottom: 28%;
}

.swiper-container {
  width: 100%;
  overflow: hidden;
  position: relative;
  margin-left: 40px;
  margin-right: 40px;
}

.swiper-slide {
  flex: 0 0 auto;
  width: 180px;
  height: 270px;
  background-color: white;
  color: black;
  cursor: pointer;
  position: relative;
  border-radius: 10px;
  box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.3);
}

.swiper-wrapper {
  display: flex;
  justify-content: last baseline; /* Adjust as needed */
  perspective: 6000px;
  transform-style: preserve-3d;
  transition: transform 0.09s ease; /* Add transition for smooth animation */
}
.card {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  transform-style: preserve-3d;
  position: relative; /* Ensure position relative for absolute positioning */
}

.card-image {
  width: 80px; /* Adjust the width as needed */
  height: 86px; /* Adjust the height as needed */
  overflow: hidden;
  align-items: center;
  position: relative;
  margin-bottom: 20px; /* Ensure position relative for absolute positioning */
}

.card-image img {
  width: 100%;
  height: 100%;
}

.card-content {
  text-align: center;
  font-size: x-small;
}

.flag-image {
  position: absolute;
  bottom: 170px;
  right: 58px;
  width: 18px !important; /* Adjust the width as needed */
  height: 12px !important; /* Maintain aspect ratio */
  z-index: 0; /* Ensure it's above the card content */
}

.active {
  transform: translateZ(700) rotateY(0deg) rotateX(0deg);
}

.swiper-slide:not(.active) {
  transform: translateZ(-900px) rotateY(0deg) rotateX(0deg);
}

.heading {
  background-color: azure;
  border-radius: 10px;
  text-align: center;
  width: 110px;
}
.title {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight: 900;
  margin-top: -10px;
}
.sub-title {
  font-size: 12px;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  color: #4a77ff;
  font-weight: 900 !important;
}
.column {
  font-size: 10px;
}
.text-color-ff {
  color: #4a77ff;
  font-size: 14px !important;
  margin-bottom: 8px;
  margin-top: -px;
}
@media only screen and (max-width: 600px) {
  /* Adjustments for mobile screens */
  .card-slider {
    align-items: center;
   overflow-x: hidden;/* Ensure correct positioning of arrows */
     /* Center arrows and swiper horizontally */
  }
  .offer{
    margin-top: 40px;
  }
}
.card-slider {
  display: flex;
  justify-content: center; /* Center horizontally */
  position: relative; 
}
</style>
