<template>
    <div>
  <b-card no-body>
    <b-tabs card>
      <b-tab title="signUp" active> <SignUp/></b-tab>
      <b-tab title="signIn"> <SignIn/></b-tab>
    </b-tabs>
  </b-card>
</div>
</template>

<script>
import SignUp from './SignUp.vue'
import SignIn from './SignIn.vue'
export default {
  name: 'FormHandler',
  components:{
      SignUp,
      SignIn,
  },
  props: {
    msg: String
  }
}
</script>