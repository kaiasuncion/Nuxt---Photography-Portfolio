<template>
  <form name="contact" method="POST" data-netlify="true">
    <!-- <form name="contact" action="/success" method="POST" data-netlify="true"> -->
    <label for="name">Name</label><br />
    <input id="name-field" type="text" name="name" required /><br />
    <label for="email">Email</label><br />
    <input id="email-field" type="email" name="email" required /><br />
    <label for="">Message</label><br />
    <textarea
      id="message-field"
      name="message"
      cols="30"
      rows="10"
      required
    /><br />
    <p class="hidden">
      <label>
        Don’t fill this out if you’re human:
        <input name="bot-field" />
      </label>
    </p>
    <input id="send-it" type="submit" value="Send it!" />
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
  transition: 0.3s;
}
#send-it:hover {
  cursor: pointer;
  background-color: #000;
  color: #fff;
}
</style>
