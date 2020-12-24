<template>
  <div class="container">
    <div class="py-8">
      <img class="me p-4" src="~/assets/photos/self_port.jpg" alt="Me!" />
      <p>
        <span class="font-bold">Hi</span>, I'm Kai. I’m a
        <span class="accentuate">Kansas City</span> based photographer.
        Capturing moments and freezing them in time forever so you can
        experience it again is my passion. If I’m not doing something
        photography related, I’m doing something with code or design.
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
form {
  width: 100%;
  display: flex;
  flex-flow: column nowrap;
}
label {
  font-size: 24px;
}
input,
textarea {
  border: 1px solid #000;
  margin-bottom: 20px;
  padding: 10px;
  font-size: 24px;
  letter-spacing: 5px;
}
#send-it {
  padding: 10px;
  border: 1px solid #000;
  transition: 0.3s;
}
#send-it:hover {
  cursor: pointer;
  background-color: #000;
  color: #fff;
}
@media only screen and (min-width: 600px) {
  .me {
    float: left;
  }
}
</style>
