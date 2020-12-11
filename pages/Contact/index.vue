<template>
  <div class="container">
    <div class="py-8">
      <img class="me p-4" src="~/assets/photos/self_port.jpg" alt="Me!" />
      <p>
        <span class="font-bold">Hi</span>, I'm Kai. I’m a
        <span class="accentuate">Kansas City</span> based photographer. I like
        to take portrait and product photos. I love experimenting with long
        exposures and landscapes too. I’ve been shooting for a few years now and
        try to learn something new each day. I love to capture moments and
        freezing them in time forever. I like to challenge and give myself
        different assignments in my free time. If I’m not doing something
        photography related, I’m doing something code or design related.
      </p>
    </div>
    <ContactForm />
  </div>
</template>

<style>
.me {
  max-height: 300px;
}
.something-about-me {
  font-size: 2em;
}
p {
  font-size: 21px;
}
.accentuate {
  transition: 0.3s;
}
.accentuate:hover {
  font-weight: bold;
  background-color: red;
  color: yellow;
  padding: 0 20px;
}
@media only screen and (min-width: 600px) {
  .me {
    float: left;
  }
}
</style>
