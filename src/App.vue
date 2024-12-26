<template>
  <v-app>
    <v-container
      class="d-flex justify-center align-center h-screen"
    >
      <v-card
        min-width="768"
        max-width="1024"
      >
        <v-row class="ma-0 pa-0">
          <v-col
            cols="6"
            class="bg-primary d-flex flex-column justify-center align-center"
          >
            <v-img
              src="https://yt3.googleusercontent.com/8GxrbZ86xLMxqlUR_V1YwuOU7l7wRkLb590OOjgnbr6A0YgEA0zkoYb0yqAwchwxC5JcXhDH=s900-c-k-c0x00ffffff-no-rj"
              :width="300"
              cover
            />
            <h1 class="text-center">
              NatchaLatte Official
            </h1>
          </v-col>
          <v-col
            cols="6"
            class="d-flex flex-column justify-center align-center"
          >
            <div>
              <div>
                <h2>NatchaLatte</h2>
                <p>Owner, NatchaLatte Official Channel</p>
              </div>

              <div class="d-flex pt-4">
                <v-icon class="mr-2">
                  mdi-youtube
                </v-icon>
                <p>NatchaLatte Official</p>
              </div>

              <div class="d-flex pt-4">
                <v-icon class="mr-2">
                  mdi-email
                </v-icon>
                <p>foxteary@gmail.com</p>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-card>
    </v-container>
  </v-app>
</template>