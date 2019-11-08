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
</template>

<script>
import AppServers from "./servers/Servers.vue";
import AppServerStatus from "./servers/ServerStatus.vue";
import AppInfo from "./servers/Info.vue";
import AppFooter from "./servers/Foot.vue";

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