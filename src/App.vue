<script setup lang="ts">
import NavbarVue from './components/Navbar.vue';
import HeaderVue from './components/Header.vue';
import StakeVue from './components/Stake.vue';
import BalanceVue from './components/Balance.vue';
import FooterVue from './components/Footer.vue';
</script>

<template>
  <header>
    <!-- <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->

    <!-- <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div> -->
    <NavbarVue />
    <HeaderVue />
    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-2">
      <StakeVue />
      <StakeVue />
      <StakeVue />
      <StakeVue />
      <StakeVue />
      <StakeVue />
    </div>
    <BalanceVue />
    <FooterVue />
  </header>
</template>