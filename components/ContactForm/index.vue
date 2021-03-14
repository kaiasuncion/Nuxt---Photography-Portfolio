<template>
  <form
    name="contact"
    action="/success/"
    method="POST"
    netlify-honeypot="bot-field"
    data-netlify-recaptcha="true"
    data-netlify="true"
  >
    <input type="hidden" name="contact-form" value="contact" />
    <label for="person-name">Name</label>
    <input id="name-field" type="text" name="person-name" required />
    <label for="email">Email</label>
    <input id="email-field" type="email" name="email" required />
    <label for="message">Message</label>
    <textarea
      id="message-field"
      name="message"
      cols="30"
      rows="10"
      required
    ></textarea>
    <p class="hidden">
      <label class="hidden">
        Don’t fill this out if you’re human:
        <input name="bot-field" />
      </label>
    </p>
    <button id="send-it" type="submit">Send</button>
  </form>
</template>
