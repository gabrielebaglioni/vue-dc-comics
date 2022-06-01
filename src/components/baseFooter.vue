<template>
 <footer class="footer">
    <div class="footer__blue">
       <img src="../assets/img/img/buy-comics-digital-comics.png" alt="">
       <span>digital comics</span>
       <img src="../assets/img/img/buy-comics-merchandise.png" alt="">
       <span>DC merchandise</span>
       <img src="../assets/img/img/buy-comics-subscriptions.png" alt="">
       <span>subscrtion</span>
       <img src="../assets/img/img/buy-comics-shop-locator.png" alt="">
       <span>shop locator</span>
       <!-- <img src="../assets/img/img/buy-dc-power-visa.svg" alt="">
       <span>DC power visa</span> -->

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
    height: auto;
    display: flex;
    background-color: #0282F9;
    justify-content: space-around;
    align-items: center;
    &__blue{
       padding: 20px;
       
    }img{
       height: 3.125rem;
       width: 3.125rem;
    }
    span{
       margin-left:.475rem ;
       justify-content: center;
       color: white;
    }
   
 }
</style>