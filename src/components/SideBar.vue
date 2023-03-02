<template>
  <div>
    <q-layout view="lHh lpr lFf" container style="height: 50px">
      <q-header bordered class="bg-white text-primary">
        <q-toolbar>
          <q-toolbar-title class="text-center">
            Quasar E-commerce UI
          </q-toolbar-title>
        </q-toolbar>
      </q-header>
    </q-layout>
  </div>
</template>

<script>
import { ref } from "vue";

export default {
  setup() {
    return {
      tab: ref("images"),
    };
  },
};
</script>

<style>

</style>
