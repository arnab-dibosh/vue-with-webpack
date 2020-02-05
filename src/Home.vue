<template>
  <div>
    <app-service v-for="i in 5" :key="i" ></app-service>
  </div>
</template>

<script>
import AppService from './AppService.vue';

  export default{
    components:{
      'app-service': AppService
    }

  }
</script>
