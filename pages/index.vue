<template>
  <div>
    <div id="main-body">
      <Navbar />
      <Welcome />
      <Synopsis />
      <NavTabs />
    </div>
    <div>
      <Footer />
    </div>
  </div>
</template>

<script>
import Synopsis from "~/components/Synopsis.vue";
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

<style>
/* Gives padding to the bottom of the document so text isnt forced 
   to the edge of the page
 */
#main-body {
  padding-bottom: 3em;
}
</style>
