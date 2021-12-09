<template>
  <div class="container">
    <div class="py-8">
      <h1>Under Construction</h1>
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
