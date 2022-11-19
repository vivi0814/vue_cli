<template>
  <div>
    <Carousel v-model="value" loop >
        <CarouselItem v-for="item in 7" :key="item">
            <div class="demo-carousel">
              <img alt="Vue logo" :src="require(`@/assets/images/img${item}.jpg`)">
            </div>
        </CarouselItem>
        <!-- <CarouselItem>
            <div class="demo-carousel">2</div>
        </CarouselItem>
        <CarouselItem>
            <div class="demo-carousel">3</div>
        </CarouselItem>
        <CarouselItem>
            <div class="demo-carousel">4</div>
        </CarouselItem> -->
    </Carousel>
  </div>
  <Space direction="vertical">
        <Space wrap>
            <Button type="default" ghost>Default</Button>
            <Button type="primary" ghost>Primary</Button>
            <Button type="dashed" ghost>Dashed</Button>
            <Button type="text" ghost>Text</Button>
        </Space>
        <Space wrap>
            <Button type="info" ghost>Info</Button>
            <Button type="success" ghost>Success</Button>
            <Button type="warning" ghost>Warning</Button>
            <Button type="error" ghost>Error</Button>     
        </Space>
    </Space>
</template>
<script>
    export default {
        data () {
            return {
                value: 0
            }
        }
    }
</script>

<style>
img{
  width: 80%;
}
  
</style>

