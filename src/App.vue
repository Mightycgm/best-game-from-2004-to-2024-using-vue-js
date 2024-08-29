<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import mycard from "./components/mycard.vue";
import items from "./items.json";
import end from "./components/footer.vue";
import navbar from "./components/navbar.vue";
</script>

<template>
  <div>
    <navbar />
    <mycard v-bind="items[0]" />
    <mycard v-bind="items[1]" />
    <mycard v-bind="items[2]" />
    <mycard v-bind="items[3]" />
    <mycard v-bind="items[4]" />
    <mycard v-bind="items[5]" />
    <mycard v-bind="items[6]" />
    <mycard v-bind="items[7]" />
    <mycard v-bind="items[8]" />
    <mycard v-bind="items[9]" />
    <mycard v-bind="items[10]" />
    <mycard v-bind="items[11]" />
    <end />
  </div>

</template>

<style scoped>

/* header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
} */
</style>
