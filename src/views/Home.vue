<template>
  <v-container class="grey lighten-5">
    <v-row>
      <v-col
        sm="6"
        md="6"
      >
        <v-img
          contain
          :src="require('../assets/images/ravi.png')"
          max-height="600"
          min-width="200"
        ></v-img>
      </v-col>
      <v-col
      >
        <p class="forced-padding">
          <span class="internal-h1">Hi, I'm Ravi!</span>
          I'm a Software Engineer, with experience in managing small and huge scale applications. 
          I started my professional career with Quality Assurance. 
          After I learned how quality can be met, I started building applications. 
          I've worked as a Python Developer, developing many apps for desktops, web, 
          and automation. Stretching out of my comfort zone, I started building Frontend 
          applications. I've worked on native HTML websites with custom css and javascript 
          all the way. I've developed small applications on Vue.js. My affection towards Machine 
          Learning never depleted, in every road I took, I saw the applications and necessity of 
          an additional intelligence. I want to pursue a career in Data Science provided that I've 
          learned how to code in backend and I've learned how to display in frontend. 
          My favorite quote is "Imagination is a power of man, against nature". 
         </p>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
  .internal-h1{
    display: block; 
    height: 50px;
    font-weight: 800;
    color: rgb(177, 115, 0);
  }
  .forced-padding {
    padding-top: 200px;
    text-align: left;
  }
  @media (max-width: 1200px){
  .forced-padding {
    padding-top: 50px;
  }
}
</style>