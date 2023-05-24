<template>
  <p><a href="#">로그인</a></p>
    <header class="Header_list">
      <div id="logo">
        <a href="index-footer.html">
          <h1>intro.</h1>
        </a>
      </div>
      <nav>
        <ul id="topMenu">
          <li><a href="#">단체 기부</a></li>
          <li><a href="#">맞춤 추천</a></li>
          <li><a href="#">갤러리</a></li>
          <li><a href="#">문의하기</a></li>
        </ul>
      </nav>
    </header>
</template>

<script>
export default {
  name: 'Header_list',
  props: {
    msg: String
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  scroll-snap-align: start;
  margin:0;   /* 마진 리셋 */
  padding:0;   /* 패딩 리셋 */
  box-sizing: border-box;   /* 박스 영역은 테두리까지 */
}
a {
  text-decoration:none;  /* 텍스트 링크 밑줄 없애기 */
}
ul {
  list-style: none;
}
p {
  text-align: right;
  padding-right: 20px;
  padding-top: 20px;
  font-family: 'Dancing Script', cursive;
  font-weight:700;
  font-size:20px;   /* 글자 크기 */
  color:#ECC9EE;   /* 글자 색*/
  text-shadow:0 -1px 0 #222;  /* 그림자 색 */
  font-family: sans-serif;
}
p > a:hover {
  color:#1fa8f8;
  text-shadow:0 -2px #222;
}
#container {
  margin:0 auto;  /* 화면 중앙에 배치 */
  width:1200px;    /* 너비 */
  background-color: #fff;
}
header{
  width:100%;    /*  너비 */
  height:100px;   /* 높이 */
  background-color:#AA3F39;
}
/* 로고 */
#logo{
  float:left;   /* 왼쪽으로 플로팅 */
  width:300px;   /*  너비 */
  height:100px;   /* 높이 */
  line-height:100px;  /* 세로로 중간에 맞춤 - 줄간격을 높이 값과 같게 */
  padding-left:20px;  /* 왼쪽에 여백 */
}
#logo h1 {
  font-family:'Merienda', cursive;
  font-weight:700;
  font-size:40px;   /* 글자 크기 */
  color:#fff;   /* 글자 색*/
  text-shadow:0 -1px 0 #222;  /* 그림자 색 */
}
nav{
  float:right;   /* 오른쪽으로 플로팅 */
  width:900px;   /*   너비 */
  height:100px;   /* 메뉴 영역 높이 */
  padding-top:40px;  /* 메뉴를 아래로 내리기 위해 */
}

#topMenu {
  height:60px;
}
#topMenu > li {
  float:left;  /* 메뉴 항목을 왼쪽으로 플로팅 */
  position: relative;
}
#topMenu > li > a{
  display:block;  /* 링크 텍스트는 블록으로 */
  font-size:1.1em;
  color:#fff;  /* 글자 색 */
  font-weight:600;  /* 글자 굵기 */
  padding:20px 60px;  /* 패딩 */
}
#topMenu > li > a:hover {
  color:#1fa8f8;
  text-shadow:0 -2px #222;
}
</style>
