<template>
  <form
    name="contact"
    action="/success"
    method="POST"
    enctype="Content-Type of application/x-www-form-urlencoded"
    data-netlify="true"
  >
    <label for="person-name">Name</label>
    <input id="name-field" type="text" name="person-name" required />
    <label for="email">Email</label>
    <input id="email-field" type="email" name="email" required />
    <label for="message">Message</label>
    <textarea id="message-field" name="message" cols="30" rows="10" required />
    <p class="hidden">
      <label>
        Don’t fill this out if you’re human:
        <input name="bot-field" />
      </label>
    </p>
    <button id="send-it" type="submit">Send it!</button>
  </form>
</template>

<style>
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
</style>
