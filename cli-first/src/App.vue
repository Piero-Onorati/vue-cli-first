<template>
  <div id="app">
    

    <div class="image-outer">
      <div class="image-inner">
        <Hero/>
      </div>

      <div class="didascalia">
        <img alt="Vue logo" src="./assets/logo.png">
      <Title/>
    </div>


    </div>
    
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing:border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.image-outer {
  width: 600px;
  height: 600px;
  margin: 75px auto;
  background-color: #fff;
  border: 1px solid #aaa;
  border-radius: 6px;
  box-shadow: 0 0 5px #333, 5px 3px 5px #aaa;
}

.image-inner {
  width: 570px;
  height: 450px;
  margin: 15px auto;
  border-radius: 6px;
  overflow: hidden;
}

.didascalia{
  display: flex;
  align-items: center;
  justify-content: center;
}

.didascalia>img{
  width:100px
}



</style>
