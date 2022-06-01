<template>
 <footer class="footer">
    <div class="footer__blue">
       <div class="footer__img">
           <img src="../assets/img/img/buy-comics-digital-comics.png" alt="">
       <span>digital comics</span>
       </div>
       <div class="footer__img">
          <img src="../assets/img/img/buy-comics-digital-comics.png" alt="">
          <span>digital comics</span>
       </div>
       <div class="footer__img">
           <img src="../assets/img/img/buy-comics-merchandise.png" alt="">
           <span>DC merchandise</span>
       </div>
       <div class="footer__img">
           <img src="../assets/img/img/buy-comics-subscriptions.png" alt="">
           <span>subscrtion</span>
       </div>
       <div class="footer__img">
          <img src="../assets/img/img/buy-comics-shop-locator.png" alt="">
          <span>shop locator</span>
       </div>
       
       <!-- <img src="../assets/img/img/buy-dc-power-visa.svg" alt="">
       <span>DC power visa</span> -->
    </div>
    <div class="footer__info">

    </div>
 </footer> 
</template>

<script>
export default {
   name : 'baseFooter',
}
</script>

<style lang="scss" scoped>
 .footer{
    
    
    &__blue{
       display: flex;
      padding: 20px 0;
      display: flex;
      background-color: #0282F9;
      align-items: center;
      gap: 20px;
      justify-content: space-around;
      
       
    }&__img{
       display: flex;
       align-items: center;
       justify-content: center;
       img{
           height: 3.125rem;
           width: 3.125rem;
       }
       span{
            margin-left: 10px;
            justify-content: center;
            color: white;
    }
      
    }
    
    &__info{
       background-color: yellow;
    }
   
 }
</style>