<template>
  <div>
    <b-nav tabs>
      <b-nav-item disabled><b> fancy Quiz App </b></b-nav-item>
      <b-nav-item disabled>
        Counter: {{ numCorrect }} / {{ numTotal }}</b-nav-item
      >
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ['numCorrect', 'numTotal'],
};
//console.log(numCorrect);
</script>

<style scoped></style>
