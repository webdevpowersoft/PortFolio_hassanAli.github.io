<template>
  <router-view />
</template>

<script>
import { Loading, QSpinnerPuff } from "quasar";
// import { LoadingBar } from "quasar";
export default {
  name: 'app',
  setup() {
    Loading.show({
      spinner: QSpinnerPuff,
      spinnerSize: 100,
      spinnerColor: "white",
      message: "Loading...",
      messageColor: "white",
      customClass: "bg-primary",
    });
    Loading.hide(
      setTimeout(() => {
        Loading.hide();
      }, 3000)
    );
    return {};
  },
}
</script>
