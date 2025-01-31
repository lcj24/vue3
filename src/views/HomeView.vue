
<script setup>
import Skip from "./Skip.vue";
import Header from "./Header.vue";
import Intro from './Intro.vue';
import Skill from "./Skill.vue";
import Site from "./Site.vue";
import Port from "./Port.vue";
import Contact from "@/components/Contact.vue";
import Footer from "./Footer.vue";
</script>

<template>
  <main>
    <Skip />
    <Header></Header>
    <main id="main" role="main">
      <Intro></Intro>
      <Skill></Skill>
      <Site></Site>
      <Port></Port>
      <Contact></Contact>
    </main>
    <Footer></Footer>
  </main>
</template>
