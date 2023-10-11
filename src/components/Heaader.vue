
 <script>
 export default {
    
 }
 </script>


<template>
   <header id="header">
    <div class="container">

      <div class="menu selection">
        <ul class="menu">
          <li>Donna</li>
          <li>Uomo</li>
          <li>Bambini</li>
        </ul>
      </div>

      <div class="divlogo">
        <img src="img/boolean-logo.png" alt="" class="logo">
      </div>

      <div class="menu icon">
        <ul class="menu">
          <li><i class="fa-regular fa-user"></i></li>
          <li><i class="fa-regular fa-heart"></i></li>
          <li><i class="fa-solid fa-bag-shopping"></i></li>
        </ul>
      </div>

    </div>
  </header>
</template>

<style lang="scss" scoped>

    header{
    height: 70px;
    background-color: #FF6900;
    align-items: center;
    justify-content: center;
    display: flex;
          .container{
        display: flex;
        align-items: center;
        justify-content: space-around;
        height: 80px;
        width: 80%;
        max-width: 1800px;
      }
  }
.menu{
  list-style: none;
  display: flex;
  font-size: small;
  font-weight: 800;
  font-family: Arial, Helvetica, sans-serif;
  &:hover{
    cursor: pointer;
  }
}


.divlogo{ 
  padding: 20px;
  height: 65px;
  width: 100px;
}

</style>