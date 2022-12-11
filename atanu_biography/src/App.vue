<script setup>
import HeaderPage from './components/HeaderPage.vue'
import HomePage from './components/HomePage.vue'
</script>

<template>

  
  <header>
    
    <img alt="Atanu's Profile Picture" class="logo" src="./assets/profile.jpeg" width="150" height="150" />

    <div class="wrapper">
      <HeaderPage msg="HELLO, I'M ATANU" />
    </div>
  </header>

  <main>
    <HomePage />
  </main>
</template>
<script>

</script>
<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
  border-radius: 9999px;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
    border-radius: 9999px;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  
}



</style>
