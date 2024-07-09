<script setup lang="ts">
const profileName = "Marcos Roberto"
const profileDescription = "Front-End Developer | Educator <br/> A passionate developer who loves to create new interfaces and experiences."

</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ profileName }}</h1>
    <h3 v-html="profileDescription">
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

h4 {
  display: flex;
}

span {
  display: flex;
  flex-wrap: wrap;
}
.greetings h1,
.greetings h3 {
  text-align: center;
  max-width: 366px;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
