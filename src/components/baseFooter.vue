<template>
 <footer class="footer">
    <div class="footer__container">
      <div class="footer__container-blue">
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
         </div>
       </div>
       <!-- <img src="../assets/img/img/buy-dc-power-visa.svg" alt="">
       <span>DC power visa</span> -->
    </div>
    <div class="footer__container-DC">
         <div class="footer__info footer__social">
            <div class="footer__info-list">
              
            </div>
            <div class="footer__info-logo">
               <img src="../assets/img/img/dc-logo-bg.png" alt="">
            </div>

         </div>
    </div> 
    <div class="footer__container-social">
         <div class="footer__social">

         </div>
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
    &__container{
       background-color: #0282F9;
    }
   
    &__blue{
       
      display: flex;
      padding: 20px 0;
      display: flex;
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
    
    &__container-DC{
       height:26.25rem ;
       background-image: url(../assets/img/img/footer-bg.jpg);
       
    }
    &__info{
        display: flex;
        justify-content: space-between;
        
    }
    &__info-logo{
       height: 100%;
       
       
      img{
         height: 100%;
        object-fit:contain;
      }
    }
    &__container-social{
       height: 7.4rem;
       background-color: #303030;
    }
   
 }
</style>