<!--ส่วนสำหรับการแสดงผล-->
<template>
<div>
   <ul>
    <li><a href="#home">🏠Home</a></li>
    <li><a href="mycard">❤️My Card</a></li>
    <li><a href="about">😻About</a></li>
</ul>
</div>

</template>
<!--สำหรับเขียน java script เพื่อควบคุมการทำงานของ Component
เช่น การกำหนด data,methode เป็นต้น-->
<script>
export default {
}
</script>
<!--ส่วนสำหรับเขียน css เพื่อตกแต่ง template-->
<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #8a7fc7;
}

li {
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

/* change the link color to #111 (black) on hovwr */
li a:hover {
    background-color: #111;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
body{
  height: 100vh;
  display: flex;
  align-items: left;
  justify-content: center;
  background: #c1f7f5;
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
}
.nav-links{
  display: flex;
  align-items: center;
  background: #fff;
  padding: 20px 15px;
  border-radius: 12px;
  box-shadow: 0 5px 10px rgba(0,0,0,0.2);
}
</style>
