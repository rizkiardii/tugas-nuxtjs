<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import FormSiswa from "@/components/FormSiswa.vue";

export default {
  name: "IndexPage",
  components: {
    Header,
    Footer,
    FormSiswa,
  },

  data() {
    return {
      nomor: "",
      nama: "",
      nilai: "",
    };
  },
};
</script>

<template>
  <div>
    <Header />

    <main>
      <div class="container">
        <FormSiswa />
      </div>
    </main>

    <Footer />
  </div>
</template>

<style scoped></style>
