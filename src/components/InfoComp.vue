<template>
<div class="info"> 
    <div class="info-container">
        <ul>
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </li>            
            <li>
               <img src="../assets/img/buy-comics-merchandise.png" alt=""> 
               <p>DC MERCHANDISE</p>
            </li>
            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>BUY COMICS SUBSCRIPTION</p>
            </li>
            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>COMIC SHOP LOCATOR</p>
            </li>
            <li>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p>DC POWER VISA</p>
            </li>
        </ul>
    </div>
</div>  
</template>

<script>
export default {
  name: 'InfoComp',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
    .info{
        background-color: rgba(2,130,249,255);
        color: white;
        display: flex;
        align-items: center;
        justify-content: center;
        /* TO ELIMINATE */
        height: 15vh;
    }
    .info-container{
        display: flex;    
        justify-content: center;
        // align-items: center;
        // height: 10vh;
        // width: 80%;
        // margin: 0 auto;        
        // background-color: red;
    }
    ul{
        list-style-type: none;
        display: flex;        
        flex-direction: row;  
        justify-content: space-between;      

        li{      
            font-size: 15px;
            display: flex;    
            align-items: center;
            margin: 15px;

            p{
                margin: 10px;
                padding-right: 50px;
            }
        }
    }
    img{
        max-height: 60px;        
    }
    
</style>