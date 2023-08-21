<script setup>
import Button from './Button.vue'
</script>

<template>
    <div class="nav-bar">
        <img class="logoPhone" src="../assets/llogo.svg"/>
        <img class="IconMenu" src="../assets/menu.svg"/>
        <div class="desk-nav-bar">
            <img src="../assets/Logo.svg"/>
            <ul>
                <li>About</li>
                <li>How it work</li>
                <li>Pricing</li>
                <li>Solution</li>
                <li>Features</li>
            </ul>
            <div class="btn-nav">
                <p>Login</p>
                <Button buttonText="Register" />
            </div>
        </div>
    </div>
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap');

    .desk-nav-bar{
        display: none;
    }
    .nav-bar{
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: #000000;
        padding: 24px 7%;
    }

@media (min-width: 1024px) {
    .logoPhone, .IconMenu{
        display: none;
    }

    .nav-bar{
        display: block;
        padding: 28px 0px;

    }

    .desk-nav-bar{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    ul{
        display: flex;
        color: #FFF;
        font-family: "Inter";
        font-size: 18px;
        font-style: normal;
        font-weight: 400;
        line-height: 100%;
        gap: 40px;
    }
    ul li{
        list-style: none;
    }

    .btn-nav{
        display: flex;
        gap: 40px;
        align-items: center;
    }
    .btn-nav p{
        color: #FFF;
        text-align: center;
        font-family: "Inter";
        font-size: 18px;
        font-style: normal;
        font-weight: 400;
        line-height: 100%;
    }
}
</style>
