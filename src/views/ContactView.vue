<template>
  <HeaderCont />
  <main id="main">
    <section class="contact__cont">
      <div class="contact__inner"></div>
    </section>
  </main>
  <FooterCont />
</template>

<script>
import HeaderCont from "@/components/HeaderCont.vue";
import FooterCont from "@/components/FooterCont.vue";

export default {
  components: {
    HeaderCont,
    FooterCont,
  },
};
</script>

<style lang="scss" scoped></style>
