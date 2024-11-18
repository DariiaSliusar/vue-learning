<script setup>
import QuizFooter from './QuizFooter.vue';
import QuizHeader from './QuizHeader.vue';
import QuizQuestion from './QuizQuestion.vue';
import { state } from '@/stores/quizStore';

</script>

<template>
  <QuizHeader />

  <QuizQuestion />

  <QuizFooter />
</template>
