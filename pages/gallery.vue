
<template>
  <v-content>
    <section>
      <v-parallax src="/IMG_2920.jpg" height="600">
        <v-layout
        column
        align-center
        justify-center
        class="white--text"
        >
          <h1 class="white--text mb-2 display-1 text-xs-center">Gallery</h1>
        </v-layout>
      </v-parallax>
    </section>

    <section>
      <v-container>
        <br />
        <v-layout row wrap elevation-13 py-3 >
          <v-flex xs12>
            <v-card class="elevation-0 transparent">
              <v-card-text class="display-1 text-xs-center pb-4">Rifles</v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs2></v-flex>
          <v-flex xs2>
            <v-card dark class=" hidden-xs-only">
              <v-card-text class="text-xs-center">CUSTOM</v-card-text>
            </v-card>
            <v-card class="transparent elevation-0 hidden-sm-and-up">
              <v-card-text class="text-xs-center">CUSTOM</v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs1></v-flex>
          <v-flex xs2>
            <v-card dark class="hidden-xs-only">
              <v-card-text class="text-xs-center">PRECISE</v-card-text>
            </v-card>
            <v-card class="transparent elevation-0 hidden-sm-and-up">
              <v-card-text class="text-xs-center">PRECISE</v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs1></v-flex>
          <v-flex xs2 pb-4>
            <v-card dark class="hidden-xs-only">
              <v-card-text class="text-xs-center">ELITE</v-card-text>
            </v-card>
            <v-card class="transparent elevation-0 hidden-sm-and-up">
              <v-card-text class="text-xs-center">ELITE</v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs2></v-flex>
        </v-layout>
        <br />
        <v-carousel id="test" pb-4 delimiter-icon="stop">
          <v-carousel-item id="test" v-for="(item,i) in items" v-bind:src="item.src" :key="i"></v-carousel-item>
        </v-carousel>
      </v-container>
    </section>

    <section>
      <br />
      <br />
      <br />
      <br />
      <br />
      <hr />
      <br />
      <br />
      <br />
      <v-parallax src="/IMG_3013.jpg" height="300">
        <v-layout
        column
        align-center
        justify-center
        class="white--text"
        >
          <h1 class="white--text mb-2 display-2 text-xs-center">Pistols</h1>
        </v-layout>
      </v-parallax>
    </section>

    <section>
      <v-container>
        <br />
        <v-layout row wrap elevation-13 py-3>
          <v-flex xs12>
            <v-card class="elevation-0 transparent">
            </v-card>
          </v-flex>
          <v-flex xs2></v-flex>
          <v-flex xs2>
            <v-card dark class=" hidden-xs-only">
              <v-card-text class="text-xs-center">CUSTOM</v-card-text>
            </v-card>
            <v-card class="transparent elevation-0 hidden-sm-and-up">
              <v-card-text class="text-xs-center">CUSTOM</v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs1></v-flex>
          <v-flex xs2>
            <v-card dark class="hidden-xs-only">
              <v-card-text class="text-xs-center">PRECISE</v-card-text>
            </v-card>
            <v-card class="transparent elevation-0 hidden-sm-and-up">
              <v-card-text class="text-xs-center">PRECISE</v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs1></v-flex>
          <v-flex xs2>
            <v-card dark class="hidden-xs-only">
              <v-card-text class="text-xs-center">ELITE</v-card-text>
            </v-card>
            <v-card class="transparent elevation-0 hidden-sm-and-up">
              <v-card-text class="text-xs-center">ELITE</v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs2></v-flex>
        </v-layout>

        <br />

<!--   example carousel with data binding
<div id="header-carousel">
   <v-carousel style="height: 100%">
     <v-carousel-item v-for="(slide, i) in slides" :src="slide.src" :key="i">
       <v-jumbotron dark>
         <v-container fill-height>
           <v-layout align-center>
             <v-flex>
               <h3 class="display-3">{{ slide.title }}</h3>
               <span class="subheading">{{ slide.text }}</span>
             </v-flex>
           </v-layout>
         </v-container>
       </v-jumbotron>
     </v-carousel-item>
   </v-carousel>
 </div>
-->


        <v-carousel pb-4 delimiter-icon="stop">
          <v-carousel-item id="test" v-for="(item2,i) in item2s" v-bind:src="item2.src" :key="i"></v-carousel-item>
        </v-carousel>
      </v-container>
    </section>

    <section>
        <br />
        <br />
        <br />
        <br />
        <br />
        <hr>
        <br />
        <br />
        <br />
    </section>

<section>
    <v-parallax src="/IMG_3183.JPG" height="300">
      <v-layout
      column
      align-center
      justify-center
      >
      <span class="black px-4">
        <h1 color="white" class="white--text mb-2 display-2 text-xs-center" id="shadow2">Available at DSG Arms!</h1>
