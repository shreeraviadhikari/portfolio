<template>
  <div class="home">
    <v-img
      :src="imgSource"
      gradient="to top right, rgba(100,115,201,.7), rgba(25,32,72,.7)"
    ></v-img>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
  },
  data () {
    return {
      imgSource: "../assets/images/master.jpeg"
    }
  },
}
</script>
