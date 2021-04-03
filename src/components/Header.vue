<template>
  <div class="topnav">
  <a  href="">Scool</a>
  
  <div class="topnav-right">
    <a href="">Become a mentor</a>
    <a><button >JOIN US</button></a>
  </div>
  </div>
</template>

<script>
export default {
    name:'Header',
    
}
</script>

<style scoped>
.topnav {
    background-color: white;
    overflow: hidden;
}


.topnav a {
  float: left;
  color: black;
  text-align: center;
  padding: 0pt 16px;
  text-decoration: none;
  font-size: 17px;
}



.topnav-right {
  float: right;
}
</style>