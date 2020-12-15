<template>
  <div class="header clearfix">
    <div class="branding">
      <img src="../../assets/images/logo.png">
    </div>
    <ul class="gnb">
      <li><menu-item text="Study"></menu-item></li>
      <li><menu-item text="Team"></menu-item></li>
      <li><a href="#">RESOURCE</a></li>
      <li><a href="#">GUIDE</a></li>
      <li><a href="#">DOWNLOAD</a></li>
    </ul>
  </div>
</template>

<script>
import MenuItem from '@/components/common/MenuItem.vue';

export default {
  name: 'Header',
  components: {
    MenuItem
  },
};
</script>

<style scoped>

</style>