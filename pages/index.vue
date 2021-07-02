<template>
  <div>
    <Navbar />
    <Welcome />
    <Synopsis />
  </div>
</template>

<script>
import Synopsis from '../components/Synopsis.vue';
export default {
  components: { Synopsis },
  // Meta information
  head() {
    return {
      title: "Senior Googlers 4800 Project Page",
    };
  },
};
</script>
