<template lang="html">
  
<!DOCTYPE html>

<html>
  <body>
  <!-- header -->

<header>
  <meta charset="UTF-8">
  <h1 class="head-line">
<HeaderItems/>
    </h1>
    <ul class="Navigation-List">
      <li class="Navigation-Item">
       <homeButton/>
      </li>
      </ul>
</header>
  </body>
</html>

</template>

<style>
  * {
  margin:0; padding:0;
}
header {
  width: 100%;
  padding: 15px 0;
  margin: 0 auto;
  text-align: center;
  background-color:aqua;
}
.head-line{
}

</style>


<script lang="ts">
import HeaderItems from '~/components/Header-Items.vue';
import Vue from 'vue'
import homeButton from '~/components/home-button.vue';

export default Vue.extend({
name: 'IndexPage',
components: {
HeaderItems,
homeButton
  }
})
</script>