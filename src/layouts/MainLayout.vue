<template>
  <q-layout class="bg-color" >
    <div class="header-container" >
      <q-header class="bg-transparent">
        <q-toolbar>
          <q-toolbar-title>
            <div class="header-content q-gutter-md q-mx-sm">
              <div class="logo-container">
                <img
                  src="src\assets\icons\download.png"
                  alt="Hyperhire Logo"
                  class="logo"
                />
              </div>
              <div class="menu-container">
                <q-btn-dropdown
                  color="transparent"
                  label="채용"
                  class="menu-dropdown"
                >
                  <q-list>
                    <q-item clickable v-close-popup>
                      <q-item-section>
                        <q-item-label class="normal-font">해외 개발자 원격 채용</q-item-label>
                      </q-item-section>
                    </q-item>
                    <q-item clickable v-close-popup>
                      <q-item-section>
                        <q-item-label class="normal-font">외국인 원격 채용 (비개발 직군)</q-item-label>
                      </q-item-section>
                    </q-item>
                    <q-item clickable v-close-popup>
                      <q-item-section>
                        <q-item-label class="normal-font">한국어 가능 외국인 채용</q-item-label>
                      </q-item-section>
                    </q-item>
                  </q-list>
                </q-btn-dropdown>
                <q-p color="transparent" class="menu-description hide-on-mobile">해외 개발자 활용 서비스</q-p>

              </div>
              <q-btn color="white" text-color="blue" class="contact-button hide-on-mobile">문의하기</q-btn>

            </div>
          </q-toolbar-title>
        </q-toolbar>
      </q-header>
    </div>
    <!-- Place mainComponentVue here -->
    <mainComponentVue />
  </q-layout>
</template>

<script setup lang="ts">
import mainComponentVue from './mainComponent.vue';
</script>

<style scoped>
.bg-color {
  background-image: linear-gradient(151.17deg, #26c2b9 8.69%, #288be7 126.06%);
}

.bg-transparent {
  background: transparent !important;
}


.header-container {
  margin: 0 20px; /* Adjust margins as needed */
}

.header-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.logo-container {
  display: flex;
  align-items: center;
}

.logo {
  width: 74px;
  height: 14px;
}

.menu-container {
  display: flex;
  align-items: center;
}

.menu-dropdown {
  font-size: 10px;
}

.menu-description {
  font-size: 10px;
}

.contact-button {
  font-size: 10px;
  border-radius: 6px;
}

.normal-font {
  font-size: 10px;
}

@media only screen and (max-width: 600px) {
  .hide-on-mobile {
    display: none;
  }
}
</style>