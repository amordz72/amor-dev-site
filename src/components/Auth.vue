<template>
  <div class="">
 <!-- Modal toggle -->
 
 







  </div>
</template>

<script>
export default {
  methods: {
    tgl() {
      document.getElementById("exampleModal").classList.toggle("hidden");
    },
  },
};
</script>

<style scoped>
 #i-tgl:checked + #exampleModal {
  display: flow ;
} /**/
</style>