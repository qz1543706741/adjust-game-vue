<template>
  <div></div>
</template>

<script>
  import card from '@/components/card';

  export default {
    data() {
      return {
        motto: 'Hello miniprograme',
        userInfo: {
          nickName: 'mpvue',
          avatarUrl: 'http://mpvue.com/assets/logo.png'
        }
      };
    },

    components: {
      card
    },

    methods: {
      upload() {}
    },

    created() {
      // let app = getApp()
    }
  };
</script>

<style scoped></style>