</span>
      </v-layout>
    </v-parallax>
    <br />
    <br />
    <v-container>
      <v-carousel pb-4 delimiter-icon="stop">
        <v-carousel-item v-for="(item3,i) in item3s" v-bind:src="item3.src" :key="i"></v-carousel-item>
      </v-carousel>
      <br />
      <br />
      </v-container>
    </section>

    <section>
      <v-flex xs12>
        <v-container grid-list-xl elevation-13>
          <h2 class="text-xs-center">
            <v-icon x-large class="green--text text--darken-2">
              rate_review
            </v-icon>
          </h2>
          <div class="headline text-xs-center">
            Testimonials
          </div>
          <div class="subheading text-xs-center">
            Hear it from our customers.
          </div>
          <br />
          <v-layout row wrap align-center pt-6>
            <v-flex xs12 py-6 md6>
              <br />
              <v-card class="elevation-4 text-xs-center pt-4">
                <v-avatar
                  :size="40"
                >
                  <img src="/image1.jpeg" alt="avatar">
                </v-avatar>
                <v-card-text class="text-xs-center py-4">
                  <blockquote cite="Chad Lane - US Navy Veteran">
                    Prometheus rifles are among the best rifles I have ever owned. Every last detail is polished to perfection. There is never any doubt that the rifle will perform. From the beginning of the build to the end result, I could not be happier with my Prometheus Arms Co. Precision Rifle!
                    <br />
                    <br />
                    - Chad Lane - US Navy Veteran
                    <br />
                    <v-container fluid v-bind="{ [`grid-list-${size}`]: true }">
                      <v-layout row pt-4>
                        <v-flex xs4>
                          <v-card flat tile>


                          </v-card>
                        </v-flex>
                      </v-layout>
                    </v-container>

                  </blockquote>
                </v-card-text>







              </v-card>
            </v-flex>
            <v-flex xs12 md6>
              <v-card class="elevation-4">
                <v-card-text class="text-xs-center py-4">
                  <blockquote cite="Chad Lane - US Navy Veteran">
                    Having had several full custom rifles built over the years I can honestly say Prometheus exceeded my expecatations in every category. The build process was painless, the stockwork and inletting is superb, and the overall fit and finish is second to none. The barrel work was done outside of saami spec at my request; I delevered the cartidge I wanted to them, and they delivered a mile smasher. Turn around time was very reasonable as well. My next custom build will come from Prometheus, that is for sure.
                    <br />
                    <br />
                     - Alex Frie
                     <v-container fluid v-bind="{ [`grid-list-${size}`]: true }">
                       <v-layout row pt-4>
                         <v-flex xs4>
                           <v-card flat tile>
                             <v-card-media
                               height="150px"
                             >
                              <lightbox
                                thumbnail="/testimony/thumb1.JPG"
                              ></lightbox>
                            </v-card-media>
                          </v-card>
                        </v-flex>
                        <v-flex xs4>
                          <v-card flat tile>
                            <v-card-media
                            height="150px"
                            >
                              <lightbox
                                thumbnail="/testimony/thumb2.JPG"
                                images="['/testimony/IMG_1063.JPG', /testimony/IMG_1066.JPG', '~/static/testimony/IMG_1064.JPG']"
                               ></lightbox>
                             </v-card-media>
                           </v-card>
                         </v-flex>
                         <v-flex xs4>
                           <v-card flat tile>
                             <v-card-media
                               height="150px"
                             >
                             <lightbox
                             thumbnail="/testimony/thumb3.JPG"
                             images="['/testimony/IMG_1063.JPG', src/assets/testimony/IMG_1066.JPG', '/src/assets/testimony/IMG_1064.JPG']"
                             ></lightbox>
                             </v-card-media>
                           </v-card>
                         </v-flex>
                       </v-layout>
                     </v-container>
                  </blockquote>
                </v-card-text>
              </v-card>
              <br />
            </v-flex>
          </v-layout>
        </v-container>
      </v-flex>
    </section>
    <br /><br />

  </v-content>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: '/gallery/black.jpg'
          },
          {
            src: '/gallery/Camo.jpg'
          },
          {
            src: '/gallery/Camo2.jpg'
          },
          {
            src: '/gallery/Dual.jpg'
          },
          {
            src: '/gallery/Dual2.jpg'
          },
          {
            src: '/gallery/heli.jpg'
          },
          {
            src: '/gallery/heliblack.jpg'
          },
          {
            src: '/gallery/heliblack2.jpg'
          },
          {
            src: '/gallery/helicamo1.jpg'
          },
          {
            src: '/gallery/helicamo2.jpg'
          },
          {
            src: '/gallery/helicamo3.jpg'
          },
          {
            src: '/gallery/helicamo4.jpg'
          }
        ],
        item2s: [
          {
            src: '/gallery/pistol.jpg'
          },
          {
            src: '/gallery/pistol2.jpg'
          },
          {
            src: '/gallery/pistolblack.jpg'
          },
          {
            src: '/gallery/pistolblack2.jpg'
          },
          {
            src: '/gallery/pistoldark.jpg'
          },
          {
            src: '/gallery/pistoldark2.jpg'
          }
        ],
        item3s: [
          {
            src: 'src/assets/gallery/dsg/IMG_3029.jpg'
          },
          {
            src: 'src/assets/gallery/dsg/IMG_3035.jpg'
          },
          {
            src: 'src/assets/gallery/dsg/IMG_3039.jpg'
          },
          {
            src: 'src/assets/gallery/dsg/IMG_3047.jpg'
          },
          {
            src: 'src/assets/gallery/dsg/IMG_3048.jpg'
          },
          {
            src: 'src/assets/gallery/dsg/IMG_3051.jpg'
          },
          {
            src: 'src/assets/gallery/dsg/IMG_3053.jpg'
          },
          {
            src: 'src/assets/gallery/dsg/IMG_3055.jpg'
          },
          {
            src: 'src/assets/gallery/dsg/IMG_3057.jpg'
          },
          {
            src: 'src/assets/gallery/dsg/IMG_3070.jpg'
          },
          {
            src: 'src/assets/gallery/dsg/IMG_3074.jpg'
          }
        ]
      }
    },

    mounted () {
    }
  }
</script>

<style scoped>

#test {
  max-width: 100%;
  width: auto;
}
</style>
