<script setup>
import Button from '../components/Button.vue'
</script>

<template>
  <section class="body4">
    <h2>All platform connect to Findtrend</h2>
    <div class="body4-img">
        <img class="phone" src="../assets/image95.png"/>
        <img class="phone twitter" src="../assets/image96.png"/>
        <img class="phone" src="../assets/Rectangle6.png"/>
        <img class="phone" src="../assets/image97.png"/>
        <img class="desk" src="../assets/image113.png"/>
        <img class="desk" src="../assets/image114.png"/>
        <img class="desk" src="../assets/image115.png"/>
        <img class="desk" src="../assets/image112.png"/>
    </div>
    <div class="tweet-phone">
        <img src="../assets/tweet1m.png"/>
        <img src="../assets/tweet2m.png"/>
        <img src="../assets/tweet3m.png"/>
    </div>
    <div class="tweetdesk">
        <img src="../assets/tweet1.png"/>
        <img src="../assets/tweet2.png"/>
        <img src="../assets/tweet3.png"/>
    </div>
    <button class="body4-btn" button-text="View More Trend"/>
  </section>  
</template>

<style scoped>
.body4{
    background: #FAFAFA;
}
.body4 h2{
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: normal;
    padding-top: 80px;
    padding-bottom: 32px;
}

.desk{
    display: none;
}
.body4-img{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 16px;
    padding-bottom: 32px;
}
.mob{
    border-radius: 8px;
    background: #FFF;
    padding: 16.5px;
    
}
.twitter{
    background: #A8FF35;
}

.tweetdesk{
    display: none;
}

.tweet-phone{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 16px;
    padding: 0px 18px 32px 18px;
}
.body4-btn{
    color: #FFF;
    text-align: center;
    font-family: "Inter";
    font-size: 14px;
    font-style: normal;
    font-weight: 700;
    line-height: 140%;
    background: #000;
    padding: 16px 24px;
    margin: 0 auto;
    display: flex;
}
.body4{
    padding-bottom: 80px;
}
@media (min-width: 1024px){
    .mob, .tweet-phone {
        display: none;
    }
    .desk{
        display: block;
        border-radius: 8px;
        background: #FFF;
        padding: 20px;
    }
    .twitter{
    background: #A8FF35;
    }
    
    .body4 h2{
        font-weight: 700;
        font-size: 64px;
        padding-top: 140px;
        padding-bottom: 80px;
    }

    .body4-img{
        gap: 24px;
        padding-bottom: 77px;
    }

    .tweetdesk{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 40px;
    padding: 0px 320px 80px 320px;
    }
    .body4-btn{
        padding: 16px 32px;
        font-size: 18px;
    }
    .body4{
        padding-bottom: 140px;
    }

}
</style>