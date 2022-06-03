<template>
  <header class="header">
     <div class="header__logo">
       <img src="../assets/img/img/dc-logo.png" alt="">
     </div>
     <nav class="header__nav">
       <ul class="header__list"> 
         <li><a href="#"></a>CHARACTERS</li>
         <li><a href="#"></a>COMICS</li>
         <li><a href="#"></a>MOVIES</li>
         <li><a href="#"></a>TV</li>
         <li><a href="#"></a>GAMES</li>
         <li><a href="#"></a>COLLECTIBLES</li>
         <li><a href="#"></a>VIDEOS</li>
         <li><a href="#"></a>FANS</li>
         <li><a href="#"></a>NEWS</li>
         <li><a href="#"></a>SHOP</li>
       </ul>
     </nav>
     
  </header>
</template>

<script>
export default {
name: 'baseHeader',
}
</script>

<style lang="scss" scoped>
.header {
    height: 20%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    &__list {
        display: flex;
        list-style: none;
        gap: .625rem;
        justify-content: center;
        color:grey;
        a{
           text-decoration: none;
           
        }
    }
}
</style>