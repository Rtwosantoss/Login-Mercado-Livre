<script setup>
import Footer from "./components/FooterComponents.vue";

</script>

<template>

<div class="flex flex-col min-h-screen bg-gray-100">
   <div class="main container mx-auto px-4 py-6">
      <router-view> </router-view>
    </div>

    <Footer />
</div>

</template>
