<template>
  <section class="hi-i">
    <h1 class="title">❤Chaining❤</h1>
    <p>
      블록체인 기술과 함꼐하는 기부문화. <br>
      새로운 기술과 함께 행복한 시간을 만끽해보세요.
    </p>
  </section>
</template>

<script>
export default {
  name: "H-i",
};
</script>

<style scoped>
.title {
  font-family: 'Dancing Script', cursive;
  font-size: 7rem;
  margin-bottom: 2rem;
}
p {
  line-height: 1.7;
  font-size: 1.125rem;
}
.hi-i {
  background-image: url("@/assets/vecteezy_vector-illustration-for-charity-welfare-assistance-concept_6902005.jpg");
  text-align: center;
  padding-top: 10vh;
}
section {
  color : #DB005B;
  height: 100vh;
  scroll-snap-align: start;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
}
</style>