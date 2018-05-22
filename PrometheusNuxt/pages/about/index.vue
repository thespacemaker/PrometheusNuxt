
<template>
  <v-content>
    <section>
      <v-parallax src="/IMG_2904.jpg" height="600">
        <v-layout
        column
        align-center
        justify-center
        class="white--text"
        >
          <h1 class="white--text mb-2 display-1 text-xs-center">Our Philosophy</h1>
        </v-layout>
      </v-parallax>
    </section>

    <section>
      <v-flex xs12>
        <v-container grid-list-xl elevation-4 py-12 my-4>
          <br />
          <h2 class="text-xs-center">
          <v-icon x-large class="green--text text--darken-2">
            pan_tool
          </v-icon>
          </h2>
          <div class="headline text-xs-center">
            Hand-Made
          </div>
          <div class="subheading text-xs-center">
            Precision in manfuacturing is not the same as precision in a fiream.
          </div>
          <br />
          <br />
          <v-layout row wrap align-center pt-6>
            <v-flex xs12>
              <v-card class="white--text elevation-6">
            <v-container fluid grid-list-lg>
              <v-layout row>
                <v-flex xs7>
                  <div>
                    <br />
                    <br />
                    <v-card-text class="elevation-10 pb-2">
                      CNC and Machine-stamping can only operate within the scope of tolerances. To manufacture the most precise rifles in the world you have to have the human mind and hand behind the machine. <br /><br />
                      Everything we do at Prometheus Arms Co. is centered around creating the most accurate firing tools possible. Because of this, we never settle for less than hand-made.
                      <br />
                    </v-card-text>
                  </div>
                </v-flex>
                <v-flex>
                    <v-card-media
                      src="/IMG_3199.jpg"
                      height="200px"
                      contain
                      vertical-align

                    ></v-card-media>
                </v-flex>
              </v-layout>
            </v-container>
          </v-card>
<!--
              <v-card>
        <v-card-media
          class="white--text"
          height="300px"
          src="src/Assets/IMG_3199.jpg"
        >
        <v-container fill-height fluid>
            <v-layout fill-height>
              <v-flex xs12 align-end flexbox>
                <div class="white--text grey" id="shadow">
                  <span id="shadowwords">
                  <v-card-text shadowwords class="text-xs-center white--text py-4 elevation-4 shadowwords" id="shadowwords">
                    CNC and Machine-stamping can only operate within the scope of tolerances. To manufacture the most precise rifles in the world you have to have the human mind and hand behind the machine. <br /><br />
                    Everything we do at Prometheus Arms Co. is centered around creating the most accurate firing tools possible. Because of this, we never settle for less than hand-made.
                  </v-card-text>
                  </span>
                </div>
              </v-flex>
            </v-layout>
          </v-container>
        </v-card-media>
      </v-card>
    -->
      <br />
            </v-flex>
          </v-layout>
        </v-container>
      </v-flex>
    </section>

    <section>
      <v-parallax src="/IMG_2933.jpg" height="380">
        <v-layout column align-center justify-center>

        </v-layout>
      </v-parallax>
    </section>

    <section>
      <v-flex>
        <v-container grid-list-xl>
          <v-layout row align-center>
            <v-flex xs1></v-flex>
            <v-flex xs10>
              <v-card class="elevation-13 transparent">
                <div align="center">
                  <v-icon x-large class="green--text text--darken-2 pt-4">
                    add_circle_outline
                  </v-icon>
                </div>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">
                    Provability
                  </div>
                </v-card-title>
                <v-card-text class="text-xs-center pb-4">
                  Prometheus Arms Co. has a proven track record of precision. All of our firearms undergo a rigorous quality control, inspection and testing. Every one of our precision bolt-action rifles are delivered with a proof target group.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs1></v-flex>
          </v-layout>
        </v-container>
      </v-flex>
    </section>
  </v-content>
</template>

<script>
    export default {

      data () {
        return {}
      },

      mounted () {

      }
    }
</script>

<style>
#shadow {
  opacity: 0.7;
}

#shadowwords {
    color: white;
    opacity: 1.0;
}
#vert {
  vertical-align: -25px;
}
</style>
