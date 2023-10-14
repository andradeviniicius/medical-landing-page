<template>
  <NavBar />
  <Header />
  <MedicalServices />
  <ServiceDetails />
  <AboutCompany />

  <SystemFeatures />
  <Testimonials />
  <CustomersSlider />
  <MedicalServicesIntroduction />

  <ContactUs />
  <Footer />
  <Copyright />

  <button id="myBtn">
    <img src="assets/images/up-arrow.png" alt="alternative" />
  </button>
</template>

<script setup lang="ts">
import NavBar from "./components/LandingPage/NavBar.vue";
import Header from "./components/LandingPage/Header.vue";
import MedicalServices from "./components/LandingPage/MedicalServices.vue";
import AboutCompany from "./components/LandingPage/AboutCompany.vue";
import ServiceDetails from "./components/LandingPage/ServiceDetails.vue";
import SystemFeatures from "./components/LandingPage/SystemFeatures.vue";
import Testimonials from "./components/LandingPage/Testimonials.vue";
import CustomersSlider from "./components/LandingPage/CustomersSlider.vue";
import MedicalServicesIntroduction from "./components/LandingPage/MedicalServicesIntroduction.vue";
import ContactUs from "./components/LandingPage/ContactUs.vue";
import Footer from "./components/LandingPage/Footer.vue";
import Copyright from "./components/LandingPage/Copyright.vue";
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
