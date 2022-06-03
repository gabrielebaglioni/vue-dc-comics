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
            <div class="footer__img">
               <img src="../assets/img/img/buy-dc-power-visa.svg" alt="">
               <span>DC power visa</span>
            </div>
         </div>
       </div>
       
    </div>
   <div class="footer__container-DC">
      <div class="footer__container-list">
         <div class="footer__info">
               <div class="col">
                  <h3><strong>dc Comics</strong></h3>
                  <ul>
                     <li><a href="#">characters</a></li>
                     <li><a href="#">comics</a></li>
                     <li><a href="#">movies</a></li>
                     <li><a href="#">tv</a></li>
                     <li><a href="#">games</a></li>
                     <li><a href="#">videos</a></li>
                     <li><a href="#">news</a></li>
                  </ul>
                  <h3><strong>shop</strong></h3>
                  <ul>
                     <li><a href="#">shop DC</a></li>
                     <li><a href="#">shop DC collectibles</a></li>
                  </ul>
            </div>
            <div class="col">
               <h3><strong>DC</strong></h3>
               <ul>
                  <li><a href="#">terms of use</a></li>
                  <li><a href="#">privacy policy (New)</a></li>
                  <li><a href="#">ad choices</a></li>
                  <li><a href="#">advertising</a></li>
                  <li><a href="#">jobs</a></li>
                  <li><a href="#">subscriptions</a></li>
                  <li><a href="#">talent workshop</a></li>
                  <li><a href="#">cpsp certificates</a></li>
                  <li><a href="#">ratings</a></li>
                  <li><a href="#">shop help</a></li>
                  <li><a href="#">contact us</a></li>
               </ul>
            </div>
               <div class="footer__col">
                  <h3><strong>sites</strong></h3>
                  <ul>
                     <li><a href="#">DC</a></li>
                     <li><a href="#">MAD magazine</a></li>
                     <li><a href="#">DC kids</a></li>
                     <li><a href="#">DC universe</a></li>
                     <li><a href="#">DC power visa</a></li>
                  </ul>
               </div>
         </div>
      </div>
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
               <button>Sing-up Now</button>
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
      height: 9.5rem; 
      display: flex;
      padding: 50px 0;
      align-items: center;
      gap: 20px;
      justify-content: space-around;
      
       
    }&__img{
       display: flex;
       align-items: center;
       justify-content: center;
       
       img{
         height: 40px;
         width: 40px;
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
       overflow: hidden;
       position: relative;
       
    }
    &__info{
         display: flex;
        justify-content: space-between;
        
    }
    &__info-logo{
       height: 100%;
       
       
      img{
         height: 100%;
        position: relative;
        bottom: 50px;
        left: 150px;
      }
    }
    &__container-social{
       height: 7.4rem;
       background-color: #303030;
       padding: 20px;
       display: flex;
       align-items: center;
       justify-content: center;
       justify-content: space-between;
       
       button{
          padding: .625rem;
          text-transform: uppercase;
          cursor: pointer;
          background-color: transparent;
          border: 1px solid #0082F9;
          color: white;
       }
       button:hover{
          background-color: #0082F9;
          transition: 1ms;
       }

    }
    &__container-list{
       position: absolute;
       left: 250px;
       top: 100px;
       strong{
          color: white;
       }
       li{
          list-style: none;
       }
       a{
          text-decoration: none;
          color: grey;
       }
       
    }
     &__col{
          padding-right: 60px;
       }
       

 }
</style>