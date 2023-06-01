<script setup>
import HeaderView from "./components/Header.vue";
import HomeView from "./components/HomeView.vue";
import OnSale from "./components/OnSale.vue";
import NewaView from "./components/NewsView.vue";
import NewArrival from "./components/NewArrival.vue";
import FooterView from "./components/Footer.vue";
</script>

<template>
    <div class="wrap">
          <HeaderView />
          <HomeView />
          <OnSale />
          <NewaView />
          <NewArrival />
    </div>
    <FooterView />
</template>

<style scoped>
.wrap {
  width: 960px;
}

</style>
