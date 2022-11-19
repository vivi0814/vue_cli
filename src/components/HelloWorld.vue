<template>
  <div class="hello" :class="type">
    <div class="img" v-for="item in 7" :key="item">
      <img alt="Vue logo" :src="require(`@/assets/images/img${item}.jpg`)">
    </div>
    <div :style="{
        backgroundImage:`url(${ require('@/assets/images/img8.jpg')})`
      }">

    </div>
    <div>
      <h1>{{ title }}</h1>
      <h1>{{ msg }}</h1>
      <p>123123</p>
      <button>444</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    title: String,
    msg: String,
    type: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hello{
  width: 100%;
  display: inline-flex;
}
.img{
  width: 100px;
  height: 100px;
  background: #ddd;
  margin: 40px;
}
h1 {
  margin: 15px 25px;
}
p{
  margin: 5px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
