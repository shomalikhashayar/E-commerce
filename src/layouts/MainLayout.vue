<template>
  <v-container>
    <SideBar />
    <div class="row">
      <div class="col-3 blue_background" style="height: 700px">
        <q-list class="text-white rounded-borders q-mx-md q-mt-lg">
          <q-item>
            <q-item-section class="text-h5">Inventory</q-item-section>
          </q-item>
          <q-separator color="white" inset />
          <q-item>
            <q-item-section>CATEGORIES</q-item-section>
          </q-item>
          <q-separator color="white" inset />
          <q-item>
            <q-item-section class="">PRODUCTS</q-item-section>
            <q-item-section avatar>
              <q-icon name="fas fa-chevron-right" style="font-size: 1rem" />
            </q-item-section>
          </q-item>
          <q-separator color="white" inset />
          <q-item>
            <q-item-section>OPTIONS</q-item-section>
          </q-item>
          <q-separator color="white" inset />
          <q-item>
            <q-item-section>IMPORT/EXPORT</q-item-section>
          </q-item>
          <q-separator color="white" inset />
          <q-item>
            <q-item-section>VENDORS</q-item-section>
          </q-item>
          <q-separator color="white" inset />
          <q-item>
            <q-item-section>PURCHASE ORDERS</q-item-section>
          </q-item>
          <q-separator color="white" inset />
          <q-item>
            <q-item-section>RECEVING</q-item-section>
          </q-item>
          <q-separator color="white" inset />
          <q-item>
            <q-item-section>PRODUCT KEY DISTRIBUTION</q-item-section>
          </q-item>
          <q-separator color="white" inset />
          <q-item>
            <q-item-section>WHAREHOUSES</q-item-section>
          </q-item>
        </q-list>
      </div>
      <div class="col-9">
        <q-toolbar class="bg-grey-3">
          <q-toolbar-title>Products</q-toolbar-title>
          <q-input
            borderless
            v-model="text"
            input-class="text-left"
            class="q-ml-md"
            label="Search .."
          >
            <template v-slot:prepend>
              <q-icon name="search"></q-icon>
            </template>
          </q-input>
          <q-space></q-space>
          <q-separator vertical />
          <q-btn dense round flat icon="notifications" class="q-mx-lg">
            <q-badge color="green" floating transparent>4</q-badge>
          </q-btn>
          <q-separator vertical />
          <q-avatar class="q-ml-lg">
            <img src="../assets/khashayar.jpeg" />
          </q-avatar>
        </q-toolbar>
        <div class="row q-mt-sm q-px-sm">
          <div class="col-4">
            <q-card
              class="my-card q-ma-sm my-box cursor-pointer q-hoverable"
              v-ripple
            >
              <div
                class="row justify-center full-height full-width text-center"
              >
                <img
                  src="0.png"
                  class="q-mt-sm"
                  fit="contain"
                  style="max-width: 170px; height: 200px"
                />
                <q-card-section>
                  <div class="text-h6">Green Vest</div>
                  <div class="text-subtitle-2">$15.00</div>
                </q-card-section>
              </div>
            </q-card>
          </div>
          <div class="col-4">
            <q-card
              class="my-card q-ma-sm my-box cursor-pointer q-hoverable"
              v-ripple
            >
              <div
                class="row justify-center full-height full-width text-center"
              >
                <img
                  src="1.png"
                  class="q-mt-sm"
                  fit="contain"
                  style="max-width: 170px; height: 200px"
                />
                <q-card-section>
                  <div class="text-h6">Green Pantallon</div>
                  <div class="text-subtitle-2">$13.00</div>
                </q-card-section>
              </div>
            </q-card>
          </div>
          <div class="col-4">
            <q-card
              class="my-card q-ma-sm my-box cursor-pointer q-hoverable"
              v-ripple
            >
              <div
                class="row justify-center full-height full-width text-center"
              >
                <img
                  src="5.png"
                  class="q-mt-sm"
                  fit="contain"
                  style="max-width: 170px; height: 200px"
                />
                <q-card-section>
                  <div class="text-h6">Veste Noir</div>
                  <div class="text-subtitle-2">$35.00</div>
                </q-card-section>
              </div>
            </q-card>
          </div>
          <div class="col-4">
            <q-card
              class="my-card q-ma-sm my-box cursor-pointer q-hoverable"
              v-ripple
            >
              <div
                class="row justify-center full-height full-width text-center"
              >
                <img
                  src="3.png"
                  class="q-mt-sm"
                  fit="contain"
                  style="max-width: 170px; height: 200px"
                />
                <q-card-section>
                  <div class="text-h6">Sweetshirt</div>
                  <div class="text-subtitle-2">$25.00</div>
                </q-card-section>
              </div>
            </q-card>
          </div>
          <div class="col-4">
            <q-card
              class="my-card q-ma-sm my-box cursor-pointer q-hoverable"
              v-ripple
            >
              <div
                class="row justify-center full-height full-width text-center"
              >
                <img
                  src="4.png"
                  class="q-mt-sm"
                  fit="contain"
                  style="max-width: 170px; height: 200px"
                />
                <q-card-section>
                  <div class="text-h6">Grey Vest</div>
                  <div class="text-subtitle-2">$15.00</div>
                </q-card-section>
              </div>
            </q-card>
          </div>
          <div class="col-4">
            <q-card
              class="my-card q-ma-sm my-box cursor-pointer q-hoverable"
              v-ripple
            >
              <div
                class="row justify-center full-height full-width text-center"
              >
                <img
                  src="2.png"
                  class="q-mt-sm"
                  fit="contain"
                  style="max-width: 170px; height: 200px"
                />
                <q-card-section>
                  <div class="text-h6">Pantalon Jean</div>
                  <div class="text-subtitle-2">$13.00</div>
                </q-card-section>
              </div>
            </q-card>
          </div>
        </div>
      </div>
    </div>
  </v-container>
</template>

<script>
import SideBar from "../components/SideBar.vue";
export default {
  name: "MainLayout",
  components: {
    SideBar,
  },
};
</script>
<style scoped>
.blue_background {
  background-color: #40a3f3;
}
.my-card:hover {
  background-color: #40a3f3;
  color: white;
}
</style>
