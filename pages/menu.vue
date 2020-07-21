<template>
  <v-container fluid class="pa-0">
    <v-row align="center">
      <v-col cols="12" sm="6">
        <div class="text-center">
          <div class="my-2">
            <nuxt-link to="/activity/line"><v-btn color="secondary" dark>กิจกรรมเข้าเเถว</v-btn> </nuxt-link>
          </div>
          <div class="my-2">
            <nuxt-link to="/activity/homeroom"><v-btn  color="primary" dark>กิจกรรมโฮมรูม</v-btn></nuxt-link>
          </div>
          <div class="my-2">
            <nuxt-link to="/activity/special"><v-btn color="warning" dark>กิจกรรมพิเศษ</v-btn></nuxt-link>
          </div>
          <div class="my-2">
            <nuxt-link to="/activity/profession"><v-btn color="error" dark large>กิจกรรมวิชาชีพ</v-btn></nuxt-link>
          </div>
          <nuxt-link to="/"><v-btn color="success" dark large>กลับสู่หน้าหลัก</v-btn></nuxt-link>
          </div>
            
        </div>
      </v-col>
      <v-col cols="12" sm="6">
        <div class="text-center">
          <div class="my-2">
            <v-btn color="secondary" fab x-small dark>
              <v-icon>mdi-television</v-icon>
            </v-btn>
          </div>
          <div class="my-2">
            <v-btn color="primary" fab small dark>
              <v-icon>mdi-pencil</v-icon>
            </v-btn>
          </div>
          <div class="my-2">
            <v-btn color="warning" fab dark>
              <v-icon>mdi-account-circle</v-icon>
            </v-btn>
          </div>
          <div class="my-2">
            <v-btn color="error" fab large dark>
              <v-icon>mdi-alarm</v-icon>
            </v-btn>
          </div>
          <div class="my-2">
            <v-btn color="success" fab x-large dark>
              <v-icon>mdi-domain</v-icon>
            </v-btn>
          </div>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>