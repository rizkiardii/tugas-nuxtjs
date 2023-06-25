<script>
export default {
  components: {},

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
    <div class="container">
      <h1>Input nilai mahasiswa</h1>
      <hr />

      <label>Nomor Induk Siswa</label>
      <b-form-input
        v-model="nomor"
        placeholder="Nomor Induk Siswa"
      ></b-form-input>

      <label>Nama Lengkap</label>
      <b-form-input v-model="nama" placeholder="Nama Lengkap"></b-form-input>

      <label>Nilai Tugas</label>
      <b-form-input v-model="nilai" placeholder="Nilai Tugas"></b-form-input>

      <div class="mt-2">NIS = {{ nomor }}</div>
      <div class="mt-2">Nama Lengkap = {{ nama }}</div>
      <div class="mt-2">Nilai = {{ nilai }}</div>
    </div>
  </div>
</template>

<style scoped></style>
