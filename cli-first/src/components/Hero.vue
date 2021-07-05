<template>
<div class="hero">
  <img src="./../assets/maxwell-nelson-Ix64NPGxZoQ-unsplash.jpg" alt="">
</div>
  
</template>

<script>
export default {
  name: 'Hero',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped >

.hero{
  width:100%;
  height: 500px;
  overflow: hidden;
}

img{
 max-width:100%;
 max-height:100%;
 
}

</style>
