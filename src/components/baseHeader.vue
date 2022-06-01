<template>
  <header class="header">
     <div class="header__logo">
       <img src="../assets/img/img/dc-logo.png" alt="">
     </div>
     <nav class="header__nav">
       <ul class="header__list"> 
         <li><a href="#"></a>link</li>
         <li><a href="#"></a>link</li>
         <li><a href="#"></a>link</li>
         <li><a href="#"></a>link</li>
         <li><a href="#"></a>link</li>
         <li><a href="#"></a>link</li>
         <li><a href="#"></a>link</li>
         <li><a href="#"></a>link</li>
         <li><a href="#"></a>link</li>
         <li><a href="#"></a>link</li>
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