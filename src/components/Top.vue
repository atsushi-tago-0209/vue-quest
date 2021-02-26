<template>
  <v-container>
    <input-form
      formRounded="xl"
      :formElevation="formElevation"
      @storeMovie="storeMovie"
      />
  </v-container>
</template>

<script>
  import InputForm from './InputForm.vue'

  export default {
    components: {
      InputForm,
    },
    data(){
      return {
        fomrElevation: "10",
      }
    },
    methods: {
      storeMovie(movieUrl,comment){
        console.log(movieUrl,comment)
      },
    },
  }
</script>