<script setup>

</script>

<template>
<div class="body1">
    <h2>Open new tabs is sh*t</h2>
    <img class="finismall" src="../assets/finimage.png"/>
    <img class="finibig" src="../assets/finibig.png"/>
    <p>A solution for your browser tabs and don’t make your device get slower over time. Get ease and faster to discover a trend with just one tab.</p>
</div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500;600;700;800;900&display=swap');
.finibig{
    display: none;
}

.body1{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 34px;
    background-color: #A8FF35;
}
.body1 h2{
    padding-top: 80px;
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 700;
    line-height: 112%;
}

.body1 p{
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
    padding: 0px 44px 80px 45px;
}

@media (min-width: 1024px){
    .finismall{
        display: none;
    }
    .finibig{
        display: block;
    }
    .body1{
        gap: 60px;
    }
    .body1 h2{
        font-size: 72px;
    }
    .body1 p{
        font-size: 18px;
        padding: 0px 387px 140px 387px;
    }
}


</style>
