<template>
  <section class="contact">
    <h2 class="title">Contact</h2>
    <p>서울시 서초구 서운로 00-00</p>
    <p>영업시간 8:00〜20:00</p>

    <a class="btn" href="#">문의사항</a>

    <ul class="contact-sns">
      <li><a href="#"><i class="fab fa-facebook-square"></i></a></li>
      <li><a href="#"><i class="fab fa-twitter"></i></a></li>
      <li><a href="#"><i class="fab fa-instagram"></i></a></li>
    </ul>
  </section>
</template>

<script>
export default {
  name: "Infomration_list"
}
</script>

<style scoped>
section {
  height: 100vh;
  scroll-snap-align: start;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
}section {
   height: 100vh;
   scroll-snap-align: start;
   background-size: cover;
   background-repeat: no-repeat;
   background-position: center center;
 }
.contact {
  background-image: url("@/assets/unsplash.jpg");
  text-align: center;
  padding-top: 8vh;
}
.btn {
  background: #555;
  font-size: 1.5rem;
  color: #fff;
  padding: 1rem 3.5rem;
  border-radius: 6px;
  display: inline-block;
  margin: 2rem 0 2.25rem;
}
.btn:hover {
  background: #777;
}
.contact-sns {
  display: flex;
  justify-content: center;
}
.contact-sns a {
  background: #fff;
  width: 3.75rem;
  height: 3.75rem;
  display: inline-block;
  margin: 0 .5rem;
  border-radius: 50%;
  font-size: 2rem;
  padding: .75rem 0 0 .125rem;
  color: #555;
}
.contact-sns a:hover {
  background: rgba(255,255,255,.5);
}
</style>