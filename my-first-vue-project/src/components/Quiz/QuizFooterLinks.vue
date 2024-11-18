<template>
  <div>
    <h5>{{ state.name }}</h5>

    <button @click="state.name = 'A New Quiz Name'">Change Quiz Name</button>

    <ul><a href="#">Get a Job</a></ul>
    <ul><a href="#">Contact Us</a></ul>
  </div>
</template>

<script setup>
import { state } from '@/stores/quizStore';
</script>
