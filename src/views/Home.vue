<template>
  <div class="home" >
    <div class="row">
      <div class="col-md-3" id="sidepanel">
        <SidePanel msg="Welcome to Your Vue.js App"/>
      </div>
      <div class="col-md-9">
        <h1> Main Panel section </h1>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import SidePanel from '@/components/SidePanel.vue';

export default {
  name: 'Home',
  components: {
    SidePanel,
  },
};
</script>
<style scoped>
</style>
