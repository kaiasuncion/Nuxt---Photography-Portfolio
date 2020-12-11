<template>
  <div class="container">
    <h1 class="text-5xl pb-4">ERROR 404</h1>
    <p class="text-2xl text-center pb-4">
      We're sorry but the number you are trying to reach is out of service
    </p>
    <NuxtLink to="/" class="custom-border text-3xl">Return Home</NuxtLink>
  </div>
</template>

<style>
.custom-border {
  border: 1px solid #000;
  padding: 5px 40px;
  transition: 0.3s ease-in-out;
}
.custom-border:hover {
  cursor: pointer;
  background-color: #000;
  color: #fff;
}
</style>
