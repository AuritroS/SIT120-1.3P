<template>
  <section class="contact-section">
    <h2>Contact Me</h2>
    <div class="contact">
      <div class="address cursor">
        <i class="bx bx-current-location"></i>
        <p>123 Anywhere St. Any City</p>
      </div>
      <hr />
      <div class="phone cursor">
        <i class="bx bxs-phone"></i>
        <p>123-456-7890</p>
      </div>
      <hr />
      <div class="email cursor">
        <i class="bx bxl-gmail"></i>
        <p>123456@gmail.com</p>
      </div>
      <hr />
      <div class="website cursor">
        <i class="bx bx-store"></i>
        <p>123456789.com</p>
      </div>
      <hr />
    </div>
  </section>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style>
@import "../styles/contact.css";
</style>
