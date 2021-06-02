<template>
  <div>
    <div id="scroll-progress">
      <div class="scroll-progress"><span class="scroll-percent"></span></div>
    </div>
    <div id="full-container">
      <Header />
      <Banner />
      <Content />
      <Footer />
    </div>
    <a class="scroll-top-icon scroll-top" href="#"
      ><i class="fa fa-angle-up"></i
    ></a>
  </div>
</template>

<script>
export default {
  layout: "lead-1",
  head: {
    title: "TEste",
    link: [
      {
        rel: "stylesheet",
        href: "css/css-assets.css"
      },
      {
        rel: "stylesheet",
        href: "css/style.css"
      },
      {
        rel: "stylesheet",
        href:
          "https://fonts.googleapis.com/css?family=Montserrat:400,400i,600,600i,700,700i"
      },
      {
        rel: "stylesheet",
        href:
          "https://fonts.googleapis.com/css?family=Open+Sans:400,400i,700i,700"
      },
      //Favicon
      {
        rel: "shortcut icon",
        href: "images/general-elements/favicon/favicon.png"
      },
      {
        rel: "apple-touch-icon",
        href: "images/general-elements/favicon/apple-touch-icon.png"
      },
      {
        rel: "apple-touch-icon",
        href: "images/general-elements/favicon/apple-touch-icon-72x72.png",
        sizes: "72x72"
      },
      {
        rel: "apple-touch-icon",
        href: "images/general-elements/favicon/apple-touch-icon-114x114.png",
        sizes: "114x114"
      }
    ],
    script: [
      { src: "js/jquery.js" },
      { src: "js/jRespond.min.js" },
      { src: "js/jquery.easing.min.js" },
      { src: "js/jquery.waypoints.min.js" },
      { src: "js/jquery.fitvids.js" },
      { src: "js/jquery.stellar.js" },
      { src: "js/owl.carousel.min.js" },
      { src: "js/jquery.mb.YTPlayer.min.js" },
      { src: "js/jquery.magnific-popup.min.js" },
      { src: "js/jquery.ajaxchimp.min.js" },
      { src: "js/jquery.validate.min.js" },
      { src: "js/simple-scrollbar.min.js" },
      { src: "js/functions.js" }
    ]
  }
};
</script>

<style>
.bg-element {
  background-attachment: fixed !important;
}
</style>
