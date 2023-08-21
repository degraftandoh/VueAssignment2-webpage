<script setup>
import SocialCard from './SocialCard.vue';
import Button from './Button.vue'; 
import image1 from "../assets/image96.png";
import image2 from "../assets/image97.png";
import image3 from "../assets/image95.png";
import image4 from "../assets/Rectangle6.png";
</script>

<template>
   <section>
    <h2>Minimize your tabs.</h2>
    <h2>Find the trends!</h2>
    <p>Don’t let your computer memories consumes all of those browser tabs. 
        Findtrend  let you gathers all of your favorite website into one place.
    </p>
    <div class="txt-btn">
    <div>
    <Button class="button" buttonText="Get Started 🔥"/>
    </div>
    <img class="img-btn" src="../assets/img-hero.png"/>
    </div>
    <diV class="socials">
        <div>
        <diV >
        <SocialCard class="social1" :image="image1" socialText="Cryptopunk - Search"/>
        </diV>
        <div >
        <SocialCard class="social2"  :image="image2" socialText="Popular Design - Search"/>
        </div>
        </div>
        <div>
        <div >
        <SocialCard class="social3"  :image="image3" socialText="Product Design - Search"/>
        </div>
        <div >
        <SocialCard class="social4"  :image="image4" socialText="Elon Musk - Search"/>
        </div>
        </div>
    </div>
   </section>
</template>

<style scoped>
  .img-btn{
    display: none;
  }
   section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #000;
    padding-top: 56px;
   }

   section h2{
    color: #FFF;
    text-align: center;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: 112%;
   }
   section p{
    color: #8B8B8B;
    text-align: center;
    font-family: "Inter";
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
    padding: 16px 44px 32px 45px;
   }

   .button{
    background-color: #A8FF35;
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 14px;
    font-style: normal;
    font-weight: 700;
    line-height: 140%;
   }

   .socials{
    padding: 50px 0px;
    display: flex;
    flex-direction: column;

   }

   .social1{
    transform: rotate(-4deg);
    
   }
   .social2{
    transform: rotate(2deg);
    
   }
   .social3{
    transform: rotate(-2deg);
   }
   .social4{
    transform: rotate(4deg);
   }

   @media (min-width: 1024px){
    .button{
        padding: 16px 32px;
    }
    .img-btn{
        display: block;
    }
    section h2{
        font-size: 72px;
    }
    section p{
        font-size: 18px; 
        padding: 24px 387px 40px 387px;
    }
    .txt-btn{
        display: flex;
        gap: 5px;
    }
    .socials{
        flex-direction: row;
        padding: 100px 0px;
    }
  
   }
   .social1{
    padding-left: 100px;
   }
   .social2{
    padding-right: 100px;
   }
   .social3{
    padding-left: 150px;
   }
   .social4{
    padding-right: 100px;
   }

</style>