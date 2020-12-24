<template>
  <nav>
    <NuxtLink to="/"><h1 id="title">KAI ASUNCION</h1></NuxtLink>
    <ul class="navigation-holder">
      <NuxtLink to="/contact/">
        <li class="navigation-item">Contact</li>
      </NuxtLink>
    </ul>
  </nav>
</template>

<style scoped>
nav {
  width: 100%;
  display: flex;
  flex-flow: row nowrap;
  justify-content: space-between;
  align-items: center;
  margin: 0 auto;
  padding: 20px;
}
.navigation-holder {
  width: 1fr;
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
  align-items: center;
  padding: 0;
  list-style-type: none;
}
#title {
  width: 4fr;
  font-size: 24px;
  padding: 0;
}
.navigation-item {
  font-size: 20px;
  text-align: center;
  padding: 4px 8px;
  border: 2px solid #000;
  transition: 0.3s ease-in-out;
}
.navigation-item:hover {
  background-color: #000;
  color: #fff;
  cursor: pointer;
}
@media only screen and (min-width: 500px) {
  #title {
    font-size: 42px;
  }
}
@media only screen and (min-width: 800px) {
  #title {
    font-size: 50px;
    letter-spacing: 20px;
  }
}
</style>
