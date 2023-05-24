<template>
  <section class="Hi2">
    <div class="wrapper">
      <h2 class="title">News</h2>
      <table class="menu-list">
        <tr>
          <th>・소식</th>
          <td>~~~~~</td>
        </tr>
        <tr>
          <th>・소식</th>
          <td>~~~~~</td>
        </tr>
        <tr>
          <th>・소식</th>
          <td>~~~~~</td>
        </tr>
        <tr>
          <th>・소식</th>
          <td>~~~~~</td>
        </tr>
        <tr>
          <th>・소식</th>
          <td>~~~~~</td>
        </tr>
        <tr>
          <th>・소식</th>
          <td>~~~~~</td>
        </tr>
        <tr>
          <th>・소식</th>
          <td>~~~~~</td>
        </tr>
        <tr>
          <th>・소식</th>
          <td>~~~~~</td>
        </tr>
        <tr>
          <th>・소식</th>
          <td>~~~~~</td>
        </tr>
      </table>
    </div>
  </section>
</template>

<script>
export default {
  name: "Hi_yeah"
}
</script>

<style scoped>
.title {
  font-family: 'Dancing Script', cursive;
  font-size: 7rem;
  margin-bottom: 2rem;
  color : #000000;
}
.Hi2 {
  background-image: url("@/assets/jess-bailey-Bg3qkPDpopY-unsplash.jpg");
  display: flex;
  align-items: center;
}
.wrapper {
  max-width: 900px;
  width: 100%;
  margin: 0 auto;
  padding: 0 1rem;
}
.menu-list tr {
  color:#000;
  font-size: 1.125rem;
  margin-bottom: .5rem;
  line-height: 1.7;
}
.menu-list th {
  font-weight: normal;
}
.menu-list td {
  padding-left: 2rem;
}
section {
  height: 100vh;
  scroll-snap-align: start;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
}
</style>