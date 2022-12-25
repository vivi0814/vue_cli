<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld title="早安" msg="午安"/>
    <HelloWorld title="QQ" msg="1"/>
    <HelloWorld title="@@" msg="2"/>
    <HelloWorld title="XD" msg="3"/>
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
