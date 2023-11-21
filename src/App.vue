<script setup>
    import Header from "../src/components/Header.vue"
    import NavBar from "../src/components/NavBar.vue"
    import BodyComponent from "../src/components/BodyComponent.vue"
    import Footer from "../src/components/Footer.vue"
</script>

<template>
  <div id="container">
    <!-- HEADER -->
    <Header />
    <!-- MENU -->
    <NavBar />
    <!-- CONTENT & SIDEBAR -->
    <BodyComponent />
    
    <Footer />
  </div>
</template>

<style scoped>
    #container {
        width: 70%;
        margin: 0px auto;
    }
</style>
