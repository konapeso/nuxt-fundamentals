<template>
  <div class="container">
    <TheNavbar/>
    <nuxt/>
  </div>
</template>

<script>
import TheNabvar from "@/components/TheNavbar";
export default {
  components: {
    TheNavbar
  }
};
</script>

<style>
.button--green {
  display: inline-block;
}
</style>
