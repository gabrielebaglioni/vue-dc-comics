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
    display: flex;
    justify-content: space-around;
    &__list{
       display: flex;
        list-style: none;
    }
}
</style>