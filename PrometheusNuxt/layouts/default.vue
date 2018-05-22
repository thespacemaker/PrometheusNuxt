<template>
  <v-app dark>
    <v-navigation-drawer
         temporary
         v-model="drawer"
         absolute
         fixed
         app
       >
         <v-list class="pa-1">
           <v-list-tile avatar>
               <v-list-tile-title>Prometheus Arms Co.</v-list-tile-title>
             </v-list-tile-content>
           </v-list-tile>
         </v-list>
         <v-list class="pt-0" dense>
           <v-divider></v-divider>
           <v-list-tile to="/#" active-class="green darken-2">
             <v-list-tile-action>
               <v-icon>apps</v-icon>
             </v-list-tile-action>
             <v-list-tile-content>
               <v-list-tile-title>Home</v-list-tile-title>
             </v-list-tile-content>
           </v-list-tile>
           <v-list-tile to="/Gallery" active-class="green darken-2">
             <v-list-tile-action>
               <v-icon>bubble_chart</v-icon>
             </v-list-tile-action>
             <v-list-tile-content>
               <v-list-tile-title>Gallery</v-list-tile-title>
             </v-list-tile-content>
           </v-list-tile>
           <v-list-tile to="/About" active-class="green darken-2">
             <v-list-tile-action>
               <v-icon>bubble_chart</v-icon>
             </v-list-tile-action>
             <v-list-tile-content>
               <v-list-tile-title>Our Philosphy</v-list-tile-title>
             </v-list-tile-content>
           </v-list-tile>
         </v-list>
       </v-navigation-drawer>

      <v-toolbar dark fixed>
          <v-toolbar-side-icon @click.stop="drawer = !drawer"></v-toolbar-side-icon>
          <v-toolbar-title align-center>Prometheus Arms Co.</v-toolbar-title>
          <v-spacer></v-spacer>
          <v-btn icon href="tel:2147238755">
            <v-icon>phone</v-icon>
          </v-btn>
          <v-btn
          icon
          to=/>
            <v-icon>home</v-icon>
          </v-btn>
      </v-toolbar>

      <main>
          <v-fade-transition mode="out-in">
              <router-view></router-view>
          </v-fade-transition>
      </main>

      <v-footer style="background-color:#351652" id="shadow">
        <v-layout row wrap align-center>
          <v-flex xs12>
            <div class="white--text ml-3 text-xs-center">
              Made with
              <v-icon class="white--text">favorite</v-icon>
              by <a class="white--text" href="theadnan.tech" target="_blank">    TheSpaceMaker</a>
            </div>
          </v-flex>
        </v-layout>
      </v-footer>

  </v-app>
</template>

<script>
  export default {
    data () {
      return {
        drawer: false,
        items: [
          { icon: 'apps', title: 'Welcome', to: '/' },
          { icon: 'bubble_chart', title: 'Gallery', to: 'Gallery' },
          { icon: 'bubble_chart', title: 'Our Philosphy', to: 'about' }
        ],
        title: 'Prometheus Arms Co.'
      }
    }
  }
</script>
