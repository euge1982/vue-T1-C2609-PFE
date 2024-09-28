<!-- Principal -->

<script setup lang="ts">
import LoginForm from '../components/LoginForm.vue';

//Se define el objeto form que cumple con la interfaz Form
const form = {
  user: '',
  password: '',
  remember: false,
};
</script>

<template>
  <div id="app">
    <!-- Se le pasa el objeto form al componente LoginForm -->
    <LoginForm :form="form" />
  </div>
</template>