<template>
  <div class="light">
    <Header />
    <main id="main">
      <section id="youtubeCont">
        <div class="container">
          <div class="wrap__title">
            <WrapTitle name1="YOUTUBE" name2="REFERENCE" />
          </div>
          <div class="youtube__cont">
            <div class="youtube"></div>
          </div>
        </div>
      </section>
      <ContInfo />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import WrapTitle from "@/components/WrapTitle.vue";
import ContInfo from "../components/ContInfo.vue";

export default {
  components: {
    Header,
    Footer,
    WrapTitle,
    ContInfo,
  },
};
</script>

<style lang="scss">
#youtubeCont {
  background-color: #000;
  color: #fff;
}
</style>
