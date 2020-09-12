<template>
  <div>
    <img v-bind: src="image.url"/>"
  </div>
</template>

<script>
export default {
    images: [
      {
        id:"1",
        url:"../assets/img1.jpg",
        
      },
      {
        id:"2",
        url:"../assets/img2.jpeg",
        
      },
      {
        id:"3",
        url:"../assets/img3.jpeg",
      
      }
    ]
    
}
</script>

<style lang="stylus" scoped>

</style>