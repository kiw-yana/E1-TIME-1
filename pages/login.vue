<template>
  <v-row
    align="center"
    justify="center"
  >
    <v-col cols="12">
      <v-hover
        v-slot:default="{ hover }"
        disabled
      >
        <v-card
          :elevation="hover ? 12 : 2"
          class="mx-auto"
          height="300"
          max-width="350"
          color="#33FF99"
        >
           <v-card-title>
       <h1>Login</h1>
     </v-card-title>
     <v-card-text>
       <v-form>
         <v-text-field label="Username" prepend-icon="mdi-account-circle" />
         <v-text-field 
            :type="showPassword ? 'text' : 'password'" 
            label="Password"
            color="red"
            prepend-icon="mdi-lock"
            :append-icon="showPassword ? 'mdi-eye' : 'mdi-eye-off'"
            @click:append="showPassword = !showPassword"
          />
         <v-card-actions>
         <nuxt-link to="/register"><v-btn @click="doRegister" color="Light blue" dark large>REGISTER</v-btn></nuxt-link >
          <v-spacer></v-spacer>
         <v-btn @click="doLogin" color="orange" dark large>LOGIN</v-btn>
         </v-card-actions>
       </v-form>
     </v-card-text>
        </v-card>
      </v-hover>
    </v-col>
  </v-row>
</template>
<script>
export default {
  name: 'App',
  data () {
    return {
      showPassword: false
    }
  }
}
</script>