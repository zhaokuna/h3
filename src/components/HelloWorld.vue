<template>
  <div>
    <Redirect></Redirect>
    <Dashboard></Dashboard>
  </div>
</template>

<script>
import Redirect from "../components/redirect";
import Dashboard from "../components/dashboard";
export default {
  components: {
    Redirect,
    Dashboard
  }
};
</script>

<style lang="scss" scoped>
</style>