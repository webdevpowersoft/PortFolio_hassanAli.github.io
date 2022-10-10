<template>
  <div class="container text-center">
    <div style="margin-top: 100px"></div>
    <q-toolbar class="q-pb-md">
      <q-img width="60px" src="~assets/HLogo.png" />

      <q-space />

      <q-btn class="iconhover" href="https://github.com/HassanAli361" target="_Blank" color="secondary" flat dense round
        icon="eva-github-outline">
        <q-tooltip class="text-caption bg-secondary" :offset="[10, 2]" transition-show="rotate"
          transition-hide="rotate">
          Github
        </q-tooltip>
      </q-btn>

      <q-btn class="iconhover" href="https://www.linkedin.com/in/hassan-ali-498212225" target="_blank" color="secondary"
        flat dense round icon="eva-linkedin-outline">
        <q-tooltip class="text-caption bg-secondary" :offset="[10, 2]" transition-show="rotate"
          transition-hide="rotate">
          Linkedin
        </q-tooltip>
      </q-btn>

      <q-btn class="iconhover" href="https://twitter.com/Hassanali2662" target="_blank" color="secondary" flat dense
        round icon="eva-twitter-outline">
        <q-tooltip class="text-caption bg-secondary" :offset="[10, 2]" transition-show="rotate"
          transition-hide="rotate">
          Twitter
        </q-tooltip>
      </q-btn>

      <q-btn class="iconhover" color="secondary" flat dense round icon="eva-facebook-outline">
        <q-tooltip class="text-caption bg-secondary" :offset="[10, 2]" transition-show="rotate"
          transition-hide="rotate">
          FaceBook
        </q-tooltip>
      </q-btn>
    </q-toolbar>
  </div>
  <div class="text-subtitle1 text-weight-light text-center q-py-sm"
    :class="$q.dark.isActive ? 'bg-info text-white' : 'bg-black text-white'">
    Copyright ©2022 All rights reserved | This template is made with by <span class="text-weight-bold">HassanAli</span>
  </div>
</template>
<script>
export default {

}
</script>
<style lang="">

</style>
