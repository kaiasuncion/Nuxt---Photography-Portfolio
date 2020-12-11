<template>
  <div class="layout-class">
    <Navigations />
    <Nuxt />
    <Footer />
  </div>
</template>

<style>
* {
  font-family: 'Raleway', sans-serif;
}
body {
  margin: 0;
  padding: 0;
}
.layout-class {
  margin: 0 auto;
  max-width: 1500px;
}
.container {
  min-height: 80vh;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  width: 90%;
}
h1 {
  font-family: 'Open Sans', sans-serif;
}
@media only screen and (min-width: 700px) {
  .layout-class {
    max-width: 800px;
  }
}
</style>
