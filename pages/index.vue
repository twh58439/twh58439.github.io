<template>
  <div>
    <Header />
    <Welcome />
    <Footer />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Senior Googlers 4800 Project Page",
    };
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");

@font-face {
  font-family: "Product Sans";
  font-style: normal;
  font-weight: 400;
  src: local("Open Sans"), local("OpenSans"),
    url(https://fonts.gstatic.com/s/productsans/v5/HYvgU2fE2nRJvZ5JFAumwegdm0LZdjqr5-oayXSOefg.woff2)
      format("woff2");
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Product Sans", sans-serif;
}

p {
  font-family: "Roboto", sans-serif;
}
</style>
