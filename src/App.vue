<script setup>
  import "@aws-amplify/ui-vue/styles.css";

  import { Amplify } from 'aws-amplify';
import outputs from '../amplify_outputs.json';

  Amplify.configure(outputs);
</script>

<template>


      <router-view />



</template>
