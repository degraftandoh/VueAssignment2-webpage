<script setup>
import FourthSection from './components/FourthSection.vue'
import ThirdSection from './components/ThirdSection.vue';
import SecondSection from './components/SecondSection.vue';
import Navbar from './components/NavBar.vue';
import Hero from './components/Hero.vue';
import FooterComponent from './components/FooterComponent.vue';
import JoinComponent from './components/JoinComponent.vue';
import DealCard from './components/DealCard.vue';

</script>

<template>
  <div>
    <section class="body">
      <nav>
        <Navbar />
      </nav>
      <Hero />
    </section>
    <SecondSection />
    <ThirdSection/>
    <FourthSection />
    <DealCard />
    <JoinComponent />
    <FooterComponent />
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500;600;700;800;900&display=swap");
.body {
  background-color: black;
}

 @media (min-width: 1024px) {
  nav {
    padding: 0px 7%;
  }
} 

</style>
