<template>
  <div class="container">
    <app-server-status></app-server-status>
    <hr />
    <div class="row">
      <app-servers></app-servers>
      <app-info></app-info>
    </div>
    <hr />
    <app-footer></app-footer>
  </div>
</template>sdfsd

<script>
import AppServers from "./Servers.vue";
import AppServerStatus from "./ServerStatus.vue";
import AppInfo from "./Info.vue";
import AppFooter from "./Foot.vue";

export default {
  components: {
    AppServers,
    AppServerStatus,
    AppInfo,
    AppFooter
  }
};
</script>

<style>
</style>