<template>
  <div id="app">
    <Header></Header>
    <div class="wrapper">
      <transition name="fade">
        <router-view></router-view>
      </transition>
    </div>
    <Footer></Footer>
  </div>

</template>

<script>
    import Header from "../layout/Header.vue";
    import Footer from "../layout/Footer.vue";
    export default {
        name: 'AppLayout',
        components: {
            Header,
            Footer
        }
    }
</script>

