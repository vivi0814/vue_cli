<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld title="聽不懂QQ" msg="好難哦@@"/>
    <HelloWorld title="氣死" msg="1"/>
    <HelloWorld title="氣炸" msg="2"/>
    <HelloWorld title="氣瘋" msg="3"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
