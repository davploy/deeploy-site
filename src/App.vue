


<script setup>

</script>

<template>
  <h1>deeploy</h1>
  <p class="note"> Bring your design logic to the web </p>
</template>

<style scoped>
.note {
  color: #888;
}

h1 {
  will-change: filter;
  transition: filter 300ms;
  font-family: 'Rubik Doodle Shadow', system-ui;
  font-size: 3.2em;
  line-height: 1.1;
  color: #ffffffaa;
  text-decoration: inherit;


}
h1:hover {
  color: #00ff77aa;
  filter: drop-shadow(0 0 1em #00ff77) drop-shadow(0 0 0em #00ff77); /* Added multiple shadows for stronger effect */
}



h1::selection {
  background: transparent; /* Removes the blue highlight */
  color: inherit; /* Keeps the text color the same */
}

</style>

