<template>
  <section class="home" id="home">
    <div class="home-content">
      <h1>Hi, I'm Auritro Sami</h1>
      <h3>Web Developer</h3>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia autem
        aliquam nemo magnam tenetur. Eos accusantium, incidunt recusandae
        possimus sit, ad perspiciatis omnis rem, temporibus voluptates assumenda
        excepturi labore quisquam!
      </p>
      <div class="btn-box">
        <router-link to="/contact">Contact</router-link>
        <router-link to="/project">Projects</router-link>
      </div>
    </div>
    <img :src="image" alt="graphic" class="graphic" />
    <div class="home-socials">
      <a href="#"><i class="bx bxl-linkedin"></i></a>
      <a href="#"><i class="bx bxl-facebook-circle"></i></a>
      <a href="#"><i class="bx bxl-instagram-alt"></i></a>
    </div>
  </section>
</template>

<script>
import image from "../assets/Programming-amico.png";

export default {
  name: "HomePage",
  data: function () {
    return {
      image: image,
    };
  },
};
</script>

<style>
@import "../styles/home.css";
</style>
