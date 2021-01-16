<template>
  <div id="app">
    <!-- <v-card class="overflow-hidden"> -->
    <v-app-bar
      absolute
      color="#fcb69f"
      dark
      shrink-on-scroll
      :src="require('./assets/images/master.jpeg')"
      scroll-target="#scrolling-techniques-2"
    >
      <template v-slot:img="{ props }">
        <v-img
          v-bind="props"
          gradient="to top right, rgba(100,115,201,.6), rgba(25,32,72,.8)"
        ></v-img>
      </template>
      <v-app-bar-title style="width: 500px;">Ravi Adhikari</v-app-bar-title>
      <v-spacer></v-spacer>
      <v-text-field
        placeholder="Search Blogs"
      >
        <v-icon
          slot="append"
        >
          mdi-magnify
        </v-icon>
      </v-text-field>
      <template v-slot:extension>
        <v-tabs align-with-title>
          <!-- <v-spacer></v-spacer> -->
          <v-tab to="/">
              <v-icon>
                  mdi-home
              </v-icon>
              Home
          </v-tab>
          <v-tab to="/about">
            <v-icon>
                mdi-phone
            </v-icon>
            Contact
          </v-tab>
          <v-tab to='/gallery'>
          <v-icon>
              mdi-camera
          </v-icon>
          Gallery
          </v-tab>
          <v-tab to='/blogs'>
          <v-icon>
              mdi-book
          </v-icon>
          Blogs
          </v-tab>
          
        </v-tabs>
      </template>
    </v-app-bar>
      <v-container style="height: 100px; margin-top: 240px">
        <router-view/>
      </v-container>
  <!-- </v-card> -->
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

// #nav {
//   padding: 30px;

//   a {
//     font-weight: bold;
//     color: #2c3e50;

//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }
</style>

<style scoped>
.forced-width {
  width: 500px;
}
</style>
