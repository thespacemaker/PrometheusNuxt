<template>
  <v-content>
      <v-parallax src="/hero.jpeg" height="600">
        <v-layout
        column
        align-center
        justify-center
        class="white--text"
        >
          <img src="/logo.png" alt="Vuetify.js" height="200">
            <h1 class="white--text mb-2 display-1 text-xs-center">Prometheus Arms</h1>
            <div class="subheading mb-3 text-xs-center">Fire - With Precision</div>
          <v-btn
            class="green darken-2"
            dark
            large
            href=#test
          >
              Learn More
          </v-btn>
        </v-layout>
      </v-parallax>
    <section id="test">
      <v-layout
      column
      wrap
      class="my-5"
      align-center
      >
      <v-flex xs12>
        <v-container grid-list-xl>
          <v-layout row wrap align-center>
            <v-flex xs12 md4>
              <v-card class="elevation-13 transparent pt-2">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="green--text text--darken-2">pan_tool</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-xs-center">Hand-made</div>
                </v-card-title>
                <v-card-text class="text-xs-center">
                  All our manufacturing processes are done by hand. We believe that there is no substitute for human intuition and experience. Everything we build at Prometheus Arms Co. is hand-fitted for the highest level of precision. Hand-Made weapons are all we do.<br />This will never change
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card class="elevation-13 transparent pb-3 pt-2">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="green--text text--darken-2">edit</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Custom</div>
                </v-card-title>
                <v-card-text class="text-xs-center">
                  We manufacture premium, custom, precision bolt-action rifles as well as custom fit, semi-automatic rifles and hand-guns. With Prometheus Arms Co. you can have your gun made the way you want it, from start to finish.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card class="elevation-13 transparent pb-5 pt-2">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="green--text text--darken-2">build</v-icon>
                </v-card-text class="text-xs-center">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-xs-center">Made in Texas</div>
                </v-card-title>
                <v-card-text class="text-xs-center">
                  All of our firearms are manufactured right in the heart of the Lone-Star State. Our pride in Texas is strong and we are equally as proud to manfuacture all our firearms in the state of Texas.
                </v-card-text>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </v-flex>
      <v-flex xs12 pt-4>
        <v-btn
          class="green darken-2 text-xs-center"
          dark
          large
          to=about
        >
          About Our Philosphy
        </v-btn>
      </v-flex>
    </v-layout>
  </section>

    <section>
      <v-parallax src="/IMG_2933.jpg" height="300">
        <v-layout column align-center justify-center>
          <div class="display-1 white--text mb-3 text-xs-center">Your Custom Gun</div>
          <p>has never been closer</p>
          <br />
          <v-btn
            class="green darken-2"
            dark
            large
            to=gallery
            >
              View Our Firearms
          </v-btn>
        </v-layout>
      </v-parallax>
    </section>

    <section>
      <div class="py-3">
      </div>
      <v-container grid-list-xl>
        <v-layout row wrap justify-center class="my-5">
          <v-flex xs12 sm4>
            <v-card class="elevation-13 transparent text-xs-center pb-4">
              <v-card-title primary-title class="layout justify-center">
                <div class="headline">Company info</div>
              </v-card-title>
              <v-card-text class='text-xs-center'>
                Prometheus Arms Co. is a precision rifle manufacturer located in DFW, Texas. We hold both an FFL-7 and SOT-2 license. We specialize in custom precision bolt-action rifles as well as custom fit pistols a semi-automatic weapons. Our tools are trusted and used by local law enforcement, Armed Forces, and competitive shooters.
              </v-card-text>
                <v-btn
                    outline color="green"
                    class="mt-1 green"
                    medium
                    to=about
                 >
                  Learn More
                </v-btn>
              </v-card>
            </v-flex>
            <v-flex xs12 sm4>
              <v-card class="elevation-0 transparent text-xs-center pb-4 px-4">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Buy Online</div>
                </v-card-title>
                <v-card-text class="text-xs-center pb-4">
                  Our firearms are available for retail online at the distributors below! Contact us for custom jobs!
                </v-card-text>
                <a href="https://dsgarms.com/prometheus-arms" target="_blank">
                <v-card-media
                  class="white--text"
                  height="60px"
                  src="/dsg.png"
                  >
                </v-card-media>
                </a>
                <br />
                <a href="https://www.marksmenfirearms.com/locations/mansfield/" target="_blank">
                <v-card-media
                  class="white--text"
                  height="60px"
                  src="/Marksmen-logo.png"
                  >
                </v-card-media>
                </a>
                <br />
                <br />
                  <v-btn
                      outline color="green"
                      class="mt-1 green"
                      medium
                      href="https://dsgarms.com/prometheus-arms"
                      target="_blank"
                   >
                    Order Online!
                  </v-btn>
                </v-card>
              </v-flex>
            <v-flex xs12 sm4>
              <v-card class="elevation-13 transparent pb-4">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Contact us</div>
                </v-card-title>
                <v-card-text>
                  Feel free to email or call us to schedule a visit.
                </v-card-text>
                <v-list class="transparent">
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="green--text text--darken-2">phone</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>
                        <a href="tel:2147238755" class="white--text">214 723 8755</a>
                        </v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="green--text text--darken-2">place</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>DFW, TX, US</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="green--text text--darken-2">email</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>
                        <a  class="white--text"href="mailto:prometheusarmsco@gmail.com">prometheusarmsco@gmail.com</a>
                    </v-list-tile-title>
                  </v-list-tile-content>
                </v-list-tile>
              </v-list>
            </v-card>
          </v-flex>
        </v-layout>
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
<!--
                     <v-container fluid v-bind="{ [`grid-list-${size}`]: true }">
                       <v-layout row pt-4>
                         <v-flex xs4>
                           <v-card flat tile>
                             <v-card-media
                               height="150px"
                             >
                              <lightbox
                                thumbnail="/testimony/thumb1.JPG"
                                :images="['/testimony/IMG_1063.JPG', '/testimony/IMG_1066.JPG', '/testimony/IMG_1064.JPG']"
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
                                thumbnail="/thumb2.jpg"
                                :images="['/testimony/IMG_1063.JPG', '~/static/testimony/FullSizeRender2.jpg']"
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
                             :images="['/testimony/IMG_1063.JPG', 'src/assets/testimony/FullSizeRender2.jpg']"
                             ></lightbox>
                             </v-card-media>
                           </v-card>
                         </v-flex>
                       </v-layout>
                     </v-container> -->
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
            src: '/testimony/IMG_1063.JPG'
          },
          {
            src: '/testimony/IMG_1063.JPG'
          },
          {
            src: '/testimony/IMG_1063.JPG'
          },
          {
            src: '/testimony/IMG_1063.JPG'
          }
        ]
      }
    },

    mounted () {
    }
  }
</script>
<script>
  export default {
    data: () => ({
      size: 'sm',
      items: [
        { text: 'Extra small (2px)', value: 'xs' },
        { text: 'Small (4px)', value: 'sm' },
        { text: 'Medium (8px)', value: 'md' },
        { text: 'Large (16px)', value: 'lg' },
        { text: 'Extra large (24px)', value: 'xl' }
      ]
    })
  }
</script>

<style scoped>

</style>
