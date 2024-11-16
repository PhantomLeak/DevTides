<template>
  <div>
    <div>
      <img alt="DevTides Logo" width="200px" src="../assets/dev_tides_logo.jpg"/>
      <h1 style="margin-top: -3%;">
        Dev Tides
      </h1>
      <span style="font-style: italic;">Ride the waves of developer news</span>
    </div>
    <MailchimpComponent/>
    <div>
      <h5>Dedicated Developer News – Curated by hand from a variety of trusted sources.</h5>
    </div>
  </div>
  <div style="align-content: center; text-align: center">
<!--    <Footer/>-->
  </div>
</template>

<script>
import MailchimpComponent from './MailchimpComponent.vue';
import Footer from './Footer.vue';

export default {
  components: {
    MailchimpComponent,
    Footer
  }
}
</script>

<style scoped></style>
