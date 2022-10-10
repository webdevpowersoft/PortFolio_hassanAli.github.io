<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated :class="$q.dark.isActive ? 'bg-grey-9 text-white' : 'bg-white'">
      <q-toolbar class="container gt-xs" :class="$q.dark.isActive ? 'bg-dark-page text-white' : ''">
        <q-toolbar-title class="font-header text-info q-py-md">
          <q-img width="60px" src="~assets/HLogo.png" />
        </q-toolbar-title>
        <q-tabs no-caps inline-label dense indicator-color="primary" active-color="primary" class="text-grey-5">
          <q-route-tab icon="eva-home-outline" to="/" exact replace label="Home" />
          <q-route-tab icon="eva-briefcase-outline" to="/portfolio" exact replace label="Portfolio" />
          <q-route-tab icon="eva-phone-call-outline" to="/contact" exact replace label="Contact" />
        </q-tabs>
        <q-space />
        <div>
          <q-toggle dense v-model="first" @click="toggleDarkMode" checked-icon="eva-moon-outline"
            unchecked-icon="eva-sun-outline" />
        </div>
      </q-toolbar>
    </q-header>


    <q-header elevated class="lt-sm">
      <q-toolbar class="bg-white">
        <q-toolbar-title class="font-header text-info q-py-md">
          <q-img width="45px" src="~assets/HLogo.png" />
        </q-toolbar-title>
        <q-space />
        <q-toggle dense v-model="first" @click="toggleDarkMode" checked-icon="eva-moon-outline"
          unchecked-icon="eva-sun-outline" />
      </q-toolbar>
      <div class="text-weight-light" style="text-align: center">
        <q-tabs no-caps narrow-indicator active-color="primary" class="bg-white text-black">
          <q-route-tab to="/" exact replace label="Home" />
          <q-route-tab to="/portfolio" exact replace label="Portfolio" />
          <q-route-tab to="/Contact" exact replace label="Contact" />
        </q-tabs>
      </div>
    </q-header>

    <!-- <q-header class="lt-sm" elevated :class="$q.dark.isActive ? 'bg-grey-9 text-white' : 'bg-white'">
      <q-toolbar class="container" :class="$q.dark.isActive ? 'bg-dark-page text-white' : ''">
        <q-toolbar-title class="font-header text-info q-py-md">
          <q-img width="30px" src="~assets/HLogo.png" />
        </q-toolbar-title>
        <q-tabs no-caps dense indicator-color="primary" active-color="primary" class="text-grey-5">
          <q-route-tab to="/" exact replace label="Home" />
          <q-route-tab to="/portfolio" exact replace label="Portfolio" />
          <q-route-tab to="/contact" exact replace label="Contact" />
        </q-tabs>
        <q-space />
        <div>
          <q-toggle dense v-model="first" @click="toggleDarkMode" checked-icon="eva-moon-outline"
            unchecked-icon="eva-sun-outline" />
        </div>
      </q-toolbar>
    </q-header> -->

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { useQuasar } from 'quasar';
import { ref } from 'vue';

export default {
  name: 'PageIndex',
  setup() {
    const $q = useQuasar();

    function toggleDarkMode() {
      $q.dark.toggle();
    }
    return {
      first: ref(false),
      toggleDarkMode,
    };
  },
};
</script>

<style lang="scss">
body.body--dark {
  background: #333333;
}
</style>
