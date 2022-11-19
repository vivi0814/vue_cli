<template>
  <div class="news">
    <Images/>
    <Images/>
    <Images/>
    <h1>This is an news page</h1>
    <HelloWorld title="緊張"/>
  </div>
</template>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Images from '@/components/Images.vue'

export default {
  name: 'NewsView',
  components: {
    HelloWorld,
    Images
  }
}
</script>