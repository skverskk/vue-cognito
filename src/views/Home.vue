<template>
  <div class="home">
    <amplify-authenticator></amplify-authenticator>
    <amplify-sign-out></amplify-sign-out>
  </div>
</template>

<script>
// import { AmplifyEventBus } from '@aws-amplify/ui-vue';
export default {
  mounted() {
    console.log('Start Amplify Event Bus');
    // AmplifyEventBus.$on('authState', (info) => {
    //   console.log('auth', info);
    //   if (info === 'signedIn') {
    //     this.$router.push('about');
    //   }
    // });
  },
  name: 'home',
  components: {},
};
</script>
