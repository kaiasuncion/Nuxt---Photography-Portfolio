<template>
  <div class="container text-center">
    <h1 class="success-message">YOUR MESSAGE HAS BEEN</h1>
    <h1 class="success-message-large">SENT</h1>
    <NuxtLink to="/" class="custom-border text-3xl">Return Home</NuxtLink>
  </div>
</template>

<style>
.success-message {
  font-size: 3em;
}
.success-message-large {
  padding: 5px 70px;
  font-size: 12em;
  background-color: #000;
  color: #fff;
  margin-bottom: 20px;
  transition: 0.9s ease;
}
.success-message-large:hover {
  background-color: orange;
  font-size: 15em;
  cursor: crosshair;
}
</style>
